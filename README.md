# Simple SVG Brand Logos

## Description

A collection of simplified brand logos. Oftentimes those are only available on sketchy, ad-laden download sites, are of poor quality and need lots of cleaning up. This repository aims to help developers and designers to find high quality logos of any kind in one place. Also, all the color is stripped so they can be used in a consistent manner.

## Contributing

Make sure you have a vector editing tool (like [Inkscape](https://inkscape.org/) or [Adobe Illustrator](https://www.adobe.com/products/illustrator/) — I use [Affinity Designer](https://affinity.serif.com/designer/)) and [svgo](https://github.com/svg/svgo). Please be aware that by contributing, you agree that your submission will enter the public domain.

1. Acquire source vector file
2. Simplify logo in a vector editing tool
  - Constrain to a max width and height of 128px
  - Strive for no strokes
  - Simplify and minimise paths by joining into curves
  - No layers whatsoever
  - Make all paths black
  - Export SVG
3. Run `svgo` on the SVG file (`svgo --multipass -i file.svg`)

## Legal Notice

All brand graphics and associated names are trademarks and/or property of their respective owners. This repository does not have any affiliation with them nor does it claim to. Should any brand owner feel that their rights are misrepresented in any way, please open an issue with a valid contact address. The claim will be followed up on and the appropriate assets removed if warranted.

## List

<img src="https://cdn.rawgit.com/herrbischoff/simple-svg-brand-logos/master/logos/3com.svg" width="128" style="margin-right: 25px">
<img src="https://cdn.rawgit.com/herrbischoff/simple-svg-brand-logos/master/logos/3m.svg" width="128">
<img src="https://cdn.rawgit.com/herrbischoff/simple-svg-brand-logos/master/logos/500px.svg" width="128">

## License

The following license applies exclusively to the source code of this repository. It explicitly excludes any right to use the brand assets in any context. We cannot license what we don't own. If you plan to use an asset for anthing else than personal learning, you need to clear the appropriate usage rights with the respective trademark owner.

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://github.com/herrbischoff/simple-svg-brand-logos/graphs/contributors">
    <span property="dct:title">the contributors of this repository</span></a>
  have waived all copyright and related or neighboring rights to
  <span property="dct:title">Simple SVG Brand Logos</span>.
</p>
