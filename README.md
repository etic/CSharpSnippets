# CSharpSnippets

C# snippets for Sublime Text.

## Installation

### Linux

```
git clone git://github.com/etic/CSharpSnippets.git ~/.config/sublime-text-3/Packages
```

### OSX

```
git clone git://github.com/etic/CSharpSnippets.git ~/Library/Application Support/Sublime Text 3/Packages
```

### Windows

```
git clone git://github.com/etic/CSharpSnippets.git %userprofile%\AppData\Roaming\Sublime Text 3\Packages
```

## Code Snippets

### [case] Case

```csharp
case ${1:Constant}:
  ${0}
  break;
```

### [class] Class

```csharp
${1:public} class ${2:ClassName} {
  ${0}
}
```

### [default] Default

```csharp
default:
  ${0}
  break;
```

### [delegate] Delegate

```csharp
public delegate ${0:ReturnType} ${1:DelegateName}(${2:Parameters});
```

### [else] Else

```csharp
else {
	${0}
}
```

### [elseif] Else If

```csharp
else if (${0:Condition}) {
	${1}
}
```

### [for] For

```csharp
for (${0:Initializer}; ${1:Condition}; ${2:Update}) {
	${3}
}
```

### [foreach] ForEach

```csharp
foreach (${0} in ${1}) {
	${2}
}
```

### [if] If

```csharp
if (${0:Condition}) {
	${1}
}
```

### [interface] Interface

```csharp
interface ${0:InterfaceName} {
	${1}
}
```

### [ns] Namespace

```csharp
namespace ${0:NamespaceName} {
	${1}
}
```

### [pm] Private Method

```csharp
private ${0:ReturnType} ${1:MethodName}(${2:Parameters}) {
	${3}
}
```

### [pr] Property (Read-Only)

```csharp
private ${0:Type} _${1:PropertyName};
${2:public} {0:Type} ${1:PropertyName} {
	get {${3: return _${1:PropertyName}; }}
}${4}
```

### [prw] Property (Read-Write)

```csharp
private ${0:Type} _${1:PropertyName};
${2:public} {0:Type} ${1:PropertyName} {
	get {${3: return _${1:PropertyName}; }}
	set {${4: _${1:PropertyName} = value; }}
}${5}
```

### [pum] Public Method

```csharp
public ${0:ReturnType} ${1:MethodName}(${2:Parameters}) {
	${3}
}
```

### [struct] Struct

```csharp
${0:public} struct ${1:StructName} {
	${2}
}
```

### [switch] Switch

```csharp
switch (${0:Expression}) {
	${1}
}
```

### [try] Try / Catch / Finally

```csharp
try {
	${0}
} catch {${1:System.Exception} e) {
	${2}
} finally {
	${3}
}
```

### [us] Using

```csharp
using ${0:System};
```

### [while] While

```csharp
while (${0:Condition}) {
	${1}
}
```

## Documentation Snippets

### [c] C documentation tag

```csharp
<c>${1}</c>
```

### [code] Code documentation tag

```csharp
/// <code>
/// ${1}
/// </code>
```

### [example] Example documentation tag

```csharp
/// <example>
/// ${1}
/// </example>
```

### [exception] Exception documentation tag

```csharp
/// <exception cref="${1:member}">${2}</exception>
```

### [include] Include documentation tag

```csharp
/// <include file='${1:filepath}' path='${2:tagpath}[@${3:name}="${4}"]' />
```

### [list] List documentation tag

```csharp
/// <list type="{1:type}">
/// ${2}
/// </list>
```

### [description] List description documentation tag

```csharp
/// <description>${1}</description>
```

### [listheader] Listheader documentation tag

```csharp
/// <listheader>
/// ${1}
/// </listheader>
```

### [item] List item documentation tag

```csharp
/// <item>
/// ${1}
/// </item>
```

### [term] List term documentation tag

```csharp
/// <term>${1}</term>
```

### [para] Para documentation tag

```csharp
/// <para>${1}</para>
```

### [param] Param documentation tag

```csharp
/// <param name="${1:name}">${2}</param>
```

### [paramref] Paramref documentation tag

```csharp
/// <paramref name="${1:name}"/>
```

### [permission] Permission documentation tag

```csharp
/// <permission cref="${1:member}">$2}</permission>
```

### [remarks] Remarks documentation tag

```csharp
/// <remarks>
/// ${1}
/// </remarks>
```

### [returns] Returns documentation tag

```csharp
/// <returns>${1}</returns>
```

### [see] See documentation tag

```csharp
<see cref="${1:member}" />
```

### [seealso] Seealso documentation tag

```csharp
/// <seealso cref="${1:member}" />
```

### [summary] Summary documentation tag

```csharp
/// <summary>
/// ${1}
/// </summary>
```

### [typeparam] Typeparam documentation tag

```csharp
/// <typeparam name="${1:name}">${2}</typeparam>
```

### [typeparamref] Typeparamref documentation tag

```csharp
<typeparamref name="${1:name}" />
```

### [value] Value documentation tag

```csharp
/// <value>${1}</value>
```

## License

MIT