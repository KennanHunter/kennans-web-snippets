# Kennan's Web Snippets

## Usage

[open-vsx extension](https://open-vsx.org/extension/kennanhunter/kennans-web-snippets)

## Snippets

### Kennan's Anonymous React Element

#### Typescript

```typescript
export const $1: FC = () => {
  return <></>;
};
```

#### Javascript

```javascript
export const $1 = () => {
  return <></>;
};
```

### Kennan's HTML Starter

#### HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="description" content="$1" />
    <meta name="keywords" content="$2" />
    <meta name="author" content="$3" />
    <title>${4:$WORKSPACE_NAME}</title>
  </head>
  <body>
    $2
  </body>
</html>
```
