---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/init
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Init` Class



## Declaration

<div class="doxyDeclaration">
class llvm::Init { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">llvm/TableGen/Record.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/argumentinit">ArgumentInit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/typedinit">TypedInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the common superclass of types that have a specific, explicit type, stored in ValueTy. <a href="/web-llvm/docs/api/classes/llvm/typedinit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/unsetinit">UnsetInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'?' - Represents an uninitialized value. <a href="/web-llvm/docs/api/classes/llvm/unsetinit/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">InitKind : uint8_t { <a href="#a54e3c8e4571f5bf7daf2f792e4f1997e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Discriminator enum (for isa&lt;&gt;, dyn_cast&lt;&gt;, et al.) <a href="#a54e3c8e4571f5bf7daf2f792e4f1997e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabd1ee7078e7117d826899b94458f4c9">Init</a> (const Init &amp;)=delete</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae13588eb910e6f97e1b213f2c875ca8e">Init</a> (InitKind K, uint8_t Opc=0)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a5bcf3838dc863aa08b78885182505a">~Init</a> ()=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/init">Init</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba744c5d5fe317f5c009e92f5467514c">operator=</a> (const Init &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a54e3c8e4571f5bf7daf2f792e4f1997e">InitKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58eb865e6057d2dafe7de4a2bed6b5a2">getKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the kind (type) of the value. <a href="#a58eb865e6057d2dafe7de4a2bed6b5a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceb63812efd39ed325fc5579b10213f3">getRecordKeeper</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the record keeper that initialized this <a href="/web-llvm/docs/api/classes/llvm/init">Init</a>. <a href="#aceb63812efd39ed325fc5579b10213f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84ecdbe17c6975f34940e673a1204eb8">isComplete</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this a complete value with no unset (uninitialized) subvalues? <a href="#a84ecdbe17c6975f34940e673a1204eb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e9256379467310487f19e38f7c723fb">isConcrete</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this a concrete and fully resolved value without any references or stuck operations? <a href="#a7e9256379467310487f19e38f7c723fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a404733036e9f08c71a03349991806f33">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print this value. <a href="#a404733036e9f08c71a03349991806f33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a481b80008264e452153378421ebad249">getAsString</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert this value to a literal form. <a href="#a481b80008264e452153378421ebad249">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a285d0b93e0c8992d281d0cf4c89e37b7">getAsUnquotedString</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert this value to a literal form, without adding quotes around a string. <a href="#a285d0b93e0c8992d281d0cf4c89e37b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29593b415ed8217aafed21bab813cb1e">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Debugging method that may be called through a debugger; just invokes print on stderr. <a href="#a29593b415ed8217aafed21bab813cb1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdccdbcb7e5bb97939575139f2857cd5">getCastTo</a> (const RecTy *Ty) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this value is convertible to type <span class="doxyComputerOutput">Ty</span>, return a value whose type is <span class="doxyComputerOutput">Ty</span>, generating a !cast operation if required. <a href="#acdccdbcb7e5bb97939575139f2857cd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33fcbf534985fedfc7a1795aa54175b">convertInitializerTo</a> (const RecTy *Ty) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert to a value whose type is <span class="doxyComputerOutput">Ty</span>, or return null if this is not possible. <a href="#ab33fcbf534985fedfc7a1795aa54175b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b6a1d8d53a93c7d333d3e6f4a664a12">convertInitializerBitRange</a> (ArrayRef&lt; unsigned &gt; Bits) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is used to implement the bit range selection operator. <a href="#a0b6a1d8d53a93c7d333d3e6f4a664a12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b667af40218e9c4dd447198954f212b">getFieldType</a> (const StringInit *FieldName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is used to implement the <a href="/web-llvm/docs/api/classes/llvm/fieldinit">FieldInit</a> class. <a href="#a9b667af40218e9c4dd447198954f212b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00581957c4bb1587a458c3fbf4326f7a">resolveReferences</a> (Resolver &amp;R) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function is used by classes that refer to other variables which may not be defined at the time the expression is formed. <a href="#a00581957c4bb1587a458c3fbf4326f7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a853f54e09b3e93b99fe6bfaf249d8fa5">getBit</a> (unsigned Bit) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/init">Init</a></span> value of the specified bit. <a href="#a853f54e09b3e93b99fe6bfaf249d8fa5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a115f482d5164e7f829d5e3b51def89aa">anchor</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033dc74493053e93fde93554c95a288c">Opc</a></td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a54e3c8e4571f5bf7daf2f792e4f1997e">InitKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26f7c750178489bb70d6f145c5c8c327">Kind</a></td>
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


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### InitKind {#a54e3c8e4571f5bf7daf2f792e4f1997e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Init::InitKind : uint8_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Discriminator enum (for isa&lt;&gt;, dyn_cast&lt;&gt;, et al.)</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_First<a id="a54e3c8e4571f5bf7daf2f792e4f1997ead9ec53c3c7b2c50b9564e1ed918c9518"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_FirstTypedInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea9519e0da45d9a461afb0020309b440c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_BitInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea95c59ee6225b58ea28df31472b487ce5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_BitsInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997eab15cabd1977096f084e2202d31eeee77"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_DagInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea5306cc38b82cb67d656231bda70d128f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_DefInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea87c21d2e9560ab5a2abdc76bd257111b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_FieldInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997eaf75da41cf410e7886fdabaae4dd82aa3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_IntInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea2721ef6c2e38fc7c83a0194b85645ac1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_ListInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea5ec09a098648a8e575b4a584c19b73ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_FirstOpInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea672ed89469af6fbeca4c8ad2b92779e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_BinOpInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea93fa5283ed205e13f03d8a255ac7f36b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_TernOpInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997eafb2eb8812629f88b02d9abb1b1adb1df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_UnOpInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997eab695de26e5ff59ed2298833533d45a1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_LastOpInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997eadb9c929006c01f6cc833215e0453cc41"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_CondOpInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997eaf5a532403f01d019ce3a9f2ebe8179d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_FoldOpInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea04a19e05330bfe4d83871fd94ea45312"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_IsAOpInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997eabd57ce0b722a33a637eff11ad05b22c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_ExistsOpInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea83e50e99f74435eef4596cf081a3a4fb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_AnonymousNameInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997eaeddf1f3ee258880747c093fd9ff33932"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_StringInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997eab9bcc0d929df89bf630eb33beb7f2b4b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_VarInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997eada40e46d37f8ac2c8b9cf5a54e4a19b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_VarBitInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea5519fe1577ace2d051f1c353aec6779b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_VarDefInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea6d0dce88f0ee406619404c30f8e1b4df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_LastTypedInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea2adede9ed3f67560b90f9634ca52f03e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_UnsetInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea2c0e607fc8f2f88d64eb6a9fda091869"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IK_ArgumentInit<a id="a54e3c8e4571f5bf7daf2f792e4f1997ea7ebc73b9a8ae7021a66c708ce5fc5a2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>This enum is laid out by a preorder traversal of the inheritance hierarchy, and does not contain an entry for abstract classes, as per the recommendation in docs/HowToSetUpLLVMStyleRTTI.rst.</p>


<p>We also explicitly include "first" and "last" values for each interior node of the inheritance tree, to make it easier to read the corresponding classof().</p>


<p>We could pack these a bit tighter by not having the IK_FirstXXXInit and IK_LastXXXInit be their own values, but that would degrade readability for really no benefit.</p>


<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Init() {#aabd1ee7078e7117d826899b94458f4c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Init::Init (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#ae13588eb910e6f97e1b213f2c875ca8e">Init</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### Init() {#ae13588eb910e6f97e1b213f2c875ca8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Init::Init (<a href="#a54e3c8e4571f5bf7daf2f792e4f1997e">InitKind</a> K, uint8_t Opc=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a033dc74493053e93fde93554c95a288c">Opc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#abd544cd2090d6196dce829ca92f6019a">llvm::ArgumentInit::ArgumentInit</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#a0cc4aa4fbe4000af7da66aa492a4f506">llvm::ArgumentInit::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#a32bb9980f9ceade4933ea81fa4d6fc96">llvm::TypedInit::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/unsetinit/#acdd7723aa7cb94ab456ebc4b70ab19f3">llvm::UnsetInit::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#a2e1e32dc2d13727d4578b80413cea98e">llvm::ArgumentInit::cloneWithValue</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#a3b9603403f3438ff734c0eb9ccf6e912">llvm::ArgumentInit::convertInitializerTo</a>, <a href="#ab33fcbf534985fedfc7a1795aa54175b">convertInitializerTo</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#ac19efdca0970a26cd20c2130876ad6a7">llvm::TypedInit::convertInitializerTo</a>, <a href="/web-llvm/docs/api/classes/llvm/unsetinit/#ac2c75ac59d505b345e3ee4673e150577">llvm::UnsetInit::convertInitializerTo</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#a893536c2fd7da5432de36d921a28f43d">llvm::ArgumentInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#a1d1e212cfa61ab5039f8d122579e8366">llvm::ArgumentInit::getBit</a>, <a href="#a853f54e09b3e93b99fe6bfaf249d8fa5">getBit</a>, <a href="/web-llvm/docs/api/classes/llvm/unsetinit/#aa32651c4aceb36dad012e6186557dadf">llvm::UnsetInit::getBit</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#a8c5007fceb80b0609af2c0154a97a331">llvm::ArgumentInit::getCastTo</a>, <a href="#acdccdbcb7e5bb97939575139f2857cd5">getCastTo</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#abfdfeb6e9f368848e73a8eba175a99fb">llvm::TypedInit::getCastTo</a>, <a href="/web-llvm/docs/api/classes/llvm/unsetinit/#a667e4f52e830a6eb25b953294a887498">llvm::UnsetInit::getCastTo</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#a8f463cf291b1b2c5b76384f4db565480">llvm::ArgumentInit::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#ac72f75481ad1b24bed24e2251f231c99">llvm::ArgumentInit::getValue</a>, <a href="#aabd1ee7078e7117d826899b94458f4c9">Init</a>, <a href="#aba744c5d5fe317f5c009e92f5467514c">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#ae95650fc75afa29ea9c2e27f8f0425e3">llvm::ArgumentInit::resolveReferences</a>, <a href="#a00581957c4bb1587a458c3fbf4326f7a">resolveReferences</a> and <a href="/web-llvm/docs/api/classes/llvm/typedinit/#a3a850231a595c63f918ebc27fed94e08">llvm::TypedInit::TypedInit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Init() {#a8a5bcf3838dc863aa08b78885182505a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::Init::~Init ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aba744c5d5fe317f5c009e92f5467514c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Init &amp; llvm::Init::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#ae13588eb910e6f97e1b213f2c875ca8e">Init</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertInitializerBitRange() {#a0b6a1d8d53a93c7d333d3e6f4a664a12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const Init * llvm::Init::convertInitializerBitRange (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; Bits)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function is used to implement the bit range selection operator.</p>


<p>Given a value, it selects the specified bits, returning them as a new <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/init">Init</a></span> of type <span class="doxyComputerOutput">bits</span>. If it is not legal to use the bit selection operator on this value, null is returned.</p>


<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### convertInitializerTo() {#ab33fcbf534985fedfc7a1795aa54175b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const Init * llvm::Init::convertInitializerTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert to a value whose type is <span class="doxyComputerOutput">Ty</span>, or return null if this is not possible.</p>


<p>This can happen if the value's type is convertible to <span class="doxyComputerOutput">Ty</span>, but there are unresolved references.</p>


<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#ae13588eb910e6f97e1b213f2c875ca8e">Init</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5990eefbfd827c2954f6c7be3fe5a2d1">llvm::CheckAssert</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#a3b9603403f3438ff734c0eb9ccf6e912">llvm::ArgumentInit::convertInitializerTo</a>, <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a1f8ad2f0a11458133631759e29f2b54a">llvm::CondOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#af0e0cf8fa25dde613e92575630bb9475">llvm::UnOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a3b8eca57b47e415cd91ef858793a273f">llvm::BinOpInit::resolveReferences</a> and <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#aee884b61ea9174997b34ece042bde0f8">llvm::TernOpInit::resolveReferences</a>.</p>

</div>
</div>

### dump() {#a29593b415ed8217aafed21bab813cb1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Init::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Debugging method that may be called through a debugger; just invokes print on stderr.</p>

<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a404733036e9f08c71a03349991806f33">print</a>.</p>

</div>
</div>

### getAsString() {#a481b80008264e452153378421ebad249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::string llvm::Init::getAsString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert this value to a literal form.</p>

<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/settheory/#add1c3afc970f65746c97311cfdbc329d">llvm::SetTheory::evaluate</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#afc2f4e6bfa3fffaaf68316345d567338">llvm::ArgumentInit::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a9dd1f17ea0dd74bb1b576648bc75f7cf">llvm::CondOpInit::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#af2a7d55b296392d5ed5ae25c769503c6">llvm::DagInit::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/listinit/#a01c1f8a2f9cc6c7dd6ef44bc5a9f83e3">llvm::ListInit::getAsString</a>, <a href="#a285d0b93e0c8992d281d0cf4c89e37b7">getAsUnquotedString</a> and <a href="#a404733036e9f08c71a03349991806f33">print</a>.</p>

</div>
</div>

### getAsUnquotedString() {#a285d0b93e0c8992d281d0cf4c89e37b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::string llvm::Init::getAsUnquotedString ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert this value to a literal form, without adding quotes around a string.</p>

<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a481b80008264e452153378421ebad249">getAsString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/record/#a3dcfa60a1e7d19ffa3b56bb4fcdb3f75">llvm::Record::getNameInitAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/recordval/#a169258790618c09167ef99e06ae01de5">llvm::RecordVal::getNameInitAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/varinit/#af1edce64c0b0bc84dbd881f3109f7bc5">llvm::VarInit::getNameInitAsString</a> and <a href="/web-llvm/docs/api/classes/llvm/record/#a14ef30a60513d26f82c93d796deb7494">llvm::Record::resolveReferences</a>.</p>

</div>
</div>

### getBit() {#a853f54e09b3e93b99fe6bfaf249d8fa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const Init * llvm::Init::getBit (unsigned Bit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/init">Init</a></span> value of the specified bit.</p>

<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#ae13588eb910e6f97e1b213f2c875ca8e">Init</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#a1d1e212cfa61ab5039f8d122579e8366">llvm::ArgumentInit::getBit</a> and <a href="/web-llvm/docs/api/classes/llvm/bitsinit/#ac80663dd5a98becc34254b6f72fc0339">llvm::BitsInit::resolveReferences</a>.</p>

</div>
</div>

### getCastTo() {#acdccdbcb7e5bb97939575139f2857cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const Init * llvm::Init::getCastTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this value is convertible to type <span class="doxyComputerOutput">Ty</span>, return a value whose type is <span class="doxyComputerOutput">Ty</span>, generating a !cast operation if required.</p>


<p>Otherwise, return null.</p>


<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#ae13588eb910e6f97e1b213f2c875ca8e">Init</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#a8c5007fceb80b0609af2c0154a97a331">llvm::ArgumentInit::getCastTo</a>.</p>

</div>
</div>

### getFieldType() {#a9b667af40218e9c4dd447198954f212b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const RecTy * llvm::Init::getFieldType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringinit">StringInit</a> * FieldName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function is used to implement the <a href="/web-llvm/docs/api/classes/llvm/fieldinit">FieldInit</a> class.</p>


<p>Implementors of this method should return the type of the named field if they are of type record.</p>


<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### getKind() {#a58eb865e6057d2dafe7de4a2bed6b5a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InitKind llvm::Init::getKind ()</td>
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

<p>Get the kind (type) of the value.</p>

<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

### getRecordKeeper() {#aceb63812efd39ed325fc5579b10213f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordKeeper &amp; Init::getRecordKeeper ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the record keeper that initialized this <a href="/web-llvm/docs/api/classes/llvm/init">Init</a>.</p>

<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5990eefbfd827c2954f6c7be3fe5a2d1">llvm::CheckAssert</a> and <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a540b4a99be94bc991bf4948b8f97e9bb">llvm::BinOpInit::getStrConcat</a>.</p>

</div>
</div>

### isComplete() {#a84ecdbe17c6975f34940e673a1204eb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Init::isComplete ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is this a complete value with no unset (uninitialized) subvalues?</p>

<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/listinit/#a7698e11ca04caabd50208e0ba0805c15">llvm::ListInit::isComplete</a>.</p>

</div>
</div>

### isConcrete() {#a7e9256379467310487f19e38f7c723fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::Init::isConcrete ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is this a concrete and fully resolved value without any references or stuck operations?</p>


<p>Unset values are concrete.</p>


<p>Definition at line 358 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fieldinit/#a2c30e04a4f53b4ecbc0897f161ae00de">llvm::FieldInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/fieldinit/#afaa2e182c896e42578a6606bc7a638c8">llvm::FieldInit::isConcrete</a> and <a href="/web-llvm/docs/api/classes/llvm/listinit/#a490a9aecb9cb4c9fba9aace8b98880a8">llvm::ListInit::isConcrete</a>.</p>

</div>
</div>

### print() {#a404733036e9f08c71a03349991806f33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Init::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>Print this value.</p>

<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#a481b80008264e452153378421ebad249">getAsString</a>.</p>


<p>Referenced by <a href="#a29593b415ed8217aafed21bab813cb1e">dump</a>.</p>

</div>
</div>

### resolveReferences() {#a00581957c4bb1587a458c3fbf4326f7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const Init * llvm::Init::resolveReferences (<a href="/web-llvm/docs/api/classes/llvm/resolver">Resolver</a> &amp; R)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function is used by classes that refer to other variables which may not be defined at the time the expression is formed.</p>


<p>If a value is set for the variable later, this method will be called on users of the value to allow the value to propagate out.</p>


<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Reference <a href="#ae13588eb910e6f97e1b213f2c875ca8e">Init</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/record/#af965a776d26783397a4825a49a84bd11">llvm::Record::checkRecordAssertions</a>, <a href="/web-llvm/docs/api/classes/llvm/foldopinit/#a01fa2c13ef026fa0915ffbfba65b9c3b">llvm::FoldOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/recordresolver/#a6af01f6918a13cb2b415e88875d1184b">llvm::RecordResolver::resolve</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a3b8eca57b47e415cd91ef858793a273f">llvm::BinOpInit::resolveReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/bitsinit/#ac80663dd5a98becc34254b6f72fc0339">llvm::BitsInit::resolveReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a6bb67693444e665aa7e34c718f4d9166">llvm::CondOpInit::resolveReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#a967db113515bd01d32db6a426d7c73c1">llvm::DagInit::resolveReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/foldopinit/#abf5c6303f8771b4a93c937eea625e4a8">llvm::FoldOpInit::resolveReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/listinit/#a77628fbcb57174907a143918285c0e70">llvm::ListInit::resolveReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a14ef30a60513d26f82c93d796deb7494">llvm::Record::resolveReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#aee884b61ea9174997b34ece042bde0f8">llvm::TernOpInit::resolveReferences</a> and <a href="/web-llvm/docs/api/classes/llvm/unopinit/#ac56f3b64a789146946b48afe5613c2f5">llvm::UnOpInit::resolveReferences</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a115f482d5164e7f829d5e3b51def89aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Init::anchor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Opc {#a033dc74493053e93fde93554c95a288c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::Init::Opc</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a909a53b386dc20dfa36a2fb86d63ec36">llvm::BinOpInit::CompareInit</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a1717b7dc956fb447c4fd0a8ce3941b05">llvm::BinOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#acfaa331daa279dcd3a22f04d1830cf7f">llvm::TernOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#aa8ac284a20b1ea9f96469bf3d39d1f81">llvm::UnOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a74a17044f10f3fe747ea0d037e6b9085">llvm::BinOpInit::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#af33525b5a190bd3fba5fcd1e46910343">llvm::TernOpInit::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#a83abcaad6f9e99aa316e38329c8889b6">llvm::UnOpInit::getOpcode</a>, <a href="#ae13588eb910e6f97e1b213f2c875ca8e">Init</a>, <a href="/web-llvm/docs/api/classes/llvm/opinit/#ae1153460ec9adaa262e589e9d017895d">llvm::OpInit::OpInit</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a3b8eca57b47e415cd91ef858793a273f">llvm::BinOpInit::resolveReferences</a> and <a href="/web-llvm/docs/api/classes/llvm/typedinit/#a3a850231a595c63f918ebc27fed94e08">llvm::TypedInit::TypedInit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Kind {#a26f7c750178489bb70d6f145c5c8c327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InitKind llvm::Init::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">Record.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
