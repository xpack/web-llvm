---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbol-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `PDBSymbol.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/ipdbrawsymbol-h">IPDBRawSymbol.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbextras-h">PDBExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbtypes-h">PDBTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb">pdb</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol">PDBSymbol</a> defines the base of the inheritance hierarchy for concrete symbol types (e.g. <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac24c68c8e5ffcface5a3fc495d4aac3a">FORWARD_SYMBOL_METHOD</a>(MethodName)&nbsp;&nbsp;&nbsp;  decltype(auto) MethodName() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> { return RawSymbol-&gt;MethodName(); }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa02b5287f1dcc70a87c0d9ac1297de01">FORWARD_CONCRETE_SYMBOL_ID_METHOD_WITH_NAME</a>(ConcreteType, PrivateName, PublicName)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a466a0f8a72d771ab52ddabde32b1f158">FORWARD_SYMBOL_ID_METHOD_WITH_NAME</a>(PrivateName, PublicName)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a815fc97befd320170af3accfe7ca9952">FORWARD_SYMBOL_ID_METHOD</a>(MethodName)&nbsp;&nbsp;&nbsp;  <a href="#a466a0f8a72d771ab52ddabde32b1f158">FORWARD_SYMBOL_ID_METHOD_WITH_NAME</a>(MethodName, MethodName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0839b13ee3e884378305dc804d92fbbf">DECLARE_PDB_SYMBOL_CONCRETE_TYPE</a>(TagValue)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3340eb636176455535ccbf14bbd14e">DECLARE_PDB_SYMBOL_CUSTOM_TYPE</a>(Condition)&nbsp;&nbsp;&nbsp;...</td>
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


<div class="doxySectionDef">

## Macro Definitions

### DECLARE\_PDB\_SYMBOL\_CONCRETE\_TYPE {#a0839b13ee3e884378305dc804d92fbbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECLARE_PDB_SYMBOL_CONCRETE_TYPE(TagValue)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">private:                                                                       \
  using PDBSymbol::PDBSymbol;                                                  \
  friend class PDBSymbol;                                                      \
                                                                               \
public:                                                                        \
  static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PDB_SymType Tag = TagValue;                                     \
  static bool classof(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PDBSymbol *S) { return S-&gt;getSymTag() == Tag; }
</div>
</dd>
</dl>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbol-h">PDBSymbol.h</a>.</p>

</div>
</div>

### DECLARE\_PDB\_SYMBOL\_CUSTOM\_TYPE {#a8d3340eb636176455535ccbf14bbd14e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECLARE_PDB_SYMBOL_CUSTOM_TYPE(Condition)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">private:                                                                       \
  using PDBSymbol::PDBSymbol;                                                  \
  friend class PDBSymbol;                                                      \
                                                                               \
public:                                                                        \
  static bool classof(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PDBSymbol *S) { return Condition; }
</div>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbol-h">PDBSymbol.h</a>.</p>

</div>
</div>

### FORWARD\_CONCRETE\_SYMBOL\_ID\_METHOD\_WITH\_NAME {#aa02b5287f1dcc70a87c0d9ac1297de01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FORWARD_CONCRETE_SYMBOL_ID_METHOD_WITH_NAME(ConcreteType, PrivateName, PublicName)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  decltype(auto) PublicName##Id() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> {                                      \
    return RawSymbol-&gt;PrivateName##Id();                                       \
  }                                                                            \
  std::unique_ptr&lt;ConcreteType&gt; PublicName() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> {                           \
    uint32_t Id = PublicName##Id();                                            \
    return getConcreteSymbolByIdHelper&lt;ConcreteType&gt;(Id);                      \
  }
</div>
</dd>
</dl>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbol-h">PDBSymbol.h</a>.</p>

</div>
</div>

### FORWARD\_SYMBOL\_ID\_METHOD {#a815fc97befd320170af3accfe7ca9952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FORWARD_SYMBOL_ID_METHOD(MethodName)&nbsp;&nbsp;&nbsp;  <a href="#a466a0f8a72d771ab52ddabde32b1f158">FORWARD_SYMBOL_ID_METHOD_WITH_NAME</a>(MethodName, MethodName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbol-h">PDBSymbol.h</a>.</p>

</div>
</div>

### FORWARD\_SYMBOL\_ID\_METHOD\_WITH\_NAME {#a466a0f8a72d771ab52ddabde32b1f158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FORWARD_SYMBOL_ID_METHOD_WITH_NAME(PrivateName, PublicName)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#aa02b5287f1dcc70a87c0d9ac1297de01">FORWARD_CONCRETE_SYMBOL_ID_METHOD_WITH_NAME</a>(PDBSymbol, PrivateName,          \
                                              PublicName)
</div>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbol-h">PDBSymbol.h</a>.</p>

</div>
</div>

### FORWARD\_SYMBOL\_METHOD {#ac24c68c8e5ffcface5a3fc495d4aac3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FORWARD_SYMBOL_METHOD(MethodName)&nbsp;&nbsp;&nbsp;  decltype(auto) MethodName() <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> { return RawSymbol-&gt;MethodName(); }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymbol-h">PDBSymbol.h</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
