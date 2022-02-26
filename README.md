# YIKE



https://github.com/youbastard/yike

### Installation

Install the Yike package along with Sass
`npm install @youbastard/yike sass -D`

#### Vite

Update the Vite config to make sass mixins available

vite.config.js
```
export default defineConfig({

  css: {
    preprocessorOptions: {
      scss: {
        additionalData: `
          @import '@youbastard/yike/mixins.scss';
        `
      }
    }
  }
  
});
```


#### NextJS



#### PostCSS



### Reset

Uses Tailwinds Preflight.css

`@import url('youbastard/yike.min.css');`


### Mixins

#### Animate

#### Border

#### Box Shadow

#### Corner Radius (Border Radius)

#### Font Weight

#### Grid Cols

#### Grid Gap

#### Headings

#### Height

#### Label

#### Leading

#### Margin

#### Outline

#### Padding

#### Ring

#### Screen Reader

#### Text Size

#### Tracking

#### Truncate

#### Width


## Colors

