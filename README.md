# cpnt201-a4

## Maryam Khan

## Nuxt Framework Setup

## Code Journal

 ### **NPM Project Setup**

  - First i created a repo and cloned it done then i realised in nuxt framework it is already git repo 
    so i deleted it and started over with:

  - npm setup using
    npm init nuxt-app <project-name>
  - This step created bunch of files including README.md
  so i edited it and redoing it

 ### **Nuxt Modules/Nuxt Configuration**

    
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



 ### **npm security vulnerabilities**

- I wanted to solve these problems so read the gist and documentation from class did not understood much the watched a video
 it looked simple but still not able to solve it.

 ### **Git Commits**

  1. nuxt npm setup (Hashes: eb50f56a847eba77e2733a37fb449d37258eb57d)
   - My first commit and having problem pushing 

     ![Error](/assets/images/Capture.PNG)
   - Package.jason file is not uploding fully it says its long file
   - I was wrong its there got me worried 

  2. added dependencies (Hashes:e192d4eacd2e6cb9ebf7239e1d9033e246f4c75e )
  3. added assets folder with (tailwind.css) (Hashes: 34c301d1cab467d0fb963933e50857159e3ecaf6)
  4. added modules (Hashes: e446a6ab202d50a1ad3f82bb171b2f8243aea83a)
  5. working on vulnerabilitie (Hashes: be58ac7fcaf548c40da8e289164bc1c11f5cb657)
  6. added tailwind config file (Hashes: ecfce4921c160e398ebe141cfe756fc1b0f7afd1)
  7. added eslint as js (Hashes:bb004c855b6ba23346c3bdbd9cbc69b0fbe39f82 )
  8. added animejs module (Hashes: 99e1ce311fb78d2813e521ec258ad5dc478bee24)
  9. added links for modules (Hashes: 2784ca13643cdd5188020c52db2751e27f81787c)
  10. added hashes 

     

  - I tried my best to make my journal look assembeled and easy to read every time 
  it had some issue in there. I am done this is my last commit it better look good.

## Attributions

- [Nust2](https://nuxtjs.org/docs/get-started/installation/)
- [Nuxt Modules](https://modules.nuxtjs.org/)
- [tailwindcss](https://tailwindcss.nuxtjs.org/setup)
- [storyblok](https://github.com/storyblok/storyblok-nuxt)
- [image](https://image.nuxtjs.org/getting-started/installation)
- [google-fonts](https://github.com/nuxt-community/google-fonts-module)
- [animejs](https://github.com/ivodolenc/nuxt-animejs)


- Stephan told me what hashes are.



- [GH repo](https://github.com/maryambkhan/cpnt201-a4)
