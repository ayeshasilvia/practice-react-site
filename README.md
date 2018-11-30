# Practice React Site

## Software 

Before proceeding, please ensure you have the following software installed on your computer.

* Node
* Yarn (optional but recommended)
* Git command line tools

## Installation

1. Within terminal or cmd ensure you have changed directory (into the new folder that has been cloned) and install the dependencies

```
  cd <new-dir> 
  yarn install OR npm install
```

2. Before we can build, run or deploy our app it is important to ensure that the 'webConfig.json' is configured for our environment. Please change 'siteURL' to point to either your local or live url.

```
    {
    "siteURL": "http://localhost:3000", ...

    OR

    {
    "siteURL": "http://mydomain.com", ... 
```

3. You must build the app before you can run it

```
  yarn run build OR npm run build
```

4. Run your build

```
  yarn run dev OR npm run dev
```

This should launch the application and start running on: http://localhost:3000/
