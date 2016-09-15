# Custom D3 build

Derived from [this example](https://bl.ocks.org/mbostock/bb09af4c39c79cffcde4) and the [full D3 build](https://github.com/d3/d3).


To build, do

- `npm i`;
- Make any changes you need
- `npm run build`. The newly built js files will be in the `./build` directiory.
- To make the commit history clean, revert chnages to the `build` folder before commiting. Changes to `build` commited using the below process.

To publish (after commiting your changes):
- `npm run build`
- Bump the version number `MSW-tag` in `package.json`.
- `npm run publish`. This adds and commits the built files, tags the commit with `MSW-tag` and `git push`s.

