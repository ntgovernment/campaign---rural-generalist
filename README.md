# Rural Generalist Template

## Prerequisites

-   [NodeJS](https://nodejs.org/en/download/)

## Install

Once cloned or downloaded, install the dependencies:

```bash
npm install
```

For development run:

```bash
npm run dev
```

For production builds run:

```bash
npm run prod
```

## Deploy to staging

1. The folder name will be used as the folder name for staging. Whitespace and underscores will be replaced with "-".

2. Run the following command:

```bash
npm run deploy-to-staging
```

3. If everything goes well, you should see your site at http://matrix.test.brainiumlabs.com.au/website-name

## Setting up Git File Bridge for Matrix build

1. Go the the project repository settings.

2. Navigate to the "Access Tokens" section and "Create Repository Access Token". Give the Token a name, usually just Matrix File Bridge.

3. Set the Scopes to "Read" for Repositories only.

4. Press Create.

5. On this popup, copy ONLY THE URL from the third section, "How to use this token with your Git respository". Starting from https://

6. Navigate to Matrix > Configuration > Design Assets > Build > Right Click and select DETAILS. On, the details screen "Git Url", paste the url copied and Press "Save". Next to the "Git Url" now, you will see the option "Clone Repo". Press the button and everything is good to go.
