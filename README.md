# TypeScript Crash Course

This project is a crash course in setting up a TypeScript project.

## Steps to Create the Project

1. **Install Node.js and npm**:
   - Installed Node.js and npm using Homebrew:
     ```bash
     brew install node
     ```

2. **Verify Installation**:
   - Verified the installation of Node.js and npm:
     ```bash
     node -v
     npm -v
     ```

3. **Update PATH**:
   - Added Node.js to the PATH:
     ```bash
     echo 'export PATH="/usr/local/opt/node/bin:$PATH"' >> ~/.zshrc
     source ~/.zshrc
     ```

4. **Install TypeScript Globally**:
   - Installed TypeScript globally using npm:
     ```bash
     npm install -g typescript
     ```

5. **Initialize npm**:
   - Initialized npm in the project directory:
     ```bash
     npm init -y
     ```

6. **Install TypeScript Locally**:
   - Installed TypeScript as a development dependency:
     ```bash
     npm install typescript --save-dev
     ```

7. **Initialize TypeScript Configuration**:
   - Created a `tsconfig.json` file with default settings:
     ```bash
     npx tsc --init
     ```

## Project Structure

- `package.json`: Contains project metadata and dependencies.
- `tsconfig.json`: TypeScript configuration file.

## Commands

- **Compile TypeScript**:
  ```bash
  tsc