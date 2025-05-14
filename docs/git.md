# How to usage git

1. Clone Repo
```sh
git clone https://github.com/quynhfe/RentalSystem.git
```
2. Move to folder
```sh
cd RentalSystem
```
3. Create branch
- 3.1: Only create branch
  ```sh
  git branch <name_branch>
  ```
  + 3.1.1: Move to branch
    ```sh
    git checkout <name_branch>
    ```

- 3.2 Create and move my branch 
  ```sh
  git checkout -b <name_branch>
  ```

4. Push code from your branch
- Add code
```sh
git add .
```
- Commit 
```sh
git commit -m "content"
```
- Push 
```sh
git push origin <name_branch>
```

### Lead
1. Merge code 
- back main branch
```sh
git checkout main
```
- Update main branch from remote
```sh
git pull origin main
```
- Merge code
```sh
git merge mem/<name_branch>
```
- Push code to origin/main
```sh
git push origin main
```