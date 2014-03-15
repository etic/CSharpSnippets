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

### [default] Default

```
default:
  ${0}
  break;
```

### [delegate] Delegate

```
public delegate ${0:ReturnType} ${1:DelegateName}(${2:Parameters});
```

### [else] Else

```
else {
	${0}
}
```

### [elseif] Else If

```
else if (${0:Condition}) {
	${1}
}
```

### [for] For

```
for (${0:Initializer}; ${1:Condition}; ${2:Update}) {
	${3}
}
```

### [foreach] ForEach

```
foreach (${0} in ${1}) {
	${2}
}
```

### [if] If

```
if (${0:Condition}) {
	${1}
}
```

### [interface] Interface

```
interface ${0:InterfaceName} {
	${1}
}
```

### [ns] Namespace

```
namespace ${0:NamespaceName} {
	${1}
}
```

### [pm] Private Method

```
private ${0:ReturnType} ${1:MethodName}(${2:Parameters}) {
	${3}
}
```

### [pr] Property (Read-Only)

```
private ${0:Type} _${1:PropertyName};
${2:public} {0:Type} ${1:PropertyName} {
	get {${3: return _${1:PropertyName}; }}
}${4}
```

### [prw] Property (Read-Write)

```
private ${0:Type} _${1:PropertyName};
${2:public} {0:Type} ${1:PropertyName} {
	get {${3: return _${1:PropertyName}; }}
	set {${4: _${1:PropertyName} = value; }}
}${5}
```

### [pum] Public Method

```
public ${0:ReturnType} ${1:MethodName}(${2:Parameters}) {
	${3}
}
```

### [struct] Struct

```
${0:public} struct ${1:StructName} {
	${2}
}
```

### [switch] Switch

```
switch (${0:Expression}) {
	${1}
}
```

### [try] Try / Catch / Finally

```
try {
	${0}
} catch {${1:System.Exception} e) {
	${2}
} finally {
	${3}
}
```

### [us] Using

```
using ${0:System};
```

### [while] While

```
while (${0:Condition}) {
	${1}
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