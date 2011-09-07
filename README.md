jDataViewReader
===============

jDataViewReader wraps jdataview to provide sequential read usage semantics.

Usage
-----

####Construction
A jDataViewReader is constructed by passing in a valid jDataView object.

```javascript
function jDataViewReader (jdataview)
```

```javascript
var buffer = new Array (25);//fill with some binary data
var reader = new jDataViewReader (new jDataView (buffer));
```

####Members
#####readInt8

```javascript
function readInt8 ()
```

#####readUInt8

```javascript
function readUInt8 ()
```

#####readInt16

```javascript
function readInt16 (littleEndian)
```

#####readUInt16

```javascript
function readUInt16 (littleEndian)
```

#####readInt32

```javascript
function readInt32 (littleEndian)
```

#####readUInt32

```javascript
function readUInt32 (littleEndian)
```

#####readFloat

```javascript
function readFloat (littleEndian)
```

#####readDouble

```javascript
function readDouble (littleEndian)
```

#####readChar

```javascript
function readChar ()
```

#####readString

```javascript
function readString (length)
```

#####seek

```javascript
function seek (pos)
```

#####tell

```javascript
function tell ()
```


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

