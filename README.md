# all-branches-hub

The landing page of all Coderbunker branches website

## 0. Frameworks

* Gatsby: v3.13
* PostCSS: v8.3


## 1. Hosting and deployment

We use Netlify to host the Gatsby page. 

- `production` branch: any changes, pull requests and merges to this branch will be published on the production website
- `deploy-preview` branch: the staging branch for the website preview before it goes live on production.

## 2. How to develop the project

1. clone the repo

    ```git clone git@github.com:coderbunker/all-bra```

2. install all the dependencies

    ```npm install```

3. run gatsby server to preview locally at [http://localhost:8000](http://localhost:8000)

    ```npm run develop```

4. commit the changes to `deploy-preview` branch on Github, then Netlify will automatically compile and update the website. The preview version of this website is at [https://coderbunker-hub-preview.netlify.app/](https://coderbunker-hub-preview.netlify.app/)

