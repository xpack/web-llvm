---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/settheory
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SetTheory` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SetTheory { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">llvm/TableGen/SetTheory.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae849bddddd831fff452588a2c7bc0fad">RecVec</a> = std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa72962c0b2d060b1ce6ab6f0cf3a5c42">RecSet</a> = <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> *, 16 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab39cdac16b4b0ee0ce7ea7c6619adb4c">ExpandMap</a> = std::map&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> *, <a href="#ae849bddddd831fff452588a2c7bc0fad">RecVec</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a424aa9d03302edd16fffaffdd4434fd1">SetTheory</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/settheory">SetTheory</a> instance with only the standard operators. <a href="#a424aa9d03302edd16fffaffdd4434fd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1a2fa205cba7482af6c21aab8877ddc">addExpander</a> (StringRef ClassName, std::unique_ptr&lt; Expander &gt;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addExpander - Add an expander for Records with the named super class. <a href="#af1a2fa205cba7482af6c21aab8877ddc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe22953dd142bbeca6a5e946526e8ef">addFieldExpander</a> (StringRef ClassName, StringRef FieldName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addFieldExpander - Add an expander for ClassName that simply evaluates FieldName in the <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> to get the set elements. <a href="#aebe22953dd142bbeca6a5e946526e8ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bdb4e3a2da114d21881df0af27a3f45">addOperator</a> (StringRef Name, std::unique_ptr&lt; Operator &gt;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>addOperator - Add a DAG operator. <a href="#a2bdb4e3a2da114d21881df0af27a3f45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add1c3afc970f65746c97311cfdbc329d">evaluate</a> (const Init *Expr, RecSet &amp;Elts, ArrayRef&lt; SMLoc &gt; Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>evaluate - Evaluate Expr and append the resulting set to Elts. <a href="#add1c3afc970f65746c97311cfdbc329d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Iter&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad20675bb48ddb4728f655880f5dbb2fe">evaluate</a> (Iter begin, Iter end, RecSet &amp;Elts, ArrayRef&lt; SMLoc &gt; Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>evaluate - Evaluate a sequence of Inits and append to Elts. <a href="#ad20675bb48ddb4728f655880f5dbb2fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae849bddddd831fff452588a2c7bc0fad">RecVec</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80f28e71e920f02b25534abf3c14d39d">expand</a> (const Record *Set)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>expand - Expand a record into a set of elements if possible. <a href="#a80f28e71e920f02b25534abf3c14d39d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">ExpandMap</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b4c9fe1a489f4925fb2dfd3d95d11a5">Expansions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/settheory/operator">Operator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a067a34003aba55bea1a05893b22c5b41">Operators</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/settheory/expander">Expander</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4815827066780dc935c29e56b69f742b">Expanders</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### RecSet {#aa72962c0b2d060b1ce6ab6f0cf3a5c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SetTheory::RecSet =  SmallSetVector&lt;const Record *, 16&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>.</p>

</div>
</div>

### RecVec {#ae849bddddd831fff452588a2c7bc0fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SetTheory::RecVec =  std::vector&lt;const Record *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### ExpandMap {#ab39cdac16b4b0ee0ce7ea7c6619adb4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SetTheory::ExpandMap =  std::map&lt;const Record *, RecVec&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SetTheory() {#a424aa9d03302edd16fffaffdd4434fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetTheory::SetTheory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/settheory">SetTheory</a> instance with only the standard operators.</p>

<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a>.</p>


<p>Reference <a href="#a2bdb4e3a2da114d21881df0af27a3f45">addOperator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/settheory/operator/#a1229c1a411d744d3f0b9b9c3faa4be5f">llvm::SetTheory::Operator::apply</a> and <a href="/web-llvm/docs/api/classes/llvm/settheory/expander/#ad6933f9f960cffcb68e5fd4e1a212a47">llvm::SetTheory::Expander::expand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addExpander() {#af1a2fa205cba7482af6c21aab8877ddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SetTheory::addExpander (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ClassName, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/settheory/expander">Expander</a> &gt; E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addExpander - Add an expander for Records with the named super class.</p>

<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a>.</p>


<p>Referenced by <a href="#aebe22953dd142bbeca6a5e946526e8ef">addFieldExpander</a>.</p>

</div>
</div>

### addFieldExpander() {#aebe22953dd142bbeca6a5e946526e8ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SetTheory::addFieldExpander (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ClassName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FieldName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addFieldExpander - Add an expander for ClassName that simply evaluates FieldName in the <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> to get the set elements.</p>


<p>That is all that is needed for a class like:</p>


<p>class Set&lt;dag d&gt; { dag Elts = d; }</p>


<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a>.</p>


<p>Reference <a href="#af1a2fa205cba7482af6c21aab8877ddc">addExpander</a>.</p>

</div>
</div>

### addOperator() {#a2bdb4e3a2da114d21881df0af27a3f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SetTheory::addOperator (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/settheory/operator">Operator</a> &gt; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>addOperator - Add a DAG operator.</p>

<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a>.</p>


<p>Referenced by <a href="#a424aa9d03302edd16fffaffdd4434fd1">SetTheory</a>.</p>

</div>
</div>

### evaluate() {#add1c3afc970f65746c97311cfdbc329d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SetTheory::evaluate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * Expr, <a href="#aa72962c0b2d060b1ce6ab6f0cf3a5c42">RecSet</a> &amp; Elts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &gt; Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>evaluate - Evaluate Expr and append the resulting set to Elts.</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#add1c3afc970f65746c97311cfdbc329d">evaluate</a>, <a href="#a80f28e71e920f02b25534abf3c14d39d">expand</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#a481b80008264e452153378421ebad249">llvm::Init::getAsString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2d33cbf73d16f36bdf9d289cf01d0006">llvm::PrintFatalError</a>.</p>


<p>Referenced by <a href="#add1c3afc970f65746c97311cfdbc329d">evaluate</a> and <a href="#ad20675bb48ddb4728f655880f5dbb2fe">evaluate</a>.</p>

</div>
</div>

### evaluate() {#ad20675bb48ddb4728f655880f5dbb2fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Iter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SetTheory::evaluate (Iter begin, Iter end, <a href="#aa72962c0b2d060b1ce6ab6f0cf3a5c42">RecSet</a> &amp; Elts, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &gt; Loc)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>evaluate - Evaluate a sequence of Inits and append to Elts.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>.</p>


<p>Reference <a href="#add1c3afc970f65746c97311cfdbc329d">evaluate</a>.</p>

</div>
</div>

### expand() {#a80f28e71e920f02b25534abf3c14d39d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const RecVec * SetTheory::expand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> * Set)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>expand - Expand a record into a set of elements if possible.</p>


<p>Return a pointer to the expanded elements, or NULL if Set cannot be expanded further.</p>


<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>, definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/setvector/#ad0bf95396cec46a41371341460d14a1c">llvm::SetVector&lt; T, Vector, Set, N &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#a889cc0df630d4b01e12d359517e26670">llvm::SetVector&lt; T, Vector, Set, N &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#add1c3afc970f65746c97311cfdbc329d">evaluate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Expanders {#a4815827066780dc935c29e56b69f742b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::unique_ptr&lt;Expander&gt; &gt; llvm::SetTheory::Expanders</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>.</p>

</div>
</div>

### Expansions {#a8b4c9fe1a489f4925fb2dfd3d95d11a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExpandMap llvm::SetTheory::Expansions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>.</p>

</div>
</div>

### Operators {#a067a34003aba55bea1a05893b22c5b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::unique_ptr&lt;Operator&gt; &gt; llvm::SetTheory::Operators</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/settheory-h">SetTheory.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/settheory-cpp">SetTheory.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
