# nuxtjs-vercel-integration
Nuxt.js integration vercel example

Nuxt.js ile geliştirilen bir SPA veya PWA projelerimizi vercel kullanarak dağıtabiliriz. Bunun için vercel.com'a giderek bir hesap oluşturun ve kullandığınız Git hesabını bağlayın ardından repoyu import ederek deploya edin. 

Static SPA'lar için package.json dosyasını aşağıdaki şekilde güncellemeniz yeterli olacaktır.

"scripts": {
    "dev": "nuxt",
    "build": "nuxt generate",
    "start": "nuxt start",
  },
