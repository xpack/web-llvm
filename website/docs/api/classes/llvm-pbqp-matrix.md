---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pbqp/matrix
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Matrix` Class

<p><a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> class. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PBQP::Matrix { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">llvm/CodeGen/PBQP/Math.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/mdmatrix">MDMatrix&lt;Metadata&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/mdmatrix">MDMatrix&lt;Metadata&gt;</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fbe9d7f58292be903c7a0d2a6633a78">hash_value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> for the given matrix. <a href="#a7fbe9d7f58292be903c7a0d2a6633a78">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff60358275be4d00be04fd9cbea51b30">Matrix</a> (unsigned Rows, unsigned Cols)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> with the given dimensions. <a href="#aff60358275be4d00be04fd9cbea51b30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef172092adfe7dd71c0fe88d9a4ea0dc">Matrix</a> (unsigned Rows, unsigned Cols, PBQPNum InitVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> with the given dimensions and initial value. <a href="#aef172092adfe7dd71c0fe88d9a4ea0dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeebae6d2938a067c3ca991986775507e">Matrix</a> (const Matrix &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy construct a <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> matrix. <a href="#aeebae6d2938a067c3ca991986775507e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad69d87e8d23f42a05cf54a8cf2637a51">Matrix</a> (Matrix &amp;&amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move construct a <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> matrix. <a href="#ad69d87e8d23f42a05cf54a8cf2637a51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac31cb851715bb3eb362d039b31a58aa4">operator==</a> (const Matrix &amp;M) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Comparison operator. <a href="#ac31cb851715bb3eb362d039b31a58aa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pbqp/#a7bb13d1dd9c69a2a9350ca5ba163a715">PBQPNum</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ea4fa54fdf5860c469e156747411ae3">operator[]</a> (unsigned R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> element access. <a href="#a0ea4fa54fdf5860c469e156747411ae3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/pbqp/#a7bb13d1dd9c69a2a9350ca5ba163a715">PBQPNum</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92d3aa62424d433d9deccfc55fec18fd">operator[]</a> (unsigned R) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> element access. <a href="#a92d3aa62424d433d9deccfc55fec18fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b98f6d1453e03da5869584f322e042">operator+=</a> (const Matrix &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the given matrix to this one. <a href="#a35b98f6d1453e03da5869584f322e042">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05fed501313d55d5b416da9c3c16f916">operator+</a> (const Matrix &amp;M)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87d38d8fbb575ef8c0e8915ea549da17">getRows</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of rows in this matrix. <a href="#a87d38d8fbb575ef8c0e8915ea549da17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8acdf99a763b137fbb857758fe62c7a">getCols</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of cols in this matrix. <a href="#ac8acdf99a763b137fbb857758fe62c7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/vector">Vector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae17f87f2c7fb967c41b3d4fef0cd4bf9">getRowAsVector</a> (unsigned R) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the given row as a vector. <a href="#ae17f87f2c7fb967c41b3d4fef0cd4bf9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/vector">Vector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5f1166535ca2f1cae87504485a4e814">getColAsVector</a> (unsigned C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the given column as a vector. <a href="#aa5f1166535ca2f1cae87504485a4e814">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af906ea063228e3849508904ce4e07755">transpose</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> transpose. <a href="#af906ea063228e3849508904ce4e07755">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25de2cce448fab2aa2fed71acd713aea">Rows</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a622242bbaa69b7e83c70e590644b55f1">Cols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/namespaces/llvm/pbqp/#a7bb13d1dd9c69a2a9350ca5ba163a715">PBQPNum</a>[]&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab995dcdf9873fd1dfb3b0c22d05771ba">Data</a></td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> class.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<div class="doxySectionDef">

## Friends

### hash\_value {#a7fbe9d7f58292be903c7a0d2a6633a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> &amp; M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a> for the given matrix.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#add71474638430694c84640146383fc44">llvm::hash_combine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af80edfc5e42059e045aa7bf7fe42bee3">llvm::hash_combine_range</a> and <a href="#aff60358275be4d00be04fd9cbea51b30">Matrix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Matrix() {#aff60358275be4d00be04fd9cbea51b30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::Matrix::Matrix (unsigned Rows, unsigned Cols)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> with the given dimensions.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>Referenced by <a href="#a7fbe9d7f58292be903c7a0d2a6633a78">hash_value</a>, <a href="#aeebae6d2938a067c3ca991986775507e">Matrix</a>, <a href="#ad69d87e8d23f42a05cf54a8cf2637a51">Matrix</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/mdmatrix/#a05f51c993c4eb3f433b790d5071a4c0e">llvm::PBQP::MDMatrix&lt; MatrixMetadata &gt;::MDMatrix</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/mdmatrix/#a3fb11f14f7e9e3f3238f8ca654e6775f">llvm::PBQP::MDMatrix&lt; MatrixMetadata &gt;::MDMatrix</a>, <a href="#a05fed501313d55d5b416da9c3c16f916">operator+</a>, <a href="#a35b98f6d1453e03da5869584f322e042">operator+=</a>, <a href="#ac31cb851715bb3eb362d039b31a58aa4">operator==</a> and <a href="#af906ea063228e3849508904ce4e07755">transpose</a>.</p>

</div>
</div>

### Matrix() {#aef172092adfe7dd71c0fe88d9a4ea0dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::Matrix::Matrix (unsigned Rows, unsigned Cols, <a href="/web-llvm/docs/api/namespaces/llvm/pbqp/#a7bb13d1dd9c69a2a9350ca5ba163a715">PBQPNum</a> InitVal)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> with the given dimensions and initial value.</p>

<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>

</div>
</div>

### Matrix() {#aeebae6d2938a067c3ca991986775507e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::Matrix::Matrix (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> &amp; M)</td>
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

<p>Copy construct a <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> matrix.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>Reference <a href="#aff60358275be4d00be04fd9cbea51b30">Matrix</a>.</p>

</div>
</div>

### Matrix() {#ad69d87e8d23f42a05cf54a8cf2637a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PBQP::Matrix::Matrix (<a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> &amp;&amp; M)</td>
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

<p>Move construct a <a href="/web-llvm/docs/api/namespaces/llvm/pbqp">PBQP</a> matrix.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>References <a href="#aff60358275be4d00be04fd9cbea51b30">Matrix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a0ea4fa54fdf5860c469e156747411ae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PBQPNum * llvm::PBQP::Matrix::operator[] (unsigned R)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> element access.</p>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### operator\[\]() {#a92d3aa62424d433d9deccfc55fec18fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PBQPNum * llvm::PBQP::Matrix::operator[] (unsigned R)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> element access.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### operator+() {#a05fed501313d55d5b416da9c3c16f916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Matrix llvm::PBQP::Matrix::operator+ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> &amp; M)</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aff60358275be4d00be04fd9cbea51b30">Matrix</a>.</p>

</div>
</div>

### operator+=() {#a35b98f6d1453e03da5869584f322e042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Matrix &amp; llvm::PBQP::Matrix::operator+= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> &amp; M)</td>
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

<p>Add the given matrix to this one.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aff60358275be4d00be04fd9cbea51b30">Matrix</a>.</p>

</div>
</div>

### operator==() {#ac31cb851715bb3eb362d039b31a58aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PBQP::Matrix::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> &amp; M)</td>
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

<p>Comparison operator.</p>

<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aff60358275be4d00be04fd9cbea51b30">Matrix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getColAsVector() {#aa5f1166535ca2f1cae87504485a4e814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Vector llvm::PBQP::Matrix::getColAsVector (unsigned C)</td>
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

<p>Returns the given column as a vector.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pbqp/#aca4beb871fa19efbf46dbb8487d05ae9">llvm::PBQP::backpropagate</a>.</p>

</div>
</div>

### getCols() {#ac8acdf99a763b137fbb857758fe62c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PBQP::Matrix::getCols ()</td>
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

<p>Return the number of cols in this matrix.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getRowAsVector() {#ae17f87f2c7fb967c41b3d4fef0cd4bf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Vector llvm::PBQP::Matrix::getRowAsVector (unsigned R)</td>
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

<p>Returns the given row as a vector.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pbqp/#aca4beb871fa19efbf46dbb8487d05ae9">llvm::PBQP::backpropagate</a>.</p>

</div>
</div>

### getRows() {#a87d38d8fbb575ef8c0e8915ea549da17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PBQP::Matrix::getRows ()</td>
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

<p>Return the number of rows in this matrix.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pbqp/#a7d21d6d08fe746df3e5621b4703523ea">llvm::PBQP::applyR2</a>.</p>

</div>
</div>

### transpose() {#af906ea063228e3849508904ce4e07755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Matrix llvm::PBQP::Matrix::transpose ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pbqp/matrix">Matrix</a> transpose.</p>

<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aff60358275be4d00be04fd9cbea51b30">Matrix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Cols {#a622242bbaa69b7e83c70e590644b55f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PBQP::Matrix::Cols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>

</div>
</div>

### Data {#ab995dcdf9873fd1dfb3b0c22d05771ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;PBQPNum []&gt; llvm::PBQP::Matrix::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>

</div>
</div>

### Rows {#a25de2cce448fab2aa2fed71acd713aea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PBQP::Matrix::Rows</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/pbqp/math-h">Math.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
