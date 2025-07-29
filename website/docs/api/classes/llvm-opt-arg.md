---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/opt/arg
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Arg` Class

<p>A concrete instance of a particular driver option. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::opt::Arg { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">llvm/Option/Arg.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b0d66db2f3d222a19a243a3c2ede670">Arg</a> (const Option Opt, StringRef Spelling, unsigned Index, const Arg *BaseArg=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e401accaa77741c3634023d1b2c1479">Arg</a> (const Option Opt, StringRef Spelling, unsigned Index, const char *Value0, const Arg *BaseArg=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5e3cde2f5fe51aaf1f49835db7ede68">Arg</a> (const Option Opt, StringRef Spelling, unsigned Index, const char *Value0, const char *Value1, const Arg *BaseArg=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86caf310a5976603997aa99a80a1601f">Arg</a> (const Arg &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac134760e8dc2be78ae5fc7b13d5fc05c">~Arg</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62592ff96a912f9c4734124b9fcd8a19">operator=</a> (const Arg &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a666ec80cc708a588992a87278c4e1f74">getOption</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e47a861c3eadf9c29201f82d126871a">getSpelling</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the used prefix and name of the option: For <span class="doxyComputerOutput">--foo=bar</span>, returns <span class="doxyComputerOutput">--foo=</span>. <a href="#a4e47a861c3eadf9c29201f82d126871a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4bc2ba2f9a43c63f42d58d8412c6eda">getIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14874091f02f61eef3906ebf03701d05">getBaseArg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the base argument which generated this arg. <a href="#a14874091f02f61eef3906ebf03701d05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75cbed0ab331ea130c7ed6ca4d9b2e50">getBaseArg</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f09f1a62e0c45d4a382ea58bd117933">setBaseArg</a> (const Arg *BaseArg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadc3b8d31ac039482bfa90b88eb4bc7f">getAlias</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Args are converted to their unaliased form. <a href="#aadc3b8d31ac039482bfa90b88eb4bc7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc085c3dfadc9cd2e1e07301b612827">setAlias</a> (std::unique_ptr&lt; Arg &gt; Alias)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29d52b9fb127c8147a41bda94dbe004c">getOwnsValues</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff387bacccd19c72cfd221be08db836">setOwnsValues</a> (bool Value) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78b7b00f492ac682e070f08e6a263d33">isClaimed</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb283e68273392bc0169fe79b4e8e134">claim</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada99fd6a3a004b686ca49375b9208d10">isIgnoredTargetSpecific</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d02fe7a5fa8fc4956680c0fc7a8c0a5">ignoreTargetSpecific</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90ae7bd6767672f9380640a5b784d04f">getNumValues</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac268590692356db84db78050196b4940">getValue</a> (unsigned N=0) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fae2e9403c3f2b91455abe787c41add">getValues</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad0ffef2b55df118bcf9d392785370b9">getValues</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17be2db4b7f70cff4544ab05ddd8c1c6">containsValue</a> (StringRef Value) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05377ec092a5d076c82dd3285317e6fa">render</a> (const ArgList &amp;Args, ArgStringList &amp;Output) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append the argument onto the given array as strings. <a href="#a05377ec092a5d076c82dd3285317e6fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a488519e74a0b6299d29bc459588a0329">renderAsInput</a> (const ArgList &amp;Args, ArgStringList &amp;Output) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append the argument, render as an input, onto the given array as strings. <a href="#a488519e74a0b6299d29bc459588a0329">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a464b1d11aaca4d524f715c9b2e15de78">print</a> (raw_ostream &amp;O) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7d9157a59af2af0d91f5173526d642a">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63bdece47c81d3a6e63de19cb824b788">getAsString</a> (const ArgList &amp;Args) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a formatted version of the argument and its values, for diagnostics. <a href="#a63bdece47c81d3a6e63de19cb824b788">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d4023dcfd9b2551216e392dfd74d91">Opt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The option this argument is an instance of. <a href="#a05d4023dcfd9b2551216e392dfd74d91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c52fe3f4b9efc6e8bb4a8be0c7e30fa">BaseArg</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The argument this argument was derived from (during tool chain argument translation), if any. <a href="#a4c52fe3f4b9efc6e8bb4a8be0c7e30fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ababcd47edc076ef94d258c9378a0540b">Spelling</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How this instance of the option was spelled. <a href="#ababcd47edc076ef94d258c9378a0540b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ef707a733ee2b7bf70d98de43a47414">Index</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The index at which this argument appears in the containing <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a>. <a href="#a0ef707a733ee2b7bf70d98de43a47414">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac54d68773d8bdd2aa7c75fe16557e5bc">Claimed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Was this argument used to affect compilation? <a href="#ac54d68773d8bdd2aa7c75fe16557e5bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af99d36910da8a7b98c9303b566b7bab4">IgnoredTargetSpecific</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used by an unclaimed option with the TargetSpecific flag. <a href="#af99d36910da8a7b98c9303b566b7bab4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6a693ce4d0419b89be2d6f5cc9a33be">OwnsValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this argument own its values? <a href="#aa6a693ce4d0419b89be2d6f5cc9a33be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdd5137666a9fe158068e421247400db">Values</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The argument values, as C strings. <a href="#abdd5137666a9fe158068e421247400db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b277289b3de52bff4c52dd684e1faf5">Alias</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this arg was created through an alias, this is the original alias arg. <a href="#a0b277289b3de52bff4c52dd684e1faf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A concrete instance of a particular driver option.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> class encodes just enough information to be able to derive the argument values efficiently.</p>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Arg() {#a5b0d66db2f3d222a19a243a3c2ede670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Arg::Arg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> Opt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Spelling, unsigned Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * BaseArg=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arg-cpp">Arg.cpp</a>.</p>


<p>Reference <a href="#a5b0d66db2f3d222a19a243a3c2ede670">Arg</a>.</p>


<p>Referenced by <a href="#a86caf310a5976603997aa99a80a1601f">Arg</a>, <a href="#a5b0d66db2f3d222a19a243a3c2ede670">Arg</a>, <a href="#a4e401accaa77741c3634023d1b2c1479">Arg</a>, <a href="#ab5e3cde2f5fe51aaf1f49835db7ede68">Arg</a>, <a href="#aadc3b8d31ac039482bfa90b88eb4bc7f">getAlias</a>, <a href="#a75cbed0ab331ea130c7ed6ca4d9b2e50">getBaseArg</a>, <a href="#a14874091f02f61eef3906ebf03701d05">getBaseArg</a>, <a href="#a62592ff96a912f9c4734124b9fcd8a19">operator=</a> and <a href="#a8f09f1a62e0c45d4a382ea58bd117933">setBaseArg</a>.</p>

</div>
</div>

### Arg() {#a4e401accaa77741c3634023d1b2c1479}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Arg::Arg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> Opt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Spelling, unsigned Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Value0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * BaseArg=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arg-cpp">Arg.cpp</a>.</p>


<p>Reference <a href="#a5b0d66db2f3d222a19a243a3c2ede670">Arg</a>.</p>

</div>
</div>

### Arg() {#ab5e3cde2f5fe51aaf1f49835db7ede68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Arg::Arg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> Opt, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Spelling, unsigned Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Value0, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Value1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * BaseArg=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arg-cpp">Arg.cpp</a>.</p>


<p>Reference <a href="#a5b0d66db2f3d222a19a243a3c2ede670">Arg</a>.</p>

</div>
</div>

### Arg() {#a86caf310a5976603997aa99a80a1601f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::opt::Arg::Arg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &amp;)</td>
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



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Reference <a href="#a5b0d66db2f3d222a19a243a3c2ede670">Arg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Arg() {#ac134760e8dc2be78ae5fc7b13d5fc05c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Arg::~Arg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arg-cpp">Arg.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a62592ff96a912f9c4734124b9fcd8a19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Arg &amp; llvm::opt::Arg::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &amp;)</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Reference <a href="#a5b0d66db2f3d222a19a243a3c2ede670">Arg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### claim() {#acb283e68273392bc0169fe79b4e8e134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::Arg::claim ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Reference <a href="#a14874091f02f61eef3906ebf03701d05">getBaseArg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a623040a06f67b95ab24c5e78e41c8bc8">llvm::opt::ArgList::AddAllArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#ab7ef568579e2fc175c4d3d68921a1a9b">llvm::opt::ArgList::AddAllArgsExcept</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a58ecc4f607c39abaf338915a04a29922">llvm::opt::ArgList::AddAllArgsTranslated</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a279c6ca725e36eff09469d98e6ee1988">llvm::opt::ArgList::AddAllArgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a974b1537dd2bfc45684a63390f5a0c8a">llvm::opt::ArgList::ClaimAllArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a2598c7f3e2c4d6571d84bbcd8fdaf4a9">llvm::opt::ArgList::ClaimAllArgs</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#aa7b3f568748cb5a0cab744337ae3eb52">llvm::opt::ArgList::getLastArg</a>.</p>

</div>
</div>

### containsValue() {#a17be2db4b7f70cff4544ab05ddd8c1c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::Arg::containsValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>

</div>
</div>

### dump() {#aa7d9157a59af2af0d91f5173526d642a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Arg::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arg-cpp">Arg.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a464b1d11aaca4d524f715c9b2e15de78">print</a>.</p>

</div>
</div>

### getAlias() {#aadc3b8d31ac039482bfa90b88eb4bc7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Arg * llvm::opt::Arg::getAlias ()</td>
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

<p>Args are converted to their unaliased form.</p>


<p>For args that originally came from an alias, this returns the alias the arg was produced from.</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Reference <a href="#a5b0d66db2f3d222a19a243a3c2ede670">Arg</a>.</p>

</div>
</div>

### getAsString() {#a63bdece47c81d3a6e63de19cb824b788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Arg::getAsString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> &amp; Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a formatted version of the argument and its values, for diagnostics.</p>


<p>Since this is for diagnostics, if this <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> was produced through an alias, this returns the string representation of the alias that the user wrote.</p>


<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arg-cpp">Arg.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#a05377ec092a5d076c82dd3285317e6fa">render</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a582e15236324209782fbeb6b5079e93a">llvm::dlltoolDriverMain</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1df6c429f484cbf4fd21a5d306f53671">llvm::libDriverMain</a>.</p>

</div>
</div>

### getBaseArg() {#a14874091f02f61eef3906ebf03701d05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Arg &amp; llvm::opt::Arg::getBaseArg ()</td>
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

<p>Return the base argument which generated this arg.</p>


<p>This is either the argument itself or the argument it was derived from during tool chain specific argument translation.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Reference <a href="#a5b0d66db2f3d222a19a243a3c2ede670">Arg</a>.</p>


<p>Referenced by <a href="#acb283e68273392bc0169fe79b4e8e134">claim</a>, <a href="#a8d02fe7a5fa8fc4956680c0fc7a8c0a5">ignoreTargetSpecific</a>, <a href="#a78b7b00f492ac682e070f08e6a263d33">isClaimed</a> and <a href="#ada99fd6a3a004b686ca49375b9208d10">isIgnoredTargetSpecific</a>.</p>

</div>
</div>

### getBaseArg() {#a75cbed0ab331ea130c7ed6ca4d9b2e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Arg &amp; llvm::opt::Arg::getBaseArg ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Reference <a href="#a5b0d66db2f3d222a19a243a3c2ede670">Arg</a>.</p>

</div>
</div>

### getIndex() {#aa4bc2ba2f9a43c63f42d58d8412c6eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::Arg::getIndex ()</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Referenced by <a href="#a05377ec092a5d076c82dd3285317e6fa">render</a>.</p>

</div>
</div>

### getNumValues() {#a90ae7bd6767672f9380640a5b784d04f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::Arg::getNumValues ()</td>
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



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Referenced by <a href="#a05377ec092a5d076c82dd3285317e6fa">render</a>.</p>

</div>
</div>

### getOption() {#a666ec80cc708a588992a87278c4e1f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Option &amp; llvm::opt::Arg::getOption ()</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#ab7ef568579e2fc175c4d3d68921a1a9b">llvm::opt::ArgList::AddAllArgsExcept</a>, <a href="#a05377ec092a5d076c82dd3285317e6fa">render</a> and <a href="#a488519e74a0b6299d29bc459588a0329">renderAsInput</a>.</p>

</div>
</div>

### getOwnsValues() {#a29d52b9fb127c8147a41bda94dbe004c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::Arg::getOwnsValues ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/option/#ad51076ec38d35888db2929e6df4c72b8">llvm::opt::Option::accept</a>.</p>

</div>
</div>

### getSpelling() {#a4e47a861c3eadf9c29201f82d126871a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::opt::Arg::getSpelling ()</td>
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

<p>Returns the used prefix and name of the option: For <span class="doxyComputerOutput">--foo=bar</span>, returns <span class="doxyComputerOutput">--foo=</span>.</p>


<p>This is often the wrong function to call:</p>


<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <span class="doxyComputerOutput"><a href="#ac268590692356db84db78050196b4940">getValue()</a></span> to get <span class="doxyComputerOutput">bar</span>.</li>
<li><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <span class="doxyComputerOutput"><a href="#a63bdece47c81d3a6e63de19cb824b788">getAsString()</a></span> to get a string suitable for printing an <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> in a diagnostic.</li>
</ul>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Referenced by <a href="#a05377ec092a5d076c82dd3285317e6fa">render</a>.</p>

</div>
</div>

### getValue() {#ac268590692356db84db78050196b4940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::opt::Arg::getValue (unsigned N=0)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a58ecc4f607c39abaf338915a04a29922">llvm::opt::ArgList::AddAllArgsTranslated</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a582e15236324209782fbeb6b5079e93a">llvm::dlltoolDriverMain</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a80f5931fdc6db3599ee4309f5a62b917">doList</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a8c99c6a7b32e47161b669182402a5c66">getSearchPaths</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1df6c429f484cbf4fd21a5d306f53671">llvm::libDriverMain</a> and <a href="#a05377ec092a5d076c82dd3285317e6fa">render</a>.</p>

</div>
</div>

### getValues() {#a5fae2e9403c3f2b91455abe787c41add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVectorImpl&lt; const char * &gt; &amp; llvm::opt::Arg::getValues ()</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/option/#ad51076ec38d35888db2929e6df4c72b8">llvm::opt::Option::accept</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a279c6ca725e36eff09469d98e6ee1988">llvm::opt::ArgList::AddAllArgValues</a>.</p>

</div>
</div>

### getValues() {#aad0ffef2b55df118bcf9d392785370b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; const char * &gt; &amp; llvm::opt::Arg::getValues ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>

</div>
</div>

### ignoreTargetSpecific() {#a8d02fe7a5fa8fc4956680c0fc7a8c0a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::Arg::ignoreTargetSpecific ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Reference <a href="#a14874091f02f61eef3906ebf03701d05">getBaseArg</a>.</p>

</div>
</div>

### isClaimed() {#a78b7b00f492ac682e070f08e6a263d33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::Arg::isClaimed ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Reference <a href="#a14874091f02f61eef3906ebf03701d05">getBaseArg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a974b1537dd2bfc45684a63390f5a0c8a">llvm::opt::ArgList::ClaimAllArgs</a>.</p>

</div>
</div>

### isIgnoredTargetSpecific() {#ada99fd6a3a004b686ca49375b9208d10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::Arg::isIgnoredTargetSpecific ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Reference <a href="#a14874091f02f61eef3906ebf03701d05">getBaseArg</a>.</p>

</div>
</div>

### print() {#a464b1d11aaca4d524f715c9b2e15de78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Arg::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arg-cpp">Arg.cpp</a>.</p>


<p>Referenced by <a href="#aa7d9157a59af2af0d91f5173526d642a">dump</a>.</p>

</div>
</div>

### render() {#a05377ec092a5d076c82dd3285317e6fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Arg::render (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> &amp; Args, <a href="/web-llvm/docs/api/namespaces/llvm/opt/#a2ceb2416aeccdb4b087e29abc8c6b52f">ArgStringList</a> &amp; Output)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append the argument onto the given array as strings.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arg-cpp">Arg.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="#aa4bc2ba2f9a43c63f42d58d8412c6eda">getIndex</a>, <a href="#a90ae7bd6767672f9380640a5b784d04f">getNumValues</a>, <a href="#a666ec80cc708a588992a87278c4e1f74">getOption</a>, <a href="#a4e47a861c3eadf9c29201f82d126871a">getSpelling</a>, <a href="#ac268590692356db84db78050196b4940">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a739567de085c6a58e82c61c620cff335a5c95bf60f491f70f205ec32efbc0782b">llvm::opt::Option::RenderCommaJoinedStyle</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a739567de085c6a58e82c61c620cff335acc1219b60acb3b04c128b71b3902f7b9">llvm::opt::Option::RenderJoinedStyle</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a739567de085c6a58e82c61c620cff335a2dd324dea833643936661a8ceccc2134">llvm::opt::Option::RenderSeparateStyle</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a739567de085c6a58e82c61c620cff335ab9ce42236f52b039069d85487491099d">llvm::opt::Option::RenderValuesStyle</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a9c2cac84e46d3e744aeca03dd3d557d1">llvm::raw_svector_ostream::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a623040a06f67b95ab24c5e78e41c8bc8">llvm::opt::ArgList::AddAllArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#ab7ef568579e2fc175c4d3d68921a1a9b">llvm::opt::ArgList::AddAllArgsExcept</a>, <a href="#a63bdece47c81d3a6e63de19cb824b788">getAsString</a> and <a href="#a488519e74a0b6299d29bc459588a0329">renderAsInput</a>.</p>

</div>
</div>

### renderAsInput() {#a488519e74a0b6299d29bc459588a0329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Arg::renderAsInput (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> &amp; Args, <a href="/web-llvm/docs/api/namespaces/llvm/opt/#a2ceb2416aeccdb4b087e29abc8c6b52f">ArgStringList</a> &amp; Output)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append the argument, render as an input, onto the given array as strings.</p>


<p>The distinction is that some options only render their values when rendered as a input (e.g., Xlinker).</p>


<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/option/arg-cpp">Arg.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="#a666ec80cc708a588992a87278c4e1f74">getOption</a> and <a href="#a05377ec092a5d076c82dd3285317e6fa">render</a>.</p>

</div>
</div>

### setAlias() {#a2bc085c3dfadc9cd2e1e07301b612827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::Arg::setAlias (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &gt; Alias)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>

</div>
</div>

### setBaseArg() {#a8f09f1a62e0c45d4a382ea58bd117933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::Arg::setBaseArg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> * BaseArg)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Reference <a href="#a5b0d66db2f3d222a19a243a3c2ede670">Arg</a>.</p>

</div>
</div>

### setOwnsValues() {#a7ff387bacccd19c72cfd221be08db836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::opt::Arg::setOwnsValues (bool Value)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/option/#ad51076ec38d35888db2929e6df4c72b8">llvm::opt::Option::accept</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Alias {#a0b277289b3de52bff4c52dd684e1faf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Arg&gt; llvm::opt::Arg::Alias</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this arg was created through an alias, this is the original alias arg.</p>


<p>For example, *this might be "-finput-charset=utf-8" and Alias might point to an arg representing "/source-charset:utf-8".</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>

</div>
</div>

### BaseArg {#a4c52fe3f4b9efc6e8bb4a8be0c7e30fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Arg* llvm::opt::Arg::BaseArg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The argument this argument was derived from (during tool chain argument translation), if any.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>

</div>
</div>

### Claimed {#ac54d68773d8bdd2aa7c75fe16557e5bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::Arg::Claimed</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Was this argument used to affect compilation?</p>


<p>This is used to generate an "argument unused" warning (without clang::driver::options::TargetSpecific) or "unsupported option" error (with TargetSpecific).</p>


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>

</div>
</div>

### IgnoredTargetSpecific {#af99d36910da8a7b98c9303b566b7bab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::Arg::IgnoredTargetSpecific</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used by an unclaimed option with the TargetSpecific flag.</p>


<p>If set, report an "argument unused" warning instead of an "unsupported option" error.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>

</div>
</div>

### Index {#a0ef707a733ee2b7bf70d98de43a47414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::Arg::Index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The index at which this argument appears in the containing <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a>.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>

</div>
</div>

### Opt {#a05d4023dcfd9b2551216e392dfd74d91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Option llvm::opt::Arg::Opt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The option this argument is an instance of.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>

</div>
</div>

### OwnsValues {#aa6a693ce4d0419b89be2d6f5cc9a33be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::Arg::OwnsValues</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Does this argument own its values?</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>

</div>
</div>

### Spelling {#ababcd47edc076ef94d258c9378a0540b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::opt::Arg::Spelling</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How this instance of the option was spelled.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>

</div>
</div>

### Values {#abdd5137666a9fe158068e421247400db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const char *, 2&gt; llvm::opt::Arg::Values</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The argument values, as C strings.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/arg-h">Arg.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/option/arg-cpp">Arg.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
