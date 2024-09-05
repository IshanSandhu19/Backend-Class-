<!-- Microsoft Windows [Version 10.0.22631.4037]
(c) Microsoft Corporation. All rights reserved.

C:\Users\ISHAN SANDHU>mongosh
Current Mongosh Log ID: 66d932fe593c27abea2710bb
Connecting to:          mongodb://127.0.0.1:27017/?directConnection=true&serverSelectionTimeoutMS=2000&appName=mongosh+2.3.0
Using MongoDB:          7.0.14
Using Mongosh:          2.3.0

For mongosh info see: https://www.mongodb.com/docs/mongodb-shell/


To help improve our products, anonymous usage data is collected and sent to MongoDB periodically (https://www.mongodb.com/legal/privacy-policy).
You can opt-out by running the disableTelemetry() command.

------
   The server generated these startup warnings when booting
   2024-08-31T19:54:28.897+05:30: Access control is not enabled for the database. Read and write access to data and configuration is unrestricted
------

test> use ishan sandhu
switched to db ishan
ishan> db.createCollection
[Function: createCollection] AsyncFunction {
  apiVersions: [ 1, Infinity ],
  returnsPromise: true,
  serverVersions: [ '0.0.0', '999.999.999' ],
  topologies: [ 'ReplSet', 'Sharded', 'LoadBalanced', 'Standalone' ],
  returnType: { type: 'unknown', attributes: {} },
  deprecated: false,
  platforms: [ 'Compass', 'Browser', 'CLI' ],
  isDirectShellCommand: false,
  acceptsRawInput: false,
  shellCommandCompleter: undefined,
  help: [Function (anonymous)] Help
}
ishan> db.createCollection("Student")
{ ok: 1 }
ishan> db.user.insertMany([{name:"Jack",age:20,marks:85,subject :"Mathematcis"},{name:"Bob",age:22,marks:78,subject:"Physics"},{name:"Nav",age:21,marks:92,subject:"Chemistry"},{name:"Hitesh",age:19,marks:90,subject:"Chemistry"}])
{
  acknowledged: true,
  insertedIds: {
    '0': ObjectId('66d933df593c27abea2710bc'),
    '1': ObjectId('66d933df593c27abea2710bd'),
    '2': ObjectId('66d933df593c27abea2710be'),
    '3': ObjectId('66d933df593c27abea2710bf')
  }
}
ishan> db.createCollection("Faculty")
{ ok: 1 }
ishan> db.Student.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Matheishan> db.Student.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subjPandat> db.Student.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subject:"Physics"},{name:"Naiv",age:56,rating:92,subject:"Chemistry"}
,{name:"CHinky",age:45,rating:90,subject:"Chemistry"}])
Uncaught:
SyntaxError: Unexpected token, expected "," (1:118)

> 1 | db.Student.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subjPandat> db.Student.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subject:"Physics"},{name:"Naiv",age:56,rating:92,subject:"Chemistry"},{name:"CHinky",age:45,rating:90,subject:"Chemistry"}])
    |
                                                ^
  2 |

ishan> db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Matheishan> db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subjPandat> db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subject:"Physics"},{name:"Naiv",age:56,rating:92,subject:"Chemistry"},{name:"CHinky",age:45,rating:90,subject:"Chemistry"}])
Uncaught:
SyntaxError: Unexpected token, expected "," (1:118)

> 1 | db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subjPandat> db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subject:"Physics"},{name:"Naiv",age:56,rating:92,subject:"Chemistry"},{name:"CHinky",age:45,rating:90,subject:"Chemistry"}])
    |
                                                ^
  2 |

ishan> db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Matheishan> db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subjPandat> db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subject:"Physics"},{name:"Naiv",age:56,rating:92,subject:"Chemistry"},{name:"CHinky",age:45,rating:90,subject:"Chemistry"}])
Uncaught:
SyntaxError: Unexpected token, expected "," (1:118)

> 1 | db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subjPandat> db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subject:"Physics"},{name:"Naiv",age:56,rating:92,subject:"Chemistry"},{name:"CHinky",age:45,rating:90,subject:"Chemistry"}])
    |
                                                ^
  2 |

ishan> db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subjPandat> db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subject:"Physics"},{name:"Naiv",age:56,rating:92,subject:"Chemistry"},{name:"CHinky",age:45,rating:90,subject:"Chemistry"}])
Uncaught:
SyntaxError: Unexpected token, expected "," (1:118)

> 1 | db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subjPandat> db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematcis"},{name:"Boby",age:82,rating:78,subject:"Physics"},{name:"Naiv",age:56,rating:92,subject:"Chemistry"},{name:"CHinky",age:45,rating:90,subject:"Chemistry"}])
    |
                                                ^
  2 |

ishan> db.Faculty.insertMany([{name:"Jaiko",age:60,rating:85,subject :"Mathematics"},{name:"Boby",age:82,rating:78,subject:"Home Science"}])
{
  acknowledged: true,
  insertedIds: {
    '0': ObjectId('66d936b4593c27abea2710c0'),
    '1': ObjectId('66d936b4593c27abea2710c1')
  }
}
ishan> db.user.countDocuments()
4
ishan> db.Faculty.countDocuments()
2
ishan> db.student.estimatedDocumentCount()
0
ishan> db.userInsertOne({date:ISODate()});
TypeError: db.userInsertOne is not a function
ishan> db.user.InsertOne({date:ISODate()});
TypeError: db.user.InsertOne is not a function
ishan> db.user.insertOne({date:ISODate()});
{
  acknowledged: true,
  insertedId: ObjectId('66d93767593c27abea2710c2')
}
ishan> db.user.find().pretty();
[
  {
    _id: ObjectId('66d933df593c27abea2710bc'),
    name: 'Jack',
    age: 20,
    marks: 85,
    subject: 'Mathematcis'
  },
  {
    _id: ObjectId('66d933df593c27abea2710bd'),
    name: 'Bob',
    age: 22,
    marks: 78,
    subject: 'Physics'
  },
  {
    _id: ObjectId('66d933df593c27abea2710be'),
    name: 'Nav',
    age: 21,
    marks: 92,
    subject: 'Chemistry'
  },
  {
    _id: ObjectId('66d933df593c27abea2710bf'),
    name: 'Hitesh',
    age: 19,
    marks: 90,
    subject: 'Chemistry'
  },
  {
    _id: ObjectId('66d93767593c27abea2710c2'),
    date: ISODate('2024-09-05T04:45:27.678Z')
  }
]
ishan> db.user.findOne();
{
  _id: ObjectId('66d933df593c27abea2710bc'),
  name: 'Jack',
  age: 20,
  marks: 85,
  subject: 'Mathematcis'
}
ishan> db.student.updateMany({},{$set:{Student:"DataScience",address:"Chitkara University"}})
{
  acknowledged: true,
  insertedId: null,
  matchedCount: 0,
  modifiedCount: 0,
  upsertedCount: 0
}
ishan> db.students.bulkWrite([{updateOne: { filter: { name: "Jack" },   update: { $set: { grade: "A" } } } }, {    updaupdateOne: {filter: { name: "Bob" }, update: { $set: { grade: "B" } } } }, {updateOne: {filter: { name: "Nav" },
... ...       update: { $set: { grade: "A+" } }
Uncaught:
SyntaxError: Unexpected token, expected "," (2:16)

  1 | db.students.bulkWrite([{updateOne: { filter: { name: "Jack" },   update: { $set: { grade: "A" } } } }, {    updaupdateOne: {filter: { name: "Bob" }, update: { $set: { grade: "B" } } } }, {updateOne: {filter: { name: "Nav" },
> 2 | ...       update: { $set: { grade: "A+" } }
    |                 ^
  3 |

ishan> b.Student.bulkWrite([
... ...     { updateOne: { filter: { name: "Jaiko" }, update: { $set: { gradgrade: "A" } } } },
... ...     { updateOne: { filter: { name: "Boby" }, update: { $set: { gradegrade: "B" } } } },
... ...     { updateOne: { filter: { name: "Naiv" }, update: { $set: { gradegrade: "A+" } } } },
... ...     { updateOne: { filter: { name: "Chinky" }, update: { $set: { gragrade: "A" } } } }
... ... ])
Uncaught:
SyntaxError: Unexpected token, expected "," (6:0)

  4 | ...     { updateOne: { filter: { name: "Naiv" }, update: { $set: { grade: "A+" } } } },
  5 | ...     { updateOne: { filter: { name: "Chinky" }, update: { $set: { grade: "A" } } } }
> 6 | ... ])
    | ^
  7 |

ishan> db.Student.bulkWrite([ ...     { updateOne: { filter: { name: "Jaiko" }, update: { $set: { grade: "A" } } } }, ...     { updateOne: { filter: { name: "Boby" }, update: { $set: { grade: "B" } } } }, ...     { updateOne: { filter: { name: "Naiv" }, update: { $set: { grade: "A+" } } } }, ...     { updateOne: { filter: { name: "Chinky" }, update: { $set: { grade: "A" } } } } ... ])
Uncaught:
SyntaxError: Unexpected token, expected "," (1:374)

> 1 | db.Student.bulkWrite([ ...     { updateOne: { filter: { name: "Jaiko" }, update: { $set: { grade: "A" } } } }, ...     { updateOne: { filter: { name: "Boby" }, update: { $set: { grade: "B" } } } }, ...     { updateOne: { filter: { name: "Naiv" }, update: { $set: { grade: "A+" } } } }, ...     { updateOne: { filter: { name: "Chinky" }, update: { $set: { grade: "A" } } } } ... ])
    |




^
  2 |

ishan> db.Student.bulkWrite([ ...     { updateOne: { filter: { name: "Jaiko" }, update: { $set: { grade: "A" } } } }, ...     { updateOne: { filter: { name: "Boby" }, update: { $set: { grade: "B" } } } }, ...     { updateOne: { filter: { name: "Naiv" }, update: { $set: { grade: "A+" } } } }, ...     { updateOne: { filter: { name: "Chinky" }, update: { $set: { grade: "A" } } } } ... ])
Uncaught:
SyntaxError: Unexpected token, expected "," (1:374)

> 1 | db.Student.bulkWrite([ ...     { updateOne: { filter: { name: "Jaiko" }, update: { $set: { grade: "A" } } } }, ...     { updateOne: { filter: { name: "Boby" }, update: { $set: { grade: "B" } } } }, ...     { updateOne: { filter: { name: "Naiv" }, update: { $set: { grade: "A+" } } } }, ...     { updateOne: { filter: { name: "Chinky" }, update: { $set: { grade: "A" } } } } ... ])
    |




^
  2 |

ishan> db.Student.bulkWrite([ ...     { updateOne: { filter: { name: "Jaiko" }, update: { $set: { grade: "A" } } } }, ...     { updateOne: { filter: { name: "Boby" }, update: { $set: { grade: "B" } } } }, ...     { updateOne: { filter: { name: "Naiv" }, update: { $set: { grade: "A+" } } } }, ...     { updateOne: { filter: { name: "Chinky" }, update: { $set: { grade: "A" } } } } ])
TypeError: {(intermediate value)} is not iterable
ishan> b.Student.bulkWrite([ ...     { updateOne: { filter: { name: "Jaiko" }, update: { $set: { grade: "A" } } } }, ...     { updateOne: { filter: { name: "Boby" }, update: { $set: { grade: "B" } } } }, ...     { updateOne: { filter: { name: "Naiv" }, update: { $set: { grade: "A+" } } } }, ...     { updateOne: { filter: { name: "Chinky" }, update: { $set: { grade: "A" } } } }  ])
ReferenceError: b is not defined
ishan> db.Student.bulkWrite([ ...     { updateOne: { filter: { name: "Jaiko" }, update: { $set: { grade: "A" } } } }, ...     { updateOne: { filter: { name: "Boby" }, update: { $set: { grade: "B" } } } }, ...     { updateOne: { filter: { name: "Naiv" }, update: { $set: { grade: "A+" } } } }, ...     { updateOne: { filter: { name: "Chinky" }, update: { $set: { grade: "A" } } } }  ])
TypeError: {(intermediate value)} is not iterable
ishan> db.Student.bulkWrite([ { updateOne: { filter: { name: "Jaiko" }, update: { $set: { grade: "A" } } } }, { updateOne: { filter: { name: "Boby" }, update: { $set: { grade: "B" } } } }, { updateOne: { filter: { name: "Naiv" }, update: { $set: { grade: "A+" } } } }, { updateOne: { filter: { name: "CHinky" }, update: { $set: { grade: "A" } } } }] );
{
  acknowledged: true,
  insertedCount: 0,
  insertedIds: {},
  matchedCount: 0,
  modifiedCount: 0,
  deletedCount: 0,
  upsertedCount: 0,
  upsertedIds: {}
}
ishan> db.Student.find({ age: 22, marks: 90 })

ishan> db.Student.find({ grade: "A+" })

ishan> db.student.find({ grade: "A+" })

ishan> db.Student.find({ grade: "A" }) -->