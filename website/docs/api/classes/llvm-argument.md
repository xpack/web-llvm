---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/argument
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Argument` Class Reference

<p>This class represents an incoming formal argument to a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Argument { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">llvm/IR/Argument.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Representation. <a href="/web-llvm/docs/api/classes/llvm/value/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f424034cc075c4509906e4108374647">Argument</a> (Type *Ty, const Twine &amp;Name="", Function *F=nullptr, unsigned ArgNo=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> constructor. <a href="#a5f424034cc075c4509906e4108374647">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a862c73765000251be786c801260ba7c1">getParent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ed1d642c949eef868937797f5240811">getParent</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab205d366b1137026c32f5678f7cc2726">getArgNo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index of this formal argument in its containing function. <a href="#ab205d366b1137026c32f5678f7cc2726">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ab8479e06d277e9e2036a17d37beafb">hasNonNullAttr</a> (bool AllowUndefOrPoison=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the nonnull attribute. <a href="#a4ab8479e06d277e9e2036a17d37beafb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af996ca89ce53f22731001cd4fcbe4fd8">getDereferenceableBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this argument has the dereferenceable attribute, return the number of bytes known to be dereferenceable. <a href="#af996ca89ce53f22731001cd4fcbe4fd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b06db40548ac13bc6f5e9c41cf48f10">getDereferenceableOrNullBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this argument has the dereferenceable_or_null attribute, return the number of bytes known to be dereferenceable. <a href="#a5b06db40548ac13bc6f5e9c41cf48f10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b7b250e8950824b760f81f849bccb0">getNoFPClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this argument has nofpclass attribute, return the mask representing disallowed floating-point values. <a href="#a98b7b250e8950824b760f81f849bccb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7a83acf52b94d9f56c5d5f27d0ceb0a">getRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this argument has a range attribute, return the value range of the argument. <a href="#ad7a83acf52b94d9f56c5d5f27d0ceb0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a736135f761e0d468c731ddc4327607e7">hasByValAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the byval attribute. <a href="#a736135f761e0d468c731ddc4327607e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2b9814461b8632c4b956771722a05e">hasByRefAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the byref attribute. <a href="#a4c2b9814461b8632c4b956771722a05e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabbbacb54eef8f00a267ee8637d906b4">hasSwiftSelfAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the swiftself attribute. <a href="#aabbbacb54eef8f00a267ee8637d906b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980540ac8d24b8c0e816a27c9db87edd">hasSwiftErrorAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the swifterror attribute. <a href="#a980540ac8d24b8c0e816a27c9db87edd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1a4db62863e691875684ca606e296de">hasPassPointeeByValueCopyAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the byval, inalloca, or preallocated attribute. <a href="#af1a4db62863e691875684ca606e296de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dd72d72e5774cad8447a1d8f2a82912">getPassPointeeByValueCopySize</a> (const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this argument satisfies has hasPassPointeeByValueAttr, return the in-memory ABI size copied to the stack for the call. <a href="#a7dd72d72e5774cad8447a1d8f2a82912">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64053a77bf9119a471354a77554a3152">hasPointeeInMemoryValueAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the byval, sret, inalloca, preallocated, or byref attribute. <a href="#a64053a77bf9119a471354a77554a3152">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8898f119271cf9520fe589e23b0b5b36">getPointeeInMemoryValueType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If hasPointeeInMemoryValueAttr returns true, the in-memory ABI type is returned. <a href="#a8898f119271cf9520fe589e23b0b5b36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a byval or inalloca argument, return its alignment. <a href="#ad3da5e0b4c0c86ff3f7da94396931523">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc5053f382c68b8dbdb3fae1b477441a">getParamAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a byval or inalloca argument, return its alignment. <a href="#acc5053f382c68b8dbdb3fae1b477441a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af59bfa623b37e5fb7c1130ef66e73986">getParamStackAlign</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1d02322e0e7eccafbe38a7116841018">getParamByValType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a byval argument, return its type. <a href="#ac1d02322e0e7eccafbe38a7116841018">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e2e406d1f112c192fbd431d28c31ce4">getParamStructRetType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is an sret argument, return its type. <a href="#a6e2e406d1f112c192fbd431d28c31ce4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1247bbc672e07bf7e30e147cd1990dc3">getParamByRefType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a byref argument, return its type. <a href="#a1247bbc672e07bf7e30e147cd1990dc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aace470f9201b0139a075fa91a2d340f1">getParamInAllocaType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is an inalloca argument, return its type. <a href="#aace470f9201b0139a075fa91a2d340f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb271133522d95f5bbeb0eb8c9b53a66">hasNestAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the nest attribute. <a href="#acb271133522d95f5bbeb0eb8c9b53a66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c0d4963c5d582a10687fbbad9040f20">hasNoAliasAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the noalias attribute. <a href="#a3c0d4963c5d582a10687fbbad9040f20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6899891b26f27a9b786e1eb3427cc4c">hasNoCaptureAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the nocapture attribute. <a href="#af6899891b26f27a9b786e1eb3427cc4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa32b0012927aa16ef35eed639f32ff0">hasNoFreeAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the nofree attribute. <a href="#aaa32b0012927aa16ef35eed639f32ff0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adee57277f0f37159672db6cc883e90a0">hasStructRetAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the sret attribute. <a href="#adee57277f0f37159672db6cc883e90a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7309e208bcfee0f6e04f906bc3eac7dd">hasInRegAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the inreg attribute. <a href="#a7309e208bcfee0f6e04f906bc3eac7dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e1df4428e5c6b9bfea6ef909a5f7019">hasReturnedAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the returned attribute. <a href="#a6e1df4428e5c6b9bfea6ef909a5f7019">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a605c20365a110ba796d3379e83ae733d">onlyReadsMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the readonly or readnone attribute. <a href="#a605c20365a110ba796d3379e83ae733d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a935a57935471ed504b7ec8b7c33fca03">hasInAllocaAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the inalloca attribute. <a href="#a935a57935471ed504b7ec8b7c33fca03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78ceb9b753526f90d5eaa1f9971ec915">hasPreallocatedAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the preallocated attribute. <a href="#a78ceb9b753526f90d5eaa1f9971ec915">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaec4196a617c63658e83256ccd554bd2">hasZExtAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the zext attribute. <a href="#aaec4196a617c63658e83256ccd554bd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d495a92cd21baa3b118c5145fb09611">hasSExtAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this argument has the sext attribute. <a href="#a7d495a92cd21baa3b118c5145fb09611">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7aa7a234eec956680268b4b5b0222bf">addAttrs</a> (AttrBuilder &amp;B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add attributes to an argument. <a href="#aa7aa7a234eec956680268b4b5b0222bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ebecf01cf4ede715f689b4f92de9a71">addAttr</a> (Attribute::AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15cb95d0645ccef68f704f1e68ce73e2">addAttr</a> (Attribute Attr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc24cdf7fd375d1e26da159387cd526">removeAttr</a> (Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove attributes from an argument. <a href="#a7dc24cdf7fd375d1e26da159387cd526">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a836e39b4e0fddf9df0ec7fbfbeacd50e">removeAttrs</a> (const AttributeMask &amp;AM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66059696916025f0f9d7ea35454a85fe">hasAttribute</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if an argument has a given attribute. <a href="#a66059696916025f0f9d7ea35454a85fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52abc2868487ae999bdb8ce39a5836bc">hasAttribute</a> (StringRef Kind) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f8be95d8a3801b89185cee96b4491d">getAttribute</a> (Attribute::AttrKind Kind) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae86fc6af8da2140064a1dc5e5fe3ba43">getAttributes</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b775cdf5860319880f1c2d1aa1aaf96">setParent</a> (Function *parent)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6ae68538a4990f1fc500cf96d9a9e89">Parent</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57bb0027f72ceeddca0c5e98e53741a6">ArgNo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad904765991a90849720e14565ceca7d5">classof</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method for support type inquiry through isa, cast, and dyn_cast. <a href="#ad904765991a90849720e14565ceca7d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class represents an incoming formal argument to a <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>.</p>


<p>A formal argument, since it is `‘formal`', does not contain an actual value but instead represents the type, argument number, and attributes of an argument for a specific function. When used in the body of said function, the argument of course represents the value of the actual argument that the function was called with.</p>


<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Function {#ab7194606aa12931e96f8f5448d418ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/function">Function</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a>.</p>


<p>Referenced by <a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a>, <a href="#a8ed1d642c949eef868937797f5240811">getParent</a> and <a href="#a862c73765000251be786c801260ba7c1">getParent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Argument() {#a5f424034cc075c4509906e4108374647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Argument::Argument (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F=nullptr, unsigned ArgNo=0)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> constructor.</p>

<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAttr() {#a5ebecf01cf4ede715f689b4f92de9a71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Argument::addAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuattributor-cpp-/#af95019d35f27157f1728d80f7d3baadc">anonymous{AMDGPUAttributor.cpp}::addPreloadKernArgHint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a5d2d34710da4cddfc00e2f4eacd2be7d">adjustByValArgAlignment</a> and <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### addAttr() {#a15cb95d0645ccef68f704f1e68ce73e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Argument::addAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### addAttrs() {#aa7aa7a234eec956680268b4b5b0222bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Argument::addAttrs (AttrBuilder &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add attributes to an argument.</p>

<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### getArgNo() {#ab205d366b1137026c32f5678f7cc2726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Argument::getArgNo ()</td>
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

<p>Return the index of this formal argument in its containing function.</p>


<p>For example in "void foo(int a, float b)" a is 0 and b is 1.</p>


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxlowerargs-cpp-/#aafd9b42c5de69fbe2a25e6b94f8cc299">anonymous{NVPTXLowerArgs.cpp}::copyByValParam</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a8e6dc274c7730d43ef8505856e984fa4">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#a6066aaa9c2bcca469acdce4369e03712">llvm::AbstractCallSite::getCallArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#a7e8ae04873ef7a72fbad37852333d290">llvm::AbstractCallSite::getCallArgOperandNo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a899698594c66589eab9bdca89c843798">isArgUnmodifiedByAllCalls</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ae965a8b6001eaf1612d36d070594c706">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0121eb7b984a5cf2527133cb838d5982">llvm::Attributor::registerFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a>.</p>

</div>
</div>

### getAttribute() {#a35f8be95d8a3801b89185cee96b4491d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute Argument::getAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a5d2d34710da4cddfc00e2f4eacd2be7d">adjustByValArgAlignment</a> and <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### getAttributes() {#ae86fc6af8da2140064a1dc5e5fe3ba43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet Argument::getAttributes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### getDereferenceableBytes() {#af996ca89ce53f22731001cd4fcbe4fd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Argument::getDereferenceableBytes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this argument has the dereferenceable attribute, return the number of bytes known to be dereferenceable.</p>


<p>Otherwise, zero is returned.</p>


<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getDereferenceableOrNullBytes() {#a5b06db40548ac13bc6f5e9c41cf48f10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Argument::getDereferenceableOrNullBytes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this argument has the dereferenceable_or_null attribute, return the number of bytes known to be dereferenceable.</p>


<p>Otherwise, zero is returned.</p>


<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getNoFPClass() {#a98b7b250e8950824b760f81f849bccb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest Argument::getNoFPClass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this argument has nofpclass attribute, return the mask representing disallowed floating-point values.</p>


<p>Otherwise, fcNone is returned.</p>


<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getParamAlign() {#acc5053f382c68b8dbdb3fae1b477441a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign Argument::getParamAlign ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a byval or inalloca argument, return its alignment.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a8e6dc274c7730d43ef8505856e984fa4">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp/#af00d722295f4e7b769e28af02fbefc1f">getArgumentTypeAlign</a>, <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>.</p>

</div>
</div>

### getParamAlignment() {#ad3da5e0b4c0c86ff3f7da94396931523}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::Argument::getParamAlignment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a byval or inalloca argument, return its alignment.</p>


<p>FIXME: Remove this function once transition to <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> is over. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="#acc5053f382c68b8dbdb3fae1b477441a">getParamAlign()</a> instead.</p>


<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>.</p>


<p>References <a href="#a5ebecf01cf4ede715f689b4f92de9a71">addAttr</a>, <a href="#aa7aa7a234eec956680268b4b5b0222bf">addAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="#a35f8be95d8a3801b89185cee96b4491d">getAttribute</a>, <a href="#ae86fc6af8da2140064a1dc5e5fe3ba43">getAttributes</a>, <a href="#acc5053f382c68b8dbdb3fae1b477441a">getParamAlign</a>, <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>, <a href="#a1247bbc672e07bf7e30e147cd1990dc3">getParamByRefType</a>, <a href="#ac1d02322e0e7eccafbe38a7116841018">getParamByValType</a>, <a href="#aace470f9201b0139a075fa91a2d340f1">getParamInAllocaType</a>, <a href="#af59bfa623b37e5fb7c1130ef66e73986">getParamStackAlign</a>, <a href="#a6e2e406d1f112c192fbd431d28c31ce4">getParamStructRetType</a>, <a href="#a66059696916025f0f9d7ea35454a85fe">hasAttribute</a>, <a href="#a935a57935471ed504b7ec8b7c33fca03">hasInAllocaAttr</a>, <a href="#a7309e208bcfee0f6e04f906bc3eac7dd">hasInRegAttr</a>, <a href="#acb271133522d95f5bbeb0eb8c9b53a66">hasNestAttr</a>, <a href="#a3c0d4963c5d582a10687fbbad9040f20">hasNoAliasAttr</a>, <a href="#af6899891b26f27a9b786e1eb3427cc4c">hasNoCaptureAttr</a>, <a href="#aaa32b0012927aa16ef35eed639f32ff0">hasNoFreeAttr</a>, <a href="#a78ceb9b753526f90d5eaa1f9971ec915">hasPreallocatedAttr</a>, <a href="#a6e1df4428e5c6b9bfea6ef909a5f7019">hasReturnedAttr</a>, <a href="#a7d495a92cd21baa3b118c5145fb09611">hasSExtAttr</a>, <a href="#adee57277f0f37159672db6cc883e90a0">hasStructRetAttr</a>, <a href="#aaec4196a617c63658e83256ccd554bd2">hasZExtAttr</a>, <a href="#a605c20365a110ba796d3379e83ae733d">onlyReadsMemory</a>, <a href="#a7dc24cdf7fd375d1e26da159387cd526">removeAttr</a> and <a href="#a836e39b4e0fddf9df0ec7fbfbeacd50e">removeAttrs</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### getParamByRefType() {#a1247bbc672e07bf7e30e147cd1990dc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Argument::getParamByRefType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a byref argument, return its type.</p>

<p>Declaration at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a8e6dc274c7730d43ef8505856e984fa4">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp/#af00d722295f4e7b769e28af02fbefc1f">getArgumentTypeAlign</a>, <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aba60fd25fb0b3c574e10d3b1e41bc295">llvm::getPointeeTypeByAttr</a>.</p>

</div>
</div>

### getParamByValType() {#ac1d02322e0e7eccafbe38a7116841018}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Argument::getParamByValType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is a byval argument, return its type.</p>

<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a5d2d34710da4cddfc00e2f4eacd2be7d">adjustByValArgAlignment</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxlowerargs-cpp-/#aafd9b42c5de69fbe2a25e6b94f8cc299">anonymous{NVPTXLowerArgs.cpp}::copyByValParam</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aba60fd25fb0b3c574e10d3b1e41bc295">llvm::getPointeeTypeByAttr</a>.</p>

</div>
</div>

### getParamInAllocaType() {#aace470f9201b0139a075fa91a2d340f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Argument::getParamInAllocaType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is an inalloca argument, return its type.</p>

<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### getParamStackAlign() {#af59bfa623b37e5fb7c1130ef66e73986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign Argument::getParamStackAlign ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### getParamStructRetType() {#a6e2e406d1f112c192fbd431d28c31ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Argument::getParamStructRetType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is an sret argument, return its type.</p>

<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aba60fd25fb0b3c574e10d3b1e41bc295">llvm::getPointeeTypeByAttr</a>.</p>

</div>
</div>

### getParent() {#a862c73765000251be786c801260ba7c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function * llvm::Argument::getParent ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>.</p>


<p>Reference <a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a5d2d34710da4cddfc00e2f4eacd2be7d">adjustByValArgAlignment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#acba556ecb63df60b8c2376161167bf92">allCallersPassValidPointerForArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a8e6dc274c7730d43ef8505856e984fa4">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a899698594c66589eab9bdca89c843798">isArgUnmodifiedByAllCalls</a>, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#a1eee3dd323fe708ae24f7a1e3ca7f5c4">llvm::InformationCache::isInvolvedInMustTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0121eb7b984a5cf2527133cb838d5982">llvm::Attributor::registerFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>.</p>

</div>
</div>

### getParent() {#a8ed1d642c949eef868937797f5240811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::Argument::getParent ()</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>.</p>


<p>Reference <a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a>.</p>

</div>
</div>

### getPassPointeeByValueCopySize() {#a7dd72d72e5774cad8447a1d8f2a82912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Argument::getPassPointeeByValueCopySize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this argument satisfies has hasPassPointeeByValueAttr, return the in-memory ABI size copied to the stack for the call.</p>


<p>Otherwise, return 0.</p>


<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getPointeeInMemoryValueType() {#a8898f119271cf9520fe589e23b0b5b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Argument::getPointeeInMemoryValueType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If hasPointeeInMemoryValueAttr returns true, the in-memory ABI type is returned.</p>


<p>Otherwise, nullptr.</p>


<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### getRange() {#ad7a83acf52b94d9f56c5d5f27d0ceb0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantRange &gt; Argument::getRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this argument has a range attribute, return the value range of the argument.</p>


<p>Otherwise, std::nullopt is returned.</p>


<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 271 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasAttribute() {#a66059696916025f0f9d7ea35454a85fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if an argument has a given attribute.</p>

<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a8e6dc274c7730d43ef8505856e984fa4">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a>, <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>.</p>

</div>
</div>

### hasAttribute() {#a52abc2868487ae999bdb8ce39a5836bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasAttribute (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasByRefAttr() {#a4c2b9814461b8632c4b956771722a05e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasByRefAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the byref attribute.</p>

<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuattributor-cpp-/#af95019d35f27157f1728d80f7d3baadc">anonymous{AMDGPUAttributor.cpp}::addPreloadKernArgHint</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a8e6dc274c7730d43ef8505856e984fa4">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuhsametadatastreamer-cpp/#af00d722295f4e7b769e28af02fbefc1f">getArgumentTypeAlign</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba60fd25fb0b3c574e10d3b1e41bc295">llvm::getPointeeTypeByAttr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abc5f55adba4d71094e3432734c218f49">llvm::hasPointeeTypeAttr</a>.</p>

</div>
</div>

### hasByValAttr() {#a736135f761e0d468c731ddc4327607e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasByValAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the byval attribute.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a7c67e5393efc9e53e1a841b70236bfcb">copyFunctionByValArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba60fd25fb0b3c574e10d3b1e41bc295">llvm::getPointeeTypeByAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc5f55adba4d71094e3432734c218f49">llvm::hasPointeeTypeAttr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsiteargument/#a12170d0ad51240b43cda989d850ab479">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSiteArgument::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a31f2a80a770f0aa93c1fab42e9d41407">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>.</p>

</div>
</div>

### hasInAllocaAttr() {#a935a57935471ed504b7ec8b7c33fca03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasInAllocaAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the inalloca attribute.</p>

<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### hasInRegAttr() {#a7309e208bcfee0f6e04f906bc3eac7dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasInRegAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the inreg attribute.</p>

<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### hasNestAttr() {#acb271133522d95f5bbeb0eb8c9b53a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasNestAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the nest attribute.</p>

<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 278 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuattributor-cpp-/#af95019d35f27157f1728d80f7d3baadc">anonymous{AMDGPUAttributor.cpp}::addPreloadKernArgHint</a> and <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### hasNoAliasAttr() {#a3c0d4963c5d582a10687fbbad9040f20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasNoAliasAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the noalias attribute.</p>

<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a8e6dc274c7730d43ef8505856e984fa4">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a> and <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### hasNoCaptureAttr() {#af6899891b26f27a9b786e1eb3427cc4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasNoCaptureAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the nocapture attribute.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### hasNoFreeAttr() {#aaa32b0012927aa16ef35eed639f32ff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasNoFreeAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the nofree attribute.</p>

<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### hasNonNullAttr() {#a4ab8479e06d277e9e2036a17d37beafb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasNonNullAttr (bool AllowUndefOrPoison=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the nonnull attribute.</p>


<p>Also returns true if at least one byte is known to be dereferenceable and the pointer is in addrspace(0). If AllowUndefOrPoison is true, respect the semantics of nonnull attribute and return true even if the argument can be undef or poison.</p>


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasPassPointeeByValueCopyAttr() {#af1a4db62863e691875684ca606e296de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasPassPointeeByValueCopyAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the byval, inalloca, or preallocated attribute.</p>


<p>These attributes represent arguments being passed by value, with an associated copy between the caller and callee</p>


<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasPointeeInMemoryValueAttr() {#a64053a77bf9119a471354a77554a3152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasPointeeInMemoryValueAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the byval, sret, inalloca, preallocated, or byref attribute.</p>


<p>These attributes represent arguments being passed by value (which may or may not involve a stack copy)</p>


<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasPreallocatedAttr() {#a78ceb9b753526f90d5eaa1f9971ec915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasPreallocatedAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the preallocated attribute.</p>

<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### hasReturnedAttr() {#a6e1df4428e5c6b9bfea6ef909a5f7019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasReturnedAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the returned attribute.</p>

<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### hasSExtAttr() {#a7d495a92cd21baa3b118c5145fb09611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasSExtAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the sext attribute.</p>

<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### hasStructRetAttr() {#adee57277f0f37159672db6cc883e90a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasStructRetAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the sret attribute.</p>

<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba60fd25fb0b3c574e10d3b1e41bc295">llvm::getPointeeTypeByAttr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abc5f55adba4d71094e3432734c218f49">llvm::hasPointeeTypeAttr</a>.</p>

</div>
</div>

### hasSwiftErrorAttr() {#a980540ac8d24b8c0e816a27c9db87edd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasSwiftErrorAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the swifterror attribute.</p>

<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasSwiftSelfAttr() {#aabbbacb54eef8f00a267ee8637d906b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasSwiftSelfAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the swiftself attribute.</p>

<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

### hasZExtAttr() {#aaec4196a617c63658e83256ccd554bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::hasZExtAttr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the zext attribute.</p>

<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### onlyReadsMemory() {#a605c20365a110ba796d3379e83ae733d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Argument::onlyReadsMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this argument has the readonly or readnone attribute.</p>

<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#a8e6dc274c7730d43ef8505856e984fa4">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitKernelArg</a> and <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### removeAttr() {#a7dc24cdf7fd375d1e26da159387cd526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Argument::removeAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove attributes from an argument.</p>

<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a5d2d34710da4cddfc00e2f4eacd2be7d">adjustByValArgAlignment</a> and <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

### removeAttrs() {#a836e39b4e0fddf9df0ec7fbfbeacd50e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Argument::removeAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>


<p>Referenced by <a href="#ad3da5e0b4c0c86ff3f7da94396931523">getParamAlignment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setParent() {#a0b775cdf5860319880f1c2d1aa1aaf96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Argument::setParent (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * parent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ArgNo {#a57bb0027f72ceeddca0c5e98e53741a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Argument::ArgNo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>.</p>

</div>
</div>

### Parent {#ad6ae68538a4990f1fc500cf96d9a9e89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::Argument::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ad904765991a90849720e14565ceca7d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Argument::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Method for support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a>.</p>


<p>References <a href="#ad904765991a90849720e14565ceca7d5">classof</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a18dbfcb332af7515599ee795cf462843">llvm::Value::Value</a>.</p>


<p>Referenced by <a href="#ad904765991a90849720e14565ceca7d5">classof</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">Argument.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/function-cpp">Function.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
