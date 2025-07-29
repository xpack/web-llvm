---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/functionsummary
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FunctionSummary` Class

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> summary information to aid decisions and implementation of importing. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FunctionSummary { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> and variable summary information to aid decisions and implementation of importing. <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434edf3518376986c8bb393f5e0eec33">EdgeTy</a> = std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo">CalleeInfo</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>&lt;CalleeValueInfo, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo">CalleeInfo</a>&gt; call edge pair. <a href="#a434edf3518376986c8bb393f5e0eec33">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33440b2285355fd3062506210180f321">ParamAccessesTy</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/paramaccess">ParamAccess</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Uses for every parameter to this function. <a href="#a33440b2285355fd3062506210180f321">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f62a141c9258deb1a9c56a36d269520">CallsitesTy</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/callsiteinfo">CallsiteInfo</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional list of memprof callsite metadata summaries. <a href="#a1f62a141c9258deb1a9c56a36d269520">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71bf6487af059a880f7d59d84b5f32c4">AllocsTy</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/allocinfo">AllocInfo</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional list of allocation memprof metadata summaries. <a href="#a71bf6487af059a880f7d59d84b5f32c4">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ForceSummaryHotnessType : unsigned { <a href="#ad8775375a74c04489e82ba5e39a2cf33">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Types for -force-summary-edges-cold debugging option. <a href="#ad8775375a74c04489e82ba5e39a2cf33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94439c951687389f2d27639eb527eea3">GraphTraits&lt; ValueInfo &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a241573674bcf98689b6c224b05d90f70">FunctionSummary</a> (GVFlags Flags, unsigned NumInsts, FFlags FunFlags, SmallVectorImpl&lt; ValueInfo &gt; &amp;&amp;Refs, SmallVectorImpl&lt; EdgeTy &gt; &amp;&amp;CGEdges, std::vector&lt; GlobalValue::GUID &gt; TypeTests, std::vector&lt; VFuncId &gt; TypeTestAssumeVCalls, std::vector&lt; VFuncId &gt; TypeCheckedLoadVCalls, std::vector&lt; ConstVCall &gt; TypeTestAssumeConstVCalls, std::vector&lt; ConstVCall &gt; TypeCheckedLoadConstVCalls, std::vector&lt; ParamAccess &gt; Params, CallsitesTy CallsiteList, AllocsTy AllocList)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50331d58f39c3550aefcaf624ee72d41">specialRefCounts</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/functionsummary/fflags">FFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf3998a7e0703c1eac651524d9d14a0d">fflags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get function summary flags. <a href="#adf3998a7e0703c1eac651524d9d14a0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a344658784ee3a7699b6a231e6ff57556">setNoRecurse</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b76a0a92f9763aa782c06c2c98abef">setNoUnwind</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c7a4e9c5bce12a30f1fcd3c0d2e580">instCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the instruction count recorded for this function. <a href="#aa1c7a4e9c5bce12a30f1fcd3c0d2e580">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#a434edf3518376986c8bb393f5e0eec33">EdgeTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac098d4a76445782b25543d1725a082bc">calls</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the list of &lt;CalleeValueInfo, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo">CalleeInfo</a>&gt; pairs. <a href="#ac098d4a76445782b25543d1725a082bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a434edf3518376986c8bb393f5e0eec33">EdgeTy</a>, 0 &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a543edf7198017b525fad9037f0d79550">mutableCalls</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c294f5981df28f61ab4799fb6e8935">addCall</a> (EdgeTy E)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed29929beecf0fe92c90f29d641f0169">type_tests</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of type identifiers used by this function in llvm.type.test intrinsics other than by an llvm.assume intrinsic, represented as GUIDs. <a href="#aed29929beecf0fe92c90f29d641f0169">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">VFuncId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a216eeb903b353efe736c900ddff2ba">type_test_assume_vcalls</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of virtual calls made by this function using llvm.assume(llvm.type.test) intrinsics that do not have all constant integer arguments. <a href="#a2a216eeb903b353efe736c900ddff2ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">VFuncId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c82a9e5cdd69648861f81c4c2e73c6">type_checked_load_vcalls</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of virtual calls made by this function using llvm.type.checked.load intrinsics that do not have all constant integer arguments. <a href="#a98c82a9e5cdd69648861f81c4c2e73c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">ConstVCall</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4073537ea6a1edb6a6e804d2ae792a67">type_test_assume_const_vcalls</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of virtual calls made by this function using llvm.assume(llvm.type.test) intrinsics with all constant integer arguments. <a href="#a4073537ea6a1edb6a6e804d2ae792a67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">ConstVCall</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfadddec58208f7ba766303947943af6">type_checked_load_const_vcalls</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of virtual calls made by this function using llvm.type.checked.load intrinsics with all constant integer arguments. <a href="#abfadddec58208f7ba766303947943af6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/paramaccess">ParamAccess</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd57403dd991a4c60518a612ced94b1e">paramAccesses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of known uses of pointer parameters. <a href="#acd57403dd991a4c60518a612ced94b1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4ffbf730e2a6dfdeb382bbad7cf94e">setParamAccesses</a> (std::vector&lt; ParamAccess &gt; NewParams)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the list of known uses of pointer parameters. <a href="#a9d4ffbf730e2a6dfdeb382bbad7cf94e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66ab2c18efce03641375f181f1fba59a">addTypeTest</a> (GlobalValue::GUID Guid)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a type test to the summary. <a href="#a66ab2c18efce03641375f181f1fba59a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/functionsummary/typeidinfo">TypeIdInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa564110e15a096a7f53a22826253e4e2">getTypeIdInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/callsiteinfo">CallsiteInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ece5db98ff08d6acd9b9d1dc66b112">callsites</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">CallsitesTy &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2cd6d55e7f828fd15032f838f79ad9f">mutableCallsites</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b5b24b7f3fc19301336305d50031875">addCallsite</a> (CallsiteInfo &amp;Callsite)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/allocinfo">AllocInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55fe1cb8231954ce835e4ddaf29a6fe9">allocs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">AllocsTy &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30681faa19914265942f7108cdeed161">mutableAllocs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb82c3b4302e8e690c85a329f726f3f4">InstCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of instructions (ignoring debug instructions, e.g.) computed during the initial compile step when the summary index is first built. <a href="#acb82c3b4302e8e690c85a329f726f3f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/functionsummary/fflags">FFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c10bd40ac6aea3b90c477aed70f6d32">FunFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> summary specific flags. <a href="#a9c10bd40ac6aea3b90c477aed70f6d32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="#a434edf3518376986c8bb393f5e0eec33">EdgeTy</a>, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ceb866181bb3fcdf978162eccb67dca">CallGraphEdgeList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>List of &lt;CalleeValueInfo, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo">CalleeInfo</a>&gt; call edge pairs from this function. <a href="#a7ceb866181bb3fcdf978162eccb67dca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/typeidinfo">TypeIdInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab77a5bdd92d91956f5634bb2eab59e6c">TIdInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; ParamAccessesTy &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c936178d53d3ce49b009707fb31a67">ParamAccesses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; CallsitesTy &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9108b7064591bee204a9aa9988649e92">Callsites</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; AllocsTy &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a607240413db641b3f329314fd1e4526a">Allocs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1db7848814def586ba64546a43e0fcdc">makeDummyFunctionSummary</a> (SmallVectorImpl&lt; FunctionSummary::EdgeTy &gt; &amp;&amp;Edges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an empty <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> (with specified call edges). <a href="#a1db7848814def586ba64546a43e0fcdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0bfd4aef05a892f373f946ad2ab2a4b">classof</a> (const GlobalValueSummary *GVS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a function summary. <a href="#af0bfd4aef05a892f373f946ad2ab2a4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a074b44b12e81aecb67ebcbca71e7c76f">ExternalNode</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A dummy node to reference external functions that aren't in the index. <a href="#a074b44b12e81aecb67ebcbca71e7c76f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> summary information to aid decisions and implementation of importing.</p>

<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### EdgeTy {#a434edf3518376986c8bb393f5e0eec33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::FunctionSummary::EdgeTy =  std::pair&lt;ValueInfo, CalleeInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>&lt;CalleeValueInfo, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo">CalleeInfo</a>&gt; call edge pair.</p>

<p>Definition at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### AllocsTy {#a71bf6487af059a880f7d59d84b5f32c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::FunctionSummary::AllocsTy =  std::vector&lt;AllocInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optional list of allocation memprof metadata summaries.</p>


<p>The correspondence between the alloc memprof summary and the allocation callsites in the function is implied by the order in the vector (and can be validated by comparing the stack ids in the <a href="/web-llvm/docs/api/structs/llvm/allocinfo">AllocInfo</a> to those in the instruction memprof metadata). As a memory savings optimization, we only create these for the prevailing copy of a symbol when creating the combined index during LTO.</p>


<p>Definition at line 930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### CallsitesTy {#a1f62a141c9258deb1a9c56a36d269520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::FunctionSummary::CallsitesTy =  std::vector&lt;CallsiteInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optional list of memprof callsite metadata summaries.</p>


<p>The correspondence between the callsite summary and the callsites in the function is implied by the order in the vector (and can be validated by comparing the stack ids in the <a href="/web-llvm/docs/api/structs/llvm/callsiteinfo">CallsiteInfo</a> to those in the instruction callsite metadata). As a memory savings optimization, we only create these for the prevailing copy of a symbol when creating the combined index during LTO.</p>


<p>Definition at line 920 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### ParamAccessesTy {#a33440b2285355fd3062506210180f321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::FunctionSummary::ParamAccessesTy =  std::vector&lt;ParamAccess&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Uses for every parameter to this function.</p>

<p>Definition at line 911 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ForceSummaryHotnessType {#ad8775375a74c04489e82ba5e39a2cf33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::FunctionSummary::ForceSummaryHotnessType : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Types for -force-summary-edges-cold debugging option.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSHT_None<a id="ad8775375a74c04489e82ba5e39a2cf33a91e19b0aa8dcda73fcff4dfbe4f98b8c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSHT_AllNonCritical<a id="ad8775375a74c04489e82ba5e39a2cf33aab8d457f0c94e8b981e00ddec3e6c13f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FSHT_All<a id="ad8775375a74c04489e82ba5e39a2cf33ab2c06e29582ab10b05b65ae878009a63"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### GraphTraits&lt; ValueInfo &gt; {#a94439c951687389f2d27639eb527eea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1081 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### FunctionSummary() {#a241573674bcf98689b6c224b05d90f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FunctionSummary::FunctionSummary (<a href="/web-llvm/docs/api/structs/llvm/globalvaluesummary/gvflags">GVFlags</a> Flags, unsigned NumInsts, <a href="/web-llvm/docs/api/structs/llvm/functionsummary/fflags">FFlags</a> FunFlags, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &gt; &amp;&amp; Refs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#a434edf3518376986c8bb393f5e0eec33">EdgeTy</a> &gt; &amp;&amp; CGEdges, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; TypeTests, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">VFuncId</a> &gt; TypeTestAssumeVCalls, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/vfuncid">VFuncId</a> &gt; TypeCheckedLoadVCalls, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">ConstVCall</a> &gt; TypeTestAssumeConstVCalls, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/constvcall">ConstVCall</a> &gt; TypeCheckedLoadConstVCalls, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/paramaccess">ParamAccess</a> &gt; Params, CallsitesTy CallsiteList, AllocsTy AllocList)</td>
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



<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a0c8dfea65f1f5dfba143b1fc9768614ca5034481e0a0691fa0f4b4321c33ecb5b">llvm::GlobalValueSummary::FunctionKind</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#acf835818782f78ea638f6adb59ab7c62">llvm::GlobalValueSummary::GlobalValueSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#a1db7848814def586ba64546a43e0fcdc">makeDummyFunctionSummary</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCall() {#a37c294f5981df28f61ab4799fb6e8935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FunctionSummary::addCall (<a href="#a434edf3518376986c8bb393f5e0eec33">EdgeTy</a> E)</td>
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



<p>Definition at line 985 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>.</p>

</div>
</div>

### addCallsite() {#a0b5b24b7f3fc19301336305d50031875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FunctionSummary::addCallsite (<a href="/web-llvm/docs/api/structs/llvm/callsiteinfo">CallsiteInfo</a> &amp; Callsite)</td>
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



<p>Definition at line 1069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### addTypeTest() {#a66ab2c18efce03641375f181f1fba59a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FunctionSummary::addTypeTest (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> Guid)</td>
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

<p>Add a type test to the summary.</p>


<p>This is used by WholeProgramDevirt if we were unable to devirtualize a checked call.</p>


<p>Definition at line 1050 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0acb957607a78494ea70db887d1463437c">llvm::Guid</a>.</p>

</div>
</div>

### allocs() {#a55fe1cb8231954ce835e4ddaf29a6fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; AllocInfo &gt; llvm::FunctionSummary::allocs ()</td>
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



<p>Definition at line 1075 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### calls() {#ac098d4a76445782b25543d1725a082bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; EdgeTy &gt; llvm::FunctionSummary::calls ()</td>
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

<p>Return the list of &lt;CalleeValueInfo, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo">CalleeInfo</a>&gt; pairs.</p>

<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a45395a3dca2e20d0e8dde2d0532ec401">llvm::thinLTOPropagateFunctionAttrs</a>.</p>

</div>
</div>

### callsites() {#a59ece5db98ff08d6acd9b9d1dc66b112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; CallsiteInfo &gt; llvm::FunctionSummary::callsites ()</td>
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



<p>Definition at line 1058 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### fflags() {#adf3998a7e0703c1eac651524d9d14a0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FFlags llvm::FunctionSummary::fflags ()</td>
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

<p>Get function summary flags.</p>

<p>Definition at line 971 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a45395a3dca2e20d0e8dde2d0532ec401">llvm::thinLTOPropagateFunctionAttrs</a>.</p>

</div>
</div>

### getTypeIdInfo() {#aa564110e15a096a7f53a22826253e4e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TypeIdInfo * llvm::FunctionSummary::getTypeIdInfo ()</td>
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



<p>Definition at line 1056 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### instCount() {#aa1c7a4e9c5bce12a30f1fcd3c0d2e580}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FunctionSummary::instCount ()</td>
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

<p>Get the instruction count recorded for this function.</p>

<p>Definition at line 978 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionimport-cpp/#a36d763333ed81c8ff62e28b20125a95b">computeImportForFunction</a>.</p>

</div>
</div>

### mutableAllocs() {#a30681faa19914265942f7108cdeed161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AllocsTy &amp; llvm::FunctionSummary::mutableAllocs ()</td>
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



<p>Definition at line 1081 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### mutableCalls() {#a543edf7198017b525fad9037f0d79550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; EdgeTy, 0 &gt; &amp; llvm::FunctionSummary::mutableCalls ()</td>
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



<p>Definition at line 983 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### mutableCallsites() {#ad2cd6d55e7f828fd15032f838f79ad9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallsitesTy &amp; llvm::FunctionSummary::mutableCallsites ()</td>
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



<p>Definition at line 1064 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### paramAccesses() {#acd57403dd991a4c60518a612ced94b1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; ParamAccess &gt; llvm::FunctionSummary::paramAccesses ()</td>
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

<p>Returns the list of known uses of pointer parameters.</p>

<p>Definition at line 1032 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### setNoRecurse() {#a344658784ee3a7699b6a231e6ff57556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FunctionSummary::setNoRecurse ()</td>
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



<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### setNoUnwind() {#a63b76a0a92f9763aa782c06c2c98abef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FunctionSummary::setNoUnwind ()</td>
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



<p>Definition at line 975 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### setParamAccesses() {#a9d4ffbf730e2a6dfdeb382bbad7cf94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FunctionSummary::setParamAccesses (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/functionsummary/paramaccess">ParamAccess</a> &gt; NewParams)</td>
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

<p>Sets the list of known uses of pointer parameters.</p>

<p>Definition at line 1039 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### specialRefCounts() {#a50331d58f39c3550aefcaf624ee72d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; unsigned, unsigned &gt; FunctionSummary::specialRefCounts ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>, definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/modulesummaryindex-cpp">ModuleSummaryIndex.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a57d9bc8ab2ba2eda5199dd1b46859750">llvm::GlobalValueSummary::refs</a>.</p>

</div>
</div>

### type\_checked\_load\_const\_vcalls() {#abfadddec58208f7ba766303947943af6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; ConstVCall &gt; llvm::FunctionSummary::type_checked_load_const_vcalls ()</td>
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

<p>Returns the list of virtual calls made by this function using llvm.type.checked.load intrinsics with all constant integer arguments.</p>

<p>Definition at line 1025 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### type\_checked\_load\_vcalls() {#a98c82a9e5cdd69648861f81c4c2e73c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; VFuncId &gt; llvm::FunctionSummary::type_checked_load_vcalls ()</td>
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

<p>Returns the list of virtual calls made by this function using llvm.type.checked.load intrinsics that do not have all constant integer arguments.</p>

<p>Definition at line 1008 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### type\_test\_assume\_const\_vcalls() {#a4073537ea6a1edb6a6e804d2ae792a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; ConstVCall &gt; llvm::FunctionSummary::type_test_assume_const_vcalls ()</td>
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

<p>Returns the list of virtual calls made by this function using llvm.assume(llvm.type.test) intrinsics with all constant integer arguments.</p>

<p>Definition at line 1017 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### type\_test\_assume\_vcalls() {#a2a216eeb903b353efe736c900ddff2ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; VFuncId &gt; llvm::FunctionSummary::type_test_assume_vcalls ()</td>
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

<p>Returns the list of virtual calls made by this function using llvm.assume(llvm.type.test) intrinsics that do not have all constant integer arguments.</p>

<p>Definition at line 999 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### type\_tests() {#aed29929beecf0fe92c90f29d641f0169}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; GlobalValue::GUID &gt; llvm::FunctionSummary::type_tests ()</td>
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

<p>Returns the list of type identifiers used by this function in llvm.type.test intrinsics other than by an llvm.assume intrinsic, represented as GUIDs.</p>

<p>Definition at line 990 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocs {#a607240413db641b3f329314fd1e4526a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;AllocsTy&gt; llvm::FunctionSummary::Allocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 931 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### CallGraphEdgeList {#a7ceb866181bb3fcdf978162eccb67dca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;EdgeTy, 0&gt; llvm::FunctionSummary::CallGraphEdgeList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>List of &lt;CalleeValueInfo, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo">CalleeInfo</a>&gt; call edge pairs from this function.</p>


<p>We use <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector&lt;ValueInfo, 0&gt;</a> instead of std::vector&lt;ValueInfo&gt; for its smaller memory footprint.</p>


<p>Definition at line 906 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### Callsites {#a9108b7064591bee204a9aa9988649e92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CallsitesTy&gt; llvm::FunctionSummary::Callsites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### FunFlags {#a9c10bd40ac6aea3b90c477aed70f6d32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FFlags llvm::FunctionSummary::FunFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> summary specific flags.</p>

<p>Definition at line 901 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### InstCount {#acb82c3b4302e8e690c85a329f726f3f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FunctionSummary::InstCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of instructions (ignoring debug instructions, e.g.) computed during the initial compile step when the summary index is first built.</p>

<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### ParamAccesses {#a94c936178d53d3ce49b009707fb31a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ParamAccessesTy&gt; llvm::FunctionSummary::ParamAccesses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 912 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

### TIdInfo {#ab77a5bdd92d91956f5634bb2eab59e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TypeIdInfo&gt; llvm::FunctionSummary::TIdInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#af0bfd4aef05a892f373f946ad2ab2a4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionSummary::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary">GlobalValueSummary</a> * GVS)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this is a function summary.</p>

<p>Definition at line 966 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a0c8dfea65f1f5dfba143b1fc9768614ca5034481e0a0691fa0f4b4321c33ecb5b">llvm::GlobalValueSummary::FunctionKind</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a47f1a00572fa323c4a9662ff0a479c75">llvm::GlobalValueSummary::getSummaryKind</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#acf835818782f78ea638f6adb59ab7c62">llvm::GlobalValueSummary::GlobalValueSummary</a>.</p>

</div>
</div>

### makeDummyFunctionSummary() {#a1db7848814def586ba64546a43e0fcdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSummary llvm::FunctionSummary::makeDummyFunctionSummary (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#a434edf3518376986c8bb393f5e0eec33">FunctionSummary::EdgeTy</a> &gt; &amp;&amp; Edges)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an empty <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> (with specified call edges).</p>


<p>Used to represent external nodes and the dummy root node.</p>


<p>Definition at line 875 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">llvm::GlobalValue::AvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">llvm::GlobalValue::DefaultVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a04e3abfb7aee7a96d3d56a99c9f0b737acb646dd0be0c28c71a939dc87ab59340">llvm::GlobalValueSummary::Definition</a>, <a href="#a241573674bcf98689b6c224b05d90f70">FunctionSummary</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8fc529c79977cdd01e187986f960a07f">llvm::SmallVector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#aeef8fd311d28014d31806cb5c9ad523f">llvm::ModuleSummaryIndex::calculateCallGraphRoot</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ExternalNode {#a074b44b12e81aecb67ebcbca71e7c76f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSummary FunctionSummary::ExternalNode</td>
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

<p>A dummy node to reference external functions that aren't in the index.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    <a href="#a1db7848814def586ba64546a43e0fcdc">FunctionSummary::makeDummyFunctionSummary</a>(
        <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt;<a href="#a434edf3518376986c8bb393f5e0eec33">FunctionSummary::EdgeTy</a>, 0&gt;())
</div>
</dd>
</dl>

<p>Definition at line 893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/graphtraits-54af6749b69c1b355796c199a231acf9/#a1df0ebff95cce54041e22832b0d84fb7">llvm::GraphTraits&lt; ValueInfo &gt;::child_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-54af6749b69c1b355796c199a231acf9/#a22c7599518f8b72893228c323340046e">llvm::GraphTraits&lt; ValueInfo &gt;::child_edge_begin</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-54af6749b69c1b355796c199a231acf9/#af67d95f0a474235b2b276bac8a569b32">llvm::GraphTraits&lt; ValueInfo &gt;::child_edge_end</a> and <a href="/web-llvm/docs/api/structs/llvm/graphtraits-54af6749b69c1b355796c199a231acf9/#ae51a23343f5b03579c6f891232cd3f29">llvm::GraphTraits&lt; ValueInfo &gt;::child_end</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">ModuleSummaryIndex.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/modulesummaryindex-cpp">ModuleSummaryIndex.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
