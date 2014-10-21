# CSharpSnippets

C# snippets for Sublime Text.

## Installation

### From Package Control

Recommended method of installation.  Search for **C# Snippets** or just **C#**.

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

```
case ${1:Constant}:
  ${0}
  break;
```

### [class] Class

```
${1:public} class ${2:ClassName} {
  ${0}
}
```

### [ctor] Constructor

```
${1:public} ${2:ClassName} (${3:Arguments}) {
  ${0}
}
```

### [default] Default

```
default:
  ${0}
  break;
```

### [delegate] Delegate

```
public delegate ${1:ReturnType} ${2:DelegateName}(${3:Parameters});
```

### [else] Else

```
else {
	${0}
}
```

### [elseif] Else If

```
else if (${1:Condition}) {
	${0}
}
```

### [for] For

```
for (${1:Initializer}; ${2:Condition}; ${3:Update}) {
	${0}
}
```

### [foreach] ForEach

```
foreach (${1:Type} in ${2:Collection}) {
	${0}
}
```

### [if] If

```
if (${1:Condition}) {
	${0}
}
```

### [interface] Interface

```
interface ${1:InterfaceName} {
	${0}
}
```

### [ns] Namespace

```
namespace ${1:NamespaceName} {
	${0}
}
```

### [pm] Private Method

```
private ${1:ReturnType} ${2:MethodName}(${3:Parameters}) {
	${0}
}
```

### [pr] Property (Read-Only)

```
private ${1:Type} _${2:PropertyName};
${3:public} {1:Type} ${2:PropertyName} {
	get {${4: return _${2:PropertyName}; }}
}${0}
```

### [prw] Property (Read-Write)

```
private ${1:Type} _${2:PropertyName};
${3:public} {1:Type} ${2:PropertyName} {
	get {${4: return _${2:PropertyName}; }}
	set {${5: _${2:PropertyName} = value; }}
}${0}
```

### [pum] Public Method

```
public ${1:ReturnType} ${2:MethodName}(${3:Parameters}) {
	${0}
}
```

### [struct] Struct

```
${1:public} struct ${2:StructName} {
	${0}
}
```

### [switch] Switch

```
switch (${1:Expression}) {
	${0}
}
```

### [try] Try / Catch / Finally

```
try {
	${1}
} catch {${2:System.Exception} e) {
	${3}
} finally {
	${0}
}
```

### [us] Using

```
using ${1:System};
```

### [while] While

```
while (${1:Condition}) {
	${0}
}
```

## Documentation Snippets

### [c] C documentation tag

```
<c>${1}</c>
```

### [code] Code documentation tag

```
/// <code>
/// ${1}
/// </code>
```

### [example] Example documentation tag

```
/// <example>
/// ${1}
/// </example>
```

### [exception] Exception documentation tag

```
/// <exception cref="${1:member}">${2}</exception>
```

### [include] Include documentation tag

```
/// <include file='${1:filepath}' path='${2:tagpath}[@${3:name}="${4}"]' />
```

### [list] List documentation tag

```
/// <list type="{1:type}">
/// ${2}
/// </list>
```

### [description] List description documentation tag

```
/// <description>${1}</description>
```

### [listheader] Listheader documentation tag

```
/// <listheader>
/// ${1}
/// </listheader>
```

### [item] List item documentation tag

```
/// <item>
/// ${1}
/// </item>
```

### [term] List term documentation tag

```
/// <term>${1}</term>
```

### [para] Para documentation tag

```
/// <para>${1}</para>
```

### [param] Param documentation tag

```
/// <param name="${1:name}">${2}</param>
```

### [paramref] Paramref documentation tag

```
/// <paramref name="${1:name}"/>
```

### [permission] Permission documentation tag

```
/// <permission cref="${1:member}">$2}</permission>
```

### [remarks] Remarks documentation tag

```
/// <remarks>
/// ${1}
/// </remarks>
```

### [returns] Returns documentation tag

```
/// <returns>${1}</returns>
```

### [see] See documentation tag

```
<see cref="${1:member}" />
```

### [seealso] Seealso documentation tag

```
/// <seealso cref="${1:member}" />
```

### [summary] Summary documentation tag

```
/// <summary>
/// ${1}
/// </summary>
```

### [typeparam] Typeparam documentation tag

```
/// <typeparam name="${1:name}">${2}</typeparam>
```

### [typeparamref] Typeparamref documentation tag

```
<typeparamref name="${1:name}" />
```

### [value] Value documentation tag

```
/// <value>${1}</value>
```

## License

MIT