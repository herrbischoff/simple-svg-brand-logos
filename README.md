# Simple SVG Brand Logos

## Description

A collection of simplified brand logos. Oftentimes those are only available on sketchy, ad-laden download sites, are of poor quality and need lots of cleaning up. This repository aims to help developers and designers to find high quality logos of any kind in one place. Also, all the color is stripped so they can be used in a consistent manner.

## Contributing

Make sure you have a vector editing tool (I use [Affinity Designer](https://affinity.serif.com/)) and [svgo](https://github.com/svg/svgo). 

1. Acquire source vector file
2. Simplify logo in a vector editing tool
  - Constrain within a 64x64 viewbox
  - Ensure there are no strokes
  - Simplify and minimise paths by joining into one curve
  - If a logo can be used with and without a brand text, keep the logo graphic and text in separate layers
  - Make all paths white
  - Export SVG
3. Run `svgo` on the SVG file (`svgo --multipass -i file.svg`)

## Legal Notice

All brand graphics and associated names are trademarks and/or property of their respective owners. This repository does not have any affiliation with them nor does it claim to. Should any brand owner feel that their rights are misrepresented in any way, please open an issue with a valid contact address. I will investigate the claim and remove the appropriate assets if warranted.

## License

This license applies exclusively to the source code of this repository. It explicitly excludes any right to use the brand assets in any context. We cannot license what we don't own. Please clear those usage rights with the respective trademark owner.

Copyright © 2015 https://github.com/herrbischoff/simple-svg-brand-logos/graphs/contributors

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE
OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
