<template>
  <div class="porfoliohomedesktop641227-porfoliohomedesktop641227">
    <div class="porfoliohomedesktop641227-container">
      <img
        :alt="image_alt2"
        :src="image_src2"
        class="porfoliohomedesktop641227-image"
      />
    </div>
    <span class="porfoliohomedesktop641227-text">{{ text }}</span>
    <span class="porfoliohomedesktop641227-text01">{{ text1 }}</span>
    <span class="porfoliohomedesktop641227-text02">{{ text2 }}</span>
    <img
      :alt="image_alt"
      :src="image_src"
      class="porfoliohomedesktop641227-image1"
    />
    <span class="porfoliohomedesktop641227-text03">{{ text3 }}</span>
    <span class="porfoliohomedesktop641227-text04">{{ text4 }}</span>
    <span class="porfoliohomedesktop641227-text05">
      <span class="porfoliohomedesktop641227-text06">const</span>
      <span class="porfoliohomedesktop641227-text07">
        <span v-html="raw4t8a"></span>
      </span>
      <span class="porfoliohomedesktop641227-text08">githubLink</span>
      <span class="porfoliohomedesktop641227-text09">
        =
        <span v-html="raw4nq1"></span>
      </span>
      <span class="porfoliohomedesktop641227-text10">“</span>
      <span class="porfoliohomedesktop641227-text11">
        https://github.com/example/url”
      </span>
    </span>
    <div class="porfoliohomedesktop641227-header641317">
      <span class="porfoliohomedesktop641227-text12">{{ text5 }}</span>
      <span class="porfoliohomedesktop641227-text13">{{ text6 }}</span>
      <img :alt="svg_alt" :src="svg_src" class="porfoliohomedesktop641227-svg" />
      <img
        :alt="svg_alt1"
        :src="svg_src1"
        class="porfoliohomedesktop641227-svg1"
      />
      <img
        :alt="svg_alt2"
        :src="svg_src2"
        class="porfoliohomedesktop641227-svg2"
      />
      <div class="porfoliohomedesktop641227-frame1i64131735155">
        <div class="porfoliohomedesktop641227-header-text-i64131735149">
          <span class="porfoliohomedesktop641227-text14">{{ text7 }}</span>
          <img
            :alt="svg_alt3"
            :src="svg_src3"
            class="porfoliohomedesktop641227-svg3"
          />
        </div>
        <div class="porfoliohomedesktop641227-component5i64131735152">
          <span class="porfoliohomedesktop641227-text15">{{ text8 }}</span>
          <img
            :alt="svg_alt4"
            :src="svg_src4"
            class="porfoliohomedesktop641227-svg4"
          />
        </div>
        <div class="porfoliohomedesktop641227-component6i64131735156">
          <span class="porfoliohomedesktop641227-text16">{{ text9 }}</span>
          <img
            :alt="svg_alt5"
            :src="svg_src5"
            class="porfoliohomedesktop641227-svg5"
          />
        </div>
      </div>
    </div>
    <img
      :alt="image_alt1"
      :src="image_src1"
      class="porfoliohomedesktop641227-image2"
    />
  </div>
</template>

<script>
export default {
  name: 'Porfoliohomedesktop641227',
  props: {
    svg_alt3: {
      type: String,
      default: 'Line1I6413173514935135',
    },
    image_alt2: {
      type: String,
      default: 'Mainbackground641230',
    },
    image_src: {
      type: String,
      default:
        'data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nNjkyJyBoZWlnaHQ9JzYzOScgdmlld0JveD0nMCAwIDY5MiA2MzknIGZpbGw9J25vbmUnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zyc+CjxnIG9wYWNpdHk9JzAuNCcgZmlsdGVyPSd1cmwoI2ZpbHRlcjBfZl82NF8xMjM0KSc+CjxwYXRoIGQ9J000NDkuMTMzIDUzMC4zMTNMMzE2LjQyNyA0OTguNDM0TDI2MC45ODYgNDU4LjMxOUwyNzcuNDY1IDM1Mi41MzhMMzg2LjI5MiAzNDAuNEwzODUuMjk0IDI2NC44NzRMNTEwLjc3NSAyMzEuMjE1TDU5MS42MDUgMjUwLjYzMkw1NDAuNDY0IDQxNS43MTdMNDYxLjUwOCA0MzYuMzA3TDQ0OS4xMzMgNTMwLjMxM1onIGZpbGw9JyM0RDVCQ0UnLz4KPC9nPgo8ZyBvcGFjaXR5PScwLjQnIGZpbHRlcj0ndXJsKCNmaWx0ZXIxX2ZfNjRfMTIzNCknPgo8cGF0aCBkPSdNNDE3LjgxOSAxNTkuOTI5TDQyOC4wNjQgMjk2LjAyNUw0MDYuODMyIDM2MS4wOEwzMDEuMDgxIDM3Ny43NUwyNTYuMjMzIDI3Ny44NTRMMTg0LjYzMyAzMDEuOTA3TDExNC4yMDMgMTkyLjczOEwxMDcuOTYzIDEwOS44NDNMMjgwLjc3NyAxMDguMDMyTDMyNC41MzQgMTc2LjkwNUw0MTcuODE5IDE1OS45MjlaJyBmaWxsPScjNDNEOUFEJy8+CjwvZz4KPGRlZnM+CjxmaWx0ZXIgaWQ9J2ZpbHRlcjBfZl82NF8xMjM0JyB4PScxNTMuMDQxJyB5PScxMjMuMjcxJyB3aWR0aD0nNTQ2LjUwOCcgaGVpZ2h0PSc1MTQuOTg3JyBmaWx0ZXJVbml0cz0ndXNlclNwYWNlT25Vc2UnIGNvbG9yLWludGVycG9sYXRpb24tZmlsdGVycz0nc1JHQic+CjxmZUZsb29kIGZsb29kLW9wYWNpdHk9JzAnIHJlc3VsdD0nQmFja2dyb3VuZEltYWdlRml4Jy8+CjxmZUJsZW5kIG1vZGU9J25vcm1hbCcgaW49J1NvdXJjZUdyYXBoaWMnIGluMj0nQmFja2dyb3VuZEltYWdlRml4JyByZXN1bHQ9J3NoYXBlJy8+CjxmZUdhdXNzaWFuQmx1ciBzdGREZXZpYXRpb249JzUzLjk3MjInIHJlc3VsdD0nZWZmZWN0MV9mb3JlZ3JvdW5kQmx1cl82NF8xMjM0Jy8+CjwvZmlsdGVyPgo8ZmlsdGVyIGlkPSdmaWx0ZXIxX2ZfNjRfMTIzNCcgeD0nMC4wMTg0NTU1JyB5PScwLjA4NzYwODMnIHdpZHRoPSc1MzUuOTknIGhlaWdodD0nNDg1LjYwNycgZmlsdGVyVW5pdHM9J3VzZXJTcGFjZU9uVXNlJyBjb2xvci1pbnRlcnBvbGF0aW9uLWZpbHRlcnM9J3NSR0InPgo8ZmVGbG9vZCBmbG9vZC1vcGFjaXR5PScwJyByZXN1bHQ9J0JhY2tncm91bmRJbWFnZUZpeCcvPgo8ZmVCbGVuZCBtb2RlPSdub3JtYWwnIGluPSdTb3VyY2VHcmFwaGljJyBpbjI9J0JhY2tncm91bmRJbWFnZUZpeCcgcmVzdWx0PSdzaGFwZScvPgo8ZmVHYXVzc2lhbkJsdXIgc3RkRGV2aWF0aW9uPSc1My45NzIyJyByZXN1bHQ9J2VmZmVjdDFfZm9yZWdyb3VuZEJsdXJfNjRfMTIzNCcvPgo8L2ZpbHRlcj4KPC9kZWZzPgo8L3N2Zz4K',
    },
    text6: {
      type: String,
      default: '_contact-me',
    },
    text1: {
      type: String,
      default: '> Front-end developer',
    },
    svg_src: {
      type: String,
      default:
        'data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMTEwNycgaGVpZ2h0PScxJyB2aWV3Qm94PScwIDAgMTEwNyAxJyBmaWxsPSdub25lJyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnPgo8cGF0aCBkPSdNMC44MDU0MiAwLjY2NDgyNUwxMTA2LjMxIDAuNjY0OTIyJyBzdHJva2U9JyMxRTJEM0QnIHN0cm9rZS13aWR0aD0nMC42MjAzNycvPgo8L3N2Zz4K',
    },
    text7: {
      type: String,
      default: '_hello',
    },
    image_src1: {
      type: String,
      default:
        'data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nNzcnIGhlaWdodD0nMycgdmlld0JveD0nMCAwIDc3IDMnIGZpbGw9J25vbmUnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zyc+CjxyZWN0IHg9JzAuNzQwNzIzJyB5PScwLjMwNTU0Micgd2lkdGg9Jzc1LjY4NTInIGhlaWdodD0nMS44NjExMScgZmlsbD0nI0ZFQTU1RicvPgo8L3N2Zz4K',
    },
    text9: {
      type: String,
      default: '_projects',
    },
    text: {
      type: String,
      default: 'Hello World',
    },
    svg_src2: {
      type: String,
      default:
        'data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMicgaGVpZ2h0PSczNScgdmlld0JveD0nMCAwIDIgMzUnIGZpbGw9J25vbmUnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zyc+CjxsaW5lIHgxPScxLjA1MDY2JyB5MT0nMC4yNjc3MzEnIHgyPScxLjA1MDY2JyB5Mj0nMzQuMzg4MScgc3Ryb2tlPScjMUUyRDNEJyBzdHJva2Utd2lkdGg9JzAuNjIwMzcnLz4KPC9zdmc+Cg==',
    },
    svg_alt5: {
      type: String,
      default: 'Line1I6413173515635182',
    },
    svg_src5: {
      type: String,
      default:
        'data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMicgaGVpZ2h0PSczNScgdmlld0JveD0nMCAwIDIgMzUnIGZpbGw9J25vbmUnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zyc+CjxsaW5lIHgxPScwLjc2Mzc5OCcgeTE9JzAuMjY3NzMxJyB4Mj0nMC43NjM3OTcnIHkyPSczNC4zODgxJyBzdHJva2U9JyMxRTJEM0QnIHN0cm9rZS13aWR0aD0nMC42MjAzNycvPgo8L3N2Zz4K',
    },
    text3: {
      type: String,
      default: '// you can also see it on my Github page',
    },
    text2: {
      type: String,
      default: 'Ivan Ryan',
    },
    text5: {
      type: String,
      default: 'ivan-ryan',
    },
    svg_src4: {
      type: String,
      default:
        'data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMScgaGVpZ2h0PSczNScgdmlld0JveD0nMCAwIDEgMzUnIGZpbGw9J25vbmUnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zyc+CjxsaW5lIHgxPScwLjY4MDMwMicgeTE9JzAuMjY3NzMxJyB4Mj0nMC42ODAzMDEnIHkyPSczNC4zODgxJyBzdHJva2U9JyMxRTJEM0QnIHN0cm9rZS13aWR0aD0nMC42MjAzNycvPgo8L3N2Zz4K',
    },
    text8: {
      type: String,
      default: '_about-me',
    },
    image_alt1: {
      type: String,
      default: 'Headerunderline641318',
    },
    image_src2: {
      type: String,
      default:
        'data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMTEwNycgaGVpZ2h0PSc1ODUnIHZpZXdCb3g9JzAgMCAxMTA3IDU4NScgZmlsbD0nbm9uZScgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJz4KPHJlY3QgeD0nMS4xMTU2MScgeT0nMS4xMTU3Nicgd2lkdGg9JzExMDQuODgnIGhlaWdodD0nNTgzLjM0Nycgcng9JzQuNjUyNzgnIGZpbGw9JyMwMTE2MjcnIHN0cm9rZT0nIzFFMkQzRCcgc3Ryb2tlLXdpZHRoPScwLjYyMDM3Jy8+Cjwvc3ZnPgo=',
    },
    svg_alt1: {
      type: String,
      default: 'Vector34I64131735123',
    },
    svg_alt2: {
      type: String,
      default: 'Line2I64131735136',
    },
    svg_alt4: {
      type: String,
      default: 'Line1I6413173515235182',
    },
    image_alt: {
      type: String,
      default: 'BackgroundBlurs641234',
    },
    svg_src1: {
      type: String,
      default:
        'data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMScgaGVpZ2h0PSczNicgdmlld0JveD0nMCAwIDEgMzYnIGZpbGw9J25vbmUnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zyc+CjxwYXRoIGQ9J00wLjM4ODY3MiAzNS42NjQ5TDAuMzg4NjczIDAuODA1NTg3JyBzdHJva2U9JyMxRTJEM0QnIHN0cm9rZS13aWR0aD0nMC42MjAzNycvPgo8L3N2Zz4K',
    },
    svg_alt: {
      type: String,
      default: 'Vector26I64131735118',
    },
    text4: {
      type: String,
      default: '// Example design 2022',
    },
    svg_src3: {
      type: String,
      default:
        'data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMScgaGVpZ2h0PSczNScgdmlld0JveD0nMCAwIDEgMzUnIGZpbGw9J25vbmUnIHhtbG5zPSdodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2Zyc+CjxsaW5lIHgxPScwLjU5NzA1JyB5MT0nMC4yNjc3MzEnIHgyPScwLjU5NzA0OScgeTI9JzM0LjM4ODEnIHN0cm9rZT0nIzFFMkQzRCcgc3Ryb2tlLXdpZHRoPScwLjYyMDM3Jy8+Cjwvc3ZnPgo=',
    },
  },

  data() {
    return {
      raw4t8a: ' ',
      raw4nq1: ' ',
    }
  },
}
</script>

<style scoped>
.porfoliohomedesktop641227-porfoliohomedesktop641227 {
  width: 1191px;
  height: 670px;
  display: flex;
  overflow: hidden;
  position: relative;
  max-width: 1191px;
  box-sizing: border-box;
  align-items: flex-start;
  border-color: transparent;
  background-color: rgba(1, 12, 21, 1);
}
.porfoliohomedesktop641227-container {
  display: flex;
  position: relative;
}
.porfoliohomedesktop641227-image {
  width: 1106px;
  height: 584px;
  position: relative;
  object-fit: cover;
  border-color: rgba(30, 45, 61, 1);
  border-style: solid;
  border-width: 0.6203703284263611px;
  border-radius: 4.962962627410889px;
  background-color: rgba(1, 22, 39, 1);
}
.porfoliohomedesktop641227-text {
  top: 242.5741424560547px;
  left: 235.95631408691406px;
  color: rgba(229, 233, 240, 1);
  height: auto;
  position: absolute;
  font-size: 11.166666030883789px;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-family: Fira Code;
  font-weight: 400px;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-text01 {
  top: 303.99078369140625px;
  left: 235.95631408691406px;
  color: rgba(77, 91, 206, 1);
  height: auto;
  position: absolute;
  font-size: 19.851850509643555px;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-family: Fira Code;
  font-weight: 400px;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-text02 {
  top: 257.4630126953125px;
  left: 235.7407989501953px;
  color: rgba(229, 233, 240, 1);
  height: auto;
  position: absolute;
  font-size: 38.46296310424805px;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-family: Fira Code;
  font-weight: 400px;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-image1 {
  top: 110.931396484375px;
  left: 607.962890625px;
  width: 484px;
  height: 460px;
  position: absolute;
  object-fit: cover;
  border-color: transparent;
}
.porfoliohomedesktop641227-text03 {
  top: 399.3713073730469px;
  left: 235.95631408691406px;
  color: rgba(96, 123, 150, 1);
  height: auto;
  position: absolute;
  font-size: 9.925925254821777px;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-family: Fira Code;
  font-weight: 400px;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-text04 {
  top: 380.3416748046875px;
  left: 235.95631408691406px;
  color: rgba(96, 123, 150, 1);
  height: auto;
  position: absolute;
  font-size: 9.925925254821777px;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-family: Fira Code;
  font-weight: 400px;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-text05 {
  top: 418.3588562011719px;
  left: 235.7407989501953px;
  color: rgba(77, 91, 206, 1);
  height: auto;
  position: absolute;
  font-size: 9.925925254821777px;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-family: Fira Code;
  font-weight: 500px;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-text06 {
  color: rgba(77, 91, 206, 1);
  height: auto;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-weight: 500px;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-text07 {
  color: rgba(255, 255, 255, 1);
  height: auto;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-weight: 500px;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-text08 {
  color: rgba(67, 217, 173, 1);
  height: auto;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-weight: 500px;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-text09 {
  color: rgba(255, 255, 255, 1);
  height: auto;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-weight: 500px;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-text10 {
  color: rgba(233, 146, 135, 1);
  height: auto;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-weight: 500px;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-text11 {
  color: rgba(233, 146, 135, 1);
  height: auto;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-weight: 500px;
  font-stretch: normal;
  text-decoration: underline;
}
.porfoliohomedesktop641227-header641317 {
  top: 42.80556106567383px;
  left: 42.805519104003906px;
  width: 1105px;
  height: 34.859352111816406px;
  display: flex;
  position: absolute;
  box-sizing: border-box;
  align-items: flex-start;
  border-color: transparent;
}
.porfoliohomedesktop641227-text12 {
  top: 10.915776252746582px;
  left: 13.648147583007812px;
  color: rgba(96, 123, 150, 1);
  height: auto;
  position: absolute;
  font-size: 9.925925254821777px;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-family: Fira Code;
  font-weight: 400px;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-text13 {
  top: 10.915776252746582px;
  left: 1024.457763671875px;
  color: rgba(96, 123, 150, 1);
  height: auto;
  position: absolute;
  font-size: 9.925925254821777px;
  align-self: auto;
  font-style: normal;
  text-align: right;
  font-family: Fira Code;
  font-weight: 400px;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-svg {
  top: 34.8592529296875px;
  width: 0;
  height: 1105;
  position: absolute;
}
.porfoliohomedesktop641227-svg1 {
  top: 34.85932922363281px;
  left: 1010.5834350585938px;
  width: 35;
  height: 0;
  position: absolute;
}
.porfoliohomedesktop641227-svg2 {
  top: 0.46217286586761475px;
  left: 192.93516540527344px;
  width: 34;
  height: 1px;
  position: absolute;
}
.porfoliohomedesktop641227-frame1i64131735155 {
  top: 0.46217286586761475px;
  left: 192.89813232421875px;
  width: 261px;
  display: flex;
  position: absolute;
  box-sizing: border-box;
  align-items: center;
  flex-shrink: 1;
  border-color: transparent;
}
.porfoliohomedesktop641227-header-text-i64131735149 {
  display: flex;
  padding: 0 0 0 19.851850509643555px;
  position: relative;
  box-sizing: border-box;
  align-items: center;
  flex-shrink: 1;
  border-color: transparent;
  justify-content: center;
}
.porfoliohomedesktop641227-text14 {
  color: rgba(255, 255, 255, 1);
  height: auto;
  margin: 0 19.23147964477539px 0 0;
  font-size: 9.925925254821777px;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-family: Fira Code;
  font-weight: 400px;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-svg3 {
  width: 34;
  height: 1px;
}
.porfoliohomedesktop641227-component5i64131735152 {
  display: flex;
  padding: 0 0 0 19.851850509643555px;
  position: relative;
  box-sizing: border-box;
  align-items: center;
  flex-shrink: 1;
  border-color: transparent;
  justify-content: center;
}
.porfoliohomedesktop641227-text15 {
  color: rgba(96, 123, 150, 1);
  height: auto;
  margin: 0 19.23147964477539px 0 0;
  font-size: 9.925925254821777px;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-family: Fira Code;
  font-weight: 400px;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-svg4 {
  width: 34;
  height: 1px;
}
.porfoliohomedesktop641227-component6i64131735156 {
  display: flex;
  padding: 0 0 0 19.851850509643555px;
  position: relative;
  box-sizing: border-box;
  align-items: center;
  flex-shrink: 1;
  border-color: transparent;
  justify-content: center;
}
.porfoliohomedesktop641227-text16 {
  color: rgba(96, 123, 150, 1);
  height: auto;
  margin: 0 19.23147964477539px 0 0;
  font-size: 9.925925254821777px;
  align-self: auto;
  font-style: normal;
  text-align: left;
  font-family: Fira Code;
  font-weight: 400px;
  line-height: normal;
  font-stretch: normal;
  text-decoration: none;
}
.porfoliohomedesktop641227-svg5 {
  width: 34;
  height: 1px;
}
.porfoliohomedesktop641227-image2 {
  top: 76.3055419921875px;
  left: 235.7407989501953px;
  width: 76px;
  height: 2px;
  position: absolute;
  object-fit: cover;
  border-color: transparent;
  background-color: rgba(254, 165, 95, 1);
}
</style>
