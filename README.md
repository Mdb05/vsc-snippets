# VsCode snippets

[![Version](https://vsmarketplacebadge.apphb.com/version/mdb05.vscsnippets.svg)](https://marketplace.visualstudio.com/items?itemName=mdb05.vscsnippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/mdb05.vscsnippets.svg)](https://marketplace.visualstudio.com/items?itemName=mdb05.vscsnippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/mdb05.vscsnippets.svg)](https://marketplace.visualstudio.com/items?itemName=mdb05.vscsnippets)

This extension contains code snippets for [Vs Code][code] editor.

## Installation

In order to install an extension you need to launch the Command Palette (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones. Search for *VsCode snippets* and install it.

## Supported languages (runs globaly)
* JavaScript
* Sql

## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

### Class helpers
| Trigger  | Content |
| -------: | ------- |
| `cls→`   | creates class `class() {}`|
| `con→`   | adds default constructor in the class `constructor() {}`|
| `fn→`   | creates a method inside a class `add() {}` |
| `gt→`   | creates a getter property `get propertyName() {return value;}` |
| `st→`   | creates a setter property `set propertyName(value) {}` |
|`co→`| create object |
|`no→`| initialize new object `const obj1 = new obj()` |


### Loops and coditions
| Trigger  | Content |
| -------: | ------- |
| `fe→`   | forEach loop in ES6 syntax `array.forEach(currentItem => {})`|
| `fo→`   | for ... of loop `for(const item of object) {}` |
| `fi→`   | for ... in loop `for(const item in object) {}` |
| `sw→`   | Switch statement |
| `wh→`   | While statement |
| `dwh→`   | Do While statement |
| `if→`   | if statement |
| `ife→`   | if else statement |
| `elif→`   | if else if statement |

### Various methods
| Trigger  | Content |
| -------: | ------- |
| `find→`  |`let ele = array.find(() => )`|
| `map→`  |`let newArray = array.map(() => )`|
| `filter→` |`let newArray = array.filter(() => )`|
| `afn→`  | creates an anonymous function `(params) => {}` |
| `ff→`   | creates an factory function `const method (params) => { return {}}` |
| `nfn→`   | creates a named function `const add = (params) => {}` |
| `dob→`   | destructing object syntax `const {rename} = fs` |
| `dar→`   | destructing array syntax `const [first, second] = [1,2]` |
| `sti→`   | set interval helper method `setInterval(() => {});` |
| `sto→`   | set timeout helper method `setTimeout(() => {});` |
| `tl→`   | template leteral `as {a} {b}` |
| `dt→`   | `/* h : d/m/y */`|

### Console methods
| Trigger  | Content |
| -------: | ------- |
| `cl→`   | console alert method `console.assert(expression, object)`|
| `cl→`   | console clear `console.clear()` |
| `cl→`   | console count `console.count(label)` |
| `cl→`   | console debug `console.debug(object)` |
| `cl→`   | console dir `console.dir` |
| `cl→`   | console error `console.error(object)` |
| `cl→`   | console group `console.group(label)` |
| `cl→`   | console groupEnd `console.groupEnd()` |
| `cl→`   | console log `console.log(object)` |
| `cl→`   | console log object with name `console.log('object :>> ', object);` |
| `cl→`   | console trace `console.trace(object)` |
| `cl→`   | console warn `console.warn` |
| `cl→`   | console info `console.info` |
| `cl→`   | console table `console.table` |
| `cl→`   | console time `console.time` |
| `cl→`   | console timeEnd `console.timeEnd` |


### SQL
| Trigger  | Content |
| -------: | ------- |
| `tp→`   |  Data types : `INT,CHAR(55),NVARCHAR(55),BIT,FLOAT,DOUBLE,DECIMAL,DATE,DATETIME,MONEY,NTEXT,VARBINARY,IMAGE,XML`  |
| `cn→`   |  Constraints : `IDENTITY(1,1),NOT NULL,UNIQUE,PRIMARY KEY,FOREIGN KEY,CHECK,DEFAULT,INDEX` |
| `cdb→`   | `CREATE DATABASE dbname;` |
| `ddb→`   | `DROP DATABASE dbname;` |
| `bdb→`   | `BACKUP DATABASE dbname TO DISK = filepath;` |
| `ctb→`   | `CREATE TABLE tablename;` |
| `dtb→`   | `DROP TABLE tablename;` |
| `acl→`   | `ALTER TABLE table_name ADD column_name datatype;`|
| `mcl→`   | `ALTER TABLE table_name ALTER column_name datatype;`|
| `dcl→`   | `ALTER TABLE table_name DROP column_name`|
| `acn→`   | `ALTER TABLE table_name ADD CONSTRAINT` |
| `dcn→`   | `ALTER TABLE table_name DROP CONSTRAINT` |
| `ref→`| `REFERENCES tablename columname;`|
| `sl→`   |`SELECT * FROM table_name;` |
| `ii→`   |`INSERT INTO table_name (columns) VALUES() `|
| `up→`   |`UPDATE table_name SET Col = Val WHERE` |
| `dl→`   | `DELETE FROM table_name WHERE`|
| `ind→`   |`CREATE UNIQUE INDEX index_name ON table_name (column1,column2) ;` |
| `view→` |`CREATE OR REPLACE VIEW [view_name] AS` |
| `dview→`| `DROP [view_name];`|
| `pro→`   | `CREATE PROCEDURE procudure_name @param AS`|
| `xpro→`| `EXEC PROCEDURE procudure_name @param = value ;`|
| `injoin→`   |`INNER JOIN table2 ON table1.column_name = table2.column_name;`|
| `ljoin→`   |`LEFT JOIN table2 ON table1.column_name = table2.column_name;`|
| `rjoin→`   |`RIGHT JOIN table2 ON table1.column_name = table2.column_name;`|
| `fjoin→`   |`FULL OUTER JOIN table2 ON table1.column_name = table2.column_name;`|



[code]: https://code.visualstudio.com/
