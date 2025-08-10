---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitsymbolflags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `JITSymbolFlags` Class

<p>Flags for symbols in the JIT. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::JITSymbolFlags { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">llvm/ExecutionEngine/JITSymbol.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8a3d8ffa06d35ed1b432fd4ba578ad4">UnderlyingType</a> = uint8_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52b2cde16c7a36e0ac89c4a9462f2226">TargetFlagsType</a> = uint8_t</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FlagNames : <a href="#ae8a3d8ffa06d35ed1b432fd4ba578ad4">UnderlyingType</a> { <a href="#ad509c6d010720c4f71aeac1fba93f8cb">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb7e08dd65f938cad006e4700c3f45c">JITSymbolFlags</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default-construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> instance. <a href="#a7eb7e08dd65f938cad006e4700c3f45c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b4132c67779a64e013e97d97bdc2a4e">JITSymbolFlags</a> (FlagNames Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> instance from the given flags. <a href="#a1b4132c67779a64e013e97d97bdc2a4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af72c687f366f991096682f060f21f9e1">JITSymbolFlags</a> (FlagNames Flags, TargetFlagsType TargetFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> instance from the given flags and target flags. <a href="#af72c687f366f991096682f060f21f9e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a040efd4b5ce6c8fa91a679430e066ba4">operator bool</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implicitly convert to bool. Returns true if any flag is set. <a href="#a040efd4b5ce6c8fa91a679430e066ba4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa76ccae53ac6f4de241bba9f580ea281">operator==</a> (const JITSymbolFlags &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare for equality. <a href="#aa76ccae53ac6f4de241bba9f580ea281">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36cd5820e0f9cc61f057006ba5767fd9">operator&amp;=</a> (const FlagNames &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwise AND-assignment for <a href="#ad509c6d010720c4f71aeac1fba93f8cb">FlagNames</a>. <a href="#a36cd5820e0f9cc61f057006ba5767fd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ce3ff98f508bbbe3c6983de088f3900">operator|=</a> (const FlagNames &amp;RHS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bitwise OR-assignment for <a href="#ad509c6d010720c4f71aeac1fba93f8cb">FlagNames</a>. <a href="#a2ce3ff98f508bbbe3c6983de088f3900">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e41531e33e95480c063f7f139eb78fc">hasError</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there was an error retrieving this symbol. <a href="#a1e41531e33e95480c063f7f139eb78fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada7ba4744905c1019e2f0006a70b0643">isWeak</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the Weak flag is set. <a href="#ada7ba4744905c1019e2f0006a70b0643">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91b0a000470ab8e43b8183d7520c325a">isCommon</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the Common flag is set. <a href="#a91b0a000470ab8e43b8183d7520c325a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f2acf67ee4229bb19a543d321cba7fb">isStrong</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the symbol isn't weak or common. <a href="#a3f2acf67ee4229bb19a543d321cba7fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a405bccc66ae7bea5bfaa2acab4ca9f64">isExported</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the Exported flag is set. <a href="#a405bccc66ae7bea5bfaa2acab4ca9f64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57ae82ed5fc9a257905220bc9424effc">isCallable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the given symbol is known to be callable. <a href="#a57ae82ed5fc9a257905220bc9424effc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4076fc53f24d1bd97425557221f052ad">hasMaterializationSideEffectsOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this symbol is a materialization-side-effects-only symbol. <a href="#a4076fc53f24d1bd97425557221f052ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae8a3d8ffa06d35ed1b432fd4ba578ad4">UnderlyingType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a248a6b34682b76dfd1851d32b23061fc">getRawFlagsValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the underlying flags value as an integer. <a href="#a248a6b34682b76dfd1851d32b23061fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a52b2cde16c7a36e0ac89c4a9462f2226">TargetFlagsType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ecfc51509e138b79c775e012e9e0b6e">getTargetFlags</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the target-specific flags. <a href="#a1ecfc51509e138b79c775e012e9e0b6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a52b2cde16c7a36e0ac89c4a9462f2226">TargetFlagsType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a203769acea3b2a4f7616483978a2102c">getTargetFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the target-specific flags. <a href="#a203769acea3b2a4f7616483978a2102c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a52b2cde16c7a36e0ac89c4a9462f2226">TargetFlagsType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a935ad1c881023dbe27d02cdeafae5907">TargetFlags</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad509c6d010720c4f71aeac1fba93f8cb">FlagNames</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fc6cbdc87a015bcdcfa2139eaa3410c">Flags</a> = <a href="#ad509c6d010720c4f71aeac1fba93f8cbabffa99596ece82fbf05f0f3646f70ae1">None</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa66476422470ab204074b3198bcf4d15">fromGlobalValue</a> (const GlobalValue &amp;GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> value based on the flags of the given global value. <a href="#aa66476422470ab204074b3198bcf4d15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8542a1e56f754b563a94e006caac9eea">fromSummary</a> (GlobalValueSummary *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> value based on the flags of the given global value summary. <a href="#a8542a1e56f754b563a94e006caac9eea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d8cec64deb620b732a8a6922c327cf7">fromObjectSymbol</a> (const object::SymbolRef &amp;Symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> value based on the flags of the given libobject symbol. <a href="#a6d8cec64deb620b732a8a6922c327cf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Flags for symbols in the JIT.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### TargetFlagsType {#a52b2cde16c7a36e0ac89c4a9462f2226}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::JITSymbolFlags::TargetFlagsType =  uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

### UnderlyingType {#ae8a3d8ffa06d35ed1b432fd4ba578ad4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::JITSymbolFlags::UnderlyingType =  uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### FlagNames {#ad509c6d010720c4f71aeac1fba93f8cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::JITSymbolFlags::FlagNames : <a href="#ae8a3d8ffa06d35ed1b432fd4ba578ad4">UnderlyingType</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="ad509c6d010720c4f71aeac1fba93f8cbabffa99596ece82fbf05f0f3646f70ae1"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HasError<a id="ad509c6d010720c4f71aeac1fba93f8cba25e14ff11bb62596d99781c55d212f77"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Weak<a id="ad509c6d010720c4f71aeac1fba93f8cbabe8fbc5eba26a22d11d3ed68f8ada397"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Common<a id="ad509c6d010720c4f71aeac1fba93f8cba699390ef2a5b6e4057ef4c932dc8a1e2"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Absolute<a id="ad509c6d010720c4f71aeac1fba93f8cbaaa40f69c9291fab5757c85dd11e3f125"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Exported<a id="ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Callable<a id="ad509c6d010720c4f71aeac1fba93f8cba9287f0bdea578bb13149dee3a35f69d5"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MaterializationSideEffectsOnly<a id="ad509c6d010720c4f71aeac1fba93f8cbab78b49be60a6b5faf277860a45753ea5"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LLVM_MARK_AS_BITMASK_ENUM<a id="ad509c6d010720c4f71aeac1fba93f8cbaf6a1f15241accecf02673c6c30655fc7"></a></td>
<td class="doxyEnumItemDescription">
 (=( 
        MaterializationSideEffectsOnly))
</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### JITSymbolFlags() {#a7eb7e08dd65f938cad006e4700c3f45c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbolFlags::JITSymbolFlags ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default-construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> instance.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Referenced by <a href="#aa66476422470ab204074b3198bcf4d15">fromGlobalValue</a>, <a href="#a6d8cec64deb620b732a8a6922c327cf7">fromObjectSymbol</a>, <a href="#a8542a1e56f754b563a94e006caac9eea">fromSummary</a>, <a href="#a36cd5820e0f9cc61f057006ba5767fd9">operator&amp;=</a>, <a href="#aa76ccae53ac6f4de241bba9f580ea281">operator==</a> and <a href="#a2ce3ff98f508bbbe3c6983de088f3900">operator|=</a>.</p>

</div>
</div>

### JITSymbolFlags() {#a1b4132c67779a64e013e97d97bdc2a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbolFlags::JITSymbolFlags (<a href="#ad509c6d010720c4f71aeac1fba93f8cb">FlagNames</a> Flags)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> instance from the given flags.</p>

<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

### JITSymbolFlags() {#af72c687f366f991096682f060f21f9e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbolFlags::JITSymbolFlags (<a href="#ad509c6d010720c4f71aeac1fba93f8cb">FlagNames</a> Flags, <a href="#a52b2cde16c7a36e0ac89c4a9462f2226">TargetFlagsType</a> TargetFlags)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> instance from the given flags and target flags.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a040efd4b5ce6c8fa91a679430e066ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::JITSymbolFlags::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implicitly convert to bool. Returns true if any flag is set.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Reference <a href="#ad509c6d010720c4f71aeac1fba93f8cbabffa99596ece82fbf05f0f3646f70ae1">None</a>.</p>

</div>
</div>

### operator&amp;=() {#a36cd5820e0f9cc61f057006ba5767fd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbolFlags &amp; llvm::JITSymbolFlags::operator&amp;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad509c6d010720c4f71aeac1fba93f8cb">FlagNames</a> &amp; RHS)</td>
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

<p>Bitwise AND-assignment for <a href="#ad509c6d010720c4f71aeac1fba93f8cb">FlagNames</a>.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>References <a href="#a7eb7e08dd65f938cad006e4700c3f45c">JITSymbolFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#aa76ccae53ac6f4de241bba9f580ea281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::JITSymbolFlags::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> &amp; RHS)</td>
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

<p>Compare for equality.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>References <a href="#a7eb7e08dd65f938cad006e4700c3f45c">JITSymbolFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator|=() {#a2ce3ff98f508bbbe3c6983de088f3900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbolFlags &amp; llvm::JITSymbolFlags::operator|= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad509c6d010720c4f71aeac1fba93f8cb">FlagNames</a> &amp; RHS)</td>
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

<p>Bitwise OR-assignment for <a href="#ad509c6d010720c4f71aeac1fba93f8cb">FlagNames</a>.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>References <a href="#a7eb7e08dd65f938cad006e4700c3f45c">JITSymbolFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRawFlagsValue() {#a248a6b34682b76dfd1851d32b23061fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnderlyingType llvm::JITSymbolFlags::getRawFlagsValue ()</td>
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

<p>Get the underlying flags value as an integer.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

### getTargetFlags() {#a1ecfc51509e138b79c775e012e9e0b6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetFlagsType &amp; llvm::JITSymbolFlags::getTargetFlags ()</td>
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

<p>Return a reference to the target-specific flags.</p>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvmorclazycallthroughmanagerref/#afda88d4895989e55b1d4617274bcb1d0">LLVMOrcLazyCallThroughManagerRef::fromJITSymbolFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvmorclazycallthroughmanagerref/#a3109cc1cfe3ab7823063aaf1f40b9dc4">LLVMOrcLazyCallThroughManagerRef::toJITSymbolFlags</a>.</p>

</div>
</div>

### getTargetFlags() {#a203769acea3b2a4f7616483978a2102c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetFlagsType &amp; llvm::JITSymbolFlags::getTargetFlags ()</td>
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

<p>Return a reference to the target-specific flags.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

### hasError() {#a1e41531e33e95480c063f7f139eb78fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::JITSymbolFlags::hasError ()</td>
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

<p>Return true if there was an error retrieving this symbol.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Reference <a href="#ad509c6d010720c4f71aeac1fba93f8cba25e14ff11bb62596d99781c55d212f77">HasError</a>.</p>

</div>
</div>

### hasMaterializationSideEffectsOnly() {#a4076fc53f24d1bd97425557221f052ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::JITSymbolFlags::hasMaterializationSideEffectsOnly ()</td>
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

<p>Returns true if this symbol is a materialization-side-effects-only symbol.</p>


<p>Such symbols do not have a real address. They exist to trigger and support synchronization of materialization side effects, e.g. for collecting initialization information. These symbols will vanish from the symbol table immediately upon reaching the ready state, and will appear to queries as if they were never defined (except that query callback execution will be delayed until they reach the ready state). MaterializationSideEffectOnly symbols should only be queried using the SymbolLookupFlags::WeaklyReferencedSymbol flag (see llvm/include/llvm/ExecutionEngine/Orc/Core.h).</p>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Reference <a href="#ad509c6d010720c4f71aeac1fba93f8cbab78b49be60a6b5faf277860a45753ea5">MaterializationSideEffectsOnly</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/asynchronoussymbolquery/#a840fe6c687a1b9b1597ba8f5e5bf6e36">llvm::orc::AsynchronousSymbolQuery::notifySymbolMetRequiredState</a>.</p>

</div>
</div>

### isCallable() {#a57ae82ed5fc9a257905220bc9424effc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::JITSymbolFlags::isCallable ()</td>
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

<p>Returns true if the given symbol is known to be callable.</p>

<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Reference <a href="#ad509c6d010720c4f71aeac1fba93f8cba9287f0bdea578bb13149dee3a35f69d5">Callable</a>.</p>

</div>
</div>

### isCommon() {#a91b0a000470ab8e43b8183d7520c325a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::JITSymbolFlags::isCommon ()</td>
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

<p>Returns true if the Common flag is set.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Reference <a href="#ad509c6d010720c4f71aeac1fba93f8cba699390ef2a5b6e4057ef4c932dc8a1e2">Common</a>.</p>


<p>Referenced by <a href="#a3f2acf67ee4229bb19a543d321cba7fb">isStrong</a>.</p>

</div>
</div>

### isExported() {#a405bccc66ae7bea5bfaa2acab4ca9f64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::JITSymbolFlags::isExported ()</td>
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

<p>Returns true if the Exported flag is set.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Reference <a href="#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">Exported</a>.</p>

</div>
</div>

### isStrong() {#a3f2acf67ee4229bb19a543d321cba7fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::JITSymbolFlags::isStrong ()</td>
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

<p>Returns true if the symbol isn't weak or common.</p>

<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>References <a href="#a91b0a000470ab8e43b8183d7520c325a">isCommon</a> and <a href="#ada7ba4744905c1019e2f0006a70b0643">isWeak</a>.</p>

</div>
</div>

### isWeak() {#ada7ba4744905c1019e2f0006a70b0643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::JITSymbolFlags::isWeak ()</td>
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

<p>Returns true if the Weak flag is set.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>


<p>Reference <a href="#ad509c6d010720c4f71aeac1fba93f8cbabe8fbc5eba26a22d11d3ed68f8ada397">Weak</a>.</p>


<p>Referenced by <a href="#a3f2acf67ee4229bb19a543d321cba7fb">isStrong</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Flags {#a4fc6cbdc87a015bcdcfa2139eaa3410c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FlagNames llvm::JITSymbolFlags::Flags = <a href="#ad509c6d010720c4f71aeac1fba93f8cbabffa99596ece82fbf05f0f3646f70ae1">None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

### TargetFlags {#a935ad1c881023dbe27d02cdeafae5907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetFlagsType llvm::JITSymbolFlags::TargetFlags = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fromGlobalValue() {#aa66476422470ab204074b3198bcf4d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbolFlags llvm::JITSymbolFlags::fromGlobalValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> value based on the flags of the given global value.</p>

<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/jitsymbol-cpp">JITSymbol.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad509c6d010720c4f71aeac1fba93f8cba9287f0bdea578bb13149dee3a35f69d5">Callable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ad509c6d010720c4f71aeac1fba93f8cba699390ef2a5b6e4057ef4c932dc8a1e2">Common</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">Exported</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ac10ac4576e030b231e1fbb5a8272f01f">llvm::GlobalValue::hasCommonLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a50baaf8d8a18c0cda69eb8d8eca178f9">llvm::GlobalValue::hasHiddenVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a091e6599599c4e668373e0feefa92c01">llvm::GlobalValue::hasLinkOnceLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ad9d88ae321b98d8a3b7f394977ae6d7f">llvm::Value::hasName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aaca0b3e9845b2fa35c965edaabd5c6bc">llvm::GlobalValue::hasWeakLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a7eb7e08dd65f938cad006e4700c3f45c">JITSymbolFlags</a>, <a href="#ad509c6d010720c4f71aeac1fba93f8cbabffa99596ece82fbf05f0f3646f70ae1">None</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a> and <a href="#ad509c6d010720c4f71aeac1fba93f8cbabe8fbc5eba26a22d11d3ed68f8ada397">Weak</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/irsymbolmapper/#a49258c0e5a9200b48bd7122eea077796">llvm::orc::IRSymbolMapper::add</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a6ba5ee0773bcb7bf0614f9ae9f010198">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a>.</p>

</div>
</div>

### fromObjectSymbol() {#a6d8cec64deb620b732a8a6922c327cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; JITSymbolFlags &gt; llvm::JITSymbolFlags::fromObjectSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/symbolref">object::SymbolRef</a> &amp; Symbol)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> value based on the flags of the given libobject symbol.</p>

<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/jitsymbol-cpp">JITSymbol.cpp</a>.</p>


<p>References <a href="#ad509c6d010720c4f71aeac1fba93f8cba9287f0bdea578bb13149dee3a35f69d5">Callable</a>, <a href="#ad509c6d010720c4f71aeac1fba93f8cba699390ef2a5b6e4057ef4c932dc8a1e2">Common</a>, <a href="#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">Exported</a>, <a href="#a7eb7e08dd65f938cad006e4700c3f45c">JITSymbolFlags</a>, <a href="#ad509c6d010720c4f71aeac1fba93f8cbabffa99596ece82fbf05f0f3646f70ae1">None</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57">llvm::object::BasicSymbolRef::SF_Common</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a3936e16c4ba4b109e74006ad9bdc06f8">llvm::object::BasicSymbolRef::SF_Exported</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="#ad509c6d010720c4f71aeac1fba93f8cbabe8fbc5eba26a22d11d3ed68f8ada397">Weak</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/rtdyldobjectlinkinglayer/#a640efdfe6f9a9949a292dc894222e8f5">llvm::orc::RTDyldObjectLinkingLayer::emit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#aeeec63b61f99af14a9ca2c631e6b9cec">llvm::orc::getCOFFObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a5943e7713622fd9365b27abfefd1703f">llvm::orc::getELFObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a46b8e71e338ddab38e9a33ed9502a3a2">llvm::orc::getGenericObjectFileSymbolInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldimpl/#afd8b5e95c65e3bb62ead0dd58732e382">llvm::RuntimeDyldImpl::getJITSymbolFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2143f8386a6b8bcb33011fdd240c38f1">llvm::orc::getMachOObjectFileSymbolInfo</a>.</p>

</div>
</div>

### fromSummary() {#a8542a1e56f754b563a94e006caac9eea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITSymbolFlags llvm::JITSymbolFlags::fromSummary (<a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> * S)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/jitsymbolflags">JITSymbolFlags</a> value based on the flags of the given global value summary.</p>

<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/jitsymbol-cpp">JITSymbol.cpp</a>.</p>


<p>References <a href="#ad509c6d010720c4f71aeac1fba93f8cba9287f0bdea578bb13149dee3a35f69d5">Callable</a>, <a href="#ad509c6d010720c4f71aeac1fba93f8cba699390ef2a5b6e4057ef4c932dc8a1e2">Common</a>, <a href="#ad509c6d010720c4f71aeac1fba93f8cbaeb59403a31ee3f63734a411e9e42ddd8">Exported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a76d750f65089b2e70a927cf9d275a9d7">llvm::GlobalValue::isCommonLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a89a664b58385307fbb24c02e141d864b">llvm::GlobalValue::isExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a25e8e3490a28e9178b302b76ae643443">llvm::GlobalValue::isExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a4f4d5111c78b4b976e362d12f01ad782">llvm::GlobalValue::isLinkOnceLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ad48190a47d8af6ce16465cda531725a9">llvm::GlobalValue::isWeakLinkage</a>, <a href="#a7eb7e08dd65f938cad006e4700c3f45c">JITSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#adc87d9100ef8fc4adba27a249123f1d6">llvm::GlobalValueSummary::linkage</a>, <a href="#ad509c6d010720c4f71aeac1fba93f8cbabffa99596ece82fbf05f0f3646f70ae1">None</a> and <a href="#ad509c6d010720c4f71aeac1fba93f8cbabe8fbc5eba26a22d11d3ed68f8ada397">Weak</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/jitsymbol-h">JITSymbol.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/jitsymbol-cpp">JITSymbol.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
