
A simple demo integrating SQLite WASM with a datagrid

Uses:
* https://sqlite.org/wasm/doc/trunk/about.md
* https://github.com/handsontable/handsontable (via https://github.com/topics/datagrid?l=javascript)
* https://github.com/jpwhite3/northwind-SQLite3/

Vendoring in SQLite and the Northwind create script is done with `./vendor.sh`, then the datagrid with `npm init -y && npm install handsontable && mv node_modules/handsontable/dist handsontable`
