# Prettier Angular Control Flow Whitespace Issue

## Step to reproduce the issue

1. Run `npm run test`. This will run successfully.
2. Run `npm run format`. This will format all files in the repository with prettier.
3. Run `npm run test` again. This will fail because prettier formatted `app.component.html` file to insert whitepsaces between `<h1>` html tag and `test` text content.
