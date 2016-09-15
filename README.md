# Custom D3 build

Derived from [this example](https://bl.ocks.org/mbostock/bb09af4c39c79cffcde4) and the [full D3 build](https://github.com/d3/d3).


To build, do

- `npm i`;
- Make any changes you need
- `npm run build`. The newly built js files will be in the `./build` directiory.

To publish (after commiting your changes and doing a build):
- Bump the version number `MSW-tag` in `package.json`.
- `npm run publish`. This adds and commits the built files, tags the commit with `MSW-tag` and `git push`s.

