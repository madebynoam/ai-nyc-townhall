# Marp Presentation

Generate and launch Marp presentations from markdown files.

## Usage

```
/marp-preso [file-or-folder]
```

## Examples

```
/marp-preso                           # List files, ask what to compile
/marp-preso townhall-presentation.md  # Compile specific file
```

## Instructions

1. **If no argument provided**: List `.md` files in current directory and ask which to compile

2. **Compile to HTML**:
   ```bash
   marp --no-stdin <file.md> -o <file>.html --allow-local-files
   ```

3. **Open in browser**:
   ```bash
   open <file>.html
   ```

4. **Report**: Tell user which file was compiled and that they can press P for presenter view

## Export to PDF

If user asks for PDF:
```bash
marp --no-stdin <file.md> -o <file>.pdf --allow-local-files
```

## Notes

- Always use `--no-stdin` flag to avoid hanging
- Use `--allow-local-files` when images are referenced
- Files need marp frontmatter:
  ```yaml
  ---
  marp: true
  theme: default
  paginate: true
  ---
  ```
