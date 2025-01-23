ECHO is on.
# Merge Conflict Details

## Cause of the Conflict
The merge conflict occurred because the same line in `README.md` was modified differently in two branches (`feature-xy` and `bugfix-xy`).

## Steps to Resolve the Conflict
1. Switch to the `main` branch.
2. Merge `feature-xy` into `main` (successful merge).
3. Attempt to merge `bugfix-xy` into `main`, which caused the conflict.
4. Open the conflicting file (`README.md`) and manually resolve the conflict.
   - Kept relevant changes from both branches.
   - Removed Git conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`).
5. Stage the resolved file:
   ```bash
   git add README.md
