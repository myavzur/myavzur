```js
// TODO: Make It better!
export const userConfig = {
  country: 'Russia',
  languages: ['ru', 'en'],
  technologies: {
    common: {
      languages:    ['js', 'ts', 'html', 'css', 'php'],
      bundlers:     ['webpack', 'gulp', 'vite'],
      systems:      ['windows', 'linux', 'ios'],
      misc:         ['ejs', 'handlebars', 'docker']
    },
    frontend: {
      frameworks:   ['react', 'next', 'vue', 'electron'],
      stores:       ['redux', 'zustand'],
      libraries:    ['threejs', 'gsap', 'videojs', 'react-spring'],
      styles:       ['tailwind', 'css-modules', 'sass']
    },
    backend {
      frameworks:   ['express', 'nest'],
      databases:    ['firebase', 'mysql', 'postgresql', 'redis'],
      misc:         ['rabbitmq']
    }
  }
};
```
