# minify
[terser](https://github.com/terser/terser) and [clean-css](https://github.com/clean-css/clean-css) bundled as a single stand-alone executable for easy toolchain integration.

# why
If you are like me and you hate the trainwreck that is Node.Js and the ridiculously immature and subpar JavaScript ecosystem, then you don't want crap like Node.Js or npm anywhere near your toolchain. If you are building a website, you may naturally still want to minify/bundle your assets, but sadly virtually all JavaScript and CSS minifiers out there are written in Node.Js and so it's a major PITA to use them.

I was so fed up with this that I put together this thing that packages [terser](https://github.com/terser/terser) and [clean-css](https://github.com/clean-css/clean-css) in a single stand-alone executable that you can just copy to wherever you need it and you don't have to worry about crappy Node.js and it's weekly breaking changes and countless other nuisances.

# usage
    ./minify terser|cleancss <option>
     
    # Invoke terser
    ./minify terser --help
  
    # Invoke clean-css
    ./minify cleancss --help
