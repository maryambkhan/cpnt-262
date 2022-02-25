# cpnt-262

## Maryam Khan

## Nuxt Framework Setup

## Code Journal

1. **NPM Project Setup**

  - First i created a repo and cloned it done then i realised in nuxt framework it is already git repo 
    so i deleted it and started over with:

  - npm setup using
    npm init nuxt-app <project-name>
  - This step created bunch of files including README.md
  so i edited it and redoing it

2. **Nuxt Modules/Nuxt Configuration**
  - Already added Nuxt tailwindcss
  - Added dapendencies
  - Added Nuxt Storyblok
     - npm install --save-dev @storyblok/nuxt axios
     - [In Modules Section]
        
  modules: [
    [
      "@storyblok/nuxt",
       {
        accessToken: "YOUR_PREVIEW_TOKEN",
        cacheProvider: "memory",
      },
    ],
  
      
  - Added Nuxt Image
    - npm install -D @nuxt/image
    - [In buildModules]

      '@nuxt/image',

  - Added Nuxt google-fonts
    - npm install --save-dev @nuxtjs/google-fonts
    - [In buildModules] 

     '@nuxtjs/google-fonts', 


3. **npm security vulnerabilities**

4. **Git Commits**

  - My first commit and having problem pushing 

    ![Error](/assets/images/Capture.PNG)
  - Package.jason file is not uploding fully it says its long file

## Attributions

- [Nust2](https://nuxtjs.org/docs/get-started/installation/)
- [Nuxt Modules](https://modules.nuxtjs.org/)

- [GH repo]()
