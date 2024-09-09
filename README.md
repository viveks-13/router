# Getting Started

## Cloning the Repository

Open up a terminal and run the following command to clone the repository:

```bash
git clone https://github.com/viveks-13/router.git
```

## Making Changes for a New Feature

1. **Create a new branch**:

    ```bash
    git checkout -b branch_name
    ```

2. **Save changes**:

    ```bash
    git add .
    ```

3. **Commit changes**:

    ```bash
    git commit -m "your message here"
    ```

4. **Push changes**:

    ```bash
    git push origin branch_name
    ```

5. **Pull new changes**:

    ```bash
    git pull origin branch_name
    ```

## Creating a Pull Request

Once you push your changes to save progress, create a pull request through the GitHub website UI [here](https://github.com/viveks-13/router/pulls).

## Notes

- Lowk ask chat for any github stuff that doesn't work/is confusing its hella cracked
- Do **not** push changes directly to the main branch, as it should remain stable.
- The first time you try to pull code or push changes, you might be asked to set credentials. Note that the password is a Personal Access Token (PAT), not a regular password.

To create a PAT:
1. Go to **Settings** -> **Developer settings** -> **Access tokens**.
2. Create a new classic token:
   - Give it a name
   - Set no expiration
   - Grant access to all fields

# Project Vision

- The app opens with a prompt box where users can type in their request.
  - Sample prompts: "Create me a route from Seattle to California stopping every 150 miles for gas and every 5 hours for food."
- Users submit the prompt and receive a list of different routes with key features highlighted (total time, mileage, etc.).
- Users can select a route or fine-tune a specific route by clicking on it and adding another prompt (initially, you might start with creating one route and force users to use that).
- The route opens in Google Maps or possibly within the app itself, depending on the capabilities of the Google Maps API.

## Frameworks

- The UI is set up to be run through Storyboard. There is plenty of documentation available online and through ChatGPT on how to use it.
