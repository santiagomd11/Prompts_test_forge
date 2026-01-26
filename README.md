## Git Workflow

### Branch Protection

- `master` branch is **protected** — direct pushes and force pushes are blocked.

### Contributing

1. Create a feature branch from `master`:
   ```
   git checkout -b feature/{name-of-the-thing-you-want-to-do}
   ```

2. Make your changes and commit them

3. Push your branch and open a Pull Request (PR)

4. After review and approval, the PR will be merged into `master`