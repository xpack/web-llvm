---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/mcsymboltablevalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MCSymbolTableValue` Struct Reference

<p>The value for an entry in the symbol table of an <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::MCSymbolTableValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymboltableentry-h">llvm/MC/MCSymbolTableEntry.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6ae1daee49ef18a9b2281ad2af994b2">Symbol</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The symbol associated with the name, if any. <a href="#af6ae1daee49ef18a9b2281ad2af994b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a780367c73b768f312b9b440ab811a386">NextUniqueID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The next <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to dole out to an unnamed assembler temporary symbol with the prefix (symbol table key). <a href="#a780367c73b768f312b9b440ab811a386">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e0f51ccf7e77ed2bedb5f5e8e68855c">Used</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the name associated with this value is used for a symbol. <a href="#a1e0f51ccf7e77ed2bedb5f5e8e68855c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>The value for an entry in the symbol table of an <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a>.</p>


<p>This is in a separate file, because <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> uses <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> (see below) to reuse the name that is stored in the symbol table.</p>


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymboltableentry-h">MCSymbolTableEntry.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### NextUniqueID {#a780367c73b768f312b9b440ab811a386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSymbolTableValue::NextUniqueID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The next <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> to dole out to an unnamed assembler temporary symbol with the prefix (symbol table key).</p>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymboltableentry-h">MCSymbolTableEntry.h</a>.</p>

</div>
</div>

### Symbol {#af6ae1daee49ef18a9b2281ad2af994b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MCSymbolTableValue::Symbol = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The symbol associated with the name, if any.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymboltableentry-h">MCSymbolTableEntry.h</a>.</p>

</div>
</div>

### Used {#a1e0f51ccf7e77ed2bedb5f5e8e68855c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSymbolTableValue::Used = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the name associated with this value is used for a symbol.</p>


<p>This is not necessarily true: sometimes, we use a symbol table value without an associated symbol for accessing NextUniqueID when a suffix is added to a name. However, Used might be true even if Symbol is nullptr: temporary named symbols are not added to the symbol table.</p>


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymboltableentry-h">MCSymbolTableEntry.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsymboltableentry-h">MCSymbolTableEntry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
