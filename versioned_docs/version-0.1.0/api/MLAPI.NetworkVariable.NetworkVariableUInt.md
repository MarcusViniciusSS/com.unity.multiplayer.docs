---  
id: MLAPI.NetworkVariable.NetworkVariableUInt  
title: MLAPI.NetworkVariable.NetworkVariableUInt
---

<div class="markdown level0 summary">

A NetworkVariable that holds uints and support serialization

</div>

<div class="markdown level0 conceptual">

</div>

<div class="inheritance">

##### Inheritance

<div class="level0">

System.Dynamic.ExpandoObject

</div>

<div class="level1">

System.Dynamic.ExpandoObject

</div>

<div class="level2">

System.Dynamic.ExpandoObject

</div>

</div>

<div classs="implements">

##### Implements

<div>

INetworkVariable

</div>

</div>

<div class="inheritedMembers">

##### Inherited Members

<div>

NetworkVariable&lt;UInt32&gt;.Settings"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.LocalTick"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.RemoteTick"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.OnValueChanged"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.Value"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.SetDirty(Boolean)"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.IsDirty()"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.ResetDirty()"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.CanClientRead(UInt64)"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.WriteDelta(Stream)"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.CanClientWrite(UInt64)"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.ReadDelta(Stream, Boolean, UInt16,
UInt16)"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.SetNetworkBehaviour(NetworkBehaviour)"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.ReadField(Stream, UInt16, UInt16)"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.WriteField(Stream)"

</div>

<div>

NetworkVariable&lt;UInt32&gt;.GetChannel()"

</div>

<div>

Object.Equals(Object)

</div>

<div>

Object.Equals(Object, Object)

</div>

<div>

Object.GetHashCode()

</div>

<div>

Object.GetType()

</div>

<div>

Object.MemberwiseClone()

</div>

<div>

Object.ReferenceEquals(Object, Object)

</div>

<div>

Object.ToString()

</div>

</div>

##### **Namespace**: System.Dynamic.ExpandoObject

##### **Assembly**: MLAPI.dll

##### Syntax

    [Serializable]
    public class NetworkVariableUInt : NetworkVariable<uint>, INetworkVariable

## Constructors 

### NetworkVariableUInt()

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

    public NetworkVariableUInt()

### NetworkVariableUInt(NetworkVariableSettings)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

    public NetworkVariableUInt(NetworkVariableSettings settings)

#### Parameters

| Type                    | Name     | Description |
|-------------------------|----------|-------------|
| NetworkVariableSettings | settings |             |

### NetworkVariableUInt(NetworkVariableSettings, UInt32)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

    public NetworkVariableUInt(NetworkVariableSettings settings, uint value)

#### Parameters

| Type                    | Name     | Description |
|-------------------------|----------|-------------|
| NetworkVariableSettings | settings |             |
| System.UInt32           | value    |             |

### NetworkVariableUInt(UInt32)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

    public NetworkVariableUInt(uint value)

#### Parameters

| Type          | Name  | Description |
|---------------|-------|-------------|
| System.UInt32 | value |             |

### Implements

<div>

INetworkVariable

</div>
