---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/attributor/argumentreplacementinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ArgumentReplacementInfo` Struct Reference

<p>Helper struct used in the communication between an abstract attribute (<a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a>) that wants to change the signature of a function and the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> which applies the changes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::Attributor::ArgumentReplacementInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2083e74f7ea053500761e58968041ff7">CalleeRepairCBTy</a> = std::function&lt; void( <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/attributor/argumentreplacementinfo">ArgumentReplacementInfo</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/function/#a1c9f2f058966db1f8ca270398bda8362">Function::arg_iterator</a>)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callee repair callback type. <a href="#a2083e74f7ea053500761e58968041ff7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7e2d390e89b26a2e16db36d9f522874">ACSRepairCBTy</a> = std::function&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/attributor/argumentreplacementinfo">ArgumentReplacementInfo</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite">AbstractCallSite</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp;)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract call site (ACS) repair callback type. <a href="#ae7e2d390e89b26a2e16db36d9f522874">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allow access to the private members from the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a>. <a href="#a05f3b3169e1f6a561b0c38f0150b3867">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b1836b3047bfd5561528ec8c6296b7">ArgumentReplacementInfo</a> (Attributor &amp;A, Argument &amp;Arg, ArrayRef&lt; Type * &gt; ReplacementTypes, CalleeRepairCBTy &amp;&amp;CalleeRepairCB, ACSRepairCBTy &amp;&amp;ACSRepairCB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a62b1836b3047bfd5561528ec8c6296b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad840c707a8882dee5f58d4e2168853f1">getAttributor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple getters, see the corresponding members for details. <a href="#ad840c707a8882dee5f58d4e2168853f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2daf55ff07823682a7b59cf9fb374fd">getReplacedFn</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8f10b7ea79a88ac27287063cd5266e">getReplacedArg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2e6dc74347043e18290459a75e0bc7">getNumReplacementArgs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aa8aa43319faf374d972f21b100b98d">getReplacementTypes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aaf83d13d230056c8791b9d1bb38d02">A</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reference to the attributor to allow access from the callbacks. <a href="#a4aaf83d13d230056c8791b9d1bb38d02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e2f5092cc1bcd2f123a347a652d0e44">ReplacedFn</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The "old" function replaced by ReplacementFn. <a href="#a1e2f5092cc1bcd2f123a347a652d0e44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac35dd43deb311ea8badeae84013c89d2">ReplacedArg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The "old" argument replaced by new ones defined via ReplacementTypes. <a href="#ac35dd43deb311ea8badeae84013c89d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a413a9dc777d59d24d9d3611e89ce0ef9">ReplacementTypes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The types of the arguments replacing ReplacedArg. <a href="#a413a9dc777d59d24d9d3611e89ce0ef9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a2083e74f7ea053500761e58968041ff7">CalleeRepairCBTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bd58d0bb3476cab7e8beddb085827bc">CalleeRepairCB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callee repair callback, see <a href="#a2083e74f7ea053500761e58968041ff7">CalleeRepairCBTy</a>. <a href="#a2bd58d0bb3476cab7e8beddb085827bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ae7e2d390e89b26a2e16db36d9f522874">ACSRepairCBTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a877637163487d60bd775a799b0923b0e">ACSRepairCB</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract call site (ACS) repair callback, see <a href="#ae7e2d390e89b26a2e16db36d9f522874">ACSRepairCBTy</a>. <a href="#a877637163487d60bd775a799b0923b0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Helper struct used in the communication between an abstract attribute (<a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a>) that wants to change the signature of a function and the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> which applies the changes.</p>


<p>The struct is partially initialized with the information from the <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> (see the constructor). All other members are provided by the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> prior to invoking any callbacks.</p>


<p>Definition at line 2221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ACSRepairCBTy {#ae7e2d390e89b26a2e16db36d9f522874}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Attributor::ArgumentReplacementInfo::ACSRepairCBTy = 
        std::function&lt;void(const ArgumentReplacementInfo &amp;, AbstractCallSite,
                           SmallVectorImpl&lt;Value *&gt; &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Abstract call site (ACS) repair callback type.</p>


<p>The abstract call site repair callback is invoked once on every abstract call site of the replaced function (</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>ReplacedFn). The callback needs to provide the operands <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> the call to the new replacement <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a>. The number and type of the operands appended to the provided <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a> (second argument) is defined by the number and types determined through the replacement type <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">vector</a> (</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>ReplacementTypes). The first argument is the <a href="/web-llvm/docs/api/structs/llvm/attributor/argumentreplacementinfo">ArgumentReplacementInfo</a> <a href="/web-llvm/docs/api/namespaces/llvm/object">object</a> registered with the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> through the <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0121eb7b984a5cf2527133cb838d5982">registerFunctionSignatureRewrite</a> call.</p></dd>
</dl>


<p>Definition at line 2242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### CalleeRepairCBTy {#a2083e74f7ea053500761e58968041ff7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Attributor::ArgumentReplacementInfo::CalleeRepairCBTy =  std::function&lt;void(
        const ArgumentReplacementInfo &amp;, Function &amp;, Function::arg_iterator)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callee repair callback type.</p>


<p>The function repair callback is invoked once to rewire the replacement arguments in the body of the new function. The argument replacement info is passed, as build from the registerFunctionSignatureRewrite call, as well as the replacement function and an iteratore to the first replacement argument.</p>


<p>Definition at line 2229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### Attributor {#a05f3b3169e1f6a561b0c38f0150b3867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allow access to the private members from the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a>.</p>

<p>Definition at line 2291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a>.</p>


<p>Referenced by <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a> and <a href="#ad840c707a8882dee5f58d4e2168853f1">getAttributor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ArgumentReplacementInfo() {#a62b1836b3047bfd5561528ec8c6296b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Attributor::ArgumentReplacementInfo::ArgumentReplacementInfo (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &amp; Arg, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; ReplacementTypes, <a href="#a2083e74f7ea053500761e58968041ff7">CalleeRepairCBTy</a> &amp;&amp; CalleeRepairCB, <a href="#ae7e2d390e89b26a2e16db36d9f522874">ACSRepairCBTy</a> &amp;&amp; ACSRepairCB)</td>
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

<p>}</p>


<p>Constructor that takes the argument to be replaced, the types of the replacement arguments, as well as callbacks to repair the call sites and new function after the replacement happened.</p>


<p>Definition at line 2263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAttributor() {#ad840c707a8882dee5f58d4e2168853f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attributor &amp; llvm::Attributor::ArgumentReplacementInfo::getAttributor ()</td>
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

<p>Simple getters, see the corresponding members for details.</p>


<p>{</p>


<p>Definition at line 2249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a>.</p>

</div>
</div>

### getNumReplacementArgs() {#a4c2e6dc74347043e18290459a75e0bc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Attributor::ArgumentReplacementInfo::getNumReplacementArgs ()</td>
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



<p>Definition at line 2252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### getReplacedArg() {#a9e8f10b7ea79a88ac27287063cd5266e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Argument &amp; llvm::Attributor::ArgumentReplacementInfo::getReplacedArg ()</td>
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



<p>Definition at line 2251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ae965a8b6001eaf1612d36d070594c706">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::manifest</a>.</p>

</div>
</div>

### getReplacedFn() {#ae2daf55ff07823682a7b59cf9fb374fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function &amp; llvm::Attributor::ArgumentReplacementInfo::getReplacedFn ()</td>
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



<p>Definition at line 2250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### getReplacementTypes() {#a7aa8aa43319faf374d972f21b100b98d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; Type * &gt; &amp; llvm::Attributor::ArgumentReplacementInfo::getReplacementTypes ()</td>
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



<p>Definition at line 2253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### A {#a4aaf83d13d230056c8791b9d1bb38d02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attributor&amp; llvm::Attributor::ArgumentReplacementInfo::A</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reference to the attributor to allow access from the callbacks.</p>

<p>Definition at line 2273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### ACSRepairCB {#a877637163487d60bd775a799b0923b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ACSRepairCBTy llvm::Attributor::ArgumentReplacementInfo::ACSRepairCB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Abstract call site (ACS) repair callback, see <a href="#ae7e2d390e89b26a2e16db36d9f522874">ACSRepairCBTy</a>.</p>

<p>Definition at line 2288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### CalleeRepairCB {#a2bd58d0bb3476cab7e8beddb085827bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CalleeRepairCBTy llvm::Attributor::ArgumentReplacementInfo::CalleeRepairCB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callee repair callback, see <a href="#a2083e74f7ea053500761e58968041ff7">CalleeRepairCBTy</a>.</p>

<p>Definition at line 2285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### ReplacedArg {#ac35dd43deb311ea8badeae84013c89d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Argument&amp; llvm::Attributor::ArgumentReplacementInfo::ReplacedArg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The "old" argument replaced by new ones defined via ReplacementTypes.</p>

<p>Definition at line 2279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### ReplacedFn {#a1e2f5092cc1bcd2f123a347a652d0e44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function&amp; llvm::Attributor::ArgumentReplacementInfo::ReplacedFn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The "old" function replaced by ReplacementFn.</p>

<p>Definition at line 2276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### ReplacementTypes {#a413a9dc777d59d24d9d3611e89ce0ef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVector&lt;Type *, 8&gt; llvm::Attributor::ArgumentReplacementInfo::ReplacementTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The types of the arguments replacing ReplacedArg.</p>

<p>Definition at line 2282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
