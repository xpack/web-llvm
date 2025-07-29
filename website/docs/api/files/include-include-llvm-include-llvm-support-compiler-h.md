---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/support/compiler-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `Compiler.h` File



## Included Headers

<div class="doxyIncludesList">#include "llvm/Config/llvm-config.h"
#include &lt;stddef.h&gt;
</div>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af989845e24678c452b9222afdac95e7f">__has_feature</a>(x)&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1ce1a4353334dd8968a94a98b4bf1dd">__has_extension</a>(x)&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d2d7742701f3f112afbcd8d4f9ccdb">__has_attribute</a>(x)&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a447121dcab4275b7839a56082b7a1ab8">__has_builtin</a>(x)&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac655bc80da3bd4c0e27a9ac4ac8163f9">LLVM_HAS_CPP_ATTRIBUTE</a>(x)&nbsp;&nbsp;&nbsp;0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a113552aa941976a9a34d28f3be87a732">LLVM_GNUC_PREREQ</a>(maj, min, patch)&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_GNUC_PREREQ Extend the default __GNUC_PREREQ even if glibc's features.h isn't available. <a href="#a113552aa941976a9a34d28f3be87a732">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac19e2279a0e03c0ad2a190d3e00ec15c">LLVM_MSC_PREREQ</a>(version)&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_MSC_PREREQ Is the compiler MSVC of at least the specified version? <a href="#ac19e2279a0e03c0ad2a190d3e00ec15c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8334a3b3b010ed4a1f52080ece7e81c">LLVM_ATTRIBUTE_VISIBILITY_HIDDEN</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_LIBRARY_VISIBILITY - If a class marked with this attribute is linked into a shared library, then the class should be private to the library and not accessible from outside it. <a href="#aa8334a3b3b010ed4a1f52080ece7e81c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9bda06ccdb61cb27aedb00818e5871">LLVM_ATTRIBUTE_VISIBILITY_DEFAULT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeb6f14d9f377993d79fae2efb34ecac">LLVM_EXTERNAL_VISIBILITY</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a662e21bcce5c9c71b6cc511fa04f900f">LLVM_LIBRARY_VISIBILITY</a>&nbsp;&nbsp;&nbsp;<a href="#aa8334a3b3b010ed4a1f52080ece7e81c">LLVM_ATTRIBUTE_VISIBILITY_HIDDEN</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf64debeca517afdfabfaaa9375718d4">LLVM_LIBRARY_VISIBILITY_NAMESPACE</a>&nbsp;&nbsp;&nbsp;<a href="#aa8334a3b3b010ed4a1f52080ece7e81c">LLVM_ATTRIBUTE_VISIBILITY_HIDDEN</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e33f1bd74f3e8de4d6dab912350808">LLVM_ALWAYS_EXPORT</a>&nbsp;&nbsp;&nbsp;<a href="#aec9bda06ccdb61cb27aedb00818e5871">LLVM_ATTRIBUTE_VISIBILITY_DEFAULT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdd270405f597b9e732c56397ef25888">LLVM_ABI_NOT_EXPORTED</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_ABI is the main export/visibility macro to mark something as explicitly exported when llvm is built as a shared library with everything else that is unannotated will have internal visibility. <a href="#afdd270405f597b9e732c56397ef25888">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a971b1d09709d73cab58157eaaf0637">LLVM_C_ABI</a>&nbsp;&nbsp;&nbsp;LLVM_ABI</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecc9fcaf96003481ac8c5565ca968bb9">LLVM_PREFETCH</a>(addr, rw, locality)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6881c00738b22a600dfee25a1c32dab3">LLVM_ATTRIBUTE_USED</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2166e563f0a3060d24f8b53a6d995ad6">LLVM_DEPRECATED</a>(MSG, FIX)&nbsp;&nbsp;&nbsp;[[deprecated(MSG)]]</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2177472989d8b1082a8aede8cc535cf7">LLVM_SUPPRESS_DEPRECATED_DECLARATIONS_PUSH</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42b9d7579beb5a3eead5b1c83c973602">LLVM_SUPPRESS_DEPRECATED_DECLARATIONS_POP</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37640cabda98ad892d7dc8abc13be918">LLVM_ATTRIBUTE_REINITIALIZES</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa874be876d9bf6f48931e94c251734ce">LLVM_ATTRIBUTE_WEAK</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39557b142c7bfcc54d3874aae7084907">LLVM_READNONE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2ac12f478def782d8c823536e7ebcf7">LLVM_ATTRIBUTE_MINSIZE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>(EXPR)&nbsp;&nbsp;&nbsp;(EXPR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>(EXPR)&nbsp;&nbsp;&nbsp;(EXPR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6a5e0eb6a9944baf6ba14b640eab6e1">LLVM_ATTRIBUTE_NOINLINE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_ATTRIBUTE_NOINLINE - On compilers where we have a directive to do so, mark a method "not for inlining". <a href="#ac6a5e0eb6a9944baf6ba14b640eab6e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a>&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_ATTRIBUTE_ALWAYS_INLINE - On compilers where we have a directive to do so, mark a method "always inline" because it is performance sensitive. <a href="#a338bdf98e9e600f582b7bef274bc9388">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8122a16ebef1512465fd6c3e05a831e">LLVM_ATTRIBUTE_NODEBUG</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_ATTRIBUTE_NO_DEBUG - On compilers where we have a directive to do so, mark a method "no debug" because debug info makes the debugger experience worse. <a href="#af8122a16ebef1512465fd6c3e05a831e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbae7c06e77fa64145cca176963b6863">LLVM_ATTRIBUTE_RETURNS_NONNULL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b37bec11eb1346dfa611754d0b12263">LLVM_ATTRIBUTE_RESTRICT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_ATTRIBUTE_RESTRICT - Annotates a pointer to tell the compiler that it is not aliased in the current scope. <a href="#a5b37bec11eb1346dfa611754d0b12263">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33bc304d1e6e184f3ffd9fa1620fd14c">LLVM_ATTRIBUTE_RETURNS_NOALIAS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_ATTRIBUTE_RETURNS_NOALIAS Used to mark a function as returning a pointer that does not alias any other valid pointer. <a href="#a33bc304d1e6e184f3ffd9fa1620fd14c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9579881de06b1560d242d15171ca1b86">LLVM_FALLTHROUGH</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_FALLTHROUGH - Mark fallthrough cases in switch statements. <a href="#a9579881de06b1560d242d15171ca1b86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29de8410a1056ad1b234905755dbf5da">LLVM_REQUIRE_CONSTANT_INITIALIZATION</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_REQUIRE_CONSTANT_INITIALIZATION - Apply this to globals to ensure that they are constant initialized. <a href="#a29de8410a1056ad1b234905755dbf5da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61e566d072949de225fa6912528beaf5">LLVM_GSL_OWNER</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_GSL_OWNER - Apply this to owning classes like SmallVector to enable lifetime warnings. <a href="#a61e566d072949de225fa6912528beaf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfeb6346678a2cb6295d2842b2a2805a">LLVM_GSL_POINTER</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_GSL_POINTER - Apply this to non-owning classes like StringRef to enable lifetime warnings. <a href="#acfeb6346678a2cb6295d2842b2a2805a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3d0ea99ec07497e1d0fd0cdfc18040">LLVM_LIFETIME_BOUND</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49fbbceaed01be1497ada6623f2ba42f">LLVM_CTOR_NODISCARD</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa308b4893c1ee3415893491cd9c061d1">LLVM_EXTENSION</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_EXTENSION - Support compilers where we have a keyword to suppress pedantic diagnostics. <a href="#aa308b4893c1ee3415893491cd9c061d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f50a9a032c6483fcd48e4a4f4905cc">LLVM_BUILTIN_TRAP</a>&nbsp;&nbsp;&nbsp;*(volatile int*)0x11 = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_BUILTIN_UNREACHABLE - On compilers which support it, expands to an expression which states that it is undefined behavior for the compiler to reach this point. <a href="#a20f50a9a032c6483fcd48e4a4f4905cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27f73a25903d2597cf044dbe59ddcea5">LLVM_BUILTIN_DEBUGTRAP</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_BUILTIN_DEBUGTRAP - On compilers which support it, expands to an expression which causes the program to break while running under a debugger. <a href="#a27f73a25903d2597cf044dbe59ddcea5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fd576fb00a760ba803c8a171bff051a">LLVM_ASSUME_ALIGNED</a>(p, a)&nbsp;&nbsp;&nbsp;(p)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_ASSUME_ALIGNED Returns a pointer with an assumed alignment. <a href="#a2fd576fb00a760ba803c8a171bff051a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9fc3f1d03abf0ac9ac026a546ce19be">LLVM_PACKED</a>(d)&nbsp;&nbsp;&nbsp;d __attribute__((packed))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_PACKED Used to specify a packed structure. <a href="#ad9fc3f1d03abf0ac9ac026a546ce19be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa5fcfc7c317a599182a557fbb172ca">LLVM_PACKED_START</a>&nbsp;&nbsp;&nbsp;_Pragma("pack(<a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp/#a720622fc32fd2435f7726d832d851ea6">push</a>, 1)")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade18ef060e6da6feff03adb6224a7233">LLVM_PACKED_END</a>&nbsp;&nbsp;&nbsp;_Pragma("pack(pop)")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab82d05e7fec3f6ecc5284dad0a929703">LLVM_MEMORY_SANITIZER_BUILD</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_MEMORY_SANITIZER_BUILD Whether LLVM itself is built with MemorySanitizer instrumentation. <a href="#ab82d05e7fec3f6ecc5284dad0a929703">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9e2781b72fd814787440ca2c3c0d6f0">__msan_allocated_memory</a>(p, size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b6ebda5fec619759c0522722503be67">__msan_unpoison</a>(p, size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c79436804022a1275836a6dd12946d1">LLVM_NO_SANITIZE_MEMORY_ATTRIBUTE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a697f9c28dc5a706b9e4d3fed6df67857">LLVM_ADDRESS_SANITIZER_BUILD</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_ADDRESS_SANITIZER_BUILD Whether LLVM itself is built with AddressSanitizer instrumentation. <a href="#a697f9c28dc5a706b9e4d3fed6df67857">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72741af87fe3babd5bb46653c26eff2a">__asan_poison_memory_region</a>(p, size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a820fe7b3006fe7b31f19b0258993606a">__asan_unpoison_memory_region</a>(p, size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadd18c23b9ca88ab897fbcdf1c0e14a9">LLVM_HWADDRESS_SANITIZER_BUILD</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_HWADDRESS_SANITIZER_BUILD Whether LLVM itself is built with HWAddressSanitizer instrumentation. <a href="#aadd18c23b9ca88ab897fbcdf1c0e14a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b3e49c523b219bee6271deca48ccab">LLVM_THREAD_SANITIZER_BUILD</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_THREAD_SANITIZER_BUILD Whether LLVM itself is built with ThreadSanitizer instrumentation. <a href="#ab6b3e49c523b219bee6271deca48ccab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a186eadfc2c525b71adaf35e7487eccac">TsanHappensBefore</a>(cv)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a8a06812caf14bdec3b541b578b8344">TsanHappensAfter</a>(cv)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7ae7168870d6f719670bf0f47b9ade5">TsanIgnoreWritesBegin</a>()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d95fe36240cded45e8889c2491a78f5">TsanIgnoreWritesEnd</a>()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d65fbde0458a34315c42b80acad72a1">LLVM_NO_SANITIZE</a>(KIND)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_NO_SANITIZE Disable a particular sanitizer for a function. <a href="#a6d65fbde0458a34315c42b80acad72a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>&nbsp;&nbsp;&nbsp;<a href="#ac6a5e0eb6a9944baf6ba14b640eab6e1">LLVM_ATTRIBUTE_NOINLINE</a> <a href="#a6881c00738b22a600dfee25a1c32dab3">LLVM_ATTRIBUTE_USED</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark debug helper function definitions like dump() that should not be stripped from debug builds. <a href="#aa863693eef567397d9c292da5bf22d34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add3e64f9d3d35dff1307ced174a44b29">LLVM_PRETTY_FUNCTION</a>&nbsp;&nbsp;&nbsp;__func__</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_PRETTY_FUNCTION Gets a user-friendly looking function signature for the current scope using the best available method on each platform. <a href="#add3e64f9d3d35dff1307ced174a44b29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a793005af6ae802d5a2a2e8ceb4ac2135">LLVM_THREAD_LOCAL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_THREAD_LOCAL A thread-local storage specifier which can be used with globals, extern globals, and static globals. <a href="#a793005af6ae802d5a2a2e8ceb4ac2135">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c4f366dadc2ca8d0860f0e1fc40863">LLVM_NO_PROFILE_INSTRUMENT_FUNCTION</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_ENABLE_EXCEPTIONS Whether LLVM is built with exception support. <a href="#a14c4f366dadc2ca8d0860f0e1fc40863">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2328e1eac1d32bc55a61db8c725eac79">LLVM_PREFERRED_TYPE</a>(T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\macro LLVM_PREFERRED_TYPE Adjust type of bit-field in debug info. <a href="#a2328e1eac1d32bc55a61db8c725eac79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Macro Definitions

### \_\_asan\_poison\_memory\_region {#a72741af87fe3babd5bb46653c26eff2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __asan_poison_memory_region(p, size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#aef3aaf3bf7c0ec3ad8ad4941b14bb846">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::AllocateSlow</a>, <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#aa306ee4f02f1a5e8022576b65a7398af">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::Deallocate</a> and <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#a977c94ac0ef5e305e5cf40726351d88a">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::Reset</a>.</p>

</div>
</div>

### \_\_asan\_unpoison\_memory\_region {#a820fe7b3006fe7b31f19b0258993606a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __asan_unpoison_memory_region(p, size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#a4054c3eefe873caf49c2290808d409ac">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::Allocate</a>, <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#aef3aaf3bf7c0ec3ad8ad4941b14bb846">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::AllocateSlow</a> and <a href="/web-llvm/docs/api/classes/llvm/json/value/#a0720b5f434e636e22a3ed34f847eec57">llvm::json::Value::Object</a>.</p>

</div>
</div>

### \_\_has\_attribute {#a54d2d7742701f3f112afbcd8d4f9ccdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __has_attribute(x)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### \_\_has\_builtin {#a447121dcab4275b7839a56082b7a1ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __has_builtin(x)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### \_\_has\_extension {#ae1ce1a4353334dd8968a94a98b4bf1dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __has_extension(x)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### \_\_has\_feature {#af989845e24678c452b9222afdac95e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __has_feature(x)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### \_\_msan\_allocated\_memory {#ad9e2781b72fd814787440ca2c3c0d6f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __msan_allocated_memory(p, size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#a4054c3eefe873caf49c2290808d409ac">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::Allocate</a> and <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#aef3aaf3bf7c0ec3ad8ad4941b14bb846">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::AllocateSlow</a>.</p>

</div>
</div>

### \_\_msan\_unpoison {#a7b6ebda5fec619759c0522722503be67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define __msan_unpoison(p, size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/lib/support/blake3/blake3-c/#a6f1551c11ac8a08c294ee4bf7bf08623">llvm_blake3_hasher_finalize</a>.</p>

</div>
</div>

### LLVM\_ABI\_NOT\_EXPORTED {#afdd270405f597b9e732c56397ef25888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ABI_NOT_EXPORTED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_ABI is the main export/visibility macro to mark something as explicitly exported when llvm is built as a shared library with everything else that is unannotated will have internal visibility.</p>


<p>LLVM_ABI_EXPORT is for the special case for things like plugin symbol declarations or definitions where we don't want the macro to be switching between dllexport and dllimport on windows based on what codebase is being built, it will only be dllexport. For non windows platforms this macro behaves the same as LLVM_ABI.</p>


<p>LLVM_EXPORT_TEMPLATE is used on explicit template instantiations in source files that were declared extern in a header. This macro is only set as a compiler export attribute on windows, on other platforms it does nothing.</p>


<p>LLVM_TEMPLATE_ABI is for annotating extern template declarations in headers for both functions and classes. On windows its turned in to dllimport for library consumers, for other platforms its a default visibility attribute.</p>


<p>LLVM_C_ABI is used to annotated functions and data that need to be exported for the libllvm-c API. This used both for the llvm-c headers and for the functions declared in the different Target's c++ source files that don't include the header forward declaring them.</p>


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_ADDRESS\_SANITIZER\_BUILD {#a697f9c28dc5a706b9e4d3fed6df67857}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ADDRESS_SANITIZER_BUILD&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_ADDRESS_SANITIZER_BUILD Whether LLVM itself is built with AddressSanitizer instrumentation.</p>

<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_ALWAYS\_EXPORT {#af6e33f1bd74f3e8de4d6dab912350808}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ALWAYS_EXPORT&nbsp;&nbsp;&nbsp;<a href="#aec9bda06ccdb61cb27aedb00818e5871">LLVM_ATTRIBUTE_VISIBILITY_DEFAULT</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_ASSUME\_ALIGNED {#a2fd576fb00a760ba803c8a171bff051a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ASSUME_ALIGNED(p, a)&nbsp;&nbsp;&nbsp;(p)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_ASSUME_ALIGNED Returns a pointer with an assumed alignment.</p>

<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#acfdf941f45bc58470ed8423b98862486">llvm::support::endian::read</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a6d9995bf8da2a0fed6fa31bce97aeebd">llvm::support::endian::readAtBitAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a60b7cc9c00de00b23725cfa29e75ca3f">llvm::support::endian::writeAtBitAlignment</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_ALWAYS\_INLINE {#a338bdf98e9e600f582b7bef274bc9388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_ALWAYS_INLINE&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/alwaysinliner-cpp/#a46ccdc20c42bb5ae5b9d313e12a68421">inline</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_ATTRIBUTE_ALWAYS_INLINE - On compilers where we have a directive to do so, mark a method "always inline" because it is performance sensitive.</p>

<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a11c9966e70bbdd08c33da7c25056b0a3">llvm::DynamicAPInt::abs</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a0a6400043bb608ee08534246b6c7b0da">llvm::DynamicAPInt::ceilDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a14c617a274bb807748be86583cf743f4">CheckChildSame</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#aa34708a5452c563dc4e8e3630abf6c24">CheckType</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#ad772de3fed881a64ad7437da1599cf19">llvm::User::ConstantAggrKeyType</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a248361854adffb10ee11d3bea700310a">llvm::DynamicAPInt::DynamicAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a536afeb2c8a330ff2939560cf6f3ad81">llvm::DynamicAPInt::DynamicAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#ad4fe06c2c9fd19be7fe3e0064a08aa0f">llvm::DynamicAPInt::DynamicAPInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad434afe02efcc41347292db5c3561fb6">llvm::dynamicAPIntFromInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#ac6b039b5f68780df0184722571fe10dd">llvm::DynamicAPInt::floorDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a14d5f0348a5c7f46257fe67f95d1ab31">llvm::DynamicAPInt::gcd</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a1722f9ac2a1051a745376462eb47cb90">llvm::DynamicAPInt::lcm</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#aa8c9248faa6cc07fdc7c001259726dfc">llvm::DynamicAPInt::mod</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a01ff692fd432546ac6237603e359228b">llvm::DynamicAPInt::operator int64_t</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a0b67a4ee3011c77673baf0aa3ccf1b3c">llvm::DynamicAPInt::operator!=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a7fed75ef05b8e1ad72c1d3568e49561b">llvm::DynamicAPInt::operator!=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a2b4529a374410a1c305dbfaaf07d46a3">llvm::DynamicAPInt::operator%</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a9b6ecf37fe8a25d2caacce32cdbdaaf9">llvm::DynamicAPInt::operator%</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a04c38b9b707b05708285226e3bd1458b">llvm::DynamicAPInt::operator%=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#acb1a5a0e5f41793652d47ca73fb4e2b8">llvm::DynamicAPInt::operator*</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#aa655e9e69d1e29eea4e2f5365b2a1df5">llvm::DynamicAPInt::operator*</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a2937f8b000580e7f1bb54295da4d5d2f">llvm::DynamicAPInt::operator*=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a1ca441fbd8ce64d9fcc7aca612e4ca98">llvm::DynamicAPInt::operator+</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#af6494bd431607f8b6af90e74aac583a5">llvm::DynamicAPInt::operator+</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a8fa61b94343da02ff6081ff0ecf0361e">llvm::DynamicAPInt::operator++</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a204c2fad631146d3c34735277485ac55">llvm::DynamicAPInt::operator+=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a5bb6e6ad85226f2ff9434fe21184c5d2">llvm::DynamicAPInt::operator-</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a6737d677ac415389bd492d03386ab245">llvm::DynamicAPInt::operator-</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a9d4ccb55f7f9737a9d71bb4b818c9f16">llvm::DynamicAPInt::operator-</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a0e00c0c9f29e000969b2d2764e7bdd3a">llvm::DynamicAPInt::operator--</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#acb28624077094d0d6c47ffeb93c8f6bc">llvm::DynamicAPInt::operator-=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a24b77007c64222893b7e43da37435e2a">llvm::DynamicAPInt::operator/</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#ac481c08815381d98544bca21e2810f8d">llvm::DynamicAPInt::operator/</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a5a5161bd7a6f4f091ee8b92c7fde2a3e">llvm::DynamicAPInt::operator/=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a39b90547bf41b51e82ee0a91fea74cb5">llvm::DynamicAPInt::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a5e7939805b51f889f1d60791a59674d7">llvm::DynamicAPInt::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a88d574416e6f5fa68359b393010e445b">llvm::DynamicAPInt::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a95a996596cc929e06b3ed709db0e1e0f">llvm::DynamicAPInt::operator&lt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a5729ad037b3ba98d9b85c85382501c11">llvm::DynamicAPInt::operator&lt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a67656071decb86462eac4efed3f0b32f">llvm::DynamicAPInt::operator&lt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/typeswitchbase/#a03cd5accdd5ca9bb1fa9c9baacfd5c8d">llvm::detail::TypeSwitchBase&lt; TypeSwitch&lt; T, ResultT &gt;, T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a0e7f861f4373c4342541558e23b13fab">llvm::DynamicAPInt::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a3597823a833fb7ff71cbda0031081da4">llvm::DynamicAPInt::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#aaa5416545d0c01bba62521af0ac2db15">llvm::DynamicAPInt::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a63ee1995b96d5df1513414ade216a523">llvm::DynamicAPInt::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a09ad8d89e87e7bd9f96f9ca9897038b4">llvm::DynamicAPInt::operator&gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#ab23348cc755bc499077a86953e0950fb">llvm::DynamicAPInt::operator&gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a068916b0b7ffee36b56568f6c865a16c">llvm::DynamicAPInt::operator&gt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#aeae61c9fb3c4e0f412763a154847f079">llvm::DynamicAPInt::operator&gt;=</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#aace3bad147eeed78a2f1cab33d506d59">XXH_xorshift64</a> and <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#ab089d7ab5b50a298e0045f386fedeef2">llvm::DynamicAPInt::~DynamicAPInt</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_MINSIZE {#ac2ac12f478def782d8c823536e7ebcf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_MINSIZE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_NODEBUG {#af8122a16ebef1512465fd6c3e05a831e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_NODEBUG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_ATTRIBUTE_NO_DEBUG - On compilers where we have a directive to do so, mark a method "no debug" because debug info makes the debugger experience worse.</p>

<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/detail/typeswitchbase/#a03cd5accdd5ca9bb1fa9c9baacfd5c8d">llvm::detail::TypeSwitchBase&lt; TypeSwitch&lt; T, ResultT &gt;, T &gt;::operator=</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_NOINLINE {#ac6a5e0eb6a9944baf6ba14b640eab6e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_NOINLINE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_ATTRIBUTE_NOINLINE - On compilers where we have a directive to do so, mark a method "not for inlining".</p>

<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/executionengine/gdbregistrationlistener-cpp/#acfc836ae108641ea6231b8d9def3a15a">__jit_debug_register_code</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_REINITIALIZES {#a37640cabda98ad892d7dc8abc13be918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_REINITIALIZES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_RESTRICT {#a5b37bec11eb1346dfa611754d0b12263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_RESTRICT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_ATTRIBUTE_RESTRICT - Annotates a pointer to tell the compiler that it is not aliased in the current scope.</p>

<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#aa284de70c1521913d9eda75728495b36">llvm::GIMatchTableExecutor::fastDecodeULEB128</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_RETURNS\_NOALIAS {#a33bc304d1e6e184f3ffd9fa1620fd14c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_RETURNS_NOALIAS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_ATTRIBUTE_RETURNS_NOALIAS Used to mark a function as returning a pointer that does not alias any other valid pointer.</p>

<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_RETURNS\_NONNULL {#acbae7c06e77fa64145cca176963b6863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_RETURNS_NONNULL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#a4054c3eefe873caf49c2290808d409ac">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::Allocate</a>, <a href="/web-llvm/docs/api/classes/llvm/mallocallocator/#a46b47c18f94aa81e5205a7c67ff7daea">llvm::MallocAllocator::Allocate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a53b2f25342c49b78f06fbec9cf7fe644">llvm::safe_calloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bb931812d78f470d4ca775ac8b88e61">llvm::safe_malloc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9edff61a0e003a8bb37f5a12a8755cf2">llvm::safe_realloc</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_UNUSED {#acc1c483f4b4ee2f17bb6643a3b353609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_UNUSED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#ad36fda9d8203a5374fcb76941423c400">assertBranchOrSelectConditionHoisted</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsfastisel-cpp/#abd5d01248028e2337390fdfb4cf9bca4">CC_Mips</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a02c33f9f522dab86d5a73697ad57f443">CC_MipsO32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#ae64b1825b82ce592840287c8ebad2d2a">checkFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a499b9606a8f1365f4515e3cce4f14474">clearFeature</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a71749cadcb51437084eb14c3f3bfea8a">llvm::TargetLibraryInfo::disableAllFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp/#a0e25fc51f7806df57464873f1323c074">dumpDataAux</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a8acf25125313b0e6333bb7fa3f4404f6">dumpIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a388b3ce412f145bfac051690e8ef5596">llvm::getPGOFuncName</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/host-cpp/#a03ee6e57339003249d55cef525fc8684">getProcCpuinfoContent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#afb3752484346ea3866ff08c9b0cda41e">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a71e4e4db6c5f66881aeb1f7b981b5527">isBlendOrUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af30484061fcf2186114d7d176ae1dd90">isHorizOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a4e10ba09dea9d13b485ec2a68efb4f98">llvm::sys::unicode::nearestMatchesForCodepointName</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/slice/#a0a8bc89992786ef1cb98be7e518e6849">anonymous{SROA.cpp}::Slice::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/slice/#a086fd953b23c8ea0df25ad9ae20670ea">anonymous{SROA.cpp}::Slice::operator&lt;</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86floatingpoint-cpp-/tableentry/#a5bf5fa8c59a681ba714bf8c7023fcfc3">anonymous{X86FloatingPoint.cpp}::TableEntry::operator&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a1f8ac6e7a5b51acc2226820842e95107">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecopypropagation-cpp/#a0a8095dd7438cc22543bb5d42d0c1a71">printSpillReloadChain</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ae927868d9b86954520b923345a3d4762">llvm::LiveIntervals::pruneValue</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a858bc32432a78550f43728ac033fa4ae">llvm::TargetLibraryInfo::setUnavailable</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcframelowering-cpp/#a549f5d9335a5b083364fced7b5a5aebd">verifyLeafProcRegUse</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_USED {#a6881c00738b22a600dfee25a1c32dab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_USED</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae18b975c4cfc01423dfda64a7e2c8416">llvm::BuryPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a96e77630e47eef7894026292125e58dd">llvm::orc::linkComponents</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp/#a99bcf6310a14dca264a71b7863cf1e81">printMarkupContext</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-gdbregistrationlistener-cpp-/#aed8b12338da2e3c7fb1d304c36637450">anonymous{GDBRegistrationListener.cpp}::requiredSymbolDefinitionsFromOrcTargetProcess</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_VISIBILITY\_DEFAULT {#aec9bda06ccdb61cb27aedb00818e5871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_VISIBILITY_DEFAULT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_VISIBILITY\_HIDDEN {#aa8334a3b3b010ed4a1f52080ece7e81c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_VISIBILITY_HIDDEN</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_LIBRARY_VISIBILITY - If a class marked with this attribute is linked into a shared library, then the class should be private to the library and not accessible from outside it.</p>


<p>Can also be used to mark variables and functions, making them private to any shared library they are linked into. On PE/COFF targets, library visibility is the default, so this isn't needed.</p>


<p>LLVM_EXTERNAL_VISIBILITY - classes, functions, and variables marked with this attribute will be made public and visible outside of any shared library they are linked in to.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_ATTRIBUTE\_WEAK {#aa874be876d9bf6f48931e94c251734ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_ATTRIBUTE_WEAK</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_BUILTIN\_DEBUGTRAP {#a27f73a25903d2597cf044dbe59ddcea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_BUILTIN_DEBUGTRAP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_BUILTIN_DEBUGTRAP - On compilers which support it, expands to an expression which causes the program to break while running under a debugger.</p>

<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#a7d21bcbf03ef9764e4363ae385d99579">llvm::DebugCounter::shouldExecuteImpl</a>.</p>

</div>
</div>

### LLVM\_BUILTIN\_TRAP {#a20f50a9a032c6483fcd48e4a4f4905cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_BUILTIN_TRAP&nbsp;&nbsp;&nbsp;*(volatile int*)0x11 = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_BUILTIN_UNREACHABLE - On compilers which support it, expands to an expression which states that it is undefined behavior for the compiler to reach this point.</p>


<p>Otherwise is not defined.</p>


<p>'<a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a>' is intentionally left out so that other macro logic (e.g., LLVM_ASSUME_ALIGNED and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable()</a>) can detect whether LLVM_BUILTIN_UNREACHABLE has a definition. LLVM_BUILTIN_TRAP - On compilers which support it, expands to an expression which causes the program to exit abnormally.</p>


<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_C\_ABI {#a9a971b1d09709d73cab58157eaaf0637}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_C_ABI&nbsp;&nbsp;&nbsp;LLVM_ABI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp/#a4110565bfc3430fd4385fb1a57f05280">LLVMInitializeX86AsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#a1d8e064b1294683693f11f2e3899b562">LLVMInitializeX86AsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ad94a7ec0e2ddf818814c86ab2eca39f0">LLVMInitializeX86Disassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86targetmachine-cpp/#aa63db78a8378c10074d19a12e66ad98f">LLVMInitializeX86Target</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/targetinfo/x86targetinfo-cpp/#ae559004b4b9beeb943f2621ca8b53c5a">LLVMInitializeX86TargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86mctargetdesc-cpp/#ab1904658c919a9d143695cabebd68f53">LLVMInitializeX86TargetMC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mca/x86custombehaviour-cpp/#ad605a3a85d38e52ce2def870b0d02113">LLVMInitializeX86TargetMCA</a>.</p>

</div>
</div>

### LLVM\_CTOR\_NODISCARD {#a49fbbceaed01be1497ada6623f2ba42f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_CTOR_NODISCARD</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a49d88ad31bfdaa61d47dd7720c083823">llvm::WithColor::WithColor</a>.</p>

</div>
</div>

### LLVM\_DEPRECATED {#a2166e563f0a3060d24f8b53a6d995ad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_DEPRECATED(MSG, FIX)&nbsp;&nbsp;&nbsp;[[deprecated(MSG)]]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_DUMP\_METHOD {#aa863693eef567397d9c292da5bf22d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_DUMP_METHOD&nbsp;&nbsp;&nbsp;<a href="#ac6a5e0eb6a9944baf6ba14b640eab6e1">LLVM_ATTRIBUTE_NOINLINE</a> <a href="#a6881c00738b22a600dfee25a1c32dab3">LLVM_ATTRIBUTE_USED</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark debug helper function definitions like dump() that should not be stripped from debug builds.</p>


<p>Note that you should also surround dump() functions with <span class="doxyComputerOutput">#if !defined(NDEBUG) || defined(LLVM_ENABLE_DUMP)</span> so they do always get stripped in release builds.</p>


<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-codegenprepare-cpp-/extaddrmode/#af97ad85fa4c9caf49c807470d137a67d">anonymous{CodeGenPrepare.cpp}::ExtAddrMode::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonconstextenders-cpp-/rangetree/#a1c11a734df77bcfc56f1b9cb4bee627d">anonymous{HexagonConstExtenders.cpp}::RangeTree::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/inlinecostcallanalyzer/#aabcb13bec5e6f9ba8dc996af8a10cc10">anonymous{InlineCost.cpp}::InlineCostCallAnalyzer::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopfuse-cpp-/fusioncandidate/#a4392517c22c653d59c5deead6ccfffb7">anonymous{LoopFuse.cpp}::FusionCandidate::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/cost/#ab9ff5264fbc3faf5b26768f683a43e59">anonymous{LoopStrengthReduce.cpp}::Cost::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula/#a376acc2ec7fd1a216d5ec9fb9f04c99a">anonymous{LoopStrengthReduce.cpp}::Formula::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/lsrfixup/#a17103d1dadfcbedb1b4455345d844dc1">anonymous{LoopStrengthReduce.cpp}::LSRFixup::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsrinstance/#a890ca19e74514f1ec5cbb3e5cdd8d50b">anonymous{LoopStrengthReduce.cpp}::LSRInstance::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse/#af5eebe76701b28ce106d5ffd86fbcc27">anonymous{LoopStrengthReduce.cpp}::LSRUse::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regsortdata/#a8efa96a6fa3836082f6d19af59855749">anonymous{LoopStrengthReduce.cpp}::RegSortData::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/workitem/#a9ee84141fefcb511385561d5d59523ce">anonymous{LoopStrengthReduce.cpp}::WorkItem::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain/#aa8b7b149176869053e12294206134631">anonymous{MachineBlockPlacement.cpp}::BlockChain::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-msp430iseldagtodag-cpp-/msp430iseladdressmode/#a3170eebe744548a2d75fd1955a826421">anonymous{MSP430ISelDAGToDAG.cpp}::MSP430ISelAddressMode::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcreducecrlogicals-cpp-/ppcreducecrlogicals/crlogicalopinfo/#a10f674b27aeeeeb1496b482c01035aec">anonymous{PPCReduceCRLogicals.cpp}::PPCReduceCRLogicals::CRLogicalOpInfo::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvinsertvsetvli-cpp-/demandedfields/#a423c378f7cfc3637d0a97b19ef757fac">anonymous{RISCVInsertVSETVLI.cpp}::DemandedFields::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertvsetvli-cpp-/vsetvliinfo/#a238a21f94d9186543c9d7656c55837fb">anonymous{RISCVInsertVSETVLI.cpp}::VSETVLIInfo::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinsertwritevxrm-cpp-/vxrminfo/#a1927229203dc3a9d85b07d75ac99e3d4">anonymous{RISCVInsertWriteVXRM.cpp}::VXRMInfo::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpriorityqueue/#ac71475df20b58e4c313134e73ed1ddad">anonymous{ScheduleDAGRRList.cpp}::RegReductionPriorityQueue&lt; bu_ls_rr_sort &gt;::dump</a>, <a href="/web-llvm/docs/api/structs/anonymous-wasmobjectwriter-cpp-/wasmrelocationentry/#aaf06e15f842e20ddb2a9bde2df06ec7b">anonymous{WasmObjectWriter.cpp}::WasmRelocationEntry::dump</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86domainreassignment-cpp-/closure/#aab27e1fc3d28d4c1a429ca75475740ad">anonymous{X86DomainReassignment.cpp}::Closure::dump</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#ad60ba0b6dcb54a7fe37863ceb0165626">LiveDebugValues::MLocTracker::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasset/#af940c8979b258033f9a1fbd65f6c073a">llvm::AliasSet::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#a1fddd270f1f51237933f224d12b1d26e">llvm::AliasSetTracker::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitproposal/#a843229cfda9f61491b29bbf045507f4d">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitProposal::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/apfixedpoint/#a730a632147603ed96aef4cd6f0e92bf7">llvm::APFixedPoint::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ad4e64a2bbbacfa304679cbdd5db87098">llvm::APFloat::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aa248cd211bcff0f457bf69b596805302">llvm::APInt::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/#abdb9058a51e2fb5fd61d203dcdfd551a">llvm::AppleAcceleratorTable::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/armconstantpoolvalue/#a72e996e33d02377f36d099211fedf9bc">llvm::ARMConstantPoolValue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ae88787fab8a5d948bd5100aded6fc799">llvm::AttributeList::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelistimpl/#ac43eb5815cf8c827bfd5ab7bc71b5283">llvm::AttributeListImpl::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#af6ce36dbf14e9ac50946fb22b1c2bca2">llvm::AttributeSet::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/baseindexoffset/#ac35bc2b25cf6caba17a6b9d662b52db8">llvm::BaseIndexOffset::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/bfi-detail/blockmass/#a5ae944f41ccf807abef975067d634884">llvm::bfi_detail::BlockMass::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a00519c57242e5e3b84f82ffc21c7f75a">llvm::BranchProbability::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraph/#a3d20c4438dad4a93f2720a8866bf10d5">llvm::CallGraph::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphnode/#a6ea4c567ae49efda9dabf4830750d17b">llvm::CallGraphNode::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/cfg/update/#afafd1a3ab4b7dce339a76892868b8785">llvm::cfg::Update&lt; BasicBlock * &gt;::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/coalescingbitvector/#a1ef27b047890f6afa1034c410fbbba1e">llvm::CoalescingBitVector&lt; uint64_t &gt;::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/constantfprange/#abcf29fcc870f2cd3f5a5d8242ffc4d92">llvm::ConstantFPRange::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a59e43abf85f6911f09023f40cf86cc5f">llvm::ConstantRange::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a0a56493540d0bd657d461e920a29de55">llvm::ConstantRangeList::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvaluehistorymap/#aaaf208f55ecf4cf0c79d9f83a75c252f">llvm::DbgValueHistoryMap::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvalueloc/#addc819493f2e2bc5c100108859f0cf14">llvm::DbgValueLoc::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvaluelocentry/#ab45f19cc70d2f6377ac00b95472d762f">llvm::DbgValueLocEntry::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#ad8cb43b6edd4b61f20a6f3264c3cc562">llvm::DebugCounter::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#abf018edd9aec8ba5434e17d10f64d8cd">llvm::DebugLoc::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/die/#aeec7f1000c747324d45318321277b7b9">llvm::DIE::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#ae911475e78a1957ad4867866deeb4f01">llvm::DIEAbbrev::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dievalue/#aa3bd6bfc484bfa0120b0de652f55e7e9">llvm::DIEValue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dominancefrontierwrapperpass/#a4832c997e70c65c6e5205a398a11096a">llvm::DominanceFrontierWrapperPass::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/dieinfo/#a6bc3abd441871fd4bd6affec72c71249">llvm::dwarf_linker::classic::CompileUnit::DIEInfo::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/compileunit/dieinfo/#a0bb4b5ce7e0731e88c8a45d8de5db37b">llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/#af509255633e1bbe144cba3330e5d945c">llvm::DWARFDebugNames::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex/#a6a576c0df9fdee3ab02b174cba3cc169">llvm::DWARFDebugNames::NameIndex::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a61d3b80309ad8e1497b9decb9b16c9f5">llvm::DWARFDie::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/computedshaderflags/#abfff82082acb57ce81a08b1df06f4031">llvm::dxil::ComputedShaderFlags::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/elfrelocationentry/#af31f5f1bfb380669b7fbac97e2df7d35">llvm::ELFRelocationEntry::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/foreachloop/#a69aac7774c444f12ffae0a9608aa38e1">llvm::ForeachLoop::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovblock/#ae73f8602b05283cb0e32b9af14ffeaac">llvm::GCOVBlock::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfile/#a89e385955903f2df447919378b7144ea">llvm::GCOVFile::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a287ea9a8032be9c72e6334b75c8c2d3e">llvm::GCOVFunction::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#aefa1d7d67dd758fb993876e62c56890d">llvm::GenericDomTreeUpdater&lt; DomTreeUpdater, DominatorTree, PostDominatorTree &gt;::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/graphdiff/#a723aaccc31c607efcd14feb83f42b28e">llvm::GraphDiff&lt; MachineBasicBlock *, false &gt;::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/expression/#a9877ce60232c11ec7ef6030cf99a9655">llvm::GVNExpression::Expression::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/ilpvalue/#a2d4e7eb6e7c6d7dad1e3906d0e72cba7">llvm::ILPValue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/init/#a29593b415ed8217aafed21bab813cb1e">llvm::Init::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/ivusers/#a04b694028e4949a1f3be58fa2c561756">llvm::IVUsers::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/latencypriorityqueue/#a58764f7a88212dcec140c041126b719d">llvm::LatencyPriorityQueue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope/#aa6c3d87456bbee468f6fd51bf8163dfe">llvm::LexicalScope::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/#a224ae5ef2d871d35fcabace424654c2d">llvm::LiveDebugVariables::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a2648a95467638981fc1d97770747854b">llvm::LiveInterval::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/subrange/#ae2f024f7eb0684ed7951d19050ceaa1d">llvm::LiveInterval::SubRange::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ae5b2788f458f4763a2fa43457af4f597">llvm::LiveIntervals::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/livephysregs/#af68fa50d948afb8a15aaa9f2bea1f1d0">llvm::LivePhysRegs::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#aee80ffb31cdad64c9ef4dbd42e794b68">llvm::LiveRange::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/liverange/segment/#acaefba2d8bca4f1f27e3ec5d2efe8c4f">llvm::LiveRange::Segment::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeupdater/#a99dba5518021b799c8eb62367b225919">llvm::LiveRangeUpdater::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/livevariables/varinfo/#a578f01f3e0679351d97facbba44c583e">llvm::LiveVariables::VarInfo::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#adbe2b50c065f9de917bf34a1d573253b">llvm::LLT::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a61a487a3724136e3332c86f2f26189ce">llvm::Loop::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a8cec41e65c7ebf7da3e9d41f2317065e">llvm::MachineBasicBlock::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpool/#a17e78963698b00ac5f8adeb6c942d4a6">llvm::MachineConstantPool::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#ac42b489f21274bae5d397b8ae8ddd0cf">llvm::MachineFrameInfo::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3d931af4280c80a837ee409eb85104f7">llvm::MachineFunction::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#accc60d2019e9dff57bb0918a94422ebb">llvm::MachineInstr::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machinejumptableinfo/#a723eff4a497357d7c8602abd695daa11">llvm::MachineJumpTableInfo::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machineloop/#a8540c69f528369eb693bb2fafc1d7030">llvm::MachineLoop::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a71453c9c9ea541dab5841a0b590d56ee">llvm::MachineOperand::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregioninfopass/#a7d5fb681435942ddcd1efd2566404979">llvm::MachineRegionInfoPass::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/symbol/#a47fe98cf137102b99ab4844c2860af47">llvm::MachO::Symbol::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a3a68266def3072d13b2cafb555b9e28c">llvm::MCAssembler::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#ae9178f3e2cad3ab5a9b9cb621deac70a">llvm::MCExpr::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a73af1340aaefb3f64c1e4000ce6254e4">llvm::MCFragment::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ab8aa6b74c6bb82576347afb756807f20">llvm::MCInst::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mclabel/#a6410f21b8256de3b5f0a86ec4d38940f">llvm::MCLabel::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#aade61d67dc303176b7a668f9b5be13bd">llvm::MCOperand::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a139e160072c0a4f8626e4ffaf4aa2af7">llvm::MCSection::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#aca2ff5e9eadc78b9ea7a216595933f86">llvm::MCSymbol::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcvalue/#ac16bc08d78240466f90fbc5641efdcec">llvm::MCValue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a0211e050a705084ef5e653127a7fb3df">llvm::MemorySSA::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/multiclass/#a6746700ec43485290f48385954b7a588">llvm::MultiClass::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/nodeset/#acdacc30450012997ebfeb3c681460349">llvm::NodeSet::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsymbol/#a3412ba697c4c2976a8b1fca317eea863">llvm::object::WasmSymbol::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#aa7d9157a59af2af0d91f5173526d642a">llvm::opt::Arg::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#ab5735777324ec9864032e2673b01d58c">llvm::opt::ArgList::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/option/#a07df67e096ac6736534eeb740165d530">llvm::opt::Option::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/pbqpragraph/#a78abfb6b34e68b227c9e5c7704052df2">llvm::PBQP::RegAlloc::PBQPRAGraph::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pbqp/regalloc/pbqpragraph/#a3d4298b31bb96541c38a77aeaa34b842">llvm::PBQP::RegAlloc::PBQPRAGraph::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/phitransaddr/#a3d08402d35c5bb6cc0faf2b0e4bacb6c">llvm::PHITransAddr::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pmstack/#a5d2231cd95fe50f516610c506f57cbc6">llvm::PMStack::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/readyqueue/#a61a4a769784e3da32d297c2752646aee">llvm::ReadyQueue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a47077193efcfcbedd136c518339d8cc9">llvm::Record::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/recordkeeper/#a6d362951ba608459d8511289972ee583">llvm::RecordKeeper::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/recordsentry/#a8b468e7c34a791c89904af7cc6325c2c">llvm::RecordsEntry::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/recordval/#a50159f8fcf75668979bf2b9e037f1560">llvm::RecordVal::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/recty/#ac08f7b9bc62aa901700eef03da46e0e2">llvm::RecTy::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/mappingcost/#a7560fb1f9f314cb11cdc7761f21ad3d8">llvm::RegBankSelect::MappingCost::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfopass/#aa1d16b1a18d54d59024c399bf87cd50f">llvm::RegionInfoPass::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#a9908e6684d648ead83a4bab5f1bf7c51">llvm::RegisterBank::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/instructionmapping/#aaa302bb0b2c36a3c8b0d7ffbf7ff14be">llvm::RegisterBankInfo::InstructionMapping::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/operandsmapper/#aeccd292b19be57132f7f2539d32aac21">llvm::RegisterBankInfo::OperandsMapper::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/partialmapping/#ad6adb61747f6498e03e8169e79c4365f">llvm::RegisterBankInfo::PartialMapping::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/registerbankinfo/valuemapping/#aa08a6a3c21b4acf3c92768f1d66d7330">llvm::RegisterBankInfo::ValueMapping::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#ae4e740afafe2e17e2daf7892e794be34">llvm::sampleprof::FunctionSamples::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/sampleprof/linelocation/#ac76f76a568bbf03e252a65c04ed7c1aa">llvm::sampleprof::LineLocation::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplerecord/#a3fd74749576d39c8ed03c634f407183a">llvm::sampleprof::SampleRecord::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchaddhandler/#a32c81722d001c17b29f4d06408286da7">llvm::sandboxir::CatchSwitchAddHandler::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/genericsetter/#a78cf03974174777527608b3254bd260a">llvm::sandboxir::GenericSetter&lt; GetterFn, SetterFn &gt;::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/genericsetterwithidx/#a3f784d0bef994cdedb3580cd80370cd6">llvm::sandboxir::GenericSetterWithIdx&lt; GetterFn, SetterFn &gt;::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/irchangebase/#a53b42553bfe10f203280b280ded95ce6">llvm::sandboxir::IRChangeBase::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/module/#ab920f2e731cfd6339e7cb84b0244c08b">llvm::sandboxir::Module::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pass/#ae3bff551737ed859e8a281d830f1c05d">llvm::sandboxir::Pass::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/passmanager/#a8f5329d9d97273a1c50798ccb215d519">llvm::sandboxir::PassManager&lt; ParentPass, ContainedPass &gt;::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle/#adb2341568ceba242cfe990f24680a7e5">llvm::sandboxir::SeedBundle::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedcontainer/#ad8a856ab638a4b031aec8bdfe9543736">llvm::sandboxir::SeedContainer::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#a6ae35ec967d69bc1cd21ae482bbdd4a2">llvm::SCEV::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a6abb9875bd75a74af631f2017c2f4264">llvm::SDDbgValue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sdep/#ace1019e8cefb80490348369f12fe0a44">llvm::SDep::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a1f4346248feeb9d5c83ce930555936d1">llvm::SDNode::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#addc45c27e50b974d99ba074ebfc4930c">llvm::SDNode::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a8e7eabcdc79b470fd13a397b4464bfe2">llvm::SelectionDAG::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ab4592056c4ff0764824d139d4c65116f">llvm::SlotIndex::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindexes/#a40e7a4cc6e14f421c36f936f9f8dff58">llvm::SlotIndexes::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/slpvectorizer/boupslp/edgeinfo/#a2b5258ea831ff51e2dc51dd405c547ba">llvm::slpvectorizer::BoUpSLP::EdgeInfo::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#a8d66b6c2df1694b91c47b9ffe7a9edb8">llvm::slpvectorizer::BoUpSLP::VLOperands::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a28f3076bd731bbacde0d9b9655481b35">llvm::SMSchedule::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/smtexpr/#ac8b65a93a1afee7194e50849cc475a35">llvm::SMTExpr::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/smtsolver/#acc408995a4e7c9983df57a596c03fdd5">llvm::SMTSolver::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/smtsolverstatistics/#a5a52af58c7994688ec3e611d1a19eb76">llvm::SMTSolverStatistics::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/smtsort/#a9f166927c14943e8bb5b8c4543857c9e">llvm::SMTSort::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#af56a81de61d43765dd1352743fd0bfc3">llvm::SplitEditor::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalinfo/#a66cca95800c21ed2ebcd4a7c41763608">llvm::StackSafetyGlobalInfo::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/submulticlassreference/#a554b99f34e4a3b79a7062b789634efa0">llvm::SubMultiClassReference::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#abdb795e29b0d98b3f34cab49960a2798">llvm::SubtargetFeatures::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/suspendcrossinginfo/#ae0841bca835cfc99fa124abaca92ea47">llvm::SuspendCrossingInfo::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/threadsafetrierawhashmapbase/#a7a914a734fa37fdb1bb52291ecedc4b4">llvm::ThreadSafeTrieRawHashMapBase::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/trace/#a1aa1c60a8ceaeddb2773e255309a6585">llvm::Trace::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a61bf259f7bf14d45f68e145f121e1891">llvm::Twine::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#ab12a7ef156bf7b362cc00571276f2f1a">llvm::ValueEnumerator::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/valuesymboltable/#a4e9cc2b295b104ebd2c7d5b4d7960f10">llvm::ValueSymbolTable::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#a570cc2ad4630f9e1adf4576e36507449">llvm::VirtRegMap::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockbase/#a29b07d1e1a358501745f8436a63da2d9">llvm::VPBlockBase::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyexception/#a30c6b4e0f84f2a6f472f1973316e05b6">llvm::WebAssemblyException::dump</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#af0c9cdac0acbe1745277e6e9544aa575">LiveDebugValues::MLocTracker::dump_mloc_map</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#aab2e2064b4bde0d5487ddc0d0982f5b9">llvm::SUnit::dumpAttributes</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyconstantislandpass-cpp-/cskyconstantislands/#ae9bfa833198bca98db6ff7bb76c1f71d">anonymous{CSKYConstantIslandPass.cpp}::CSKYConstantIslands::dumpBBs</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsconstantislandpass-cpp-/mipsconstantislands/#a6e6938d2a62e2461cc8809a568a2d431">anonymous{MipsConstantIslandPass.cpp}::MipsConstantIslands::dumpBBs</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afb02c318229e5318a7db3270e1766f8c">llvm::SelectionDAG::dumpDotGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#a54b0557e2672c4799a99740259ddc41d">llvm::slpvectorizer::BoUpSLP::VLOperands::dumpMode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#a917f4d40ed0bbdaf4ab50e5df4de067b">llvm::ScheduleDAG::dumpNodeAll</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledag/#ac464b0883162724583f0f124c8be8157">llvm::ScheduleDAG::dumpNodeName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9fb7740f0fb6e5a825320f3c63df3263">dumpOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#ac5eb4db26f1949633619280980be341c">llvm::sandboxir::Value::dumpOS</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a47b14770ed9fb839f309757ca2adc80d">llvm::MachineInstr::dumpr</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a4efc0c778a7afdaf5b5a45594bc809a0">llvm::SDNode::dumpr</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a89206bcd1c676ffdbfe8a8494c187524">llvm::SDNode::dumpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a639a1e437b7586350b87cae4556342c2">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::dumpRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#af3748b109893adeac3a84c62f072ffab">llvm::Twine::dumpRepr</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#a53bfc0f964240b77c4569bea523c2b39">llvm::SchedBoundary::dumpReservedCycles</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a1b25769866228a5517d8e752fad14f10">llvm::SDNode::dumprFull</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a01b02e76c87211e7084ec17f18a2d16f">llvm::ScheduleDAGMI::dumpSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/schedboundary/#ae01f950d577dadad26a49baa47d10d66">llvm::SchedBoundary::dumpScheduledState</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a942d716003056c037d46a4144e9cf885">llvm::ScheduleDAGMI::dumpScheduleTraceBottomUp</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a3010c4b89284791284aa6e2ec510501b">llvm::ScheduleDAGMI::dumpScheduleTraceTopDown</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a553593c083449cc4db546a757010a2f4">llvm::MachineRegisterInfo::dumpUses</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a50473b1fa66150ed4edc08ede2b4e51f">llvm::Loop::dumpVerbose</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#a25c846db09b53a522a9fd2ac38462406">llvm::slpvectorizer::BoUpSLP::VLOperands::getModeStr</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a7d6da56a091d691d571fe114ec6faceb">llvm::DynamicAPInt::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonsplitdouble-cpp/#ab9a3a1f23e02f40120823d7ad6ee8531">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/instrrefbasedldv/#a625f1469290a1b9bb1bc071a5392d3cb">LiveDebugValues::InstrRefBasedLDV::InstrRefBasedLDV</a>, <a href="/web-llvm/docs/api/classes/llvm/timepasseshandler/#ac1d5878f935f77ce61e2d792797bd1e2">llvm::TimePassesHandler::operator=</a>, <a href="/web-llvm/docs/api/structs/llvm/ilpvalue/#a66e49dcd600dc169a7b3d36298e9e311">llvm::ILPValue::print</a>, <a href="/web-llvm/docs/api/classes/llvm/safestack/stacklayout/#a8a4d99268d104c4ff503df7a2d98927a">llvm::safestack::StackLayout::print</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#a1b15905b247b2552feb7d41ff01742db">llvm::SDDbgValue::print</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#ae8d07324e150cf3266d4013f6d3f0b06">llvm::slpvectorizer::BoUpSLP::VLOperands::print</a>, <a href="/web-llvm/docs/api/classes/llvm/smtexpr/#acd0b4d2d94e037380e2ba40a24a4d760">llvm::SMTExpr::print</a>, <a href="/web-llvm/docs/api/classes/llvm/smtsolverstatistics/#afdf3cc2c2213689304cc65106d3bdb7b">llvm::SMTSolverStatistics::print</a>, <a href="/web-llvm/docs/api/classes/llvm/smtsort/#a2beac2a2c70ec0f4086270bfbb865d86">llvm::SMTSort::print</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#ac2b6bcd87baa28336528735bcdb102ba">llvm::slpvectorizer::BoUpSLP::VLOperands::printMode</a> and <a href="/web-llvm/docs/api/classes/llvm/smtsolver/#a1dbc1dc18c003ed3e7b8e05493c22600">llvm::SMTSolver::~SMTSolver</a>.</p>

</div>
</div>

### LLVM\_EXTENSION {#aa308b4893c1ee3415893491cd9c061d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_EXTENSION</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_EXTENSION - Support compilers where we have a keyword to suppress pedantic diagnostics.</p>

<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp/#a8bf77e8726f283ee9fa0a48c07a871ee">bindingsErrorHandler</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#ga4ecfc4310276f36557ee231e22d1b823">LLVMContextGetDiagnosticHandler</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#gacbfc704565962bf71eaaa549a9be570f">LLVMContextSetDiagnosticHandler</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#gabdcc4e421199e9e7bb5e0cd449468731">LLVMContextSetYieldCallback</a> and <a href="/web-llvm/docs/api/groups/llvmcerror/#gaf6159e6764fb23072ec25514b90b0ebd">LLVMInstallFatalErrorHandler</a>.</p>

</div>
</div>

### LLVM\_EXTERNAL\_VISIBILITY {#adeb6f14d9f377993d79fae2efb34ecac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_EXTERNAL_VISIBILITY</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a7effa39ec7a59bd77a4a7ff830b9e507">LLVMInitializeAArch64AsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64asmprinter-cpp/#a7b0658b9527a4f9381a4ffe0d7a2f0f4">LLVMInitializeAArch64AsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#a937116e9c4a0863979038e9be05d1604">LLVMInitializeAArch64Disassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#ad29f792516a692b403e4f66d9815002f">LLVMInitializeAArch64Target</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/targetinfo/aarch64targetinfo-cpp/#a7dd86b5b88a7bceb145b4aa1db5a06e9">LLVMInitializeAArch64TargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64mctargetdesc-cpp/#ac6cc590ea14328605b961daf062e51e8">LLVMInitializeAArch64TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/asmparser/amdgpuasmparser-cpp/#a05fa1a5dede44ff50e637230e5a0c815">LLVMInitializeAMDGPUAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuasmprinter-cpp/#a049a1d1af4ce3deb01a0fa15121de758">LLVMInitializeAMDGPUAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/disassembler/amdgpudisassembler-cpp/#abf297f3f63ca3282686b6b725d3ca818">LLVMInitializeAMDGPUDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargetmachine-cpp/#ab1daa0f11648eb67d340b69f83f6e196">LLVMInitializeAMDGPUTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/targetinfo/amdgputargetinfo-cpp/#ab33344c34559a4bff01e96fd3004b7d8">LLVMInitializeAMDGPUTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumctargetdesc-cpp/#af6847ab00bc2a1f50ce559aaaeda2d0d">LLVMInitializeAMDGPUTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mca/amdgpucustombehaviour-cpp/#abff2d688ab31b2b868abd61f30ff08d6">LLVMInitializeAMDGPUTargetMCA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcasmprinter-cpp/#a320fc8a9a809dd68792d29c83c2d5d84">LLVMInitializeARCAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/disassembler/arcdisassembler-cpp/#a87812879cf9b970b38668d2b1c1c7e46">LLVMInitializeARCDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arctargetmachine-cpp/#a7a0d1dafcf74f4d12be428d38b236876">LLVMInitializeARCTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/targetinfo/arctargetinfo-cpp/#ae866df933c7fedad841afddfbefc8950">LLVMInitializeARCTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcmctargetdesc-cpp/#a5a2a9b7766a908fa2b912fef81c25849">LLVMInitializeARCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/asmparser/armasmparser-cpp/#acec6a535e4093e810f3865c41298b215">LLVMInitializeARMAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armasmprinter-cpp/#a6df578afdb0d2365512aaeef33f43e4c">LLVMInitializeARMAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/disassembler/armdisassembler-cpp/#aa278d8e4687a87388f35b9d63569b3a4">LLVMInitializeARMDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a6685488f57ab6c8880f8e18a5364181a">LLVMInitializeARMTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/targetinfo/armtargetinfo-cpp/#ab34895cddcc024b59752fd0b488d5606">LLVMInitializeARMTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmctargetdesc-cpp/#a3d8bf90e641f417abcb5fcfe8685ecf8">LLVMInitializeARMTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/asmparser/avrasmparser-cpp/#ac8c89640de3b4171dfe66a36afdb0f35">LLVMInitializeAVRAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrasmprinter-cpp/#a0478aacc04ccd1d59b814dca2fe2fc9f">LLVMInitializeAVRAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/disassembler/avrdisassembler-cpp/#ae64f5d4662302ac25f4d9ab6e0f5e17a">LLVMInitializeAVRDisassembler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8fd5bdf026357cb11043211e812f91e5">llvm::LLVMInitializeAVRTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/targetinfo/avrtargetinfo-cpp/#a6393f580118ca28315d45b974fe87585">LLVMInitializeAVRTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/lib/target/avr/mctargetdesc/avrmctargetdesc-cpp/#a6fbdffb36fc945879f1a767060c51e2c">LLVMInitializeAVRTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/asmparser/bpfasmparser-cpp/#a0cff608b9191bb5d2fbd0638724df83e">LLVMInitializeBPFAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfasmprinter-cpp/#ae4d3692815a120c2e286f29e1cefebbb">LLVMInitializeBPFAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/disassembler/bpfdisassembler-cpp/#a68b7b81c8452fef2a2c55374b2c1020d">LLVMInitializeBPFDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpftargetmachine-cpp/#a25f2b3e2f3a759d1986d97f81dab0ec5">LLVMInitializeBPFTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/targetinfo/bpftargetinfo-cpp/#a7cef0584f04fa0c25d70eaed40e74287">LLVMInitializeBPFTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/lib/target/bpf/mctargetdesc/bpfmctargetdesc-cpp/#a57c49ae0d15b512ea03aa0c8bd297a45">LLVMInitializeBPFTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/asmparser/cskyasmparser-cpp/#a790e2b5da296265b93b69d184185aeea">LLVMInitializeCSKYAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskyasmprinter-cpp/#a0dcee1df18b177084b438106e72ca785">LLVMInitializeCSKYAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/disassembler/cskydisassembler-cpp/#a4b8d70b11b38d66c590505c6e97990e3">LLVMInitializeCSKYDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/cskytargetmachine-cpp/#aef449992ce85170fc4e20ccc1fb822dc">LLVMInitializeCSKYTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/targetinfo/cskytargetinfo-cpp/#acb18194a1d2113769445111d89cb22d3">LLVMInitializeCSKYTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/csky/lib/target/csky/mctargetdesc/cskymctargetdesc-cpp/#a6f6d3c84199337a3cac544c658fe1106">LLVMInitializeCSKYTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxasmprinter-cpp/#ac48b45cb6e4d311a369eeac60361ab56">LLVMInitializeDirectXAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/directxtargetmachine-cpp/#a7c874778b9aadea658c289d076d1b8b8">LLVMInitializeDirectXTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/targetinfo/directxtargetinfo-cpp/#a05df49c5607b7ccd2d1be31875c698a2">LLVMInitializeDirectXTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/mctargetdesc/directxmctargetdesc-cpp/#ae2650072c61d204c8fe4bc597fdc6672">LLVMInitializeDirectXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/asmparser/hexagonasmparser-cpp/#a9d2025e3f355f0f1ab7c595ef89a9cb1">LLVMInitializeHexagonAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a31790fbb4dc2a3bcf2abe4c2404832ef">LLVMInitializeHexagonAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/disassembler/hexagondisassembler-cpp/#a2a7be637e77772d13f3cb8976fd40e26">LLVMInitializeHexagonDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagontargetmachine-cpp/#af01d552fbdd044b3e41bb99f905bcccd">LLVMInitializeHexagonTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/targetinfo/hexagontargetinfo-cpp/#a1b10e8298d3539b891dfa848ab77996d">LLVMInitializeHexagonTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmctargetdesc-cpp/#a98a868de586290904766e4922d3e870b">LLVMInitializeHexagonTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/asmparser/lanaiasmparser-cpp/#a2e5ead42eb4dd8866056044d67007260">LLVMInitializeLanaiAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaiasmprinter-cpp/#ad34425deb5d178af12e83c0cb791742c">LLVMInitializeLanaiAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/disassembler/lanaidisassembler-cpp/#a58c788bf8078444aa61008a70c9d77c0">LLVMInitializeLanaiDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lanaitargetmachine-cpp/#ab3f2305043d5778e874d45de4b7f9ea2">LLVMInitializeLanaiTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/targetinfo/lanaitargetinfo-cpp/#a5d6f7fac27d9aa94258bf547cac361f1">LLVMInitializeLanaiTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/lanai/lib/target/lanai/mctargetdesc/lanaimctargetdesc-cpp/#a3c16773835d3cf48abb3332a6e735de6">LLVMInitializeLanaiTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/asmparser/loongarchasmparser-cpp/#a5c82b517d9dffe6b41975f2bc42442b8">LLVMInitializeLoongArchAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchasmprinter-cpp/#a77f5135069ff25fca2b2dba4915c3b30">LLVMInitializeLoongArchAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/disassembler/loongarchdisassembler-cpp/#a9c45f02a91fb54fb1f1f0ba8c4da1e77">LLVMInitializeLoongArchDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchtargetmachine-cpp/#adf9c18b7627d3daa19cd81911ffcf703">LLVMInitializeLoongArchTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/targetinfo/loongarchtargetinfo-cpp/#a0b36e3957ce955f07519fe75d250da6a">LLVMInitializeLoongArchTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/lib/target/loongarch/mctargetdesc/loongarchmctargetdesc-cpp/#a45bfbd633beacf42b102d7b0103a0d4c">LLVMInitializeLoongArchTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/asmparser/m68kasmparser-cpp/#a7373484d0d70040759e4679035b8267c">LLVMInitializeM68kAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kasmprinter-cpp/#ae85d74fb363ed6b4cf3920062d208e03">LLVMInitializeM68kAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/disassembler/m68kdisassembler-cpp/#a663216d33b120b3f4c7e181ae055595d">LLVMInitializeM68kDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68ktargetmachine-cpp/#a37850ef8b98b5c3049cf47d36a0fa38a">LLVMInitializeM68kTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/targetinfo/m68ktargetinfo-cpp/#a210715dc849dea3155e9fdec2afeaaaf">LLVMInitializeM68kTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/lib/target/m68k/mctargetdesc/m68kmctargetdesc-cpp/#a60d27d11f3d31ed0356606efc80102d0">LLVMInitializeM68kTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/asmparser/mipsasmparser-cpp/#a4e1a81e73b2baa0d49edcd6d3c42ff74">LLVMInitializeMipsAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsasmprinter-cpp/#a8df5d94b952d5029135b55de5ae1dfb1">LLVMInitializeMipsAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/disassembler/mipsdisassembler-cpp/#af30d43c4117f5ef8cd82a778aa3ce38c">LLVMInitializeMipsDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipstargetmachine-cpp/#abef57f2f45a7ce74cf7267749570eb17">LLVMInitializeMipsTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/targetinfo/mipstargetinfo-cpp/#a5f12a0bb471ae891b1b8f5e4e059ed71">LLVMInitializeMipsTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipsmctargetdesc-cpp/#a32aa9aae9369c8b517be80ffecbc711c">LLVMInitializeMipsTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/asmparser/msp430asmparser-cpp/#a606cfbf4fb2e8aa81895b712e1246420">LLVMInitializeMSP430AsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430asmprinter-cpp/#ac97215577d6ea77a328f438b43da9c46">LLVMInitializeMSP430AsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/disassembler/msp430disassembler-cpp/#a5d7efe5f6d2d6b3e091d245b621d4450">LLVMInitializeMSP430Disassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430targetmachine-cpp/#a4d4f67c31571fbace48e599ebbd66fc9">LLVMInitializeMSP430Target</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/targetinfo/msp430targetinfo-cpp/#a4b0929b87ee4e0890d89d2847e5c7b7e">LLVMInitializeMSP430TargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/lib/target/msp430/mctargetdesc/msp430mctargetdesc-cpp/#ae4728e7bd5eb4cc404ac5fbbbce5cec5">LLVMInitializeMSP430TargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxasmprinter-cpp/#abca044f9b116a4f84eaef0ad8f2e3790">LLVMInitializeNVPTXAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxtargetmachine-cpp/#aaed7e2473819aa12e64e58f5e9e8d79f">LLVMInitializeNVPTXTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/targetinfo/nvptxtargetinfo-cpp/#a0c256d53a704e03041fac359914cc3c5">LLVMInitializeNVPTXTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/lib/target/nvptx/mctargetdesc/nvptxmctargetdesc-cpp/#a6cc0e9f51ef7d135cc855521020d9c08">LLVMInitializeNVPTXTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/asmparser/ppcasmparser-cpp/#ae4ceb74c4eff25df1f2facd30e0da5e7">LLVMInitializePowerPCAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcasmprinter-cpp/#a463d61a5d359ec3dfb5a80cc4c1a9aae">LLVMInitializePowerPCAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/disassembler/ppcdisassembler-cpp/#a23e71205a1f02a8366a0530ec04e6f56">LLVMInitializePowerPCDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctargetmachine-cpp/#afcd90d71029f6f8cc67de62444a5d681">LLVMInitializePowerPCTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/targetinfo/powerpctargetinfo-cpp/#a5a55d83958fff6797dcc5c5325734fdb">LLVMInitializePowerPCTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/lib/target/powerpc/mctargetdesc/ppcmctargetdesc-cpp/#a7355d88f591aa5dd5f1d812ea99218ec">LLVMInitializePowerPCTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/asmparser/riscvasmparser-cpp/#a21a3e5f0be05170ba0770c83199e4db2">LLVMInitializeRISCVAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvasmprinter-cpp/#a27824c12da09de79ef94151cccf77eda">LLVMInitializeRISCVAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/disassembler/riscvdisassembler-cpp/#ad982bc371e77bd90d8c3ef90909379a3">LLVMInitializeRISCVDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvtargetmachine-cpp/#a8b9a09dbbf4b2bacd980a00284a2c143">LLVMInitializeRISCVTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/targetinfo/riscvtargetinfo-cpp/#a6dcc1577a9c311debe6604c09266f824">LLVMInitializeRISCVTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmctargetdesc-cpp/#a1e93b89ed4a5f8e3974124fedfcf4b27">LLVMInitializeRISCVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mca/riscvcustombehaviour-cpp/#ad6c3b190f3ba99eb436c77c8ab194e78">LLVMInitializeRISCVTargetMCA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/asmparser/sparcasmparser-cpp/#a9da82f020e415c833e0e97af8a275af8">LLVMInitializeSparcAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparcasmprinter-cpp/#a2c3ee8310ea1759628789269f9e4ae3f">LLVMInitializeSparcAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/disassembler/sparcdisassembler-cpp/#a597a1749b319b1320aa1987a804f636c">LLVMInitializeSparcDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/sparctargetmachine-cpp/#a5ced6bd290b4ef3d5c9eb4d47d164490">LLVMInitializeSparcTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/targetinfo/sparctargetinfo-cpp/#aae1ab610631f641afc5657107cb446f5">LLVMInitializeSparcTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/sparc/lib/target/sparc/mctargetdesc/sparcmctargetdesc-cpp/#a8c9015b70cac029d8b59b9331d506300">LLVMInitializeSparcTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvasmprinter-cpp/#a342e1e4047a4dc10fb8178734def15ff">LLVMInitializeSPIRVAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvtargetmachine-cpp/#aa3b9ca78bbd44f9b9c4417b261aa1175">LLVMInitializeSPIRVTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/targetinfo/spirvtargetinfo-cpp/#ae4afd27cf19cb5c6c4eea7af67677b32">LLVMInitializeSPIRVTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/lib/target/spirv/mctargetdesc/spirvmctargetdesc-cpp/#a9615460be0935d2aab84ea024c2d821b">LLVMInitializeSPIRVTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/asmparser/systemzasmparser-cpp/#a871f670e54963b2730d6233ef2436f22">LLVMInitializeSystemZAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#ab2cfa340905fea57c1ee004790f3c822">LLVMInitializeSystemZAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/disassembler/systemzdisassembler-cpp/#a75dfd8bcdb5822d649b827b78a889992">LLVMInitializeSystemZDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemztargetmachine-cpp/#a6b9585b9bf84e64f4acc5808772f0eec">LLVMInitializeSystemZTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/targetinfo/systemztargetinfo-cpp/#acd2e4ea61e47994dd9e57047f3a9864c">LLVMInitializeSystemZTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmctargetdesc-cpp/#abbf3c4fe1fddd6f8c4afe905d4122929">LLVMInitializeSystemZTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/asmparser/veasmparser-cpp/#aa793dde266f9b22a4f5b60c27bba70d5">LLVMInitializeVEAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/veasmprinter-cpp/#a694773053cf48ae1c7ded9f6a7eb4628">LLVMInitializeVEAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/disassembler/vedisassembler-cpp/#ad88a246e4481af7d20c2e1430b90a0d1">LLVMInitializeVEDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/vetargetmachine-cpp/#a4c27f0cd53f78a7bb743fe7d1653726e">LLVMInitializeVETarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/targetinfo/vetargetinfo-cpp/#a18c245d150fecc81195b5fe45fb5da31">LLVMInitializeVETargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/ve/lib/target/ve/mctargetdesc/vemctargetdesc-cpp/#aa17f62e3150eef038e4a6d3fb31d2af3">LLVMInitializeVETargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/asmparser/webassemblyasmparser-cpp/#ac27f74a08a5fa521cd8f7a0ef461325e">LLVMInitializeWebAssemblyAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp/#ac358693eef34fd8527167f153de538ed">LLVMInitializeWebAssemblyAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblytargetmachine-cpp/#a5193d47b6ee96653d85049ae1ab002e9">LLVMInitializeWebAssemblyTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/targetinfo/webassemblytargetinfo-cpp/#a1c96e8d5c7f2712140f7a4c8e7523bf0">LLVMInitializeWebAssemblyTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/lib/target/webassembly/mctargetdesc/webassemblymctargetdesc-cpp/#a0f83ad11a759c56547fd4b239e605f5e">LLVMInitializeWebAssemblyTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreasmprinter-cpp/#a3870ae3f06892be3c02937b150687ab5">LLVMInitializeXCoreAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/disassembler/xcoredisassembler-cpp/#aae3a06bbf7034d74374c6acfe81f9bb1">LLVMInitializeXCoreDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoretargetmachine-cpp/#a2ed1605d9ce6d806b0b046dcc4d30819">LLVMInitializeXCoreTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/targetinfo/xcoretargetinfo-cpp/#a690c3dc78396495d2205e82beb3bd945">LLVMInitializeXCoreTargetInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/lib/target/xcore/mctargetdesc/xcoremctargetdesc-cpp/#a252ba3ed8208cac6aff7149891cc9c4a">LLVMInitializeXCoreTargetMC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/asmparser/xtensaasmparser-cpp/#aabade2f68f2f4f28f136a49a092f1b04">LLVMInitializeXtensaAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensaasmprinter-cpp/#a3b80786ba26a8f5863f8f42ea1d93f61">LLVMInitializeXtensaAsmPrinter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/disassembler/xtensadisassembler-cpp/#a2f8ff26b6100f84d64aa1700205ad980">LLVMInitializeXtensaDisassembler</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/xtensatargetmachine-cpp/#afad196468ae7709008684e81c811bc73">LLVMInitializeXtensaTarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/targetinfo/xtensatargetinfo-cpp/#a2cb3883b7e5b9235acbb23b9fc829b3e">LLVMInitializeXtensaTargetInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensamctargetdesc-cpp/#ad9def10e0f63f81dd8a4d3e2316f4795">LLVMInitializeXtensaTargetMC</a>.</p>

</div>
</div>

### LLVM\_FALLTHROUGH {#a9579881de06b1560d242d15171ca1b86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_FALLTHROUGH</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_FALLTHROUGH - Mark fallthrough cases in switch statements.</p>

<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#acf3f78aff4143b42112848d8f0dd4d7a">findmust</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a37b2c71be1bd09705bd8e3fa728c6b57">p_ere_exp</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#aee283f9c02a8848c8782c35713aad80c">p_simp_re</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-siphash-cpp-/#a159cdb1934bd81019941f78b393b0f0c">anonymous{SipHash.cpp}::siphash</a>.</p>

</div>
</div>

### LLVM\_GNUC\_PREREQ {#a113552aa941976a9a34d28f3be87a732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_GNUC_PREREQ(maj, min, patch)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_GNUC_PREREQ Extend the default __GNUC_PREREQ even if glibc's features.h isn't available.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_GSL\_OWNER {#a61e566d072949de225fa6912528beaf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_GSL_OWNER</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_GSL_OWNER - Apply this to owning classes like SmallVector to enable lifetime warnings.</p>

<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_GSL\_POINTER {#acfeb6346678a2cb6295d2842b2a2805a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_GSL_POINTER</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_GSL_POINTER - Apply this to non-owning classes like StringRef to enable lifetime warnings.</p>

<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_HAS\_CPP\_ATTRIBUTE {#ac655bc80da3bd4c0e27a9ac4ac8163f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_HAS_CPP_ATTRIBUTE(x)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_HWADDRESS\_SANITIZER\_BUILD {#aadd18c23b9ca88ab897fbcdf1c0e14a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_HWADDRESS_SANITIZER_BUILD&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_HWADDRESS_SANITIZER_BUILD Whether LLVM itself is built with HWAddressSanitizer instrumentation.</p>

<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_LIBRARY\_VISIBILITY {#a662e21bcce5c9c71b6cc511fa04f900f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_LIBRARY_VISIBILITY&nbsp;&nbsp;&nbsp;<a href="#aa8334a3b3b010ed4a1f52080ece7e81c">LLVM_ATTRIBUTE_VISIBILITY_HIDDEN</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_LIBRARY\_VISIBILITY\_NAMESPACE {#adf64debeca517afdfabfaaa9375718d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_LIBRARY_VISIBILITY_NAMESPACE&nbsp;&nbsp;&nbsp;<a href="#aa8334a3b3b010ed4a1f52080ece7e81c">LLVM_ATTRIBUTE_VISIBILITY_HIDDEN</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_LIFETIME\_BOUND {#aac3d0ea99ec07497e1d0fd0cdfc18040}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_LIFETIME_BOUND</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7297c362c4fd96749704f50f1212b823">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a787c29c3a723fb96a96cb892c6e4f107">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ad7dbf1c52893ca8a5fbc208cd5dc2d30">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#acbeaf6660fa6a272706c71336f0a77b7">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a350c562c4e7b8cde89380600c0902617">llvm::ArrayRef&lt; llvm::cfg::Update&lt; MachineBasicBlock * &gt; &gt;::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/function-ref-129e1794ead5f330174da20533428dd4/#a999fb19e85adb6685ab4bb36eedf9528">llvm::function_ref&lt; Ret(Params...)&gt;::function_ref</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ae116bcdf5fac57d6da943935fb6c547a">llvm::sys::path::rbegin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a6aa32b6763df05d8187ad5551533b567">llvm::sys::path::remove_leading_dotslash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a2bc70cc8c5a83b940ed7c948b28dc512">llvm::sys::path::rend</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a70392c6eca2623b798f965f66db768df">llvm::StringRef::StringRef</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9bc1c70c28eb2f5a53ad0dcac4c56b4d">llvm::StringRef::StringRef</a>.</p>

</div>
</div>

### LLVM\_LIKELY {#ae5b35beb6f127e5f47269e9124b886fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_LIKELY(EXPR)&nbsp;&nbsp;&nbsp;(EXPR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/dynamiclibrary/handleset/#a57e48229c8cea2a8adee11137875503f">llvm::sys::DynamicLibrary::HandleSet::AddLibrary</a>, <a href="/web-llvm/docs/api/classes/llvm/bumpptrallocatorimpl/#a4054c3eefe873caf49c2290808d409ac">llvm::BumpPtrAllocatorImpl&lt; MallocAllocator, 65536 &gt;::Allocate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386/#a1cf84875ae743236d8dd98fd56af9f7b">llvm::jitlink::i386::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#a4640b55f4a0124796c017fc725e87add">llvm::jitlink::x86_64::applyFixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a53f135c84cfb135c8e3f890659a3f782">llvm::jitlink::aarch32::applyFixupArm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a2cc2e3fa12d8c5d0d37310647c9c3a4d">llvm::jitlink::aarch32::applyFixupData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a183363f7e8482b2c1e193956dea835ee">llvm::jitlink::aarch32::applyFixupThumb</a>, <a href="/web-llvm/docs/api/classes/llvm/json/ostream/#a39613bf6aa1a8059a4dd25d57c7fd1e5">llvm::json::OStream::attributeBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/basiclayout/#af3fa75b45aafa6c528042df53446d8e1">llvm::jitlink::BasicLayout::BasicLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a0a6400043bb608ee08534246b6c7b0da">llvm::DynamicAPInt::ceilDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7ccbc2b7c2fc5cf4c9dbb648570bcf01">llvm::SelectionDAG::copyExtraInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elf-ppc64-cpp-/#abde45e89e81f599cbf6a29b9a645eead">anonymous{ELF_ppc64.cpp}::createELFGOTHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a4bffcdebfabeca1c58db99b58eb5d5c7">llvm::DynamicAPInt::divByPositive</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#ae71f82ffc717b5eb1713c51ac15a0fb3">llvm::DynamicAPInt::divByPositiveInPlace</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a807369cf0e8ddbe75c8c4a671bfc4258">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#a4bed18f645cf76fb884f4ee5e9aacea0">llvm::StringMapImpl::FindKey</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/globalsstream/#a281ab4dd4b03840bd4217ce9aa1241cd">llvm::pdb::GlobalsStream::findRecordsByName</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#ac6b039b5f68780df0184722571fe10dd">llvm::DynamicAPInt::floorDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a14d5f0348a5c7f46257fe67f95d1ab31">llvm::DynamicAPInt::gcd</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#ab848a96ad435084447eb2e861efad8ee">llvm::json::Value::getAsArray</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#aff50ac6f6c371ba4f52a773675ac2c94">llvm::json::Value::getAsArray</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#a1f409fb49d7e2dcb2515d4b2591ac4d3">llvm::json::Value::getAsBoolean</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#a786d622442c72566e5d18db4174b3753">llvm::json::Value::getAsInteger</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#af4329315e698667f31e8c2114fa8ae42">llvm::json::Value::getAsNull</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#a2bfcd5c94a0424908bef97d9da3055c8">llvm::json::Value::getAsNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#a77428427461f125c633b3b81f9a72b9f">llvm::json::Value::getAsObject</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#afed60bdad89b18864aea16ad10318de0">llvm::json::Value::getAsObject</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#af408235bbc39a6c55d4a99ee95c72a9c">llvm::json::Value::getAsString</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a8c2dd03c3f7b301cda6ac1ba9b31f113">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::getVPLegalizationStrategy</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp/#a2e84df1cbf9375ee66f23c5ca414c638">hashValueMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a68e0dd48505f955c8681f11b6957afdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isSafeToReferenceAfterResize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/json/#a385765e73480a0f2d49dcc84a8fb70da">llvm::json::isUTF8</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#af6caebcd7dc40dea28562fde4f260414">llvm::dwarf_linker::classic::DWARFLinker::link</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyatomicpointer/#aa2b1f76810fa4eb122a4057c975c9396">llvm::LazyAtomicPointer&lt; TrieNode &gt;::loadOrGenerate</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#a1681c3e5a8a4f67991745ffca1cb72fc">llvm::StringMapImpl::LookupBucketFor</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#aa8c9248faa6cc07fdc7c001259726dfc">llvm::DynamicAPInt::mod</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a0b67a4ee3011c77673baf0aa3ccf1b3c">llvm::DynamicAPInt::operator!=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a9e402b6cb2335886077c73e5880f6b1c">llvm::DynamicAPInt::operator!=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a7fed75ef05b8e1ad72c1d3568e49561b">llvm::DynamicAPInt::operator!=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a32ad614e29ae907332a56ec93a8204a4">llvm::DynamicAPInt::operator%</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a92058b3197343bafff7c2b7ed12fda07">llvm::DynamicAPInt::operator*</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a3c03c38ddfc7b3f1c705ab7e79a8cc6a">llvm::DynamicAPInt::operator*=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a6ea9bf04175edbaf311d08fab83f3e9d">llvm::DynamicAPInt::operator+</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a679bd6fb3996011d457c3459a6c124cb">llvm::DynamicAPInt::operator+=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a5bb6e6ad85226f2ff9434fe21184c5d2">llvm::DynamicAPInt::operator-</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#abcaa206b230e25e078c0d85543a00511">llvm::DynamicAPInt::operator-</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a8cbd17e4a142aee0f926b4976f79d963">llvm::DynamicAPInt::operator-=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a1bf96844b3c7492681c9cb678f4f9ff7">llvm::DynamicAPInt::operator/</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a146b3314862fa63bb4698b80cadad93c">llvm::DynamicAPInt::operator/=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a39b90547bf41b51e82ee0a91fea74cb5">llvm::DynamicAPInt::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a5e7939805b51f889f1d60791a59674d7">llvm::DynamicAPInt::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a88d574416e6f5fa68359b393010e445b">llvm::DynamicAPInt::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/mappingcost/#aa0252d6f02b3a363b68e4438db3f82a7">llvm::RegBankSelect::MappingCost::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a95a996596cc929e06b3ed709db0e1e0f">llvm::DynamicAPInt::operator&lt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a5729ad037b3ba98d9b85c85382501c11">llvm::DynamicAPInt::operator&lt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a67656071decb86462eac4efed3f0b32f">llvm::DynamicAPInt::operator&lt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a0e7f861f4373c4342541558e23b13fab">llvm::DynamicAPInt::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#aaa5416545d0c01bba62521af0ac2db15">llvm::DynamicAPInt::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a3d34bb4856f154b92988bdf76d688463">llvm::DynamicAPInt::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a63ee1995b96d5df1513414ade216a523">llvm::DynamicAPInt::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a09ad8d89e87e7bd9f96f9ca9897038b4">llvm::DynamicAPInt::operator&gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#aebc02de586c4a4c0c5d805b086e43155">llvm::DynamicAPInt::operator&gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#ab23348cc755bc499077a86953e0950fb">llvm::DynamicAPInt::operator&gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a068916b0b7ffee36b56568f6c865a16c">llvm::DynamicAPInt::operator&gt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a6403d3854d39d682cc552b2bf122c6ce">llvm::DynamicAPInt::operator&gt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#aeae61c9fb3c4e0f412763a154847f079">llvm::DynamicAPInt::operator&gt;=</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#aa6cf2c07bc856d1cb198de49c5523317">llvm::jitlink::aarch32::readAddendThumb</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a1cbc5251f13ad42510760ed61c71e874">llvm::BinaryStreamReader::readCString</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a4ff60fb0f0d249b4623327ef5976867b">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::reserveForParamAndGetAddressImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a4214f202c6a3b5b3933489a6edc49b6b">llvm::MachineRegisterInfo::shouldTrackSubRegLiveness</a>, <a href="/web-llvm/docs/api/classes/anonymous-metadataloader-cpp-/bitcodereadermetadatalist/#a7e3787ebeee00be2cb3d75570a27420f">anonymous{MetadataLoader.cpp}::BitcodeReaderMetadataList::upgradeTypeRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/xxhash-cpp/#adf1ca5feb6e370f2f2d4ceb328c927e6">XXH3_len_0to16_64b</a>.</p>

</div>
</div>

### LLVM\_MEMORY\_SANITIZER\_BUILD {#ab82d05e7fec3f6ecc5284dad0a929703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_MEMORY_SANITIZER_BUILD&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_MEMORY_SANITIZER_BUILD Whether LLVM itself is built with MemorySanitizer instrumentation.</p>

<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_MSC\_PREREQ {#ac19e2279a0e03c0ad2a190d3e00ec15c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_MSC_PREREQ(version)&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_MSC_PREREQ Is the compiler MSVC of at least the specified version?</p>


<p>The common</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">version</td>
<td class="doxyParamItemDescription"><p>values to check for are:</p>


<ul class="doxyList ">
<li>1910: VS2017, version 15.1 &amp; 15.2</li>
<li>1911: VS2017, version 15.3 &amp; 15.4</li>
<li>1912: VS2017, version 15.5</li>
<li>1913: VS2017, version 15.6</li>
<li>1914: VS2017, version 15.7</li>
<li>1915: VS2017, version 15.8</li>
<li>1916: VS2017, version 15.9</li>
<li>1920: VS2019, version 16.0</li>
<li>1921: VS2019, version 16.1</li>
<li>1922: VS2019, version 16.2</li>
<li>1923: VS2019, version 16.3</li>
<li>1924: VS2019, version 16.4</li>
<li>1925: VS2019, version 16.5</li>
<li>1926: VS2019, version 16.6</li>
<li>1927: VS2019, version 16.7</li>
<li>1928: VS2019, version 16.8 + 16.9</li>
<li>1929: VS2019, version 16.10 + 16.11</li>
<li>1930: VS2022, version 17.0</li>
</ul></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_NO\_PROFILE\_INSTRUMENT\_FUNCTION {#a14c4f366dadc2ca8d0860f0e1fc40863}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_NO_PROFILE_INSTRUMENT_FUNCTION</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_ENABLE_EXCEPTIONS Whether LLVM is built with exception support.</p>


<p>\macro LLVM_NO_PROFILE_INSTRUMENT_FUNCTION Disable the profile instrument for a function.</p>


<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_NO\_SANITIZE {#a6d65fbde0458a34315c42b80acad72a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_NO_SANITIZE(KIND)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_NO_SANITIZE Disable a particular sanitizer for a function.</p>

<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_NO\_SANITIZE\_MEMORY\_ATTRIBUTE {#a2c79436804022a1275836a6dd12946d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_NO_SANITIZE_MEMORY_ATTRIBUTE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_PACKED {#ad9fc3f1d03abf0ac9ac026a546ce19be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_PACKED(d)&nbsp;&nbsp;&nbsp;d __attribute__((packed))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_PACKED Used to specify a packed structure.</p>


<p>LLVM_PACKED( struct A { int i; int j; int k; long long l; });</p>


<p>LLVM_PACKED_START struct B { int i; int j; int k; long long l; }; LLVM_PACKED_END</p>


<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_PACKED\_END {#ade18ef060e6da6feff03adb6224a7233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_PACKED_END&nbsp;&nbsp;&nbsp;_Pragma("pack(pop)")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_PACKED\_START {#afaa5fcfc7c317a599182a557fbb172ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_PACKED_START&nbsp;&nbsp;&nbsp;_Pragma("pack(<a href="/web-llvm/docs/api/files/lib/lib/remarks/bitstreamremarkserializer-cpp/#a720622fc32fd2435f7726d832d851ea6">push</a>, 1)")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_PREFERRED\_TYPE {#a2328e1eac1d32bc55a61db8c725eac79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_PREFERRED_TYPE(T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_PREFERRED_TYPE Adjust type of bit-field in debug info.</p>

<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_PREFETCH {#aecc9fcaf96003481ac8c5565ca968bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_PREFETCH(addr, rw, locality)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_PRETTY\_FUNCTION {#add3e64f9d3d35dff1307ced174a44b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_PRETTY_FUNCTION&nbsp;&nbsp;&nbsp;__func__</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_PRETTY_FUNCTION Gets a user-friendly looking function signature for the current scope using the best available method on each platform.</p>


<p>The exact format of the resulting string is implementation specific and non-portable, so this should only be used, for example, for logging or diagnostics.</p>


<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_READNONE {#a39557b142c7bfcc54d3874aae7084907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_READNONE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7ff290402c84552fd9fd3caedb9b00e7">llvm::AMDGPU::isLegalSMRDImmOffset</a>.</p>

</div>
</div>

### LLVM\_READONLY {#ab8e0eab61769d9974aeed9345ce11baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_READONLY</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5eb95c1fe12d25bcfe6d3b63f6148605">llvm::AMDGPU::getAddr64Inst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a08b135e0f9484354a83410d97d698b22">llvm::AMDGPU::getBasicFromSDWAOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ac4c95246ad0278e01cc6e03560005f0b">llvm::AMDGPU::getCommuteOrig</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a96286d8f7d90ece30046d826bbb71422">llvm::AMDGPU::getCommuteRev</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2888339a06c839e6231a8391d379cc69">llvm::AMDGPU::getDPPOp32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aa98382e49aca921e295d8f8f80c61f6f">llvm::AMDGPU::getDPPOp64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ae86326b2bc0ff967b391246b7c63b46f">llvm::AMDGPU::getFlatScratchInstSSfromSV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a328299d8f8d9100f6eaadc2bbf13ba43">llvm::AMDGPU::getFlatScratchInstSTfromSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a2c49a690cf18ca46eda313ffdfe93ac5">llvm::AMDGPU::getFlatScratchInstSVfromSS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5c4e292db193538fa8ef82438d1ca2e2">llvm::AMDGPU::getFlatScratchInstSVfromSVS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0a35ade96e14e74ae51d74559eeb2e5d">llvm::AMDGPU::getGlobalSaddrOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a42e6f807e1852ff50f30ed48bce3abea">llvm::AMDGPU::getGlobalVaddrOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af7672ecd68ad0182beb360a4453b51ba">llvm::AMDGPU::getIfAddr64Inst</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d0a7baab8d078065b2de10e3460892a">llvm::Function::getIntrinsicID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a5ff7467be99b93194854ce84b534f711">llvm::AMDGPU::getMFMAEarlyClobberOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a724a8297a44c4fd44c28f6d87ac12fd5">llvm::AMDGPU::getMFMASrcCVDstAGPROp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a913ff7957dafc27d90f1f68b630c7560">llvm::AMDGPU::getMIMGBiasMappingInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ad69abc53c68db78ad61f21abb89e7ea5">llvm::AMDGPU::getMIMGDimInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7967181b077a4a08f5baf9950e30660d">llvm::AMDGPU::getMIMGDimInfoByEncoding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a03ae61d27fd3e265ad881a31a75b49f3">llvm::AMDGPU::getMIMGG16MappingInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0b5b29d1275f84b9e530fd2419cc03ac">llvm::AMDGPU::getMIMGInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4d00fb8f6d351e866977b0209c47ac8f">llvm::AMDGPU::getMIMGMIPMappingInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a15c2685fdd459d0b1b9a6e9bc2c1679d">llvm::AMDGPU::getMIMGOffsetMappingInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a721c83954a20f8b52f471cbafe2458bb">llvm::AMDGPU::getSDWAOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a0b3f411f0032973ee08934a9d8611c8d">llvm::AMDGPU::getSOPKOp</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#acf3c3aa4880eb60d00963ba93082c298">llvm::BasicBlock::getTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af40d7434499e43e3d3f9c5d22bc7546f">llvm::AMDGPU::getVCMPXNoSDstOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a17fda9e2f2cb60c24bfdec02d7793b86">llvm::AMDGPU::getVOPe32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#ab0ccda834736fa549ceccbbb9d4aa340">llvm::AMDGPU::getVOPe64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a23a7144281e79bf3c766e624e298083b">llvm::AMDGPU::isDPMACCInstruction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a4807909d05e79661bca2d9ff6a90ccd2">llvm::AMDGPU::isInvalidSingleUseConsumerInst</a>.</p>

</div>
</div>

### LLVM\_REQUIRE\_CONSTANT\_INITIALIZATION {#a29de8410a1056ad1b234905755dbf5da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_REQUIRE_CONSTANT_INITIALIZATION</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_REQUIRE_CONSTANT_INITIALIZATION - Apply this to globals to ensure that they are constant initialized.</p>

<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_SUPPRESS\_DEPRECATED\_DECLARATIONS\_POP {#a42b9d7579beb5a3eead5b1c83c973602}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_SUPPRESS_DEPRECATED_DECLARATIONS_POP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_SUPPRESS\_DEPRECATED\_DECLARATIONS\_PUSH {#a2177472989d8b1082a8aede8cc535cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_SUPPRESS_DEPRECATED_DECLARATIONS_PUSH</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_THREAD\_LOCAL {#a793005af6ae802d5a2a2e8ceb4ac2135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_THREAD_LOCAL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_THREAD_LOCAL A thread-local storage specifier which can be used with globals, extern globals, and static globals.</p>


<p>This is essentially an extremely restricted analog to C++11's thread_local support. It uses thread_local if available, falling back on gcc __thread if not. __thread doesn't support many of the C++11 thread_local's features. You should only use this for PODs that you can statically initialize to some constant value. In almost all circumstances this is most appropriate for use with a pointer, integer, or small aggregation of pointers and integers.</p>


<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_THREAD\_SANITIZER\_BUILD {#ab6b3e49c523b219bee6271deca48ccab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_THREAD_SANITIZER_BUILD&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>\macro LLVM_THREAD_SANITIZER_BUILD Whether LLVM itself is built with ThreadSanitizer instrumentation.</p>

<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>

</div>
</div>

### LLVM\_UNLIKELY {#a104cae72182bec0ab951e3faea6ce509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_UNLIKELY(EXPR)&nbsp;&nbsp;&nbsp;(EXPR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#ae58e570d50b3ef11bc8cd906ee008222">llvm::dwarf_linker::classic::DWARFLinker::addObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/ppc64/#a5a393f897c1439c03e7ef35e7874a8a1">llvm::jitlink::ppc64::applyFixup</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a0a6400043bb608ee08534246b6c7b0da">llvm::DynamicAPInt::ceilDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyatomicpointer/#a1ef184ef819b5890fc765374952031c0">llvm::LazyAtomicPointer&lt; TrieNode &gt;::compare_exchange_strong</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aa619d96a87c8a5be606b1a4a4ac0115d">llvm::APInt::countl_one</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elf-ppc64-cpp-/#abde45e89e81f599cbf6a29b9a645eead">anonymous{ELF_ppc64.cpp}::createELFGOTHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a405b6cecd013148b4b443dd37854b4c4">llvm::decodeSLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3720bbfe79232f7792ab4b969dfbeed0">llvm::decodeULEB128</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocfast-cpp/#a73ba38b119a12eb092295458fde44f52">dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a536afeb2c8a330ff2939560cf6f3ad81">llvm::DynamicAPInt::DynamicAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::const_iterator&lt; MemoryLocation &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#aa284de70c1521913d9eda75728495b36">llvm::GIMatchTableExecutor::fastDecodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/simpleexecutormemorymanager/#a0c3a2679314fcbd29c249386447c8ba4">llvm::orc::rt_bootstrap::SimpleExecutorMemoryManager::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a82369bea2700347f68e1f43e30d2d47b">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#ac6b039b5f68780df0184722571fe10dd">llvm::DynamicAPInt::floorDiv</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocfast-cpp-/instrposindexes/#a8fa5c8981b665309d8d0243a267c5a0b">anonymous{RegAllocFast.cpp}::InstrPosIndexes::getIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/gsistreambuilder-cpp/#ad8de58e5ee26f7e8a2a509355b0156f4">gsiRecordCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#abbb20c80e0c1ab59446de978f898fc1e">handleMethodOverloadList</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a96ae8a0897a355d1c0a04a7eae3f2466">handleOneMethod</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/globaltypetablebuilder/#a7c1575ca2aa02aa24752ae549aa177f8">llvm::codeview::GlobalTypeTableBuilder::insertRecordAs</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker/#af6caebcd7dc40dea28562fde4f260414">llvm::dwarf_linker::classic::DWARFLinker::link</a>, <a href="/web-llvm/docs/api/classes/llvm/json/objectkey/#a956bf032105bef7c40ebc21c3d3382db">llvm::json::ObjectKey::ObjectKey</a>, <a href="/web-llvm/docs/api/classes/llvm/json/objectkey/#aab18e463fcd9b0040f321fe8e80d9dfe">llvm::json::ObjectKey::ObjectKey</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a1bf96844b3c7492681c9cb678f4f9ff7">llvm::DynamicAPInt::operator/</a>, <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#a146b3314862fa63bb4698b80cadad93c">llvm::DynamicAPInt::operator/=</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a571c3958ecb1aa9ee1e3178b3544b9ca">llvm::BitVector::operator&lt;&lt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#a09395da97c764bcd5804c40f1f0bff35">llvm::BitVector::operator&gt;&gt;=</a>, <a href="/web-llvm/docs/api/classes/llvm/pagedvector/#a63e3ad7aaf150227878cef2db7eb45df">llvm::PagedVector&lt; T, PageSize &gt;::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmapimpl/#a498d235dfa951d6728354cc777896219">llvm::StringMapImpl::RehashTable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a4ff60fb0f0d249b4623327ef5976867b">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::reserveForParamAndGetAddressImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/apint-cpp/#a6e85075a57f714ace735081ee4e4134e">rotateModulo</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aa548cc4a0fd9e7c713b180f7780655e2">llvm::APInt::rotl</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#ad7198c4852982f1005eb076b6ab126de">llvm::LocationSize::upperBound</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#aa1465e2b320fbcb13a49ee925ef1909d">llvm::json::Value::Value</a>, <a href="/web-llvm/docs/api/classes/llvm/json/value/#ae6e91d6ff92490ec9e59e57411a14a4e">llvm::json::Value::Value</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a581a276005e9f911c53aa145e4a01e53">llvm::raw_ostream::write</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a> and <a href="/web-llvm/docs/api/classes/llvm/dynamicapint/#ab089d7ab5b50a298e0045f386fedeef2">llvm::DynamicAPInt::~DynamicAPInt</a>.</p>

</div>
</div>

### TsanHappensAfter {#a4a8a06812caf14bdec3b541b578b8344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TsanHappensAfter(cv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 602 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>.</p>

</div>
</div>

### TsanHappensBefore {#a186eadfc2c525b71adaf35e7487eccac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TsanHappensBefore(cv)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>.</p>

</div>
</div>

### TsanIgnoreWritesBegin {#ae7ae7168870d6f719670bf0f47b9ade5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TsanIgnoreWritesBegin()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>.</p>

</div>
</div>

### TsanIgnoreWritesEnd {#a6d95fe36240cded45e8889c2491a78f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TsanIgnoreWritesEnd()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">Compiler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
