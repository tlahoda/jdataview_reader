jDataViewReader
===============

jDataViewReader wraps jdataview to provide sequential read usage semantics.

Interface
---------

####Constructor
A jDataViewReader is constructed by passing in a valid jDataView object.

```javascript
function jDataViewReader (jdataview)
```

####Members
+ **readInt8**  
Reads an 8 bit int.  

```javascript
function readInt8 ()
```
#####returns
int


+ **readUInt8**  
Reads an 8 bit unsigned int.  

```javascript
function readUInt8 ()
```

+ **readInt16**  
Reads a 16 bit int.

```javascript
function readInt16 (littleEndian)
```

+ **readUInt16**  
Reads a 16 bit unsigned int.

```javascript
function readUInt16 (littleEndian)
```

+ **readInt32**  
Reads a 32 bit int.

```javascript
function readInt32 (littleEndian)
```

+ **readUInt32**  
Reads a 32 bit unsigned int.

```javascript
function readUInt32 (littleEndian)
```

+ **readFloat**  
Reads a 32 bit float.

```javascript
function readFloat (littleEndian)
```

+ **readDouble**  
Reads a 64 bit double.

```javascript
function readDouble (littleEndian)
```

+ **readChar**  
Reads a char.

```javascript
function readChar ()
```

+ **readString**  
Reads a string of the given length.

```javascript
function readString (length)
```

+ **seek**  
Seeks to pos.

```javascript
function seek (pos)
```

+ **tell**  
Tells where you are in the data.

```javascript
function tell ()
```

Usage
-----


####Copyright (C) 2011 Thomas P. Lahoda

This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  
02110-1301  USA

