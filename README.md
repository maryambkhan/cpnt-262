# cpnt201-a4

## Maryam Khan

## Nuxt Framework Setup

## Code Journal

1. ### **NPM Project Setup**

  - First i created a repo and cloned it done then i realised in nuxt framework it is already git repo 
    so i deleted it and started over with:

  - npm setup using
    npm init nuxt-app <project-name>
  - This step created bunch of files including README.md
  so i edited it and redoing it

2. ### **Nuxt Modules/Nuxt Configuration**

    
  - Already added Nuxt tailwindcss
  - Added dapendencies

     
  - Added Nuxt Storyblok
     - `npm install --save-dev @storyblok/nuxt axios`
     - [In Modules Section]
        
  modules: [
    [
      `"@storyblok/nuxt",`
       {
        accessToken: "YOUR_PREVIEW_TOKEN",
        cacheProvider: "memory",
      },
    ],

  
    
  - Added Nuxt Image
    - `npm install -D @nuxt/image`
    - [In buildModules]

     ` '@nuxt/image',`

      
  - Added Nuxt google-fonts
    - `npm install --save-dev @nuxtjs/google-fonts`
    - [In buildModules] 

     `'@nuxtjs/google-fonts', `
  - I have added google-fonts becouse text is major thing 
   we always writing content user is looking at this content.
  - So i need to make sure i have this module added and i can use plenty of styles.

     
  - Added Animejs module
    - ` npm install --save-dev nuxt-animejs`

    - `buildModules: ['nuxt-animejs']`
  - I added this module becouse i would love to work on 
   animation



3. ### **npm security vulnerabilities**

- I wanted to solve these problems so read the gist and documentation from class did not understood much the watched a video
 it looked simple but still not able to solve it.

4. ### **Git Commits**

  1. nuxt npm setup
   - My first commit and having problem pushing 

     ![Error](/assets/images/Capture.PNG)
   - Package.jason file is not uploding fully it says its long file
   - I was wrong its there got me worried 

  2. added dependencies
  3. added assets folder with (tailwind.css)
  4. added modules
  5. working on vulnerabilitie
  6. added tailwind config file
  7. added eslint as js
  8. added animejs module
  9. added links for modules

## Attributions

- [Nust2](https://nuxtjs.org/docs/get-started/installation/)
- [Nuxt Modules](https://modules.nuxtjs.org/)
- [tailwindcss](https://tailwindcss.nuxtjs.org/setup)
- [storyblok](https://github.com/storyblok/storyblok-nuxt)
- [image](https://image.nuxtjs.org/getting-started/installation)
- [google-fonts](https://github.com/nuxt-community/google-fonts-module)
- [animejs](https://github.com/ivodolenc/nuxt-animejs)



- [GH repo](https://github.com/maryambkhan/cpnt201-a4)
