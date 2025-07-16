---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smallvectortemplatecommon
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SmallVectorTemplateCommon` Class Template Reference

<p>This is the part of <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase">SmallVectorTemplateBase</a> which does not depend on whether the type T is a POD. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename = void&gt;
class llvm::SmallVectorTemplateCommon&lt;T, typename&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorbase">SmallVectorBase&lt;Size_T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is all the stuff common to all SmallVectors. <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a">SmallVectorTemplateBase&lt;T, true&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase">SmallVectorTemplateBase</a>&lt;TriviallyCopyable = true&gt; - This is where we put method implementations that are designed to work with trivially copyable T's. <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase">SmallVectorTemplateBase&lt;T, bool&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase">SmallVectorTemplateBase</a>&lt;TriviallyCopyable = false&gt; - This is where we put method implementations that are designed to work with non-trivial T's. <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a">SmallVectorTemplateBase&lt;T, true&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase">SmallVectorTemplateBase</a>&lt;TriviallyCopyable = true&gt; - This is where we put method implementations that are designed to work with trivially copyable T's. <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a163fe217cc28bc0ea2d64bf6d18b975e">size_type</a> = size_t</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abaf002eb85f45e089d3bd802d8d1466b">difference_type</a> = ptrdiff_t</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a86711705729196a86bfa1148972f84dd">value_type</a> = T</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9eae7ba1448d9866beca95a042de2e11">iterator</a> = T *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa11b903431c1931920939bac6b5293a2">const_iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a739c383b97286396ce969b521da2f642">const_reverse_iterator</a> = std::reverse_iterator&lt; <a href="#aa11b903431c1931920939bac6b5293a2">const_iterator</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6a3df9bf4da2b9af52a9ad973e6f30c">reverse_iterator</a> = std::reverse_iterator&lt; <a href="#a9eae7ba1448d9866beca95a042de2e11">iterator</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa97e80e39ef9b2c6b624a41adb3595b9">reference</a> = T &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a51868addf898a33aa9f1092b36d965d5">const_reference</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a153684af5f24c9a49de8b4b8f952d3de">pointer</a> = T *</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a89a44a4d396c790185f90246d3c83532">const_pointer</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0d5ed35314b544d00a1de614ba467136">Base</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase">SmallVectorBase</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8c03fc5361775d8b9c9412745110274b">SmallVectorSizeType</a>&lt; T &gt; &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a54ef871baaeb33ef86752839fd32a0bc">SmallVectorTemplateCommon</a> (size_t Size)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa97e80e39ef9b2c6b624a41adb3595b9">reference</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaaa3b341d046538bc32d1fa942c14dd0">operator[]</a> (size_type idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a51868addf898a33aa9f1092b36d965d5">const_reference</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a620fc60422ca6f659337204be4bb9a75">operator[]</a> (size_type idx) const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9eae7ba1448d9866beca95a042de2e11">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a045d250952c0867382a9840ee18fdf">begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa11b903431c1931920939bac6b5293a2">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa79987e1b75d1b81763c867d25574245">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a9eae7ba1448d9866beca95a042de2e11">iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a075e34e98605d0e7c289763a104869ac">end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa11b903431c1931920939bac6b5293a2">const_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0f315bc48d2692cc5a1630f616de9d09">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#af6a3df9bf4da2b9af52a9ad973e6f30c">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a23aab542398091e1fcfd46b6006d64ac">rbegin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a739c383b97286396ce969b521da2f642">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8bbdaa9c9ad9b9f8d9418ba8a7bdc9fd">rbegin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#af6a3df9bf4da2b9af52a9ad973e6f30c">reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad696953257cf1c4e5bd12d02146e7287">rend</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a739c383b97286396ce969b521da2f642">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afcddc80413694e433d45ea9fcd3b583a">rend</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a163fe217cc28bc0ea2d64bf6d18b975e">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab810710f3a8de47c520c1f6055389b30">size_in_bytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a163fe217cc28bc0ea2d64bf6d18b975e">size_type</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac098b1f6b194f100da588329fcba0b5f">max_size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aada0b15b0ff38a96bd9dc9db16ebb88f">capacity_in_bytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a153684af5f24c9a49de8b4b8f952d3de">pointer</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7b68be12c974b6b70bc86062f221a344">data</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pointer to the vector's buffer, even if <a href="#ad9a3c7bc26b130377bbafc170b5f88a2">empty()</a>. <a href="#a7b68be12c974b6b70bc86062f221a344">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a89a44a4d396c790185f90246d3c83532">const_pointer</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd92d4019cf2882e4b429cc864f6b4d1">data</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pointer to the vector's buffer, even if <a href="#ad9a3c7bc26b130377bbafc170b5f88a2">empty()</a>. <a href="#afd92d4019cf2882e4b429cc864f6b4d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa97e80e39ef9b2c6b624a41adb3595b9">reference</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a58dc840fc84420b7f0b773794b8101c1">front</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a51868addf898a33aa9f1092b36d965d5">const_reference</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adda3896b77b1f4cb8ece30c89581b5d7">front</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#aa97e80e39ef9b2c6b624a41adb3595b9">reference</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd9e771a3296c6b24146955754620557">back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a51868addf898a33aa9f1092b36d965d5">const_reference</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad2ff893c472ce3c6f1ab7e2a01a39c5e">back</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa079814a3e516904064e9980a83765c5">capacity</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad9a3c7bc26b130377bbafc170b5f88a2">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c479a8c434377c2b8cb056bdfdfc201">size</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aff209a96323a14068980fd74f1fa53df">getFirstEl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the address of the first element. <a href="#aff209a96323a14068980fd74f1fa53df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a87b74e4076979c8d4ca61387848cf77f">grow_pod</a> (size_t MinSize, size_t TSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a02335466a102901ccd2e0d4a29af8910">isSmall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a smallvector which has not had dynamic memory allocated for it. <a href="#a02335466a102901ccd2e0d4a29af8910">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a65d2c81df9337e5c2d7532c8cdaa29cc">resetToSmall</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Put this vector in a state of being small. <a href="#a65d2c81df9337e5c2d7532c8cdaa29cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a87abc734ab9fa7907c29680075619395">isReferenceToRange</a> (const void *V, const void *First, const void *Last) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if V is an internal reference to the given range. <a href="#a87abc734ab9fa7907c29680075619395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac8019ffabda94935c17ae83f97db769d">isReferenceToStorage</a> (const void *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if V is an internal reference to this vector. <a href="#ac8019ffabda94935c17ae83f97db769d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada19bc367321342a58ed18b2a0e03e96">isRangeInStorage</a> (const void *First, const void *Last) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if First and Last form a valid (possibly empty) range in this vector's storage. <a href="#ada19bc367321342a58ed18b2a0e03e96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a68e0dd48505f955c8681f11b6957afdf">isSafeToReferenceAfterResize</a> (const void *Elt, size_t NewSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true unless Elt will be invalidated by resizing the vector to NewSize. <a href="#a68e0dd48505f955c8681f11b6957afdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aef6ec04f270e752d22af5ce1457f8827">assertSafeToReferenceAfterResize</a> (const void *Elt, size_t NewSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether Elt will be invalidated by resizing the vector to NewSize. <a href="#aef6ec04f270e752d22af5ce1457f8827">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae0e4f4c34cddd8f514efe4f9e0accf09">assertSafeToAdd</a> (const void *Elt, size_t N=1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether Elt will be invalidated by increasing the size of the vector by N. <a href="#ae0e4f4c34cddd8f514efe4f9e0accf09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a709b8b7b7dd6a5ea1f9e8255b1dd5b13">assertSafeToReferenceAfterClear</a> (const T *From, const T *To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether any part of the range will be invalidated by clearing. <a href="#a709b8b7b7dd6a5ea1f9e8255b1dd5b13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af71954476a996d6650da3e6481e705dd">assertSafeToReferenceAfterClear</a> (ItTy, ItTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a60bcdd74c5b92ca311a77068b177286b">assertSafeToAddRange</a> (const T *From, const T *To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether any part of the range will be invalidated by growing. <a href="#a60bcdd74c5b92ca311a77068b177286b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a00e625603e2d7045b8f43e73115fc6b5">assertSafeToAddRange</a> (ItTy, ItTy)</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class U&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4ff60fb0f0d249b4623327ef5976867b">reserveForParamAndGetAddressImpl</a> (U *This, const T &amp;Elt, size_t N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserve enough space to add one element, and return the updated element pointer in case it was a reference to the storage. <a href="#a4ff60fb0f0d249b4623327ef5976867b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This is the part of <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase">SmallVectorTemplateBase</a> which does not depend on whether the type T is a POD.</p>


<p>The extra dummy template argument is used by <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> to avoid unnecessarily requiring T to be complete.</p>


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#aa11b903431c1931920939bac6b5293a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::const_iterator =  const T *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### const\_pointer {#a89a44a4d396c790185f90246d3c83532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::const_pointer =  const T *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### const\_reference {#a51868addf898a33aa9f1092b36d965d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::const_reference =  const T &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### const\_reverse\_iterator {#a739c383b97286396ce969b521da2f642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::const_reverse_iterator =  std::reverse_iterator&lt;const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### difference\_type {#abaf002eb85f45e089d3bd802d8d1466b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::difference_type =  ptrdiff_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### iterator {#a9eae7ba1448d9866beca95a042de2e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::iterator =  T *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### pointer {#a153684af5f24c9a49de8b4b8f952d3de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::pointer =  T *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### reference {#aa97e80e39ef9b2c6b624a41adb3595b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::reference =  T &amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### reverse\_iterator {#af6a3df9bf4da2b9af52a9ad973e6f30c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::reverse_iterator =  std::reverse_iterator&lt;iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### size\_type {#a163fe217cc28bc0ea2d64bf6d18b975e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size_type =  size_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### value\_type {#a86711705729196a86bfa1148972f84dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::value_type =  T</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### Base {#a0d5ed35314b544d00a1de614ba467136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::Base =  SmallVectorBase&lt;SmallVectorSizeType&lt;T&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### SmallVectorTemplateCommon() {#a54ef871baaeb33ef86752839fd32a0bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::SmallVectorTemplateCommon (size_t Size)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#aff209a96323a14068980fd74f1fa53df">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::getFirstEl</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a7b5a03b19133c790a4d6fff66a5d2135">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#a59bf49ac292d1f2d6ab5db4be8d98f3d">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::SmallVectorTemplateBase</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#a2eaa8792fb5065c28ec053372ad5ed99">llvm::SmallVectorTemplateBase&lt; T, true &gt;::SmallVectorTemplateBase</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#aaaa3b341d046538bc32d1fa942c14dd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::operator[] (<a href="#a163fe217cc28bc0ea2d64bf6d18b975e">size_type</a> idx)</td>
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



<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a> and <a href="#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### operator\[\]() {#a620fc60422ca6f659337204be4bb9a75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reference llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::operator[] (<a href="#a163fe217cc28bc0ea2d64bf6d18b975e">size_type</a> idx)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a> and <a href="#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### back() {#acd9e771a3296c6b24146955754620557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back ()</td>
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



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a> and <a href="#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afda2c0f22be043ae42b0ec71b661f565">llvm::MachineInstr::addRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#ac45bdcc05a92d63f2249f476eeb17e77">advanceToNextLeafType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aa29e0988d94a53fecfac0bc63e665d06">analyzeCompressibleUses</a>, <a href="/web-llvm/docs/api/classes/llvm/annotations/#a0ac05d465c3984a3a3fe146902cf3759">llvm::Annotations::Annotations</a>, <a href="/web-llvm/docs/api/classes/llvm/a57chainingconstraint/#af022d8d0187b3df267d3e7754cb4b80b">llvm::A57ChainingConstraint::apply</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a83e6ea9ad14301bc03c55827f0689dc0">ARM64FindSegmentsInFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a85cbdd891f1cd43d6c79f7d68a2caf46">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::BuildBlockList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#af1dbaf0e42fc61259e10468caeb7f4b5">CalcNodeSethiUllmanNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a9e6b15b1005dd460a35359f104cb06fe">canRewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/hipstdpar/hipstdpar-cpp/#aaf9c9bd3b96d08e2f7ad45aa3304aa20">checkIfSupported</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/#a7e6c4318cd8d3ae5bbe88df3d4a58490">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::checkNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ab230432af09554d7dd357c77b0ec3cde">checkOrAndOpImpliedByOther</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/scopedaliasmetadatadeepcloner/#a7bc92ff74f9a62146656fbaf0732c09a">anonymous{InlineFunction.cpp}::ScopedAliasMetadataDeepCloner::clone</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af8092b588e16c93a54d21da99af4814c">combineBVOfConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af366ca9511826f13c9d2e4494be70cd9">combineHorizOpWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aab7406f11829e7505acce1a7d4a7803d">combineX86ShuffleChainWithExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a49694eb08442bb35020b9d8dfad6d7e5">llvm::EHStreamer::computeCallSiteTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#ac7d08af4bb81846173b6186f568fcc8b">llvm::RegBankSelect::computeMapping</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gac3778bafa67cdae223698e5bba785a76">ComputePostOrders</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#acfb266590cdac3ed6480244efcd5899c">llvm::coro::BaseCloner::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/memprofcontextdisambiguation-cpp/#a0282ad8b650e02a78742f8a718f888f4">createFunctionClones</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/region/#a8a8865325da7e23f2f527bb04e1a26d6">llvm::sandboxir::Region::createRegionsFromMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ab34667f1d218ea0b6566dd8f861dfe93">llvm::ScheduleDAGSDNodes::dumpNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a420cc4a7a63b33a52659768b133b5f1b">llvm::EHStreamer::emitExceptionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetwasmstreamer/#acd61544675a1873eab270dd83138d509">llvm::WebAssemblyTargetWasmStreamer::emitLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtooffsettable/#a1878d931b7c5cb9a938690f5a73d75a2">llvm::StringToOffsetTable::EmitStringTableDef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::const_iterator&lt; MemoryLocation &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/macho/#af0902234f18e67e03ce4b3d4d8a6a273">llvm::objcopy::macho::executeObjcopyOnMachOUniversalBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizedag-cpp/#a07a2d3fcc11565312fcc713d6cf38c6f">ExpandBVWithShuffles</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a45b1664e25bf2a7220367462f2580044">ExtractSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/controlflowhub/#a14e3b2ee272be893fb7d474a5530705c">llvm::ControlFlowHub::finalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec1d6e397956b9f5fa62416d0beba785">llvm::FindFunctionBackedges</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#a455039cd6aa5d034220ca078a6b6c30e">firstRealType</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/runtimefunctioninfo/#aa3d7bedeec36948ecc6bae39a75c5da9">anonymous{OpenMPOpt.cpp}::OMPInformationCache::RuntimeFunctionInfo::foreachUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvsupport-cpp/#a23439311200e3762a6d40848ee6b4728">getAllLexicalIndexes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad3e63520dcd2b8f8aa1b2e66e734a575">getBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#a4b3f1bd46bc2567bcc606b0f927b8e97">llvm::RegionInfoBase&lt; Tr &gt;::getCommonRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a814ccfa400b06db7a01885ddcc21196a">llvm::orc::JITDylib::getDFSLinkOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a8cbdb500ba4abd11fd23de4e7a020a2d">llvm::ScheduleDAGSDNodes::getGraphNodeLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a957f4d1425cced530d8488b4bbeaa425">llvm::logicalview::getInnerComponent</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a9169bb55b3ed74fd3be3e062980a2cb7">llvm::SimpleDDGNode::getLastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aca1828635e30f34e4958afeb5541766e">llvm::Intrinsic::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af0de1c3bdac42cb94cca3cce185c3d8a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::growAndEmplaceBack</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#a906c320a7c0ac63b48da21eb00618145">llvm::SmallVectorTemplateBase&lt; T, true &gt;::growAndEmplaceBack</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ab99310a04afb6c28186b1a6428eb75b0">hoistConditionalLoadsStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate/#a3471d30b320c2d011979c2956eb33ab1">anonymous{ARMLowOverheadLoops.cpp}::VPTState::isValid</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a6a12fa96c1212a99f965fcce98aa550a">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::joinVectorElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a8ed485ff9b2526376525b8f792929a31">loadCSE</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#ab12a9d7c65de7b4e040ca540157bf373">anonymous{Trace.cpp}::loadNaiveFormatLog</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a4f5aa6feffe52b80166f0d252cf354cb">llvm::PPCInstrInfo::loadRegFromStackSlotNoUpd</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a7df4bae7dbd152d7a3c399384a110fe8">anonymous{SLPVectorizer.cpp}::HorizontalReduction::matchAssociativeReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6fbf492764a869e2539fbdaf90b259f3">MatchVectorAllEqualTest</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a1dc2ed29bdcb3fedb0639cc8e88a7ecd">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeAssumes</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#a9591638124c46e05817cd8e91a97775d">nextRealType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90896a5c2c14e27297f4fdb0196e24b3">llvm::nonStrictlyPostDominate</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ae577a9371ea38b78cffc39d0ca5f6623">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430isellowering-cpp/#ac48599976d79c3e82a4f1d76f5451482">ParseFunctionArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::const_iterator&lt; MemoryLocation &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ad7ad4b4d9c6fc993c58ff56612f4031b">llvm::AsmPrinter::preprocessXXStructorList</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a6084253c0f3954d2b8479befc2a6be61">llvm::GCOVFunction::propagateCounts</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a4082748189dc3460ea7130cd8d7790b5">llvm::MemoryDependenceResults::removeInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#aa00cbe94721ef6343a9a10ab26af3744">removeRedundantBlockingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#af2c671e8273bc99e266f62322b29a157">replaceAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a635463dc5e146744799163c2f820e51b">llvm::SCEVExpander::replaceCongruentIVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a70727db13f5962a76e5dd0ffd21ecd07">llvm::returnTypeIsEligibleForTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/hipstdparacceleratorcodeselectionpass/#a3c59b50e60a44b5fa3871d0449aa4744">llvm::HipStdParAcceleratorCodeSelectionPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#a98d8aaed2e429cfec371c300cb8244c2">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsoptimizepiccall-cpp-/optimizepiccall/#af8fb60c334fa1c7571459b115762b09e">anonymous{MipsOptimizePICCall.cpp}::OptimizePICCall::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a2bdacd126c6e2d17f0f5a195043c9aa3">selectConstantAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#adc11c5fbec9bf293b000637357da66e4">simplifySwitchOfPowersOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4611905728c0ddaed9f8964ae8b074a2">simplifyWithOpsReplaced</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp/#ab52c873c8169af2a8b1256ace3fe7a7c">sortBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp/#a08fb230c2b93e704a4fd84ef773b6002">sortLocalVars</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a57d1263b6f2a16c765d594a59c2f8130">llvm::CallLowering::splitToValueTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a97de15cd29255b90b2ce510e967340bf">llvm::PPCInstrInfo::storeRegToStackSlotNoUpd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#af6776e5555063ea14c4668a4bcacae27">swapMIOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a96fe0cb15ded58bd1824fa4e3daec680">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a4b538c66a1c14747f4194ba323cb7680">takeInexpensiveLog2</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64framelowering-cpp-/#ab1cb1e5a0ad356f946b7001f0f133cf9">anonymous{AArch64FrameLowering.cpp}::tryMergeAdjacentSTG</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#a72482e46711748fee7ce49e1d66002de">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseGPROperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmparser-cpp-/aarch64asmparser/#aedd4ddd3d36c07298e0d1c8ea2903593">anonymous{AArch64AsmParser.cpp}::AArch64AsmParser::tryParseSVEDataVector</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad4296b2b81379548b300c4676f0d2125">llvm::InstCombinerImpl::tryToSinkInstructionDbgVariableRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a83fe54fc062eda7c1086493dd4155f8a">llvm::DominatorTreeBase&lt; BlockT, false &gt;::updateDFSNumbers</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a066fd5533813e5df6d52cb59fc8afd4e">llvm::dwarf_linker::parallel::DependencyTracker::verifyKeepChain</a>.</p>

</div>
</div>

### back() {#ad2ff893c472ce3c6f1ab7e2a01a39c5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reference llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back ()</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a> and <a href="#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>.</p>

</div>
</div>

### begin() {#a8a045d250952c0867382a9840ee18fdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin ()</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#aeae003355ebd5135c415924b38964abd">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::BeginX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#a9b52ca5c1374c43bc1800b838514562a">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::addDeadBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/spirv/requirementhandler/#a4d5fe47ba4a3c6cbc8d9655eafdb13f2">llvm::SPIRV::RequirementHandler::addExtensions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-cpp/#aaf08c51751e9ec671a84a92af1daab99">addHints</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#abfb093b6e752567e7a893c63309daa66">llvm::logicalview::LVScope::addMissingElements</a>, <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a9e5d9d56a410f0bd58fa931731c9e644">anonymous{IRSymtab.cpp}::Builder::addModule</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetree/#ad1246639c464dee99101df3e7c1c4dc8">llvm::MCPseudoProbeInlineTree::addPseudoProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2713b4a910e8cfdceb4114823a49123d">llvm::InstrProfWriter::addTemporalProfileTraces</a>, <a href="/web-llvm/docs/api/classes/anonymous-minidumpemitter-cpp-/bloballocator/#af08557fb29f0c4129ff2121db66a7e43">anonymous{MinidumpEmitter.cpp}::BlobAllocator::allocateString</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/allocainfo/#aed57a9dd738a483f6ac02904b981c94d">anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::AnalyzeAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a249186f7374b6b9ca0ffd254bb5d79f6">llvm::CCState::AnalyzeArgumentsSecondPass</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a1a1c9931dc5cfff031352bf6a5c7c3ff">llvm::MipsInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a882dcfc2455d525e78a8bbf46863ace2">analyzeExitPHIsForOutputUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#a635fd9f6c5f2092419d60086cb1e0b87">llvm::OpenMPIRBuilder::MapInfosTy::append</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#a08fddb3d382c1c806dee38774e6464d7">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::appendToVectors</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#a568501d2ea6d5786f4981de195297020">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::const_iterator&lt; MemoryLocation &gt;::assign</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a6aed977bf8ca76ee498836d1fe4cedb6">llvm::const_iterator&lt; MemoryLocation &gt;::assignRemote</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsection/#a4e8a9897d0989ba8aa344e0b9804015d">llvm::codeview::DebugInlineeLinesSubsection::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a3e2cbb63f36cb93feaa4efc375d42f2a">llvm::ConstantRangeList::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragedata/#a93d223ca819258ddf3f245338d307856">llvm::coverage::CoverageData::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/mmrametadata/#a843a73428d3d42f8c35fdf583f9472a3">llvm::MMRAMetadata::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#afd03c4734cd0e7de64e4b808b6391f7e">llvm::RecordStreamer::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4ad92667dcad9ad33a52a2e1c505a03a">buildOverlapMapAndRecordDeclares</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a246a48082d0e8d3e7ec999f91b584590">callBufferedPrintfArgPush</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7e7374e59505b56b9bf65507fb90dd40">casesAreContiguous</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#ac41c50a3b85aa5098391b76548f04e3b">checkDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::const_iterator&lt; MemoryLocation &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#aee68454c02cb09e9dc1213c607ee78b9">TransferTracker::clobberMloc</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a0ac5df8f0304981180d602dacb13512c">llvm::LoopVectorizationCostModel::collectValuesToIgnore</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a0130b17dd269a2bf18408bf108d2cf84">llvm::mca::RegisterFile::collectWrites</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62f4b8744e4b75d5371fb9a8a471ca26">llvm::computeAccessFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#a3ae1aa627fae3bd5a88112c59afb492c">llvm::AccelTableBase::computeBucketCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a3d42f23852edcd240ef3a605fdc2bcec">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::concat</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a993771e7c58c60044cbc4c57f689406e">llvm::RandomIRBuilder::connectToSink</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#a7587e2867090ef850ef2bda4ac192e48">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::convertFromOptType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad365e0d64063a233710fdba41a0da57e">llvm::ScalarEvolution::convertSCEVToAddRecWithPredicates</a>, <a href="/web-llvm/docs/api/classes/llvm/intervaltree/#ae65afb93ec69b4bab0c72c8b5ca28f9b">llvm::IntervalTree&lt; LVAddress, LVScope * &gt;::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/irsimilarityidentifier-cpp/#adb57434f498dac697cfa36cd1cb9394c">createCandidatesFromSuffixTree</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#adaccd674ba7dc69d1ce2b88c6155e691">anonymous{MipsAsmParser.cpp}::MipsOperand::CreateRegList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/path-cpp/#a29c8f00b8e38e6ff83c39923934de954">createUniqueEntity</a>, <a href="#a7b68be12c974b6b70bc86062f221a344">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="#afd92d4019cf2882e4b429cc864f6b4d1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/datadependencegraph/#aca5669c8b9a5b58a747bcbd9b9836f2d">llvm::DataDependenceGraph::DataDependenceGraph</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue/#a3e5ffea0fa3c8e006a9bb56d22a0aa12">anonymous{LiveDebugVariables.cpp}::DbgVariableValue::DbgVariableValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/#a0bbf7be621bd7377f3f4a7498010f98a">anonymous{OpenMPOpt.cpp}::OMPInformationCache::declMatchesRTFTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aeabcdff1c388af9ac5a98f1ec4ba2471">deleteDeadBlocksFromLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a13971a178ec8248ecf4b0a903c4db1c6">deleteDeadClonedBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#ab85ec1f9019bc54f0c9962a347b9dc45">determineGPRegsToClear</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ac9ad3a87998e6044d7e0ef77cd6e7d7d">llvm::DWARFContext::dwo_info_section_units</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a86b96eacf90b70918b473cbb3eaf4b5f">llvm::DWARFContext::dwo_types_section_units</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ae8e69a65912ebaef59c5fc4fefab821d">llvm::DWARFContext::dwo_units</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmprinter/#a76034d4641de33d9cf07b5513adfbe60">llvm::MipsAsmPrinter::emitEndOfAsmFile</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a420cc4a7a63b33a52659768b133b5f1b">llvm::EHStreamer::emitExceptionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/unwindopcodeassembler/#ab1cfb912a74d848789c9edb810753f17">llvm::UnwindOpcodeAssembler::EmitRaw</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ab40658c61a66f761473f4b53aa60dd19">llvm::AsmPrinter::emitXXStructorList</a>, <a href="#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#a0f315bc48d2692cc5a1630f616de9d09">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a0935a3e7269909f95115fb8452b1058c">llvm::LegalizerHelper::equalizeVectorShuffleLengths</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aa3787c69a41c14127758c359911180aa">llvm::const_iterator&lt; MemoryLocation &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a687e754bf03f8d135bc899b49db74472">llvm::X86TargetLowering::ExpandInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a47832d6753036cd8ce039993854b3162">llvm::extractInstructionFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a174350306649bc16f97803763bcae8f7">llvm::findArrayDimensions</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a3d50f3f3bb104fb854ac8de326c5bb64">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindAvailableVals</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a4dd660f230b1343ae79f15573d7da3d4">llvm::RegBankSelect::findBestMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aa1382b606ff796c22a7416ba7f6b856b">llvm::cl::ExpansionContext::findConfigFile</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae17b24216f27d8266c87b9fa9a70f533">llvm::SelectionDAGBuilder::FindMergedConditions</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8688fe7e12511bba710a19b4aaf027a1">llvm::RandomIRBuilder::findOrCreateSource</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a37f98e168f7cc70d180aa6bed1625c87">foldGEPChainAsStructAccess</a>, <a href="#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="#adda3896b77b1f4cb8ece30c89581b5d7">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmtypecheck/#a84727116774114016406f20cb5e699ba">llvm::WebAssemblyAsmTypeCheck::funcDecl</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="/web-llvm/docs/api/classes/llvm/prediteratorcache/#aa4997ba4fd2495e1737dcf98457f8419">llvm::PredIteratorCache::get</a>, <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#af99419a971a2b329732cb2a89e6a004b">llvm::RecordRecTy::get</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#ace2ec29a8f2231556c7f8a20929cc138">llvm::opt::ArgList::getAllArgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a63bdece47c81d3a6e63de19cb824b788">llvm::opt::Arg::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#aa12ce67d21274bae7db762b1e5728bf6">llvm::SampleContextTracker::getContextString</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#ad782fe84b36a1c379ac9f1ac367706e1">llvm::RegsForValue::getCopyFromRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a9e635b2c582b6500e2c79faf06360ca2">llvm::GenericCycle&lt; ContextT &gt;::getExitBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#ade1da0b29f5e3cb310ac591da00699c3">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/machineinstrexpressiontrait/#a3344d356ddabbe21340a4b078300a789">llvm::MachineInstrExpressionTrait::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobe/#ae65fd4d6ca6b5107072abefc811a63b0">llvm::MCDecodedPseudoProbe::getInlineContext</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a724d32daf4f554526f15b36eab12e129">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a138bc82a9943aa3008ab86bec2d2c91a">getOrCreateFrameHelper</a>, <a href="/web-llvm/docs/api/structs/llvm/hvxselector/#ae954fcbf0e9b2fe89cfa9d21b931b063">llvm::HvxSelector::getPerfectCompletions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7144f12bd93229efcf87a052ab80d5e6">getSalvageOpsForGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#ae1be3a2fc5dfa3281d32b6fb4e4ea6dd">getSchedRegions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debuginfosupport-cpp-/#af708da9529b70292b2712cd7ed80d14e">anonymous{DebugInfoSupport.cpp}::getSectionData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14a462c7b5d011363ae9c50a15595609">llvm::GetShadowBytesAfterScope</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1e2ab02b19200a9749a3a7f67d7e7cdb">llvm::RISCVTTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a671590a0e2685f1038479bd7c00b920a">llvm::X86TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84a0cf35704ac6286dc4f1395a6893e3">llvm::getShuffleReduction</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult/#a4bf35524898c34b917e813177d64d735">llvm::gsym::LookupResult::getSourceFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp/#a509ce85b468f4da99d1111c7498e2557">getStableFunctionEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/object/minidumpfile/#aa7de35b1ad345a06e1d7c38dc51d94fb">llvm::object::MinidumpFile::getString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a70d3e07bad78e3a1d2ba86aa871b9501">llvm::SelectionDAG::getTokenFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#ae12b387e4a14699e4f1229bf9d3d0905">llvm::DWARFUnitVector::getUnitForIndexEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#a887387b3f904d16301c7dae667aaa42b">llvm::DWARFUnitVector::getUnitForOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#ae3341aa2a4a16c49b2be04002018a1a6">getVectorDeinterleaveFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a8adf44ad04562ff150b0e8e352a38d46">llvm::VFABI::getVectorVariantNames</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ab6cf8f5418ae17302373eb658de2c4a5">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::growAndAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#aa671e144c1a4aa0196cf9333fc17054d">llvm::SmallVectorTemplateBase&lt; T, true &gt;::growAndAssign</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#ac3fdb189d1625b937b2aedcf1de64f09">llvm::IRSimilarity::IRInstructionData::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp/#a2e84df1cbf9375ee66f23c5ca414c638">hashValueMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6beebf86835d6582b0550cd7731ee9">llvm::SDNode::hasPredecessorHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a4cda46bdec29ace64dfd3dff3e55bbf3">hasSupportedLoopDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ac511031ed298b7bbcc65d432ffe88912">llvm::DWARFContext::info_section_units</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a95851c48d68c2406ef12a7cca9c65f76">initializeUniqueCases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa730b58924baf8f35394c2e5a0bb3714">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a59fd5e59ca0c03b061035a6c9de2b39c">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a520e903dce9cfbdd0d1073fe447ce52e">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a1109f77d1d986c8e1e04f5da7ed197f9">llvm::ConstantRangeList::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a864a2ad11bbf83cf2b910e43d461cd02">insertParsePoints</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a78ca5c76a5ac76f5ad51ce5ced36fbb8">llvm::CallLowering::insertSRetIncomingArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aa75e387193fd10b9055d76076288f1ad">instCombineConvertFromSVBool</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a16658fce14f4b2888f76f0972d239139">isFreeConcat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab0469afc3caef8616d4b1c7501cba1b8">isHorizontalBinOp</a>, <a href="#ada19bc367321342a58ed18b2a0e03e96">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isRangeInStorage</a>, <a href="#ac8019ffabda94935c17ae83f97db769d">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isReferenceToStorage</a>, <a href="#a68e0dd48505f955c8681f11b6957afdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isSafeToReferenceAfterResize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9855e2b319987248786fd81ba1d8c35d">isUpperSubvectorUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#adef158856b4fece74dc557d8c3212320">isVECTOR_SHUFFLE_SPLATI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a670137fe83c1213c3c2e82b8144e9af3">isWideDUPMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalopt-cpp-/llvmused/#ab0be9add964b354b741b4881efc2b40e">anonymous{GlobalOpt.cpp}::LLVMUsed::LLVMUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemapping/#a91d6d8d5af0b8ba44a006860ef830113">llvm::coverage::CoverageMapping::load</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#aa40f4913df15aca03301144b7f1673df">llvm::MipsSEInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#a304b877a673788ae4edd0e8f5fa1d5d8">TransferTracker::loadInlocs</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#af64654b3c46ec3154963aed1dbb016d2">TransferTracker::loadVarInloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6b80a10cdcf5d9289539034640364a6a">LowerInterruptReturn</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac7304188de3005e0d0f0a62cbff5ad31">lowerV16I8Shuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a96929c573ae5a98213a4d8c25554e53f">lowerV8I16GeneralSingleInputShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ac33e82a131d1fbb45282af6f71f1bd61">lowerVECTOR_SHUFFLE_ILVEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#afeb969a79018bac52d21bcfb43705342">lowerVECTOR_SHUFFLE_ILVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aab2c6ae0788500f10a4e102ab9d31380">lowerVECTOR_SHUFFLE_ILVOD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a294c52ead479abd3003207596dee2f38">lowerVECTOR_SHUFFLE_ILVR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aa1b6fff8c6938823f859ff9d8f17a823">lowerVECTOR_SHUFFLE_PCKEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a603a3b428c41e07bb96d88e57a7f24e5">lowerVECTOR_SHUFFLE_PCKOD</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#a6abf8a645bd24dfb42085db9672ac39a">shuffles::mask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a079f719b6af4bba305e041821a1e3da0">matchScalarReduction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain/#a939be2486e7faed5e6e1fd9d02311273">anonymous{MachineBlockPlacement.cpp}::BlockChain::merge</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a1dc2ed29bdcb3fedb0639cc8e88a7ecd">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeAssumes</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a2711d3bc7c6c769a8f34c7fc3937169d">llvm::Instruction::mergeDIAssignID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a7fae42d42333d13848fe4d545dc50049">mergeDILocations</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a6277ecb456c87743b292a5dd69542a4e">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a627f84abfceb75ffd72119423d0147a4">mergeVectorRegsToResultRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#a06264674191b53ea377acb0fbf98c80b">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::moveElementsForGrow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#ad08f0dd526b3f602ccb0f0d39832ae08">llvm::sys::unicode::nameToCodepoint</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a8cd858c6644228cba53bd8631155b4a2">llvm::DWARFContext::normal_units</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a1b51573bc0b0e62d37537759a24a44c3">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyFreeingObject</a>, <a href="/web-llvm/docs/api/structs/llvm/sampleprof/samplecontextframehash/#a2b24a4a6c5c99e60c70e9dc95c945e9b">llvm::sampleprof::SampleContextFrameHash::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aa225cb6d40046134e5dc8fb135009568">llvm::const_iterator&lt; MemoryLocation &gt;::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#acd1bf4a3cc2b247cdeac15790a9e6a1e">llvm::SmallVector&lt; BitWord &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad39bccc86684b3407edcd580b5a38143">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#adfc4e95670f6dd96a86182e51411d47b">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a400590dcfcda901d773ddb593591bf9d">llvm::const_iterator&lt; MemoryLocation &gt;::operator==</a>, <a href="#aaaa3b341d046538bc32d1fa942c14dd0">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::operator[]</a>, <a href="#a620fc60422ca6f659337204be4bb9a75">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::operator[]</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#afd07d19c7174c06cd7c7415f63596839">llvm::slpvectorizer::BoUpSLP::optimizeGatherSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#adee8390bf727c3086a7b864de6c6913e">llvm::X86FrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a1ac412f2e4cc981d3b9d3f6cf6d5988a">anonymous{MachineOutliner.cpp}::MachineOutliner::outline</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#aec5e1563ca339dbf7905cf069c364e39">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/spirvextensionsparser/#a9c59e739efd5cf76e15f932543c272e3">llvm::SPIRVExtensionsParser::parse</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0048548b4f1cc9455cf3af293d2b52bf">performCONCAT_VECTORSCombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c87701e16414a07520790dfd88c52aa">anonymous{ARMAsmParser.cpp}::ARMOperand::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcov-cpp-/context/#af21fe9969dd2d37f96a144b9d7376ffa">anonymous{GCOV.cpp}::Context::print</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a873cd38481c3ed6a7e21bc016ec10ae2">llvm::logicalview::LVBinaryReader::processLines</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a65eee5509cce98dcc69693ea13bb9220">llvm::logicalview::LVBinaryReader::processLines</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopinterchange-cpp-/loopinterchange/#a2a08cef5ef885ecb702cabcedb86c95e">anonymous{LoopInterchange.cpp}::LoopInterchange::processLoopList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a25241903dcf363fdf53dc9e8f1037e7a">llvm::sys::fs::readNativeFileToEOF</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#aa386dbcb508e02e5910438040aed2cac">llvm::BinaryStreamReader::readSLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab9f41a80bcb29a219eff47dfac886cce">llvm::BinaryStreamReader::readULEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8fb04904ff931fa4871c8b9601f2a04">llvm::readWideAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a15993d541998ac409f0fe09abfef6fe8">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::RecordMatchingPHIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#ab28699e21ef7b0aa06794bee56959a32">anonymous{CommandLine.cpp}::CommandLineParser::removeOption</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5b064b03163c5f9304d4b702da5fa1e4">RemovePreallocated</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ad959466c7f8b886a2caa4967c46d48db">removeRedundantDbgLocsUsingBackwardScan</a>, <a href="#ad696953257cf1c4e5bd12d02146e7287">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rend</a>, <a href="#afcddc80413694e433d45ea9fcd3b583a">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rend</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a2eb73a15ea2a5105bd2cec95863d7113">llvm::slpvectorizer::BoUpSLP::reorderBottomToTop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a633db91afb11db086004de9e3eb37217">reorderOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4a3e80130d3f25468190ba343064b37e">reorderReuses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp/#aeaf0abeac6c9f6e4698dd90c080611fa">reorderSubVector</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a1bc3cc02c0dc6dcb9ad315b7755475e7">llvm::slpvectorizer::BoUpSLP::reorderTopToBottom</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a6300c8f1d33302d372c953398dd5f18c">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithNamedStructOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a8a6fce329f29e0ec830e61c629b70739">resolveSources</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a3fc78aa19b9e30af7cb534f1a58e22de">llvm::AArch64FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a26c8cba96e72f333e829e607938ce893">llvm::CCState::resultsCompatible</a>, <a href="/web-llvm/docs/api/classes/anonymous-loadstorevectorizer-cpp-/vectorizer/#afdc19a1fe655b43b92647431e2e8ec8a">anonymous{LoadStoreVectorizer.cpp}::Vectorizer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionspecializer/#a27893e2167969de71fd88771382a93ad">llvm::FunctionSpecializer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#a98d8aaed2e429cfec371c300cb8244c2">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mergefunctionspass/#a9a54c5c31e75d72fccddee99422e6eb3">llvm::MergeFunctionsPass::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a9208ba235fd513181d17277332f9bde2">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectLoadLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a87024e3cd8e787fed3e17063882847aa">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPostLoadLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#af52e44fa59b89ae4c520c10a6de3eb4d">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectPostStoreLane</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a5984d3a5a8969d8d3238c4eaea8e4835">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectStoreLane</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad272ce4631595e235e560baf59dc1ffd">llvm::setProfMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aaf604b7b4ff087fce0b71852f5ddefbe">setUsedInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a0f09c6db065cba05fa4431f921a73715">SimplifyValuePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a52b8b307321627e612e77041260ece84">sink</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a0a5c60e5cebd520f95b9813fd9807016">llvm::InnerLoopVectorizer::sinkScalarOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa725413bc28036ce9c795a24503f654b">llvm::coro::sinkSpillUsesAfterCoroBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/arraylist/#adf19460a3c702d261e7ffe25d77cabbb">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::sort</a>, <a href="/web-llvm/docs/api/classes/llvm/intervaltree/#ac8662d075b7aefa245f4557a80bf1a24">llvm::IntervalTree&lt; LVAddress, LVScope * &gt;::sortIntervals</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a0bb855d418108ea53140e71d7b35a2cd">splitPredecessorsOfLoopExit</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a603517a82c194cc3daa912831dff244a">llvm::Regex::sub</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a96fe0cb15ded58bd1824fa4e3daec680">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a36955f44027693881a174e8d3f1d3854">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::SwitchLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#aa653aeaa776bdaa3656d01a2198d99fd">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::takeAllocationForGrow</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loopstrengthreduce-cpp-/#a391c5efa7f6eb049718971aeeb9b71d5">anonymous{LoopStrengthReduce.cpp}::ToDwarfOpIter</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#abf0867b6082e1e0408b1b5d8301f27e2">llvm::object::ELFFile&lt; ELFT &gt;::toMappedAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#abbfb15ef66003a1f34d28fa4fb90ac93">toStringAPFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aae26f659b722d1d053b93b5f1735f52f">llvm::const_iterator&lt; MemoryLocation &gt;::truncate</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/preloadkernelarginfo/#a7a5253091344c2d534f5afd16941e25d">anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::tryAllocImplicitArgPreloadSGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#a789d043cecadfc51338fee7f9683324a">tryFoldCommutativeMath</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#aa3f0516b6857ed87b9547d6f65dd6897">tryFoldCommutativeMathWithArgInBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#aaa2373cd29671119d8d4c12077c4f9da">tryFoldConstants</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#a067186aa899ad496af6a360ce9515eee">tryFoldNoOpMath</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a1bc5915736e0e4317a049e55fa502667">llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ac48731694e324e56e35cb2b4f20345d0">tryToVectorizeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/mcdc/tvidxbuilder/#a85f4860524d04ca3d92dae7f5b1a9fba">llvm::coverage::mcdc::TVIdxBuilder::TVIdxBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a9582935f8e1daa71195a6c76ce4f6c20">llvm::DWARFContext::types_section_units</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a8fcc33897ff2ea4ebc874792c49497ef">llvm::BlockFrequencyInfoImplBase::updateLoopWithIrreducible</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#ae8bfab8841d5d8482833437e8b4309b9">shuffles::vdealvdd</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a4cc24eca5caee29bd57f43e84c285ee3">llvm::GenericCycle&lt; ContextT &gt;::verifyCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a6dcb5e3d63691e83e0fdc0d67148077a">llvm::MemorySSA::verifyOrderingDominationAndDefUses</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a2337e506453c5ed1ec20ebabbafbc014">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a9c48163b33da5da66af7a1e8f4deb637">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7af99fa2202fcc7db245865dd1bcec1f">llvm::InstCombinerImpl::visitLandingPadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#aeb3015db092e8e97f7a585096688b6cf">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::vresize</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#a05231a6703f721a7938ce95de41743f1">shuffles::vshuffvdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0096360a382602b21e0e980fb8069d52">llvm::dxil::WriteDXILToFile</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#a548541a1080f84a4dbde718332e55ba5">llvm::SmallVector&lt; BitWord &gt;::~SmallVector</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#af56a778d4fe0d873fcc879c78fb733a6">llvm::const_iterator&lt; MemoryLocation &gt;::~SmallVectorImpl</a>.</p>

</div>
</div>

### begin() {#aa79987e1b75d1b81763c867d25574245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin ()</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#aeae003355ebd5135c415924b38964abd">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::BeginX</a>.</p>

</div>
</div>

### capacity() {#aa079814a3e516904064e9980a83765c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::capacity ()</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::const_iterator&lt; MemoryLocation &gt;::assign</a>, <a href="#aada0b15b0ff38a96bd9dc9db16ebb88f">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::capacity_in_bytes</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::const_iterator&lt; MemoryLocation &gt;::emplace_back</a>, <a href="#a68e0dd48505f955c8681f11b6957afdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isSafeToReferenceAfterResize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad39bccc86684b3407edcd580b5a38143">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#adfc4e95670f6dd96a86182e51411d47b">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::const_iterator&lt; MemoryLocation &gt;::reserve</a> and <a href="#a4ff60fb0f0d249b4623327ef5976867b">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::reserveForParamAndGetAddressImpl</a>.</p>

</div>
</div>

### capacity\_in\_bytes() {#aada0b15b0ff38a96bd9dc9db16ebb88f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::capacity_in_bytes ()</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#aa079814a3e516904064e9980a83765c5">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::capacity</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### data() {#a7b68be12c974b6b70bc86062f221a344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data ()</td>
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

<p>Return a pointer to the vector's buffer, even if <a href="#ad9a3c7bc26b130377bbafc170b5f88a2">empty()</a>.</p>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Reference <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3d3da964f7eb14ef2eabf0c4a08ba5">llvm::c_str</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#acb572d27661acd51c80b1bca18cd1ee3">llvm::orc::cloneToNewContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectortypes-cpp/#addec051710bc0afc4147859062eb31a4">CollectOpsToWiden</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diasession/#a2219741a985be587beb5e75fee1417f7">llvm::pdb::DIASession::createFromExe</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diasession/#a7861193fc9b9776bd882bc12d58cb356">llvm::pdb::DIASession::createFromPdb</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a232c76d4c06ded6c02597dfae877aca3">emitExternalFile</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7d36cf8691cdd5195631e8bbd8d38fc2">llvm::MCStreamer::emitIntValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a90b631351c27f8d64f1788ec334d7b4c">llvm::COFF::encodeSectionName</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diarawsymbol/#aa5f5eb1b85c8ce026a2ca6afda61edb4">llvm::pdb::DIARawSymbol::findChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diarawsymbol/#a33a52e12c8197df34d4de144bc4d3547">llvm::pdb::DIARawSymbol::findChildrenByAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diarawsymbol/#abed32fb835b2160ddaf29fe49183a0fd">llvm::pdb::DIARawSymbol::findChildrenByRVA</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diarawsymbol/#a08a205d187ffe3cdb4d70f30508b61cb">llvm::pdb::DIARawSymbol::findChildrenByVA</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a293fb71d9772916004e2e65674d0bed0">GenerateFixedLengthSVETBL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a07cdd12114b2452d5dc26ab23460bb60">GenerateTBL</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elfnixplatform-cpp-/#ae8fb1e7d144d58bebdc065615673d9f4">anonymous{ELFNixPlatform.cpp}::getArgDataBufferType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a9205d579e79767f52c5af57c94d2be74">llvm::omp::getCompoundConstruct</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/diarawsymbol/#ae6794a3baa4e6411c629bd08f2c718c8">llvm::pdb::DIARawSymbol::getDataBytes</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizedag-cpp-/selectiondaglegalize/#a9440e31a32ea6624c0b77e7e45223be9">anonymous{LegalizeDAG.cpp}::SelectionDAGLegalize::LegalizeOp</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga4af207d5a28d38c765a7f33d658df2a5">LLVMOrcExecutionSessionLookup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a96929c573ae5a98213a4d8c25554e53f">lowerV8I16GeneralSingleInputShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04b59de220180462277a0d8d7f146b0e">lowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#ae787b71e8d775a2b662d04e913489d8d">llvm::Regex::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a53577fb6bbcd0c6556b4f8f0c71089cb">matchUnaryPermuteShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ab071132a634a15df871b6901c1375c90">llvm::sys::path::native</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3002d96da0f9030af718fbe2961b913f">llvm::ReadByteArrayFromGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aeffc1bb4ebe64a8ad3478e1253683847">llvm::LiveIntervals::splitSeparateComponents</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a5d968bc337af0be1f18813553a046df6">llvm::Twine::toNullTerminatedStringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#ac521760e9a45f304a4cbe46ed4fff845">llvm::Twine::toStringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdxbc/signature/#a608616d2779ddc0d1ca2669b17119ba2">llvm::mcdxbc::Signature::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexsectionwriter/#ac2982fe0f31deef1fc4d20346a6e3daf">llvm::objcopy::elf::IHexSectionWriter::writeData</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#aaf1d0c4d37d55950252509e0b0c84501">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeSectionData</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodewriter/#aaaca861df948bd93da0afb6891e9d662">llvm::BitcodeWriter::writeSymtab</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#a9f26efe564d8f7f1afb5f3033156d58d">writeUniversalArchsToStream</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a383a9c6d7b337512fa69de542cec0375">llvm::sampleprof::SampleProfileWriter::writeWithSizeLimitInternal</a>.</p>

</div>
</div>

### data() {#afd92d4019cf2882e4b429cc864f6b4d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_pointer llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::data ()</td>
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

<p>Return a pointer to the vector's buffer, even if <a href="#ad9a3c7bc26b130377bbafc170b5f88a2">empty()</a>.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Reference <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>.</p>

</div>
</div>

### empty() {#ad9a3c7bc26b130377bbafc170b5f88a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::empty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ab7c7120f48a91e5972592b16ee7fd81b">llvm::PMDataManager::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#af408665da3f00cec50ecb935ad72e689">addAllGlobalValueUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#aaf0f291dde691ba9d8a7667963f6c7fc">addBlockAndPredsToSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a0faf2520b671c3cb14b4f291c873cb88">addBoundsChecking</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#a9b52ca5c1374c43bc1800b838514562a">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::addDeadBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a0f682f69a2b53113b0df4e2b9a7e3aae">anonymous{ConstraintElimination.cpp}::State::addInfoFor</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetree/#ad1246639c464dee99101df3e7c1c4dc8">llvm::MCPseudoProbeInlineTree::addPseudoProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a538047e21679cd2bf4cfd1e73fe022aa">addRange</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afda2c0f22be043ae42b0ec71b661f565">llvm::MachineInstr::addRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a086f090ebea74999eafa96dc69047a67">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addTemplateParamNames</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a27e1c2d39aa2a1a6763bfa05cbcb169a">allPathsGoThroughCold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#acd4d68acd948bdbd54c4e69f3bb5a835">allUsersAreInFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8e68884ca018dde6dfadf535637290d0">allUsesOfLoadAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a26f6a2c21d213fbcbe99a2c09d88a2c4">allUsesOfLoadedValueWillTrapIfNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#aa863110e9781bd6febba48dd5b5af5ab">allZeroIndices</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-alwaysinliner-cpp-/#af5bb12426b6361914b816365eee4b4fd">anonymous{AlwaysInliner.cpp}::AlwaysInlineImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a492be44ddc8ccbf85c4ef650b6111868">llvm::LanaiInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#af8967731195e767bf313308f20b640de">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::analyzeVGPRToSGPRCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/annotations/#a0ac05d465c3984a3a3fe146902cf3759">llvm::Annotations::Annotations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a253deb4046b74b2df2b5acd762b95d58">llvm::appendReversedLoopsToWorklist</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#a08fddb3d382c1c806dee38774e6464d7">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::appendToVectors</a>, <a href="/web-llvm/docs/api/classes/llvm/a57chainingconstraint/#af022d8d0187b3df267d3e7754cb4b80b">llvm::A57ChainingConstraint::apply</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afd96526160e781989c15d6879ad1f9f1">llvm::AMDGPURegisterBankInfo::applyMappingSMULU64</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ad89ca302de455d3971f751c8d1a5bd58">llvm::MemorySSAUpdater::applyUpdates</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a8b1432c767e3cc50f7cb6900285d003f">llvm::AMDGPUCallLowering::areCalleeOutgoingArgsTailCallable</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a6553ca5670588f279c72f84d46b05033">llvm::RegBankSelect::assignInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a6b0bf1d2a5eba4af2825113954bb846f">llvm::RegBankSelect::assignRegisterBanks</a>, <a href="#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="#ad2ff893c472ce3c6f1ab7e2a01a39c5e">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstackradixtreebuilder/#a05db798ae8ae11328fce938cd0d012f9">llvm::memprof::CallStackRadixTreeBuilder&lt; FrameIdTy &gt;::build</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a85cbdd891f1cd43d6c79f7d68a2caf46">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::BuildBlockList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/csemirbuilder/#a9c2e15b867893ec15cb49acfbb38e542">llvm::CSEMIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af5d3388e53cb2767927dba7c18c64a00">llvm::CombinerHelper::buildSDivUsingMul</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#af1dbaf0e42fc61259e10468caeb7f4b5">CalcNodeSethiUllmanNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a714e5448566006046f747d9ec4df8241">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::calculate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afcc6ddcd882a86a3d6028e2530b4d4cc">llvm::calculateClrEHStateNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bf41f2408094f54097744991c82336a">llvm::calculateCXXStateForAsynchEH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b49442c1c01ddc388c51d7599c0f876">llvm::calculateSEHStateForAsynchEH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#a3ee1760c4d2815d8dc3fad889e2d8953">callIsStructReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#a60735e0d022845d03d123916bb48e1e8">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::canCheckPtrAtRT</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroelide-cpp-/coroidelider/#adb122f608fe469bd24f486598a4bc881">anonymous{CoroElide.cpp}::CoroIdElider::canCoroBeginEscape</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aa10cee1a6cc1fbb381e3dab0c92c4cb2">canFoldStoreIntoLibCallOutputPointers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a22244f1af2bc880ef42bfd77068ce13a">canonicalizePHIOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a596a49623f77050eb85eb8f12b88de3e">canReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aea73058623ab7225aabe7a95068784a4">llvm::ScalarEvolution::canReuseInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a9e6b15b1005dd460a35359f104cb06fe">canRewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#a20d58a0069048b80461676a4132ad1d4">canRotateDeoptimizingLatchExit</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a8fffb36a3e1523ff3d26521f27c02df8">llvm::TailDuplicator::canTailDuplicate</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a54bef4de515c1876b876bac86b81975c">CC_LoongArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb12d99088ce4e78fe29e5306ab42c5c">llvm::CC_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3624679803f9a11d8362aca440f744a6">llvm::CC_SystemZ_I128Indirect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a41dd5c8db0f0898d613b138097515474">CC_X86_32_MCUInReg</a>, <a href="/web-llvm/docs/api/structs/llvm/patternmatch/undef-match/#aa0fa56355fdd655db9e9ef53dcde99d0">llvm::PatternMatch::undef_match::check</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryssa-cpp/#a930e3a524f031bdb14fe281e4eff4219">checkClobberSanity</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#abbea65eed8b9b7cd07f0b8eef53df6f5">llvm::Attributor::checkForAllUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/hipstdpar/hipstdpar-cpp/#aaf9c9bd3b96d08e2f7ad45aa3304aa20">checkIfSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af1fba45879c49d4839b11ec30afd7532">checkMixedPrecision</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/#a7e6c4318cd8d3ae5bbe88df3d4a58490">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::checkNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af9b65d81d95d19757080cfae034e3d7e">checkVectorTypesForPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ac3cf098d54027ac28278b060376bdcbd">CleanupConstantGlobalUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adc803f628b45e58e3de84b46dd0b7d83">CleanupPointerRootUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a03cdd58b24dc91b4e3819e218a399cbf">cleanupSinglePredPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/bdce-cpp/#a54ab652f375db02ea7894a5f9a512d15">clearAssumptionsOfUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af747cc9f106d837a03d08bd395ede216">cloneLoopNest</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a889b75e55af23f854f7f597b0e912b98">codegen</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#ab0236d3f5f443260abf1ccfb1e5cc5a6">anonymous{FunctionAttrs.cpp}::collectArgumentUsesPerBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#a218bc49443ef1f05fc8074d872d41fcd">llvm::OpenMPIRBuilder::OutlineInfo::collectBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#a586a0928ddd8c387ebb2032e9f61e55b">collectCastInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#a86959c09e02e571589af525c983cdf4e">collectEHScopeMembers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62219a4c97e27d64593245e4e9187cd1">llvm::collectEphemeralRecipesForVPlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a1061b839196c8068b89d05aced41de29">collectHomogenousInstGraphLoopInvariants</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a12d2850f420726c4acb262b626e95b7d">llvm::LoopVectorizationCostModel::collectInLoopReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#af91d9f50a649787e882b7383c7e997d3">llvm::DDGNode::collectInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#aff1b71fb51fbfeefc8cb3c92021ee0de">collectLeaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4062c17e282cb2667cf0d52150c67fea">collectSRATypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#a0f2532bb6e482a8f04b68585b8cfc032">collectTransitivePredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a7737deb6a166cd21dc8465bb48f110b2">collectUnswitchCandidates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a3a97fed79c86bf242b0f090e1cb2e6">llvm::colorEHFunclets</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af366ca9511826f13c9d2e4494be70cd9">combineHorizOpWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3ff4156c9862c64e6d354f5413c3da5e">combineOp_VLToVWOp_VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a027102ec674270eecc2a1a6ec8588e44">combineOrCmpEqZeroToCtlzSrl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4bfc9dfb6bf7ab5af8b76e28d94162c2">combineRedundantDWordShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7af5f6d50f3be3168a1d91d056c78c8c">combineToHorizontalAddSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aab7406f11829e7505acce1a7d4a7803d">combineX86ShuffleChainWithExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a4ca10cc5976994ee1c01be4b019c1ee6">llvm::FunctionComparator::compare</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#ab79e380b2ff4d4653bc9a766e1a59220">anonymous{MachineOutliner.cpp}::MachineOutliner::computeAndPublishHashSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a46b279956ad150f9e6ff57d03e1fe539">computeBlocksDominatingExits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b5d72a4e8c39c8d0ea81cb9c547bc8c">llvm::computeDeadSymbolsAndUpdateIndirectCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>, <a href="/web-llvm/docs/api/classes/moduleimportsmanager/#af806f9d842ec97d31bd9550eb338f678">ModuleImportsManager::computeImportForModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdaterbulk-cpp/#ab90f4a46f63bfddff132d20866be2da2">ComputeLiveInBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7b6ae12af3578f7a20ccc11a4458f9f">llvm::computeMinimumValueSizes</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gac3778bafa67cdae223698e5bba785a76">ComputePostOrders</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#ade155905429b0a259a1030f418c04ad9">computeUnlikelySuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a23d6b914952799027040a351f501a0ad">llvm::SMSchedule::computeUnpipelineableNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/constantaggrkeytype/#ae8292a7cecde5084390268d22e3d522e">llvm::ConstantAggrKeyType&lt; ConstantArray &gt;::ConstantAggrKeyType</a>, <a href="/web-llvm/docs/api/structs/llvm/constantexprkeytype/#a35a51401bc41aa572a56b74c20a89409">llvm::ConstantExprKeyType::ConstantExprKeyType</a>, <a href="/web-llvm/docs/api/structs/llvm/constantptrauthkeytype/#a44ad5fe712f97b8c81a668457580928c">llvm::ConstantPtrAuthKeyType::ConstantPtrAuthKeyType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp/#a8bba5860a29dd4e3f3bca8f97b4e9199">ConstHasGlobalValuePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervalcalc/#af5198110c0058e3d60524eecf500ee51">llvm::LiveIntervalCalc::constructMainRangeFromSubranges</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a52d249cc9856fb556e92d5a1b03e5e80">llvm::InstCombinerImpl::convertOrOfShiftsToFunnelShift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a8a59001c151594d4ff93a12b10c8368f">llvm::MachO::convertToInterfaceFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a944b77cb28ad77cdf28380c4453f8d02">convertToParamAS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad23b52a299ca563f6e6a6c6cece54dcc">llvm::convertUTF8ToUTF16String</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a7ccbc2b7c2fc5cf4c9dbb648570bcf01">llvm::SelectionDAG::copyExtraInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#a9c4196edca24d644ff96e55945abd207">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::createMemoryDependencyEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a6022d366369fcd539dadfaefc80927db">llvm::MDBuilder::createPCSections</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae54a581ccf494afe52ae45af317bbd58">llvm::OpenMPIRBuilder::createTargetData</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ac10429a8c82694552d49e1aba0b85491">DbgVariableRecordsRemoveRedundantDbgInstrsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a961e2695793920fc477be3d95e20babe">DbgVariableRecordsRemoveRedundantDbgInstrsUsingForwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#aa1970a96b57d122e4bb765d0f82e96e6">DbgVariableRecordsRemoveUndefDbgAssignsFromEntryBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a7fbae83b06276268455de0368194f94a">defaultComponentBroadcast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#acac0a0a393ce41aadc29e623549b6bfa">llvm::at::deleteAssignmentMarkers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aeabcdff1c388af9ac5a98f1ec4ba2471">deleteDeadBlocksFromLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a32e5e2e67b52bcd45fef4487f664f9ec">anonymous{DeadStoreElimination.cpp}::DSEState::deleteDeadInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc378caf5071493fe3b2b98bf224be7c">llvm::delinearize</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a878a2b864e18e3d074d75b426ea7912d">llvm::HexagonFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp/#ab036d04a80df6b9a9f3dbf42a3884bb8">dropIntrinsicWithUnknownMetadataArgument</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa0f143b8d4693978b984f0639c90e508">llvm::VPlanTransforms::dropPoisonGeneratingRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ab34667f1d218ea0b6566dd8f861dfe93">llvm::ScheduleDAGSDNodes::dumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a326b69bb87197af5c7e9398da090d754">llvm::SMSchedule::earliestCycleInChain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#add47e6d974ce584ea3fa3fc80ee34259">llvm::LiveRangeEdit::eliminateDeadDefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a83b0a34d940365e97b9a531c1f13f3b9">eliminateDeadSwitchCases</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a311a80924f5342813ae67daa5e5ff444">eliminateSwiftError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#ad04238a3223242e0565e4f98df0461a6">llvm::SIFrameLowering::emitCSRSpillRestores</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a84c4c1518f3593f9c1d0b10f8364ebb8">llvm::SIFrameLowering::emitCSRSpillStores</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmprinter-cpp-/riscvasmprinter/#ada43bee484c2300200c9ab0884003563">anonymous{RISCVAsmPrinter.cpp}::RISCVAsmPrinter::emitDirectiveOptionArch</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a232c76d4c06ded6c02597dfae877aca3">emitExternalFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aa216c2cbc8d9610dc20db065aca671d3">llvm::LoopVectorizationPlanner::emitInvalidCostRemarks</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a88fd52c520cef6a03af97c37c308ae78">LiveDebugValues::MLocTracker::emitLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetwasmstreamer/#acd61544675a1873eab270dd83138d509">llvm::WebAssemblyTargetWasmStreamer::emitLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a013467bb98e0c35a48763e22de49cc75">llvm::WebAssemblyAsmPrinter::EmitProducerInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a66752f73169dfa9247fe4f788c08e49e">llvm::dwarf_linker::classic::DwarfStreamer::emitStringOffsets</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a9702d30c99a5459e9565631adf1fdf1b">emitTaskDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3bb33831dbcaa836f630ed1dc986b5c2">llvm::OpenMPIRBuilder::emitUsed</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#ab50c4c40350eb077f3f414ff6b9226ab">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitXXStructorList</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ab40658c61a66f761473f4b53aa60dd19">llvm::AsmPrinter::emitXXStructorList</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a6d548a27495e0e978c1ef0cc0f185744">llvm::SelectionDAGISel::EnforceNodeIdInvariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/wasmehprepare-cpp/#a48acf2682b08c15f3725186f3c3dfa1f">eraseDeadBBsAndChildren</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblylateehprepare-cpp/#a58c2aca158357d93b6b6519cdfee099a">eraseDeadBBsAndChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#acbe2feb9e960936a43c845a1fa8eaba4">llvm::LoopVectorizationPlanner::executePlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#a3b32f7427a25293e5cb32d481a342ebc">ExpandBasePaths</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a88dfee6623475363a4e46966d8383c0f">llvm::SCEVExpander::expandUnionPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/makeguardsexplicit-cpp/#aeee7951092aa5ce8f95ecb2f03d42893">explicifyGuards</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a021f42abfec39ba02f6b719a449b21db">ExtendUsesToFormExtLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a138b93205c71960aa94763a1081c50e9">llvm::DIBuilder::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a274a99ee4eac8fbc5e112f80cd84c71e">llvm::PPCInstrInfo::finalizeInsInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21fe87bf00db76089c043fed6a23fb76">llvm::findAllocaForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a537993928c8af5b0d064fcd5ce1dec2f">llvm::CodeExtractor::findAllocas</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a174350306649bc16f97803763bcae8f7">llvm::findArrayDimensions</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a0dca3347facf58865b34df5e5df676f0">llvm::MustBeExecutedContextExplorer::findBackwardJoinPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/#a4dd660f230b1343ae79f15573d7da3d4">llvm::RegBankSelect::findBestMapping</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/funcnode/#a9d0ffbd3083be7cd886e1714817492c8">llvm::rdf::FuncNode::findBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a296bc5fd6767824b2baf15675296743f">findBuildAggregate</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#af5c8e1b8ca1f8eb101829d9fe2062c4e">anonymous{InlineCost.cpp}::CallAnalyzer::findDeadBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/dependencyanalysis-cpp/#aab3179ea6d16c5998772f644a2a205ac">findDependencies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af88f364cd09c715e8853a1027c7180ef">llvm::findDevirtualizableCallsForTypeTest</a>, <a href="/web-llvm/docs/api/classes/llvm/dgnode/#a8560da4ee52510bb0b6bec7c71cf2855">llvm::DGNode&lt; DDGNode, DDGEdge &gt;::findEdgesTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktaggingprera-cpp-/aarch64stacktaggingprera/#a7e7be476481e8e24c35c332a9e6e26ad">anonymous{AArch64StackTaggingPreRA.cpp}::AArch64StackTaggingPreRA::findFirstSlotCandidate</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#ab0cac3cc09d07bc44ffd388ff8be5e49">llvm::MustBeExecutedContextExplorer::findForwardJoinPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec1d6e397956b9f5fa62416d0beba785">llvm::FindFunctionBackedges</a>, <a href="/web-llvm/docs/api/classes/llvm/directedgraph/#a803c71157136a4df79e5422f83ae2c92">llvm::DirectedGraph&lt; DDGNode, DDGEdge &gt;::findIncomingEdgesToNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#a4664ad33bbb85ca296ac1a1d74dffc1f">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::findInductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a8b1a8fc118e74550d4d11d8740ae10eb">findNextInsertLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a63fa5eea47d71eee71631388500cc8e5">llvm::DWARFDie::findRecursively</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#ad63451798277c4bce34d6446c9cb75ac">findRefEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affd5ebabccc8fdf81ca6d2eeff2e68c1">llvm::findValuesAffectedByCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a4b45cdd0366bfaa446ebdb3f00d80496">anonymous{X86AsmBackend.cpp}::X86AsmBackend::finishLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad600d9077d7e1eadff1334ee14f7f25a">llvm::foldBranchToCommonDest</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a37f98e168f7cc70d180aa6bed1625c87">foldGEPChainAsStructAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a222f3ff6cc88e36df2f31491a77c102a">foldGEPChainAsU8Access</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48dfb4cc4f8e3891dcba6f01530f6a95">foldICmpOrXorSubChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a9fcd68a333f3123b4b1cfb871ef3d89a">foldInlineAsmMemOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a727184c28151d2b605686087351b8d7b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldInstOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/runtimefunctioninfo/#aa3d7bedeec36948ecc6bae39a75c5da9">anonymous{OpenMPOpt.cpp}::OMPInformationCache::RuntimeFunctionInfo::foreachUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp/#a4c51a380543c40939531dc2875b2cf4f">forEachUser</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a830ba09d5969cd66878b05c17fdf66b6">llvm::ScalarEvolution::forgetBlockAndLoopDispositions</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a592bdd7731b14ff4ff5d646f6f399900">llvm::ScalarEvolution::forgetLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1f7831449cd72e78894e3dcda705cd8">llvm::formDedicatedExitBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a3a5bc7f961b5c8fd57d40b09ceca0bba">formLCSSAImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ad15d45b871d3111e8da4f9b394d7c83f">forwardStoredOnceStore</a>, <a href="#a58dc840fc84420b7f0b773794b8101c1">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="#adda3896b77b1f4cb8ece30c89581b5d7">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#af03b866cfd7aa23da26179050622de5a">functionWillReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a163e06959afb15ae88efade9bb975e27">llvm::RISCVMatInt::generateInstSeq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmatint-cpp/#ab9f36d4e7420ac603ea578f39ab9aeea">generateInstSeqLeadingZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a7ea4fb4d6b0198f2b6eac325a8d93031">generateReproducer</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ae86be98f39008a27ba987e282fc8dc2c">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::genericValueTraversal</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elfnixplatform-cpp-/#ae8fb1e7d144d58bebdc065615673d9f4">anonymous{ELFNixPlatform.cpp}::getArgDataBufferType</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a853ba647ef2e86e05cd988dae8ed8897">llvm::Attributor::getAssumedConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a529439af5980ea04e96200187061c86d">llvm::Attributor::getAssumedSimplified</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#ae92d755a80dec605503e2ba653765360">llvm::Attributor::getAssumedSimplifiedValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#aa831f0a1520a405a32196cb32ec24084">getBaseType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#a1890db236ee0485fd31d3d99d6ad09b5">getCastsForInductionPHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a085e72b5a3ed050deb15aa57090c54ba">anonymous{ConstraintElimination.cpp}::ConstraintInfo::getConstraint</a>, <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a8e787163c914dba0f28ef79e92c9768b">anonymous{ConstraintElimination.cpp}::ConstraintInfo::getConstraintForSolving</a>, <a href="/web-llvm/docs/api/classes/llvm/dependencegraphinfo/#ac23db8e595427ec7b328492aa7d5749c">llvm::DependenceGraphInfo&lt; NodeType &gt;::getDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a406e4a6b7277aab7efd423ae30a9fb12">llvm::DominatorTreeBase&lt; BlockT, false &gt;::getDescendants</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a814ccfa400b06db7a01885ddcc21196a">llvm::orc::JITDylib::getDFSLinkOrder</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a54233894e754c548da87c0d21d69003d">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDWOContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa141935f9c9a1ad9c785d7b6200b119">llvm::getEHScopeMembership</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp/#a0a97488075cd2fcd03613374a36af571">getEmscriptenInvokeSymbolName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a529578790bc8de8b220cef2ca6becef1">getEntryPropAsMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a4f50f080b393ee0a2c845ddbce571ae9">getFunctionNameAndStartLineForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis/#a5594932b56f2e0629b440a3c14de9eda">llvm::ReachingDefAnalysis::getGlobalUses</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a8cbdb500ba4abd11fd23de4e7a020a2d">llvm::ScheduleDAGSDNodes::getGraphNodeLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8287f8eaeb936bb75dc1bb6ef39fbdd1">llvm::getIndexExpressionsFromGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a86af5dc1ea8da3e443ba72fcf0f9caf5">llvm::DWARFUnit::getInlinedChainForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a0a4eb676d872db65ea116ed4e983c61b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getInnerLoopsInPreorder</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a4ce494fdd302adc3c52bc02868f223c8">llvm::ARMTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ae94b800d0b8c1e3423be89c87d447c9c">llvm::WebAssembly::getLibcallSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a485097c9e18d87d37388dc46cecd1dc3">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopsInReverseSiblingPreorder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a79d70fa60cedff640ded089e56149d24">getMaskForArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a6c8d73add4e552328f931ce1681c494f">llvm::AArch64TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#accb256ada9f5d92e5a776e459618cd1d">llvm::BasicAAResult::getModRefInfoMask</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa7240503037f0c0499222a41a5f22d06">llvm::MemoryDependenceResults::getNonLocalCallDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#a57dd4a8d48a825207a80611dfef6d45e">llvm::LoopNest::getPerfectLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackerfunction/#abc9a654b8a69fecf6acc17555b12b8b2">anonymous{OpenMPOpt.cpp}::AAICVTrackerFunction::getReplacementValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#aa1696dc4b990f6a31d2c68455efe907a">llvm::logicalview::LVScope::getTemplateParameterTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8c1ff7e5e775cdba70261e34245db9e5">llvm::AMDGPU::getTransitiveUsesOfLDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aca1828635e30f34e4958afeb5541766e">llvm::Intrinsic::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f25f617547597b1772677eaf0e7a8b6">llvm::getUnderlyingObjectAggressive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc66c148bcd950ffcc3ab83989eb70bd">llvm::getUnderlyingObjects</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a317172388c9d0d3c601070d588a104d2">llvm::getUnderlyingObjectsForCodeGen</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a3cc72cfbc837c8e89491b6357c358778">getUnwindDestToken</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a4e19285f051b80099ed8b36c5c94eaf2">getUnwindDestTokenHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a54f30c8bea3912d1d0f347626c395be6">llvm::slpvectorizer::BoUpSLP::getVectorElementSize</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#aeb0bc3fb3008d1f61c5a1adb0b901c82">HandleMergeInputChains</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#acc4b9161e5bdda1e0f5482ad8b9a64ba">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#aaa5ecbb121a4af66e98e1ddbff7b925d">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a44c557dcf96034410cdb25dd01c12dde">hasCallsInBlocksBetween</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aa26a0ee0a9f0cd627c9a6dc712ae53cb">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::HasForwardSuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a0f31e8ea7a0fea18c2df924e7d6e8de8">hasHardUserWithinLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#abd610bc0b0d15cdc72ab8d32205bf2a4">anonymous{CommandLine.cpp}::CommandLineParser::hasOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae78f734e49b5ad94836bf32dda101ec6">llvm::hasPartialIVCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6beebf86835d6582b0550cd7731ee9">llvm::SDNode::hasPredecessorHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a697cde840957bbc0b2848a593c3e0d5a">hoistMulAddAssociation</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a3b776824b1ee93e75dcf982fec706900">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a457f3c8acd738586fab8d9ac08f44013">llvm::DebugHandlerBase::identifyScopeMarkers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64speculationhardening-cpp/#aaf42ae80200bb2380ef4be8ff9c28402">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxproxyregerasure-cpp/#a9d0f767158270855806d4e9899311db5">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula/#a5e104e7ceecb5b2eddfc08e66e925c09">anonymous{LoopStrengthReduce.cpp}::Formula::initialMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a1f625b90be26a131061ab1e43740cc81">llvm::VPBlockUtils::insertBlockAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a69d51be488551c2983a022bb98494901">llvm::VPBlockUtils::insertBlockBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a21fc5eae685ef3e2dce4403a75d5ff2f">llvm::MemorySSAUpdater::insertDef</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a01b1581633bb40f86d6dc62a1c1a7f72">llvm::LazyCallGraph::RefSCC::insertIncomingRefEdge</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a864a2ad11bbf83cf2b910e43d461cd02">insertParsePoints</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#a8e7acd0466662074bd2486d1964cd173">insertPHI</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aa1f63192a86614e73a03f83e46813bb8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/classes/llvm/vpblockutils/#a3a43b6445802190031bda62347e97453">llvm::VPBlockUtils::insertTwoBlocksAfter</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a489ae04c136c4b088d849d7d6dc20965">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofiler-cpp-/memprofiler/#aa38dcf9a1b93414e7bd1b956a1d04895">anonymous{MemProfiler.cpp}::MemProfiler::instrumentFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a063217bcbb8b81adfdc88feb1a52ddcb">llvm::MachineTraceMetrics::Ensemble::invalidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a5d94ee8aaee00c42c11954aaa6022894">isAllocSiteRemovable</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a35a8d25c6df3f1d3bc5faba32de1dd55">llvm::LazyCallGraph::RefSCC::isAncestorOf</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc/#a024bad6935b15f7080b08b5dfec4eade">llvm::LazyCallGraph::SCC::isAncestorOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a5a7fe53bda3cbce584280a177a18d5ab">isBlockValidForExtraction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af55cf9792d5f9186df02c58b337a1511">llvm::AMDGPU::isClobberedInFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9330a86a613cf892ee5c7f515713f200">llvm::SITargetLowering::isEligibleForTailCallOptimization</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ab0e6b4d1d3051c45cd140206e89a6378">isEphemeralValueOf</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a203487323e0aa341b6c24f9ef20b5909">llvm::RecurrenceDescriptor::isFixedOrderRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a5a1f8f7e12808825560c7a10ec2f970b">llvm::SCEVExpander::isHighCostExpansion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab0469afc3caef8616d4b1c7501cba1b8">isHorizontalBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a08c9c2fedd8f175884c88275c7987e03">isKnownNonNullFromDominatingCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ae32b03825183735233b4142e1945abf8">isLoadCombineCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#aef5a823f024815a31e9be15d48d037dc">isLoopDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp/#a1c1b80628be0f97adf568cccacc8e8e3">isNonEscapingGlobalNoAliasWithLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a878ce10ca89edf5ebef798cc4871b6bf">isNotInCycle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#af278f33f3e54a61566b7fdff3835e980">isObjectSizeLessThanOrEq</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#ae1c9444bcb6b157e8f8c4ec8bf265010">isOnlyCopiedFromConstantMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a365173e63bd73b3ee58033678429636e">isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affedc93ead6b25c57a7196d32ff11e89">llvm::isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aca012302770ad32503de5e2c62344290">isProfitableChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/sveintrinsicopts-cpp/#ab3363381f198b25f4ce23364c08ea1f0">isPTruePromoted</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyexceptioninfo-cpp/#a98b83595b3773bb85e07a74292309c7c">isReachableAmongDominated</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaintrafnreachabilityfunction/#aa6f399598404d630b1091693ed0a6f88">anonymous{AttributorAttributes.cpp}::AAIntraFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/cfg-cpp/#a3044854435d0fc239faf5505d55a80dc">isReachableImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b369f94d5ebc6e107a988f17b42b3eb">llvm::isSafeToDestroyConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a915d3a27fc972595a451b8f2b092bec9">isSafeToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a7d76643dfe192e91b138cb1e156b92cf">isSaveReachableThroughClean</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#a7b61861295f70647f6dd85931782b93d">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#a333d3161d9b4420d11b777bd154148bf">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-cpp/#ab27518c8dcc76b28d6bcdd2cb40648fb">IsStoredObjCPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#aa1bdad6ac04deb5b4e5990a020b616c7">isSuccOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a94ebe004dfbba2e68530d0125ed16293">llvm::mca::ResourceManager::issueInstructionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsectionorderchecker/#a0b575c4fbaec067108afa87be8ca0ade">llvm::object::WasmSectionOrderChecker::isValidSectionOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a96179307953b47569983bcd440f76130">IsValueFullyAvailableInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af6735614e085435a0f3bb90aab527213">isVectorPromotionViable</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae7d28b348c77e17419b65d3f3d7d55a4">llvm::SMSchedule::latestCycleInChain</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a80314c2b261b78cb7335a265f43ba1b5">llvm::Legalizer::legalizeMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a51e42fbc8748c4097b19ad130cb61959">LinearizeExprTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a8ed485ff9b2526376525b8f792929a31">loadCSE</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/x86calllowering/#a699fa07bf5290218677fc2a1e69e0781">llvm::X86CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreisellowering-cpp/#a1a9dd0281442f33e9d9c88a3162d0274">LowerCallResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcisellowering-cpp/#aa0dc943f955ef5657bcc9eb702f611fd">lowerCallResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab8b58d0a8c95d411d0f7aa891c9fd3f1">lowerConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2763beadd2a14bcdb482f2b66a802019">llvm::lowerConstantIntrinsics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7994fd7ca0d8f8fcf2a9d18d151d0988">llvm::LowerDbgDeclare</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a6107db1593ae7bb4074d606368898747">llvm::NVPTXTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ae87be78c50d3026c58e203aa8f0b9164">llvm::SparcTargetLowering::LowerFormalArguments_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerguardintrinsic-cpp/#a6c30165ed98029182d00cb428a64fd29">lowerGuardIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/philoweringhelper/#a0321e28cc3da73c666a6f5e58a541de8">llvm::PhiLoweringHelper::lowerPhis</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#aece826681b1fdc9ec7c82f4a9152000f">llvm::LoongArchTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a5f7819dcae52567c11033d63e3d6421a">llvm::NVPTXTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4ce28f633cfe7a89369965cd9792e8fb">llvm::SITargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a3a9a464956d7d22291e5a6a29d4266e5">llvm::SystemZTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ae491d50e304bf7057a2f4dfbf1650e56">llvm::XtensaTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a97298a7350df5e0302d0678065f5a1e2">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::lowerVGPR2SGPRCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerwidenablecondition-cpp/#adb00c4c46ce23c327d6cf77f723255ee">lowerWidenableCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsrinstance/#a9bcf42be7435217d79cd175d4e6993d7">anonymous{LoopStrengthReduce.cpp}::LSRInstance::LSRInstance</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a665e880cc41e9fd97416741590e2e0d0">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/llvm/irattribute/#aa8300749b291967b0d8fc610924741dc">llvm::IRAttribute&lt; AK, BaseType, AAType &gt;::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/shrinkwrap-cpp/#a0c3bc0926778b155544ae7c190921f4e">markAllReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp/#af31ca6130fc1fdac86bfb75b1acac4ac">markTails</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a051cfe914c1c4eb2ceabb758d018a966">llvm::LiveVariables::MarkVirtRegAliveInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a23cdde8b9bdd40fd4a93d3635ca77dc6">llvm::Pattern::match</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a7df4bae7dbd152d7a3c399384a110fe8">anonymous{SLPVectorizer.cpp}::HorizontalReduction::matchAssociativeReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab97e7bb67059e0b2b6b66c4a784b5106">matchIndexAsShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a528aff11b730581c8d7cfae0e5fb6254">mergeBlocksIntoPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a2711d3bc7c6c769a8f34c7fc3937169d">llvm::Instruction::mergeDIAssignID</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a2e18d86a676154c8ddeb0a9dbdce719d">mergeEltWithShuffle</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a6277ecb456c87743b292a5dd69542a4e">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a148f25a7131bb353315edfc43df0c79c">llvm::RISCVInstrInfo::movImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a023f82db84f5e5ed13398308496689e7">llvm::mustExecuteUBIfPoisonOnPathTo</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/escapeenumerator/#ac63ecd195310b8a31b445bb613028893">llvm::EscapeEnumerator::Next</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90896a5c2c14e27297f4fdb0196e24b3">llvm::nonStrictlyPostDominate</a>, <a href="/web-llvm/docs/api/classes/globalsimporter/#a40e5e7c43d6af77e6e3e40f4421501a8">GlobalsImporter::onImportingSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/sequencebbquery/#a01cdf467a56a2b88b09065dd68b333a9">llvm::orc::SequenceBBQuery::operator()</a>, <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/lockstepreverseiterator/#add4e11e58e765474930767db18feb623">anonymous{GVNSink.cpp}::LockstepReverseIterator::operator--</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#ae812aaa917422c3c4b067cda1b1d7019">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::optimizeAMXCastFromPhi</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64redundantcopyelimination-cpp-/aarch64redundantcopyelimination/#a1ee0cfcd17ed3a5b4826b8a5f93e50e1">anonymous{AArch64RedundantCopyElimination.cpp}::AArch64RedundantCopyElimination::optimizeBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#afd07d19c7174c06cd7c7415f63596839">llvm::slpvectorizer::BoUpSLP::optimizeGatherSequence</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#aa50432deded202fb241ca2c204e8137a">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::optimizeLiveType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#afbc1088fd64459bec1157940aa59eb69">llvm::X86InstrInfo::optimizeLoadInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8b1b5c42e2e99bb24a27219f8df7294d">OptimizeNonTrivialIFuncs</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa2b80c1201a1baeb6ee4466e970957ba">llvm::AArch64FrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a897d513f6255e5eeaba5074ca4095230">llvm::HexagonFrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#adee8390bf727c3086a7b864de6c6913e">llvm::X86FrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a9d7f3f2b0dc486075d4d462b7d744174">anonymous{MIParser.cpp}::MIParser::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/packedversion/#a607acfa934a3c0188743a1edac5b3826">llvm::MachO::PackedVersion::parse32</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/packedversion/#a6954336e0b10193d5bea01a716c5f182">llvm::MachO::PackedVersion::parse64</a>, <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#aa7b40dda7a09e0c055d6138b404d0789">llvm::DebugCounter::parseChunks</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/guardutils-cpp/#af7534ff6924d87e8750acd2d12a707c3">parseCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ae577a9371ea38b78cffc39d0ca5f6623">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab65e752ef8a4ee9e6df01039bfa00b0e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#a02d8a789e50e085fa66aac9180bb03f3">llvm::ELFAttributeParser::parseSubsection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a89d936a98d65c79ddb962452b2d670bd">llvm::PointerMayBeCaptured</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartition/#a9feb888b40cb5010ca125c921f15c0f8">anonymous{LoopDistribute.cpp}::InstPartition::populateUsedSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#acc71b3922c4a5138a77520c4e90f48bc">PrepareTailCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcov-cpp-/context/#af21fe9969dd2d37f96a144b9d7376ffa">anonymous{GCOV.cpp}::Context::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/mdfieldprinter/#a941fadcc66e266a39f624bc5c112371f">anonymous{AsmWriter.cpp}::MDFieldPrinter::printDIFlags</a>, <a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/mdfieldprinter/#a0fa3beee983c3c5ddd6a4b3fd43edced">anonymous{AsmWriter.cpp}::MDFieldPrinter::printDISPFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a1007dc3842414831c7641e4b5824e4a0">anonymous{CommandLine.cpp}::HelpPrinter::printHelp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af74d55b9091c302365e3af53f446a2a2">llvm::printLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a12b99b3e536e8f7ddb0167814d1c0d50">printSyncScope</a>, <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a42ba71cba0e3d5e1b4e5395fd080016d">llvm::AlignmentFromAssumptionsPass::processAssumption</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a071cd98d76a1c63f215ad16388bfdfe2">llvm::JumpThreadingPass::processBranchOnXOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a471ef961ae64095de93c59dea0a3262f">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::processFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a873cd38481c3ed6a7e21bc016ec10ae2">llvm::logicalview::LVBinaryReader::processLines</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a65eee5509cce98dcc69693ea13bb9220">llvm::logicalview::LVBinaryReader::processLines</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#a1b795b0cd98521a7cf4ab769d9207258">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::processLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad35f9d7d71a4bdf20246882f712b3c88">llvm::processShuffleMasks</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a96191c096e61f77ea0a6771263bdb5e1">llvm::JumpThreadingPass::processThreadableEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a53602f27c06fcab4b6b5d552984a5ad7">promoteArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a6084253c0f3954d2b8479befc2a6be61">llvm::GCOVFunction::propagateCounts</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a611115d09f3dd3ef310f70c87a8ba402">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::propagateShapeBackward</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#adf1371d869d3a7468c48401a2a321b26">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::propagateShapeForward</a>, <a href="/web-llvm/docs/api/classes/llvm/swifterrorvaluetracking/#afc960ff953a4a9d9fbf91baf590222d2">llvm::SwiftErrorValueTracking::propagateVRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#ab79f3dcf9607c6a8908cda57cc964f49">rebuildLoopAfterUnswitch</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a9e0695dc8fb597f66ca702309da941f7">llvm::LiveVariables::recomputeForSingleDefVirtReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a0c9b0aa6fff67d00a95f47fc121491e5">recomputeLoopBlockSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af2093ca4a132848caa9d8acc509df1b2">ReconstructShuffleWithRuntimeMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ab5d43362c1fefd60d9bfcc1e28ba4688">recursivelyDeleteDeadRecipes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1de454f8f11d343f01bde5f057af057e">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#af3b3d27cd53936e3c52e01a34817d6be">TransferTracker::redefVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeredundantdebugvalues-cpp/#ab500564693e7d4da8ba1c02c723a057a">reduceDbgValsBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeredundantdebugvalues-cpp/#a0cb9f41d03e7efefe10150f7941cdd16">reduceDbgValsForwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ac33f356faceb9655cb64611d2971d24f">ReduceLoopStrength</a>, <a href="/web-llvm/docs/api/classes/llvm/dotcfgchangereporter/#a8561a3cb89ee3981d033ad4f4074bd07">llvm::DotCfgChangeReporter::registerCallbacks</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0121eb7b984a5cf2527133cb838d5982">llvm::Attributor::registerFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55412d2c237115c95f20e12ba0d95922">relocationViaAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa175634946d91981b87f76ed9a583f27">rematerializeLiveValuesAtUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa91c37999052160d434c5bf803257c9">llvm::SelectionDAG::RemoveDeadNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#a09ac67e36db813f2a3e69173f7638037">llvm::PMDataManager::removeDeadPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6b42b6fca05063155c689008d30a2751">llvm::AMDGPU::removeFnAttrFromReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a56b5a0fa4891dca73946affd4e6e3ffd">removeFromUsedList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#aceb0dbb192df1147bd5191db4c960ec1">removeGEPBuiltinsInFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a4082748189dc3460ea7130cd8d7790b5">llvm::MemoryDependenceResults::removeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aa8ccbcf19b9150f2872f794ecdc53d3e">llvm::slpvectorizer::BoUpSLP::removeInstructionsAndOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a87dd1a69c8d8492e78b32708ceacb2c6">llvm::LazyCallGraph::RefSCC::removeInternalRefEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a36fe1ed1682023b7fb3c4699f9009d31">removePAICalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a2373ebe62ac37c5f7d838e9ca92a7f2e">removeRedundantDbgInstrsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#aceb315f70b8f69369df84d79274ef420">removeRedundantDbgInstrsUsingForwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/lowerallowcheckpass-cpp/#aeab949c1d2a96004a9076b8b2176ca74">removeUbsanTraps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a579e878e02e34bf9699e3d82da2bc070">removeUndefDbgAssignsFromEntryBlock</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#ae31219d422e76099c3c5dfaa2c7171cb">anonymous{LoadStoreVectorizer.cpp}::reorder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a633db91afb11db086004de9e3eb37217">reorderOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a1bc3cc02c0dc6dcb9ad315b7755475e7">llvm::slpvectorizer::BoUpSLP::reorderTopToBottom</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#af2c671e8273bc99e266f62322b29a157">replaceAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcorelowerthreadlocal-cpp/#a1ad5c109b5218ec1d5f5fcd6390636ba">replaceConstantExprOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#abf799de7147065c0e7f525e1b6009dde">llvm::coro::replaceCoroFree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5f6fb45b8f4ed44ba033601a9700b4e">llvm::replaceDbgUsesWithUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a649ac561acbab510055b0e8f48ca0617">replaceLoopPHINodesWithPreheaderValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#add7c3bdd8428904f63f53569807b8df6">anonymous{RegisterCoalescer.cpp}::JoinVals::resolveConflicts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab8b1a901ef225bb4a12ca046d13f4b45">rewriteDebugUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcorelowerthreadlocal-cpp/#ae5532112c4ead645d90e6fe4e5092f5f">rewriteNonInstructionUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2cadcdd1750ca8ba3197c1266052c059">rewritePHIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/amdgpulowerbufferfatpointers/#a00d87849a4eb6524d910ab07f0fd968f">anonymous{AMDGPULowerBufferFatPointers.cpp}::AMDGPULowerBufferFatPointers::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuremoveincompatiblefunctions-cpp-/amdgpuremoveincompatiblefunctions/#a8d8058631456eb8173e42f7af6f4555f">anonymous{AMDGPURemoveIncompatibleFunctions.cpp}::AMDGPURemoveIncompatibleFunctions::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-controlheightreduction-cpp-/chr/#ac4b57ee03a4f60d7d9c7800f192771b3">anonymous{ControlHeightReduction.cpp}::CHR::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-functionattrs-cpp-/attributeinferer/#a322a5409ce5be2c9d2045f16b8439048">anonymous{FunctionAttrs.cpp}::AttributeInferer::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheckelimination/#af56db9cf79e7501bf38278f849774369">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinelicm-cpp-/machinelicmimpl/#a91e4daed2453931a75ea961f1dce12ad">anonymous{MachineLICM.cpp}::MachineLICMImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-safestack-cpp-/safestack/#a77d82dc0922a0f94f90fcc7e9e194035">anonymous{SafeStack.cpp}::SafeStack::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#ab0ed42131f44a7ce15c2e5ba199bbfe3">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfaspacecastsimplifypass/#a76364c57022d89ac618f1b1e22bef6e2">llvm::BPFASpaceCastSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrpreparepass/#a9281dc805301bc24be1f5401e30a878f">llvm::CallBrPreparePass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycleinfocompute/#a8af31f91b7b3fe098e8966229069b1ae">llvm::GenericCycleInfoCompute&lt; ContextT &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/globaldcepass/#ae98558816f50b4a9f6f7244b2deadd53">llvm::GlobalDCEPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/kcfipass/#a19dcb564cb3c8a4de327c6f9cabed5b3">llvm::KCFIPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsinkpass/#a11eda417d0372700a9b48e41f267ab92">llvm::LoopSinkPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a0d3ab70393b799b3be4875c3334a4f42">llvm::LoopVectorizePass::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a62c6882e8be05d55fb7e7f743f43d902">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#aca9bbb9fc2968bbb644730c5c2567409">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#a8f3d27d1b480f6b3c90405707be76295">runMoveAutoInit</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a53fcf95621b95aa7165074a98b5df0b3">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-callbrprepare-cpp-/callbrprepare/#a059a9f67e58a405134e69baa176e4ee1">anonymous{CallBrPrepare.cpp}::CallBrPrepare::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a66256b4fc858af974d6bea00a0d0639b">anonymous{CFGuard.cpp}::CFGuardImpl::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc/#ad69716246dabb743839cafceb902ef46">llvm::RewriteStatepointsForGC::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionoptimizer-cpp-/aarch64conditionoptimizer/#a1ee52a66badadfe0d31d88d614305f41">anonymous{AArch64ConditionOptimizer.cpp}::AArch64ConditionOptimizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguardlongjmp-cpp-/cfguardlongjmp/#a17b3d486f52582c92dec4b050aedb70a">anonymous{CFGuardLongjmp.cpp}::CFGuardLongjmp::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/fixupstatepointcallersaved/#a3c8b04474d6af8577024260b88fb8352">anonymous{FixupStatepointCallerSaved.cpp}::FixupStatepointCallerSaved::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#a98d8aaed2e429cfec371c300cb8244c2">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-implicitnullchecks-cpp-/implicitnullchecks/#adfa9682269920db0fdac767478243124">anonymous{ImplicitNullChecks.cpp}::ImplicitNullChecks::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsoptimizepiccall-cpp-/optimizepiccall/#af8fb60c334fa1c7571459b115762b09e">anonymous{MipsOptimizePICCall.cpp}::OptimizePICCall::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-pseudoprobeinserter-cpp-/pseudoprobeinserter/#acf62b36239ac36c52ffc9a58a18332ab">anonymous{PseudoProbeInserter.cpp}::PseudoProbeInserter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siformmemoryclauses-cpp-/siformmemoryclauses/#a3b412b093194b8e66d1d42d1cc79d692">anonymous{SIFormMemoryClauses.cpp}::SIFormMemoryClauses::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-silatebranchlowering-cpp-/silatebranchlowering/#a2f96cc01100e6467c2b124371cf417c0">anonymous{SILateBranchLowering.cpp}::SILateBranchLowering::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblycleancodeaftertrap-cpp-/webassemblycleancodeaftertrap/#a02a6d4c45d72193f89b19418a71f7ab5">anonymous{WebAssemblyCleanCodeAfterTrap.cpp}::WebAssemblyCleanCodeAfterTrap::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86speculativeloadhardening-cpp-/x86speculativeloadhardeningpass/#a862b3b4b5ed250fcfb2d6f9a130f4a0c">anonymous{X86SpeculativeLoadHardening.cpp}::X86SpeculativeLoadHardeningPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#afe18f2bacebf9cbf307a33cf86b81e4e">salvageDbgAssignAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26be1141b23850a2b4eb78021d99e862">llvm::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a245a901981dbba45d423697bb3351b1b">llvm::salvageDebugInfoForDbgValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a22d247369eb256f74de55d2260c3b82e">salvageDebugInfoImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a8cf671ed90e3e80717aaa6318b24794c">llvm::SelectionDAGBuilder::salvageUnresolvedDbgValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-hwaddresssanitizer-cpp-/hwaddresssanitizer/#abe3ea5f5ad2a17b7552318e8ffb3b0bb">anonymous{HWAddressSanitizer.cpp}::HWAddressSanitizer::sanitizeFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-typesanitizer-cpp-/typesanitizer/#a063b446da637b4357deed499cbbe11fe">anonymous{TypeSanitizer.cpp}::TypeSanitizer::sanitizeFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a9b3924d6dbe1bfa285ef3d3a6c3d4b6f">anonymous{WholeProgramDevirt.cpp}::DevirtModule::scanTypeTestUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a58104473aed2159b638d90e6a56e23b8">searchPredecessors</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a2bdacd126c6e2d17f0f5a195043c9aa3">selectConstantAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a2b20fa727cb3be2d7338de943bc81490">selectImm</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae8d11752355845a0e271111de7be7d3a">llvm::LoopVectorizationCostModel::setCostBasedWideningDecision</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#addb1364902bd813841491d91970ce02b">llvm::SUnit::setDepthDirty</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a9798204f943ee8fc7c6efd2ab0f7c3d6">llvm::VPRegionBlock::setEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/vpregionblock/#a414a617643992b9d0e5b70df5fd423d5">llvm::VPRegionBlock::setExiting</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae44a97a569de65d01e1f80ae5261121b">llvm::MCContext::setGenDwarfRootFile</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a5ba3791568e29a8d9214ec7dad855a56">llvm::SUnit::setHeightDirty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#aac66fb1c2d35d04a9d0af5abca7898b3">setRequiredFeatureString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ac326b52d617d41f386c715d297f96a72">shouldTransformMulToShiftsAddsSubs</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker/#ac632fa4ac33de997f4fc1b02b416462c">anonymous{CodeGenPrepare.cpp}::SimplificationTracker::Simplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a7118a8527081192cbd8b839926fb95d4">simplifyCommonValuePhi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0083a69883e0f97e111dbff064c60f42">llvm::simplifyLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f380ccafb36b01f687b5507c39d3c6e">llvm::simplifyLoopAfterUnroll</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinstsimplify-cpp/#ac7156f23f48b5eb96ead0522896d7574">simplifyLoopInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a1ba99155749ea6a41858f9bc4449f543">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::simplifyUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa725413bc28036ce9c795a24503f654b">llvm::coro::sinkSpillUsesAfterCoroBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#aca7c31a6dcc095ed3c2831f6876c6dc0">SoleWriteToDeadLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp/#ab52c873c8169af2a8b1256ace3fe7a7c">sortBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp/#a08fb230c2b93e704a4fd84ef773b6002">sortLocalVars</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#ab2d41fa069e7edcedf9949fa64aa6e30">anonymous{RegAllocBasic.cpp}::RABasic::spillInterferences</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a27b94c48d58dc48bf80e98e92e6ba7a1">llvm::DominatorTreeBase&lt; BlockT, false &gt;::Split</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af34178528cc721dfa273965733da1f37">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::split</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#adc7bbccb30409488c60813454af8c81d">llvm::coro::AnyRetconABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#ae51f7f2d35223ec01d09e205c757a4df">llvm::coro::AsyncABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af376f4f0e0b55e40407912678b736863">SRAGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a09a156bd41fe293ee8743b4beca76960">stripDeadDebugInfoImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/stripgcrelocates-cpp/#a5d9143fec81c7c1bea9330ccc664f45c">stripGCRelocates</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a0f1b1f36c5069336e43ad70639b7f176">substituteSimpleCopyRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a7223c62dc4b1db59861cb3a7e225a387">llvm::coro::suppressCoroAllocs</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a2957918db7f91f405b11d92c1ebf3b0f">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToCall</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a96fe0cb15ded58bd1824fa4e3daec680">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#aff28c3d477d3a7870ec643381f186ed4">llvm::cl::TokenizeGNUCommandLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#aaa5adc2409ac3c78b33d4813ff31ae6e">tokenizeWindowsCommandLineImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a67a4cef5addbdc43c571874df4ea020d">llvm::detail::anonymous{APFloat.cpp}::toStringImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/macho/machowriter/#ace4d95a09224c0956cada6a3a7319e3a">llvm::objcopy::macho::MachOWriter::totalSize</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a91b0e07ff96232db2a91d6cfdf67a5e0">llvm::slpvectorizer::BoUpSLP::transformNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/looptraversal/#a87cd9704fc800af5dddb87f26badfb3a">llvm::LoopTraversal::traverse</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/preloadkernelarginfo/#a7a5253091344c2d534f5afd16941e25d">anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::tryAllocImplicitArgPreloadSGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#aa541e074a612b8ca4a7291a3b0746b7e">tryBuildVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a3eb465a2b7eef72ebd92bf15445c5903">llvm::LegalizationArtifactCombiner::tryCombineInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#aac5e465289c9bc7adb88b6b682fdf85b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4b167ac2fde7b3d71172817650150a6">llvm::InstCombinerImpl::tryToSinkInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad4296b2b81379548b300c4676f0d2125">llvm::InstCombinerImpl::tryToSinkInstructionDbgVariableRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ac48731694e324e56e35cb2b4f20345d0">tryToVectorizeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/mcdc/tvidxbuilder/#a85f4860524d04ca3d92dae7f5b1a9fba">llvm::coverage::mcdc::TVIdxBuilder::TVIdxBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a00b3b7cedd83de61be0312c6535f3f37">unswitchLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#a775d8b54712dddd880b29ca02e8f1ee6">anonymous{StructuralHash.cpp}::StructuralHashImpl::update</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a1d6bceebc19a80123ae26670c7645d1a">updateCallGraphAfterCoroutineSplit</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a83fe54fc062eda7c1086493dd4155f8a">llvm::DominatorTreeBase&lt; BlockT, false &gt;::updateDFSNumbers</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1a9bc340dcef73647e894b19458ec9a9">llvm::SelectionDAG::updateDivergence</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaglobalvalueinfofloating/#ad2836a92e1e5443f5318dc46446a9197">anonymous{AttributorAttributes.cpp}::AAGlobalValueInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a6aaeb440ac0f45225f89b6b83444db1a">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#ab462c5bbf745633740ccfb2920040000">updateLiveness</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a26d6acb7d8248e5d25f190b5d8fecbd3">llvm::JumpThreadingPass::updateSSA</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#aa91fc385b3c151e89ac23b656e9bf8b6">usersDominator</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a406d93c10bd410f7ef8af5c00b037b8b">valueIsOnlyUsedLocallyOrStoredToOneGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/phitransaddr/#a706fc677031e5d0fc38869aed8478491">llvm::PHITransAddr::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aff82c03c1ce8b945170bcb1f0f624c17">llvm::ScalarEvolution::verify</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a302583dfd143c9bb87f8274ba0dc727b">verifyCTRBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a066fd5533813e5df6d52cb59fc8afd4e">llvm::dwarf_linker::parallel::DependencyTracker::verifyKeepChain</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a49a46654ca2c32ce99be52de089052f8">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Visit</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxtype/#ac270a700d1efd59267c89e1539ff7e3e">anonymous{X86LowerAMXType.cpp}::X86LowerAMXType::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a196df57d98a1307c0ced654a8e1d202b">llvm::SelectionDAGBuilder::visitDbgInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a18b0f192065386f9e0bc793a08bbf3ff">visitDomSubTree</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a22bc54f319e33d248b169116b757a143">llvm::InstCombinerImpl::visitGEPOfGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a99bbdbd6641e69bcad8fda4bf1726525">visitPointers</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a778d0494c2f8dec95d60160b1ce89a07">llvm::LazyCallGraph::visitReferences</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#ad71ead87ca8f3fc5edfb6173a970f792">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitStoreInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-tailrecursionelimination-cpp-/allocaderivedvaluetracker/#adf48fa3a2373efca5ac054e8bff29b20">anonymous{TailRecursionElimination.cpp}::AllocaDerivedValueTracker::walk</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/resourcebase/extendedproperties/#a59fdcbcb099ce1f5d729fcefa7bb8206">llvm::dxil::ResourceBase::ExtendedProperties::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#ac4946ac3df4a88e078136a4444ef1185">llvm::objcopy::elf::BinaryWriter::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0096360a382602b21e0e980fb8069d52">llvm::dxil::WriteDXILToFile</a>.</p>

</div>
</div>

### end() {#a075e34e98605d0e7c289763a104869ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end ()</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a> and <a href="#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp/#a9baafe0b9a21c4fea0ca7cc671837a29">addData</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#a9b52ca5c1374c43bc1800b838514562a">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::addDeadBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/spirv/requirementhandler/#a4d5fe47ba4a3c6cbc8d9655eafdb13f2">llvm::SPIRV::RequirementHandler::addExtensions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-cpp/#aaf08c51751e9ec671a84a92af1daab99">addHints</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#abfb093b6e752567e7a893c63309daa66">llvm::logicalview::LVScope::addMissingElements</a>, <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a9e5d9d56a410f0bd58fa931731c9e644">anonymous{IRSymtab.cpp}::Builder::addModule</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetree/#ad1246639c464dee99101df3e7c1c4dc8">llvm::MCPseudoProbeInlineTree::addPseudoProbe</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#adfcb78856461567d0d6f7012aee7a89a">addRegLanes</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2713b4a910e8cfdceb4114823a49123d">llvm::InstrProfWriter::addTemporalProfileTraces</a>, <a href="/web-llvm/docs/api/classes/anonymous-minidumpemitter-cpp-/bloballocator/#af08557fb29f0c4129ff2121db66a7e43">anonymous{MinidumpEmitter.cpp}::BlobAllocator::allocateString</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a592045324d9ab5a208ce36932f3a7c2d">llvm::SIMachineFunctionInfo::allocateVGPRSpillToAGPR</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/allocainfo/#aed57a9dd738a483f6ac02904b981c94d">anonymous{PromoteMemoryToRegister.cpp}::AllocaInfo::AnalyzeAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a249186f7374b6b9ca0ffd254bb5d79f6">llvm::CCState::AnalyzeArgumentsSecondPass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::const_iterator&lt; MemoryLocation &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#acf1f3ec6174852d235b520ae37b9a13c">llvm::const_iterator&lt; MemoryLocation &gt;::append</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/mapinfosty/#a635fd9f6c5f2092419d60086cb1e0b87">llvm::OpenMPIRBuilder::MapInfosTy::append</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a5f48305fa7d23161515c94bca7c2beb6">llvm::DIExpression::appendOpsToArg</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#a08fddb3d382c1c806dee38774e6464d7">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::appendToVectors</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#a568501d2ea6d5786f4981de195297020">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::const_iterator&lt; MemoryLocation &gt;::assign</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a6aed977bf8ca76ee498836d1fe4cedb6">llvm::const_iterator&lt; MemoryLocation &gt;::assignRemote</a>, <a href="#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="#ad2ff893c472ce3c6f1ab7e2a01a39c5e">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4ad92667dcad9ad33a52a2e1c505a03a">buildOverlapMapAndRecordDeclares</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7e7374e59505b56b9bf65507fb90dd40">casesAreContiguous</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue/#ac8891666086c72776f0c83fa8eef8b98">anonymous{LiveDebugVariables.cpp}::DbgVariableValue::changeLocNo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#ac41c50a3b85aa5098391b76548f04e3b">checkDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/hipstdpar/hipstdpar-cpp/#aaf9c9bd3b96d08e2f7ad45aa3304aa20">checkIfSupported</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a38e9b77a3c8508ea8ff0ba1f5bf81eba">anonymous{DXILOpLowering.cpp}::OpLowerer::cleanupHandleCasts</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::const_iterator&lt; MemoryLocation &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a0ac5df8f0304981180d602dacb13512c">llvm::LoopVectorizationCostModel::collectValuesToIgnore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/gcnregpressure-cpp/#a08414c5d48fed44354cf4c4ea6ca464c">collectVirtualRegUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62f4b8744e4b75d5371fb9a8a471ca26">llvm::computeAccessFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a3d42f23852edcd240ef3a605fdc2bcec">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::concat</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a993771e7c58c60044cbc4c57f689406e">llvm::RandomIRBuilder::connectToSink</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#a7587e2867090ef850ef2bda4ac192e48">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::convertFromOptType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad365e0d64063a233710fdba41a0da57e">llvm::ScalarEvolution::convertSCEVToAddRecWithPredicates</a>, <a href="/web-llvm/docs/api/classes/llvm/intervaltree/#ae65afb93ec69b4bab0c72c8b5ca28f9b">llvm::IntervalTree&lt; LVAddress, LVScope * &gt;::create</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#adaccd674ba7dc69d1ce2b88c6155e691">anonymous{MipsAsmParser.cpp}::MipsOperand::CreateRegList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/datadependencegraph/#aca5669c8b9a5b58a747bcbd9b9836f2d">llvm::DataDependenceGraph::DataDependenceGraph</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue/#a3e5ffea0fa3c8e006a9bb56d22a0aa12">anonymous{LiveDebugVariables.cpp}::DbgVariableValue::DbgVariableValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aeabcdff1c388af9ac5a98f1ec4ba2471">deleteDeadBlocksFromLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a13971a178ec8248ecf4b0a903c4db1c6">deleteDeadClonedBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#ab85ec1f9019bc54f0c9962a347b9dc45">determineGPRegsToClear</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a60e96ac40c51e2ad7e24f9776fda71d1">llvm::RegPressureTracker::discoverLiveInOrOut</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a86b96eacf90b70918b473cbb3eaf4b5f">llvm::DWARFContext::dwo_types_section_units</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ae8e69a65912ebaef59c5fc4fefab821d">llvm::DWARFContext::dwo_units</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a420cc4a7a63b33a52659768b133b5f1b">llvm::EHStreamer::emitExceptionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/unwindopcodeassembler/#ab1cfb912a74d848789c9edb810753f17">llvm::UnwindOpcodeAssembler::EmitRaw</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ab40658c61a66f761473f4b53aa60dd19">llvm::AsmPrinter::emitXXStructorList</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::const_iterator&lt; MemoryLocation &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/debuginlineelinessubsection/#a619dcb9a422c2e796481d8fe9b9b5e91">llvm::codeview::DebugInlineeLinesSubsection::end</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a437bcee0646cbd03fd420aff5e977443">llvm::ConstantRangeList::end</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragedata/#a95b903f31f657852408a6fe7e4a239f0">llvm::coverage::CoverageData::end</a>, <a href="/web-llvm/docs/api/classes/llvm/mmrametadata/#a9fad045c033490f84912cf335c4f53b3">llvm::MMRAMetadata::end</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#a7fa65a4aa10fe30c34ed69cf5051448c">llvm::RecordStreamer::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::const_iterator&lt; MemoryLocation &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aa3787c69a41c14127758c359911180aa">llvm::const_iterator&lt; MemoryLocation &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a687e754bf03f8d135bc899b49db74472">llvm::X86TargetLowering::ExpandInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a47832d6753036cd8ce039993854b3162">llvm::extractInstructionFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a174350306649bc16f97803763bcae8f7">llvm::findArrayDimensions</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a3d50f3f3bb104fb854ac8de326c5bb64">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindAvailableVals</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aa1382b606ff796c22a7416ba7f6b856b">llvm::cl::ExpansionContext::findConfigFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/btf/btfparser-cpp/#ac835023c2f2a4fbe350567206319f0bb">findInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae17b24216f27d8266c87b9fa9a70f533">llvm::SelectionDAGBuilder::FindMergedConditions</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8688fe7e12511bba710a19b4aaf027a1">llvm::RandomIRBuilder::findOrCreateSource</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a37f98e168f7cc70d180aa6bed1625c87">foldGEPChainAsStructAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a592bdd7731b14ff4ff5d646f6f399900">llvm::ScalarEvolution::forgetLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmtypecheck/#a84727116774114016406f20cb5e699ba">llvm::WebAssemblyAsmTypeCheck::funcDecl</a>, <a href="/web-llvm/docs/api/classes/llvm/prediteratorcache/#aa4997ba4fd2495e1737dcf98457f8419">llvm::PredIteratorCache::get</a>, <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#af99419a971a2b329732cb2a89e6a004b">llvm::RecordRecTy::get</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#ace2ec29a8f2231556c7f8a20929cc138">llvm::opt::ArgList::getAllArgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a63bdece47c81d3a6e63de19cb824b788">llvm::opt::Arg::getAsString</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#aa12ce67d21274bae7db762b1e5728bf6">llvm::SampleContextTracker::getContextString</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/linecoverageiterator/#a6ba859babf8638a336c01fc30f4c0337">llvm::coverage::LineCoverageIterator::getEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a9e635b2c582b6500e2c79faf06360ca2">llvm::GenericCycle&lt; ContextT &gt;::getExitBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#ade1da0b29f5e3cb310ac591da00699c3">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/llvm/machineinstrexpressiontrait/#a3344d356ddabbe21340a4b078300a789">llvm::MachineInstrExpressionTrait::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobe/#ae65fd4d6ca6b5107072abefc811a63b0">llvm::MCDecodedPseudoProbe::getInlineContext</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplcrtpbase/#a95442a0e0980e874df3bf77d6c8dee44">llvm::TargetTransformInfoImplCRTPBase&lt; T &gt;::getInstructionCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a724d32daf4f554526f15b36eab12e129">llvm::RegisterBankInfo::getOperandsMapping</a>, <a href="/web-llvm/docs/api/structs/llvm/hvxselector/#ae954fcbf0e9b2fe89cfa9d21b931b063">llvm::HvxSelector::getPerfectCompletions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#ae1be3a2fc5dfa3281d32b6fb4e4ea6dd">getSchedRegions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debuginfosupport-cpp-/#af708da9529b70292b2712cd7ed80d14e">anonymous{DebugInfoSupport.cpp}::getSectionData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84a0cf35704ac6286dc4f1395a6893e3">llvm::getShuffleReduction</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult/#a4bf35524898c34b917e813177d64d735">llvm::gsym::LookupResult::getSourceFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmaprecord-cpp/#a509ce85b468f4da99d1111c7498e2557">getStableFunctionEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a70d3e07bad78e3a1d2ba86aa871b9501">llvm::SelectionDAG::getTokenFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#ae12b387e4a14699e4f1229bf9d3d0905">llvm::DWARFUnitVector::getUnitForIndexEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#a887387b3f904d16301c7dae667aaa42b">llvm::DWARFUnitVector::getUnitForOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a8adf44ad04562ff150b0e8e352a38d46">llvm::VFABI::getVectorVariantNames</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ab6cf8f5418ae17302373eb658de2c4a5">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::growAndAssign</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#ac3fdb189d1625b937b2aedcf1de64f09">llvm::IRSimilarity::IRInstructionData::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp/#a2e84df1cbf9375ee66f23c5ca414c638">hashValueMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6beebf86835d6582b0550cd7731ee9">llvm::SDNode::hasPredecessorHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa730b58924baf8f35394c2e5a0bb3714">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a59fd5e59ca0c03b061035a6c9de2b39c">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a520e903dce9cfbdd0d1073fe447ce52e">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrangelist/#a1109f77d1d986c8e1e04f5da7ed197f9">llvm::ConstantRangeList::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a864a2ad11bbf83cf2b910e43d461cd02">insertParsePoints</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#a16658fce14f4b2888f76f0972d239139">isFreeConcat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab0469afc3caef8616d4b1c7501cba1b8">isHorizontalBinOp</a>, <a href="#ada19bc367321342a58ed18b2a0e03e96">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isRangeInStorage</a>, <a href="#ac8019ffabda94935c17ae83f97db769d">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isReferenceToStorage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9855e2b319987248786fd81ba1d8c35d">isUpperSubvectorUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#adef158856b4fece74dc557d8c3212320">isVECTOR_SHUFFLE_SPLATI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a670137fe83c1213c3c2e82b8144e9af3">isWideDUPMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalopt-cpp-/llvmused/#ab0be9add964b354b741b4881efc2b40e">anonymous{GlobalOpt.cpp}::LLVMUsed::LLVMUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragemapping/#a91d6d8d5af0b8ba44a006860ef830113">llvm::coverage::CoverageMapping::load</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#aa40f4913df15aca03301144b7f1673df">llvm::MipsSEInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#a304b877a673788ae4edd0e8f5fa1d5d8">TransferTracker::loadInlocs</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#af64654b3c46ec3154963aed1dbb016d2">TransferTracker::loadVarInloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac7304188de3005e0d0f0a62cbff5ad31">lowerV16I8Shuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a96929c573ae5a98213a4d8c25554e53f">lowerV8I16GeneralSingleInputShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ac33e82a131d1fbb45282af6f71f1bd61">lowerVECTOR_SHUFFLE_ILVEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#afeb969a79018bac52d21bcfb43705342">lowerVECTOR_SHUFFLE_ILVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aab2c6ae0788500f10a4e102ab9d31380">lowerVECTOR_SHUFFLE_ILVOD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a294c52ead479abd3003207596dee2f38">lowerVECTOR_SHUFFLE_ILVR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aa1b6fff8c6938823f859ff9d8f17a823">lowerVECTOR_SHUFFLE_PCKEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a603a3b428c41e07bb96d88e57a7f24e5">lowerVECTOR_SHUFFLE_PCKOD</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a296cf971c4bc03d1b469f52b687661db">llvm::LiveVariables::MarkVirtRegAliveInBlock</a>, <a href="/web-llvm/docs/api/namespaces/shuffles/#a6abf8a645bd24dfb42085db9672ac39a">shuffles::mask</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/blockchain/#a939be2486e7faed5e6e1fd9d02311273">anonymous{MachineBlockPlacement.cpp}::BlockChain::merge</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a1dc2ed29bdcb3fedb0639cc8e88a7ecd">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeAssumes</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a2711d3bc7c6c769a8f34c7fc3937169d">llvm::Instruction::mergeDIAssignID</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#a06264674191b53ea377acb0fbf98c80b">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::moveElementsForGrow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#ad08f0dd526b3f602ccb0f0d39832ae08">llvm::sys::unicode::nameToCodepoint</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a4e10ba09dea9d13b485ec2a68efb4f98">llvm::sys::unicode::nearestMatchesForCodepointName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a8cd858c6644228cba53bd8631155b4a2">llvm::DWARFContext::normal_units</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a1b51573bc0b0e62d37537759a24a44c3">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyFreeingObject</a>, <a href="/web-llvm/docs/api/structs/llvm/sampleprof/samplecontextframehash/#a2b24a4a6c5c99e60c70e9dc95c945e9b">llvm::sampleprof::SampleContextFrameHash::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aa225cb6d40046134e5dc8fb135009568">llvm::const_iterator&lt; MemoryLocation &gt;::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#acd1bf4a3cc2b247cdeac15790a9e6a1e">llvm::SmallVector&lt; BitWord &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad39bccc86684b3407edcd580b5a38143">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#adfc4e95670f6dd96a86182e51411d47b">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a400590dcfcda901d773ddb593591bf9d">llvm::const_iterator&lt; MemoryLocation &gt;::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#afd07d19c7174c06cd7c7415f63596839">llvm::slpvectorizer::BoUpSLP::optimizeGatherSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#adee8390bf727c3086a7b864de6c6913e">llvm::X86FrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#aec5e1563ca339dbf7905cf069c364e39">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaPrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/spirvextensionsparser/#a9c59e739efd5cf76e15f932543c272e3">llvm::SPIRVExtensionsParser::parse</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ae577a9371ea38b78cffc39d0ca5f6623">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0048548b4f1cc9455cf3af293d2b52bf">performCONCAT_VECTORSCombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a92cef83bd2aaa8850f69f2cb852b3fe8">placeSources</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armoperand/#a5c87701e16414a07520790dfd88c52aa">anonymous{ARMAsmParser.cpp}::ARMOperand::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp/#ad6c7bb71f11814fe88bf73f5c589a9e0">ProcessElementList</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a65eee5509cce98dcc69693ea13bb9220">llvm::logicalview::LVBinaryReader::processLines</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#adf31f040a01939eb7f7b085e5dfc0485">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#a4cd364a560035d8414c3b21b2513b0d4">llvm::SmallVectorTemplateBase&lt; T, true &gt;::push_back</a>, <a href="#a23aab542398091e1fcfd46b6006d64ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rbegin</a>, <a href="#a8bbdaa9c9ad9b9f8d9418ba8a7bdc9fd">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rbegin</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#aa386dbcb508e02e5910438040aed2cac">llvm::BinaryStreamReader::readSLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab9f41a80bcb29a219eff47dfac886cce">llvm::BinaryStreamReader::readULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a126f33e8085746e4f69b4411b61102dc">llvm::RegPressureTracker::recede</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofreaderitaniumremapper/#ab9cbc0396671b685858c523ed763e724">llvm::InstrProfReaderItaniumRemapper&lt; HashTableImpl &gt;::reconstituteName</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a15993d541998ac409f0fe09abfef6fe8">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::RecordMatchingPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp/#a080cad1d991fe0de068a346aae7cb1be">RemoveInstInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a87dd1a69c8d8492e78b32708ceacb2c6">llvm::LazyCallGraph::RefSCC::removeInternalRefEdges</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#ab28699e21ef7b0aa06794bee56959a32">anonymous{CommandLine.cpp}::CommandLineParser::removeOption</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5b064b03163c5f9304d4b702da5fa1e4">RemovePreallocated</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ad959466c7f8b886a2caa4967c46d48db">removeRedundantDbgLocsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#a7241534b422b4edd167aedf565fb8d5c">removeRegLanes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a633db91afb11db086004de9e3eb37217">reorderOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4a3e80130d3f25468190ba343064b37e">reorderReuses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcorelowerthreadlocal-cpp/#a1ad5c109b5218ec1d5f5fcd6390636ba">replaceConstantExprOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a6300c8f1d33302d372c953398dd5f18c">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithNamedStructOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a8a6fce329f29e0ec830e61c629b70739">resolveSources</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a3fc78aa19b9e30af7cb534f1a58e22de">llvm::AArch64FrameLowering::restoreCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a26c8cba96e72f333e829e607938ce893">llvm::CCState::resultsCompatible</a>, <a href="/web-llvm/docs/api/classes/anonymous-loadstorevectorizer-cpp-/vectorizer/#afdc19a1fe655b43b92647431e2e8ec8a">anonymous{LoadStoreVectorizer.cpp}::Vectorizer::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionspecializer/#a27893e2167969de71fd88771382a93ad">llvm::FunctionSpecializer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#a98d8aaed2e429cfec371c300cb8244c2">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mergefunctionspass/#a9a54c5c31e75d72fccddee99422e6eb3">llvm::MergeFunctionsPass::runOnModule</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad272ce4631595e235e560baf59dc1ffd">llvm::setProfMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#ab068414df7b5a70b9ed5e2c342435703">setRegZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aaf604b7b4ff087fce0b71852f5ddefbe">setUsedInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a0f09c6db065cba05fa4431f921a73715">SimplifyValuePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a52b8b307321627e612e77041260ece84">sink</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a0a5c60e5cebd520f95b9813fd9807016">llvm::InnerLoopVectorizer::sinkScalarOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa725413bc28036ce9c795a24503f654b">llvm::coro::sinkSpillUsesAfterCoroBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/arraylist/#adf19460a3c702d261e7ffe25d77cabbb">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a38e68958dd4cc9e1c90b0abc432f5b09">sortGlobalExprs</a>, <a href="/web-llvm/docs/api/classes/llvm/intervaltree/#ac8662d075b7aefa245f4557a80bf1a24">llvm::IntervalTree&lt; LVAddress, LVScope * &gt;::sortIntervals</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a38d361ba1ba79b6217929ada0dd69cb6">llvm::AArch64FrameLowering::spillCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a0bb855d418108ea53140e71d7b35a2cd">splitPredecessorsOfLoopExit</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a603517a82c194cc3daa912831dff244a">llvm::Regex::sub</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a96fe0cb15ded58bd1824fa4e3daec680">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToRef</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loopstrengthreduce-cpp-/#a391c5efa7f6eb049718971aeeb9b71d5">anonymous{LoopStrengthReduce.cpp}::ToDwarfOpIter</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/scalednumber-cpp/#abbfb15ef66003a1f34d28fa4fb90ac93">toStringAPFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aae26f659b722d1d053b93b5f1735f52f">llvm::const_iterator&lt; MemoryLocation &gt;::truncate</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/preloadkernelarginfo/#a7a5253091344c2d534f5afd16941e25d">anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::tryAllocImplicitArgPreloadSGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ac48731694e324e56e35cb2b4f20345d0">tryToVectorizeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a9582935f8e1daa71195a6c76ce4f6c20">llvm::DWARFContext::types_section_units</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a00b3b7cedd83de61be0312c6535f3f37">unswitchLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a8fcc33897ff2ea4ebc874792c49497ef">llvm::BlockFrequencyInfoImplBase::updateLoopWithIrreducible</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a4cc24eca5caee29bd57f43e84c285ee3">llvm::GenericCycle&lt; ContextT &gt;::verifyCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a6dcb5e3d63691e83e0fdc0d67148077a">llvm::MemorySSA::verifyOrderingDominationAndDefUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp/#af743eac3b984c084268a3d988a8ea10c">verifySubExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a2337e506453c5ed1ec20ebabbafbc014">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/elfsectionwriter/#a9c48163b33da5da66af7a1e8f4deb637">llvm::objcopy::elf::ELFSectionWriter&lt; ELFT &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#aeb3015db092e8e97f7a585096688b6cf">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::vresize</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvector/#a548541a1080f84a4dbde718332e55ba5">llvm::SmallVector&lt; BitWord &gt;::~SmallVector</a>.</p>

</div>
</div>

### end() {#a0f315bc48d2692cc5a1630f616de9d09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end ()</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a> and <a href="#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### front() {#a58dc840fc84420b7f0b773794b8101c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front ()</td>
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



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a> and <a href="#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetree/#ad1246639c464dee99101df3e7c1c4dc8">llvm::MCPseudoProbeInlineTree::addPseudoProbe</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a0bfeadac5ccd4e56b4c5df9dc6bb8817">calcPredicateUsingBooleans</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af366ca9511826f13c9d2e4494be70cd9">combineHorizOpWithShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aab7406f11829e7505acce1a7d4a7803d">combineX86ShuffleChainWithExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a3c4c42f79d79638f6b67532d3f81df58">createPHIsForSelects</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtooffsettable/#a1878d931b7c5cb9a938690f5a73d75a2">llvm::StringToOffsetTable::EmitStringTableDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1a0afc5106fca20f0a81eac37db70ab9">ExtractImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a45b1664e25bf2a7220367462f2580044">ExtractSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/controlflowhub/#a14e3b2ee272be893fb7d474a5530705c">llvm::ControlFlowHub::finalize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a627bfd890830868bb678904545f95d63">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::findPotentialRemovedFreeCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad3e63520dcd2b8f8aa1b2e66e734a575">getBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/simpleddgnode/#a2c8f322bcf8257da90a51ba357cbca67">llvm::SimpleDDGNode::getFirstInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a957f4d1425cced530d8488b4bbeaa425">llvm::logicalview::getInnerComponent</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#afbbc2492f83b9a1b2b2b850283240272">llvm::TargetInstrInfo::getMemOperandWithOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#aeeee24e4951098e13042b484886d47bb">llvm::codeview::getModifiedType</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace/#ad7ced8a37469610d46bf6b393953ae1f">llvm::MachineTraceMetrics::Trace::getPHIDepth</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a0b43ef7c72a8cb10a0cb09154a3b3b2d">llvm::slpvectorizer::BoUpSLP::getRootNodeTypeWithNoCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate/#a334e7c41df90efd700b045c03de6777d">anonymous{ARMLowOverheadLoops.cpp}::VPTState::hasImplicitlyValidVPT</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a3b776824b1ee93e75dcf982fec706900">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51d22a1ed809d7cb1c1eb46c820c8226">llvm::intersectAccessGroups</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate/#a61d5b7da194d3f775ecff29cd3db526a">anonymous{ARMLowOverheadLoops.cpp}::VPTState::isEntryPredicatedOnVCTP</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a94f9cb330567d54bc528af741e5394f5">llvm::ARMBaseInstrInfo::isLoadFromStackSlotPostFE</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a3e4d8c321b37c4d5614fe02698a59cb8">llvm::LanaiInstrInfo::isLoadFromStackSlotPostFE</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aa24fb76f9bc9070c29523bd6cc691e5c">llvm::X86InstrInfo::isLoadFromStackSlotPostFE</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ae86f72dfcfa311751247ac3a6de57621">llvm::ARMBaseInstrInfo::isStoreToStackSlotPostFE</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a9399adfb855c15ccdbd484600cadd419">llvm::X86InstrInfo::isStoreToStackSlotPostFE</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate/#a3471d30b320c2d011979c2956eb33ab1">anonymous{ARMLowOverheadLoops.cpp}::VPTState::isValid</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a6a12fa96c1212a99f965fcce98aa550a">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::joinVectorElements</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a80314c2b261b78cb7335a265f43ba1b5">llvm::Legalizer::legalizeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a2c8f5eab9499a8b7a3238177f2ecf52c">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a1dc2ed29bdcb3fedb0639cc8e88a7ecd">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeAssumes</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a98a6af42792c32db070dee8826e1412e">llvm::sampleprof::SampleProfileReaderGCC::readOneFunctionProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#ab3635230226f6d60dad04b8e83d848fd">llvm::slpvectorizer::BoUpSLP::VLOperands::reorder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14c12bda1f5a9beed612b00f3f98b888">llvm::reorderScalars</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#abf799de7147065c0e7f525e1b6009dde">llvm::coro::replaceCoroFree</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#add7c3bdd8428904f63f53569807b8df6">anonymous{RegisterCoalescer.cpp}::JoinVals::resolveConflicts</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#a98d8aaed2e429cfec371c300cb8244c2">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#adc11c5fbec9bf293b000637357da66e4">simplifySwitchOfPowersOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ac48731694e324e56e35cb2b4f20345d0">tryToVectorizeSequence</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignfloating/#a0206ea336f22470d5fe01f65dae9eb85">anonymous{AttributorAttributes.cpp}::AAAlignFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceablefloating/#a41c5ffc9c348c806bd197076e245aa1a">anonymous{AttributorAttributes.cpp}::AADereferenceableFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanonnullfloating/#a4b1fa4ad98c736b05369d73702328439">anonymous{AttributorAttributes.cpp}::AANonNullFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoundeffloating/#a6b86977408d6fd3bc77f900143401adb">anonymous{AttributorAttributes.cpp}::AANoUndefFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abe0c2621dfb4c1e6bcfbaddc38fdf572">widenVectorOpsToi8</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#ac4946ac3df4a88e078136a4444ef1185">llvm::objcopy::elf::BinaryWriter::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0096360a382602b21e0e980fb8069d52">llvm::dxil::WriteDXILToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5858c9c8d861a0d36e7c8f99b8faf7fe">llvm::writeIndexToFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a33564097625c6a9b619c60a71343c058">llvm::writeThinLinkBitcodeToFile</a>.</p>

</div>
</div>

### front() {#adda3896b77b1f4cb8ece30c89581b5d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reference llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::front ()</td>
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



<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a> and <a href="#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>.</p>

</div>
</div>

### max\_size() {#ac098b1f6b194f100da588329fcba0b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::max_size ()</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#aefdd625e279120f6d413e59f712e97e4">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::SizeTypeMax</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### rbegin() {#a23aab542398091e1fcfd46b6006d64ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rbegin ()</td>
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



<p>Definition at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Reference <a href="#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a3d50f3f3bb104fb854ac8de326c5bb64">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindAvailableVals</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a0ab1c1435c29eea38d7a8dd64f064b84">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindDominators</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#aad5016c6fea77df1d3f4af224e1472db">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindPHIPlacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48dfb4cc4f8e3891dcba6f01530f6a95">foldICmpOrXorSubChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#ade3b3b604b9b365a57f791ab198a691a">getNoopInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#afccd5d8592120c2a9f275bf59223dfbe">rewriteAccessChain</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a96fe0cb15ded58bd1824fa4e3daec680">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToRef</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

### rbegin() {#a8bbdaa9c9ad9b9f8d9418ba8a7bdc9fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rbegin ()</td>
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



<p>Definition at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Reference <a href="#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>.</p>

</div>
</div>

### rend() {#ad696953257cf1c4e5bd12d02146e7287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rend ()</td>
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



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Reference <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a3d50f3f3bb104fb854ac8de326c5bb64">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindAvailableVals</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a0ab1c1435c29eea38d7a8dd64f064b84">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindDominators</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#aad5016c6fea77df1d3f4af224e1472db">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::FindPHIPlacement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48dfb4cc4f8e3891dcba6f01530f6a95">foldICmpOrXorSubChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#afccd5d8592120c2a9f275bf59223dfbe">rewriteAccessChain</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

### rend() {#afcddc80413694e433d45ea9fcd3b583a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::rend ()</td>
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



<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Reference <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>.</p>

</div>
</div>

### size() {#a1c479a8c434377c2b8cb056bdfdfc201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::size ()</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a13b6c3ad0bdee051eda42dc7c8a1f12b">llvm::SelectionDAGBuilder::addDanglingDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp/#a9baafe0b9a21c4fea0ca7cc671837a29">addData</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#aec802e48dd5ef69029e285eddfc4158d">addEdge</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#abfb093b6e752567e7a893c63309daa66">llvm::logicalview::LVScope::addMissingElements</a>, <a href="/web-llvm/docs/api/structs/llvm/bfi-detail/irreduciblegraph/#add4c9ca63093a8270248e72b08c5302e">llvm::bfi_detail::IrreducibleGraph::addNodesInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a3f1e8df5d1ec58e81979760331f7808e">llvm::AttributeList::addParamAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#aa27ad78489e8c685d427e45e6c4bc14d">llvm::mca::RegisterFile::addRegisterRead</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a3ceb460ebf70a2fe9a7eb07de595b3d1">adjustCostForPairing</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#af9b4f3c32f38913159a0ab75cb4bf133">llvm::detail::anonymous{APFloat.cpp}::AdjustToPrecision</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ade385868ff059bef6446f70208541043">llvm::SITargetLowering::allocatePreloadKernArgSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a4841be2489ba10321338a1874b53f249">llvm::StatepointLoweringState::allocateStackSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-minidumpemitter-cpp-/bloballocator/#af08557fb29f0c4129ff2121db66a7e43">anonymous{MinidumpEmitter.cpp}::BlobAllocator::allocateString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430isellowering-cpp/#ad996415c84f27a48afd2fd7dc653efea">AnalyzeArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/aixccstate/#afbbd090afb160a82e3ec6e2d8ef513d9">llvm::AIXCCState::AnalyzeCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a919797ac95a1d84d08e4f43eedededa4">llvm::CCState::AnalyzeCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#adaa4045817581b9868dc4ec086a3dc5e">llvm::CCState::AnalyzeCallOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzccstate/#ae7250b58d44250eb0604b1548bf2d304">llvm::SystemZCCState::AnalyzeCallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a0bf014c51371fcfb7c32e932c2d3b1d6">analyzeCallOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aa29e0988d94a53fecfac0bc63e665d06">analyzeCompressibleUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a882dcfc2455d525e78a8bbf46863ace2">analyzeExitPHIsForOutputUses</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a73b07a938dd8182363ba52719d38bf53">llvm::CCState::AnalyzeReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::const_iterator&lt; MemoryLocation &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#acf1f3ec6174852d235b520ae37b9a13c">llvm::const_iterator&lt; MemoryLocation &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a8508f3dbb1f9429445f50282297b4f9a">appendToGlobalArray</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#a08fddb3d382c1c806dee38774e6464d7">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::appendToVectors</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuexportclustering-cpp-/exportclustering/#a3432dbdb86f0a5f40c9d3bcfd8633b28">anonymous{AMDGPUExportClustering.cpp}::ExportClustering::apply</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a0c7442486454c55b94469e8b7c8ab468">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/bitvector/#ad6ca449f8f0ec4831ecb61be5b25a15e">llvm::BitVector::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a21bee05dda9718594fbfd89855272cd0">llvm::CombinerHelper::applyCombineUnmergeConstant</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#ae26a44292d42d576349e053e3497c18f">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtAddvToUdotAddv</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a0647544d97241e683cd0d0b7f3f51927">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtUaddvToUaddlv</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#abe54f9c905611b1e6439acf843ea29e8">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::applyFractPat</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#a568501d2ea6d5786f4981de195297020">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#afd96526160e781989c15d6879ad1f9f1">llvm::AMDGPURegisterBankInfo::applyMappingSMULU64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae4847ee848f0f09e6e3bee5ab50c4430">areLoadedOffsetButOtherwiseSame</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a83e6ea9ad14301bc03c55827f0689dc0">ARM64FindSegmentsInFunction</a>, <a href="#ae0e4f4c34cddd8f514efe4f9e0accf09">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::const_iterator&lt; MemoryLocation &gt;::assign</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armincomingvaluehandler/#a2d9bff6057c95e354dbc28e4604517c0">anonymous{ARMCallLowering.cpp}::ARMIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-armcalllowering-cpp-/armoutgoingvaluehandler/#ac2990fcd086ddeb552b46fe5d49c77de">anonymous{ARMCallLowering.cpp}::ARMOutgoingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchive/#ade18dcd47b2bf24e98be4745ef6139a9">llvm::object::BigArchive::BigArchive</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstackradixtreebuilder/#a05db798ae8ae11328fce938cd0d012f9">llvm::memprof::CallStackRadixTreeBuilder&lt; FrameIdTy &gt;::build</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a85cbdd891f1cd43d6c79f7d68a2caf46">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::BuildBlockList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a101a4250b1fd5a230a766de2a14cb271">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildEntryThunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af1364d76011b791bbac39ca8470dd2bf">BuildExactSDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a1ca08074fa512b26eb7e8e88833892d9">BuildExactUDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a36d1ac387bd87a2b357d7ca612d7d5f7">buildFromShuffleMostly</a>, <a href="/web-llvm/docs/api/classes/llvm/vplanslp/#a58eaa1512d1998338ab6f9e8e710a46e">llvm::VPlanSlp::buildGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a7075ef788cb3dea0ea239c1a6830734c">llvm::MachineIRBuilder::buildMergeLikeInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#abe954ecff531c2cb1dcca7ed8813a318">llvm::MachineIRBuilder::buildMergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a901a49f9b5721ab01d9d371f96e4bcea">llvm::MachineIRBuilder::buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#a7bc05bcba45ed1e4e903c1c952d09178">buildRegSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#ad069ce26777bd310235dc9e8f7d7e81d">buildRegSequence16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#a2eb27f39675fc1e8bd17f11e78e855d0">buildRegSequence32</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a9ef49346139404db3757cf8ba05dc6f2">BuildSubAggregate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a1e9e055fc19307bc3c7c1be6ccd36812">llvm::MachineIRBuilder::buildUnmerge</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a330499e5e11e1c2e82e0a8c7179f335d">llvm::MachineIRBuilder::buildUnmerge</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a91466f7a82e967ed765e6d876415a3b7">llvm::LoopVectorizationCostModel::calculateRegisterUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a4fc6667c0f14f4e871d21234a6726246">canLoopBeDeleted</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#af4645ff56012ec55aea9987f6200f2a2">llvm::LoongArchTargetLowering::CanLowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a47d09a5d5cd5e9a20ebb40a166823399">llvm::RISCVTargetLowering::CanLowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvcalllowering/#a672b2d48b831e2db6310036e4bf711d0">llvm::RISCVCallLowering::canLowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a411b83001c7fb0aa941c0f6daef18f05">llvm::X86InstrInfo::canMakeTailCallConditional</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a42ca2573c85e6aa37315472c556116d1">CanMergeParamLoadStoresStartingAt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab0e42c8902538c259f008a6e8c2709de">canonicalizeBitSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac1639f9e80414a665a5826e6e4ca6095">canonicalizeShuffleMaskWithHorizOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a98b4edd31a148a751a95e80997f81c31">canProfitablyRuntimeUnrollMultiExitLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#aab2eda4003703fcc548e36043debfafa">canSplitCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#a5e731292c2474865560219c29069c6de">canUseSiblingCall</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad6fc8ed265d8edfefb78f7985fed146e">canWidenShuffleElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7e7374e59505b56b9bf65507fb90dd40">casesAreContiguous</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a6790e830edd3f7940cc257f01a794604">CC_ARM_AAPCS_Custom_Aggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a54bef4de515c1876b876bac86b81975c">CC_LoongArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb12d99088ce4e78fe29e5306ab42c5c">llvm::CC_RISCV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a41dd5c8db0f0898d613b138097515474">CC_X86_32_MCUInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a4634e79ad97015aa93f2379f619cc6ae">CC_X86_32_RegCall_Assign2Regs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a61009b749b466b57d30ec5134bf613bb">CC_X86_64_I128</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acfe25d0718869b5fc9d85c1f96cec8ef">chainLoadsAndStoresForMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#ac41c50a3b85aa5098391b76548f04e3b">checkDependencies</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#abbea65eed8b9b7cd07f0b8eef53df6f5">llvm::Attributor::checkForAllUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a9b31375abd6555d0b68683aa7238fb8e">checkHVXPipes</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#aa1129d2080e1308fd9bd27d20374ace5">TransferTracker::checkInstForNewValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ab230432af09554d7dd357c77b0ec3cde">checkOrAndOpImpliedByOther</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a687c88d4217651cc56a5a4aed7c8364f">llvm::CCState::CheckReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ac7e0c0d229fea8210c669337efd43e2a">llvm::CallLowering::checkReturn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbd48a6ba727670df45deca96345e382">llvm::checkVOPDRegConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a98f2e06ea0575c5920f76e241e4cc65f">clobbersFlagRegisters</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#acb572d27661acd51c80b1bca18cd1ee3">llvm::orc::cloneToNewContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2d26c707fd7389b46ad98970d56faf24">clusterSortPtrAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a544a0723e20148ceb9a3bb3210f45270">llvm::collectChildrenInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9e8360ec6c03540a7ad4753613cfc66f">collectConcatOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe9c37f2ba2d21ae9e526ecec89d431d">llvm::collectGlobalObjectNameStrings</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#abc12092fd1db13a69edf142bcad15556">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::collectMemchecks</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a97b8f22f6c8ebb59fe454ba80d407baa">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::collectMemOpRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/dxilmetadataanalysis-cpp/#ab109200c3fd91dd6bf0176734ad64b1f">collectMetadataInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a8853b2033702691c17576d5acc430460">anonymous{PPCMIPeephole.cpp}::collectUnprimedAccPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a0ac5df8f0304981180d602dacb13512c">llvm::LoopVectorizationCostModel::collectValuesToIgnore</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a0130b17dd269a2bf18408bf108d2cf84">llvm::mca::RegisterFile::collectWrites</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a61e686ca7b81dbf342b3af2d4e23149e">combineAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac600ed8b11d7808711e809cfb7963089">combineBitcastvxi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ace3516d005e59a05c7b3ff975d063f23">combineINSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3ff4156c9862c64e6d354f5413c3da5e">combineOp_VLToVWOp_VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adeaf659e662150ed5f19eb4c9d7cbbb0">combineSetCCMOVMSK</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac52d67d57787e5d9c93fadbe593ada02">combineShuffleToZeroExtendVectorInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8af6dae0cb4e67d7004c888ed265f82a">combineTargetShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a208df5267fac83f34e5dbb36815b17b4">combineToConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#afb154334e7a7daa07012c210ddd77bc4">combineVectorShiftImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5c6a560bbaa7931f6375fd838fcfbaa8">combineVPMADD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aab7406f11829e7505acce1a7d4a7803d">combineX86ShuffleChainWithExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#a2d2b8c755a8e7b54f4680d27cd40d244">llvm::IRSimilarity::IRSimilarityCandidate::compareStructure</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/codemetrics-cpp/#aef97e4d556598a7e91419873352ed1ba">completeEphemeralValues</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a093b0a333833131b3fb12fb62f915bf1">llvm::EHStreamer::computeActionsTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5443261ddc0795520b7c673e11af38f3">llvm::ComputeASanStackFrameDescription</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9c3dc14da623315dbade0f0d23c8976a">llvm::ComputeASanStackFrameLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a49694eb08442bb35020b9d8dfad6d7e5">llvm::EHStreamer::computeCallSiteTable</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmexception/#a8db890ae03cb072b7198ebcc5d52028b">llvm::WasmException::computeCallSiteTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a356355a0c98d7b39551d7473665510f1">computeHeadersSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a1f1ea57bc156f9e309b4049bc1d10e17">llvm::EHStreamer::computePadMap</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#acada979e9424b6f61142bbca85a0fea0">llvm::FunctionLoweringInfo::ComputePHILiveOutRegInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6d6c53298316411b939795d6959322f2">ComputePTXValueVTs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4288169d91ab0f0f01405115fd2931a7">llvm::concatenateVectors</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ad60130f0b45a3ff1e759b010afefb94d">anonymous{ConstantFolding.cpp}::ConstantFoldFixedVectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#a6ef72ec0104739f72e030a7438753638">ConstructSSAForLoadSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#ad049a79d46df2c25561d90e9d80fb5e3">convertImageAddrToPacked</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad23b52a299ca563f6e6a6c6cece54dcc">llvm::convertUTF8ToUTF16String</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a6f467de3ca984f069ee86b9558388294">anonymous{OffloadWrapper.cpp}::createBinDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cd95c4fd57b9c1804bc70a37ac24574">llvm::createCFAOffset</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopaccessanalysis-cpp-/accessanalysis/#add290ed56a35aadf648ebccf66491f0f">anonymous{LoopAccessAnalysis.cpp}::AccessAnalysis::createCheckForAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a89565d08a98c901e24daed37f35cd442">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad301df8bf0c11d0c17113d3c221025d8">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#af7b1b04b85a4e865d887cbf6f5889a10">createDefCFAOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a88fd8d22fd3856c5ed785a7d9f2a736e">CreateNewABI</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a6022d366369fcd539dadfaefc80927db">llvm::MDBuilder::createPCSections</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsasmparser-cpp-/mipsoperand/#adaccd674ba7dc69d1ce2b88c6155e691">anonymous{MipsAsmParser.cpp}::MipsOperand::CreateRegList</a>, <a href="/web-llvm/docs/api/structs/anonymous-cskyasmparser-cpp-/cskyoperand/#a87fe45f7faab0a040752d07ee871f124">anonymous{CSKYAsmParser.cpp}::CSKYOperand::createRegList</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a8437f11cfb708e9bb288796d123e84dc">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::createShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0af3c7a02c1325c04c59f857604bd4f3">llvm::OpenMPIRBuilder::createTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aa37537b95a42a73ea04d8dd2803378da">llvm::sys::fs::createUniquePath</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/executestage/#a37610deca3b50b5c9974ba424c8a7ba7">llvm::mca::ExecuteStage::cycleEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue/#a3e5ffea0fa3c8e006a9bb56d22a0aa12">anonymous{LiveDebugVariables.cpp}::DbgVariableValue::DbgVariableValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/#a0bbf7be621bd7377f3f4a7498010f98a">anonymous{OpenMPOpt.cpp}::OMPInformationCache::declMatchesRTFTypes</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/vloctracker/#a7ee9cda71a5c099141ed832aae3e70a0">LiveDebugValues::VLocTracker::defVar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a64ecdacbd49f696216e772782a109945">llvm::DeleteDeadPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a49197b24cced248bed2d2c89c641a6dd">llvm::DependenceInfo::depends</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp/#a755b4fb8450994d9125dbcd317bc4fc0">DoLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/mcfragment/#a73af1340aaefb3f64c1e4000ce6254e4">llvm::MCFragment::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#abdeee9a5e03a99e0c073cc103f75d1e9">dumpBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0303c1c5d962299e9e554c11e5400b19">llvm::EmitAnyX86InstComments</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6c1f3151b66ea2dfd6a8b9cef815d51c">llvm::X86FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b67472deb590ff2b82c73e3ff4497f4">llvm::AsmPrinter::emitConstantPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a8ea1d38f4a65135188eb7409818070e6">emitDarwinBCHeaderAndTrailer</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4372f5cbd92647d1f4f90fcdb8a5474">llvm::emitDWARF5AccelTable</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a14e6ca2286bfbfa6952e74370a9c563b">llvm::PPCFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a420cc4a7a63b33a52659768b133b5f1b">llvm::EHStreamer::emitExceptionTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a232c76d4c06ded6c02597dfae877aca3">emitExternalFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#af49d69e68344d6292702edca157e7eed">llvm::AMDGPUAsmPrinter::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a88fd52c520cef6a03af97c37c308ae78">LiveDebugValues::MLocTracker::emitLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetwasmstreamer/#acd61544675a1873eab270dd83138d509">llvm::WebAssemblyTargetWasmStreamer::emitLocal</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a827b80924bcd29f32b772a4ed162fb68">llvm::OpenMPIRBuilder::emitNonContiguousDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/unwindopcodeassembler/#ab1cfb912a74d848789c9edb810753f17">llvm::UnwindOpcodeAssembler::EmitRaw</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#af7b885257ab544caad5ce47c9939079d">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitRegSave</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ae9c7bfbd6f1a6b08ebabb1ca16be3d7e">llvm::MCStreamer::emitSLEB128IntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a06dab5b53d53c65a118f25ea11570352">llvm::WebAssemblyAsmPrinter::EmitTargetFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a2841680b34ec9c2c7185a877f8f8b4c8">llvm::OpenMPIRBuilder::emitTargetTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a9702d30c99a5459e9565631adf1fdf1b">emitTaskDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#abc5f738b9471c3ed31b8f1fc7dc8e914">llvm::MCStreamer::emitULEB128IntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3bb33831dbcaa836f630ed1dc986b5c2">llvm::OpenMPIRBuilder::emitUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::const_iterator&lt; MemoryLocation &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#aea53ea050c3442abffd1c991f4c7213a">llvm::CodeViewContext::encodeDefRange</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a2c00c11ef810b9f4ca1781a341de60d3">llvm::CodeViewContext::encodeInlineLineTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86mccodeemitter-cpp-/x86mccodeemitter/#a326c8dcef7365124098e7573ebe4bd31">anonymous{X86MCCodeEmitter.cpp}::X86MCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a90b631351c27f8d64f1788ec334d7b4c">llvm::COFF::encodeSectionName</a>, <a href="#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#a0f315bc48d2692cc5a1630f616de9d09">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvline/#af59d9bef370b8a61e8c2e49d0b930f74">llvm::logicalview::LVLine::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#abce6aa704120de7b798aabe5a5571abb">llvm::logicalview::LVScope::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol/#ae9167d7d1b415df0c28c5178ae88f3f8">llvm::logicalview::LVSymbol::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype/#aeeeaba9368ad74c9e45f53bfe1945446">llvm::logicalview::LVType::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/evaluator/#aac9fd94c18d93885c8d947121ab9721e">llvm::Evaluator::EvaluateFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizedag-cpp/#a07a2d3fcc11565312fcc713d6cf38c6f">ExpandBVWithShuffles</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a4b23196df4c243ce29f29f54a26cae7e">llvm::ARMTargetLowering::ExpandInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a687e754bf03f8d135bc899b49db74472">llvm::X86TargetLowering::ExpandInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71f46ea083b99c11351681d613bde3d0">llvm::extractBranchWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a47832d6753036cd8ce039993854b3162">llvm::extractInstructionFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a78e425f7e61cda2ed4db6054c39beb18">llvm::LegalizerHelper::fewerElementsBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#addd0c111e12b07d02698a1fdcba59b0d">llvm::LegalizerHelper::fewerElementsVectorReductions</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/vregfilter/#a7e8736b28b4391ab04842fa61209e86b">anonymous{MachineVerifier.cpp}::VRegFilter::filterAndAdd</a>, <a href="/web-llvm/docs/api/structs/llvm/controlflowhub/#a14e3b2ee272be893fb7d474a5530705c">llvm::ControlFlowHub::finalize</a>, <a href="/web-llvm/docs/api/structs/llvm/pdb/gsihashstreambuilder/#aeeea059832463bed947024ffb5b6f977">llvm::pdb::GSIHashStreamBuilder::finalizeBuckets</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a537993928c8af5b0d064fcd5ce1dec2f">llvm::CodeExtractor::findAllocas</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a174350306649bc16f97803763bcae8f7">llvm::findArrayDimensions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/delinearization-cpp/#a80f3984cb81d6b8e7810c8b313739043">findArrayDimensionsRec</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a0dca3347facf58865b34df5e5df676f0">llvm::MustBeExecutedContextExplorer::findBackwardJoinPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constanthoisting-cpp/#a48a060decf79d58559a8e9e28df764f0">findBestInsertionSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a296bc5fd6767824b2baf15675296743f">findBuildAggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#afe024d2bcdcaa9644b7270f84edd74a5">findForkedPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a202c5827957336be308d423d78ff7119">findForkedSCEVs</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#ab0cac3cc09d07bc44ffd388ff8be5e49">llvm::MustBeExecutedContextExplorer::findForwardJoinPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#aa24141aebc0d8b15405be6bcb7b6319b">llvm::sampleprof::FunctionSamples::findFunctionSamples</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae29b7bb67763c63132e57471f88ac80f">llvm::FindInsertedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a627bfd890830868bb678904545f95d63">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::findPotentialRemovedFreeCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a07a6eb3eef6937d9da40864010f07dbf">findRematerializationCandidates</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#af8ac96c98d73833321b6d95a9c88b9d4">llvm::slpvectorizer::BoUpSLP::findReusedOrderedScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/regbanklegalizehelper/#ae520a3c8f4f3de236034665deae793cf">llvm::AMDGPU::RegBankLegalizeHelper::findRuleAndApplyMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa2dfd6ae7ded046f5e5e03e0f745d5c3">llvm::MachineInstr::findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#abe0dacfb2237ff8fb43d5ad22ac45d5f">anonymous{CoroFrame.cpp}::FrameTypeBuilder::finish</a>, <a href="/web-llvm/docs/api/classes/llvm/spliteditor/#a98fa413da7a0053bf635119e74970219">llvm::SplitEditor::finish</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a11f3e864193e615bb8e8bda2cca24ff3">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::finishLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a9df1b82e469730d220e3a8d28eb985e8">fixupShuffleMaskForPermutedSToV</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9317f2efaf85a4afc7cde58a2c0d734b">llvm::InstCombinerImpl::foldBinopWithPhiOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad600d9077d7e1eadff1334ee14f7f25a">llvm::foldBranchToCommonDest</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a804421879fbddb541d8393ec3c3730ee">llvm::DIExpression::foldConstantMath</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a65dff372171f9d4e3e07a272214fb94d">foldExtractSubvectorFromShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a9fcd68a333f3123b4b1cfb871ef3d89a">foldInlineAsmMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc9feb478a72bb822133b6eec00bef9f">llvm::InstCombinerImpl::foldPHIArgGEPIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a98282716af42c878d4638603c6efb350">foldSelectShuffleOfSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a57d5dcc6c4a3f7dff5df68d2f2791bde">llvm::memtag::forAllReachableExits</a>, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#a860821de65f9474bc7c8dd1f1bb9c229">llvm::InformationCache::foreachUse</a>, <a href="/web-llvm/docs/api/structs/llvm/fmtalign/#a06665722517b54511c786e23deb8ec81">llvm::FmtAlign::format</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a480bd8ae64f6f3e4a9cc6e1a724b2ad0">forwardSwitchConditionToPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/ehframecfiblockinspector/#ad58e7c9140c2bee787d0e5f8f253af89">llvm::jitlink::EHFrameCFIBlockInspector::FromEdgeScan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchmatint/#a1e8bf674882ab22f3fa510916fab18fe">llvm::LoongArchMatInt::generateInstSeq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a163e06959afb15ae88efade9bb975e27">llvm::RISCVMatInt::generateInstSeq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmatint-cpp/#ab9f36d4e7420ac603ea578f39ab9aeea">generateInstSeqLeadingZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#aaba8002e40481888d8e4933ce4487081">generateNewInstTree</a>, <a href="/web-llvm/docs/api/classes/llvm/prediteratorcache/#aa4997ba4fd2495e1737dcf98457f8419">llvm::PredIteratorCache::get</a>, <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#af99419a971a2b329732cb2a89e6a004b">llvm::RecordRecTy::get</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a78171da3a30a449d469ccebbff57760e">getAppleRuntimeUnrollPreferences</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elfnixplatform-cpp-/#ae8fb1e7d144d58bebdc065615673d9f4">anonymous{ELFNixPlatform.cpp}::getArgDataBufferType</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#ae92d755a80dec605503e2ba653765360">llvm::Attributor::getAssumedSimplifiedValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a7fe8accb4198eb111067fe7c4bb544dd">llvm::omp::getBestVariantMatchForContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad3e63520dcd2b8f8aa1b2e66e734a575">getBranchWeights</a>, <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a085e72b5a3ed050deb15aa57090c54ba">anonymous{ConstraintElimination.cpp}::ConstraintInfo::getConstraint</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a0b9027fe8e7ff91d9d6ee565fbdb3db4">anonymous{DeadStoreElimination.cpp}::DSEState::getDomMemoryDef</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a84ea0567e15790f68c421dada011ec5f">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyasmprinter-cpp/#a0a97488075cd2fcd03613374a36af571">getEmscriptenInvokeSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a9e635b2c582b6500e2c79faf06360ca2">llvm::GenericCycle&lt; ContextT &gt;::getExitBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ac10dff634cacc4be44046af5ee45f92a">getGEPCosts</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdecodedpseudoprobe/#ae65fd4d6ca6b5107072abefc811a63b0">llvm::MCDecodedPseudoProbe::getInlineContext</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a957f4d1425cced530d8488b4bbeaa425">llvm::logicalview::getInnerComponent</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/lib/target/riscv/mctargetdesc/riscvmatint-cpp/#af68372c2e557ba09bc11be98bc3d65e3">getInstSeqCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a10d66ea364d36a165309638f88ef0b0f">getIntOperandFromRegisterString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#ac3cb3b8d15dadee766eed8f3eac75ff5">getIntOperandsFromRegisterString</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyframelowering/#ae8c531c36381ca6a666ca73f740335cb">llvm::WebAssemblyFrameLowering::getLocalForStackObject</a>, <a href="/web-llvm/docs/api/structs/llvm/expressionformat/#a3fa2c7609bef28d6ba5bdb542fb40f2d">llvm::ExpressionFormat::getMatchingString</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#acfb93588e65e2c1c3e35ba88168478c5">llvm::WebAssemblyAsmPrinter::getMCSymbolForFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#afbbc2492f83b9a1b2b2b850283240272">llvm::TargetInstrInfo::getMemOperandWithOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#a56378412b516c96bbab7cd31b530e0ff">getMinAnalyzeableBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aac6e3a0dec40a6721857cbbd4330039f">llvm::MDNode::getMostGenericRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#ade3b3b604b9b365a57f791ab198a691a">getNoopInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#ad4c0f9a1193f368bbea577f429a3050c">getOpEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringbase-cpp/#acd9d92f0d78ae680c0eb2a43573b93ff">getOpRefinementSteps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a138bc82a9943aa3008ab86bec2d2c91a">getOrCreateFrameHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodaghvx-cpp/#ac23c0fbf5fee5c6f9a064f2e5be18de7">getOutputSegmentMap</a>, <a href="/web-llvm/docs/api/structs/llvm/hvxselector/#ae954fcbf0e9b2fe89cfa9d21b931b063">llvm::HvxSelector::getPerfectCompletions</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/trace/#ad7ced8a37469610d46bf6b393953ae1f">llvm::MachineTraceMetrics::Trace::getPHIDepth</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a8d7f8a73873448dc2bae97e066450dba">llvm::NVPTXTargetLowering::getPrototype</a>, <a href="/web-llvm/docs/api/classes/llvm/filecollectorfilesystem/#a433f751b01af0722012a9d12ae43b6e6">llvm::FileCollectorFileSystem::getRealPath</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a175f10e8ec1c2ec4fa24431ac5429a36">llvm::GetReturnInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a81f7fe4844c408d799428082f599c40b">llvm::DominatorTreeBase&lt; BlockT, false &gt;::getRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a575e3a33ce947932f93b30172ca12f05">llvm::GetShadowBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#afbd7d98aac4140ad6a3343443bed5d9b">getShuffleInput</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a110f1f473cbb5a42bf9c82973ac9101c">llvm::DependenceInfo::getSplitIteration</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a70d3e07bad78e3a1d2ba86aa871b9501">llvm::SelectionDAG::getTokenFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#acbfe0838b184a2df083679877c27c27f">getTwoPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#acbd00405fe4d2eca789c1225e75bc53f">getUnmergeResults</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6c22989c03e43928e4b09cfa60a804f5">llvm::ARMTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a978825baa870839107dcb64531311bca">llvm::RISCVTTIImpl::getUnrollingPreferences</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a4f6c8ac18caa1b4beaf0d4d88b82cef9">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::GetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe3b2bbac4396d088da5c91f77754843">llvm::SelectionDAGBuilder::getValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6ad5c1831928ee2c6c5058d9580edf">llvm::getValueProfDataFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#a0776bd50b7c822627400a43977db933b">getVariantMatchScore</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af0de1c3bdac42cb94cca3cce185c3d8a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::growAndEmplaceBack</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a42f8a757a6664d70f52ec96f1b433d3d">llvm::CallLowering::handleAssignments</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#aeb0bc3fb3008d1f61c5a1adb0b901c82">HandleMergeInputChains</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepc/#a4f573eb08d6775d4348ae9efd7532f7a">llvm::orc::SimpleRemoteEPC::handleMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/simpleremoteepcserver/#a7cebd705ee395af11d16ce83bad8060e">llvm::orc::SimpleRemoteEPCServer::handleMessage</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae3c237cad94f54f0d82a18a131709d41">llvm::TargetInstrInfo::hasLoadFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a5df2834716ee814af9f2555897ecb932">llvm::TargetInstrInfo::hasStoreToStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a4cda46bdec29ace64dfd3dff3e55bbf3">hasSupportedLoopDepth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e6dfe0eaf6d1b1720be0390c764cdbd">llvm::HexagonMCShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedc31552ebf0ce116c665da44b4a97a5">hoistLockstepIdenticalDbgVariableRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a697cde840957bbc0b2848a593c3e0d5a">hoistMulAddAssociation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a9396319801f74828cfbd94177f38eabc">hoistPreviousBeforeFORUsers</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a3b776824b1ee93e75dcf982fec706900">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/#a7cc7cd380b6ceacc35ef685d5b047d80">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::identifyReductionNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64speculationhardening-cpp/#aaf42ae80200bb2380ef4be8ff9c28402">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksectionsprofilereader-cpp/#a2780e898f2ba16d5d24787e5e2126c29">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a95851c48d68c2406ef12a7cca9c65f76">initializeUniqueCases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a65c7a8ebc9a13366a19e1573563cbe0c">llvm::mca::initializeUsedResources</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a59fd5e59ca0c03b061035a6c9de2b39c">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a520e903dce9cfbdd0d1073fe447ce52e">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4dfea19770364b880a77c3f0c1c0f67c">llvm::insertDebugValuesForPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a1e16838ab40f751bc24dfa455620ed06">insertInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a864a2ad11bbf83cf2b910e43d461cd02">insertParsePoints</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a78ca5c76a5ac76f5ad51ce5ced36fbb8">llvm::CallLowering::insertSRetIncomingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a33a30176a7fd636333a4e618ef109f57">llvm::CallLowering::insertSRetLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a852a45fa0766bf5cb65ea6010d32330a">llvm::CallLowering::insertSRetStores</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#aaf3ba7d78f09755223609e4978bebef7">llvm::LazyCallGraph::RefSCC::insertTrivialCallEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a393b4565f554b9d8382c8f610b7f2ce7">llvm::LazyCallGraph::RefSCC::insertTrivialRefEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a33b84baa49efc1f81ba74a43da0119b5">insertValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#afdcb3be103dc32527286d0352eeacdd6">instCombineSVEDupqLane</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a489ae04c136c4b088d849d7d6dc20965">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51d22a1ed809d7cb1c1eb46c820c8226">llvm::intersectAccessGroups</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aec461d6b4eaa16935dd0b7691b39ec4a">isCheapImmediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4e63dbf00030b7eb77100635a4ac5c5a">isConstantPowerOf2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ae914ecbf92d09be7f8da203ec3dd5bbc">llvm::X86::isConstantSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a37f06b796addd745c44af4546b84fe76">isFNEG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab0469afc3caef8616d4b1c7501cba1b8">isHorizontalBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a94f9cb330567d54bc528af741e5394f5">llvm::ARMBaseInstrInfo::isLoadFromStackSlotPostFE</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ade4086b409f00a755cfc6c0b03f67413">isPointerValueDeadOnEntryToFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a365173e63bd73b3ee58033678429636e">isPotentiallyReachable</a>, <a href="#a68e0dd48505f955c8681f11b6957afdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isSafeToReferenceAfterResize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#af94365b75e01f45bde3699f009aa431e">isSlicingProfitable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a56e44807cae1089569cdd78a6455b4a5">llvm::memtag::isStandardLifetime</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#ae86f72dfcfa311751247ac3a6de57621">llvm::ARMBaseInstrInfo::isStoreToStackSlotPostFE</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a94ebe004dfbba2e68530d0125ed16293">llvm::mca::ResourceManager::issueInstructionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9855e2b319987248786fd81ba1d8c35d">isUpperSubvectorUndef</a>, <a href="/web-llvm/docs/api/classes/anonymous-armlowoverheadloops-cpp-/vptstate/#a3471d30b320c2d011979c2956eb33ab1">anonymous{ARMLowOverheadLoops.cpp}::VPTState::isValid</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-basicblockpathcloning-cpp-/#abbaff7e4a8cdaa59924d29ba6e305f4a">anonymous{BasicBlockPathCloning.cpp}::IsValidCloning</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#adef158856b4fece74dc557d8c3212320">isVECTOR_SHUFFLE_SPLATI</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a5eb76849763054986dcdd4f2f41d369e">anonymous{DeadStoreElimination.cpp}::DSEState::isWriteAtEndOfFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a2b10543d5f749956dd408fd7ebb3c552">llvm::LiveRange::join</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#a6a12fa96c1212a99f965fcce98aa550a">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::joinVectorElements</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp/#a2362bf87bb40f033c5d60556c196432d">llvm_getMetadata</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga8e9d8283d0b2d13fc9f119c00730c4e1">LLVMCopyModuleFlagsMetadata</a>, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga515bb8a9dede000b935e77958f35a4cf">LLVMGetDebugLocDirectory</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga46f93df14e032eacb6cc772e0a9a03ed">LLVMGetDebugLocFilename</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga886911b0d3c9399b014304c8fcb39ebb">LLVMGetDebugLocLine</a>, <a href="/web-llvm/docs/api/groups/llvmcobject/#ga59e1c8aada118b78e806cf237418233e">LLVMGetRelocationTypeName</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga4af207d5a28d38c765a7f33d658df2a5">LLVMOrcExecutionSessionLookup</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseinstrinfo/#aa40f4913df15aca03301144b7f1673df">llvm::MipsSEInstrInfo::loadImmediate</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#aeb221ffeffa3ec7eaaa8eecf37b0146d">llvm::object::ELFFile&lt; ELFT &gt;::loadVersionMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aba7165df55c01bd2653b37a6e9f4a8ae">llvm::lookupBuiltin</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe97e2bc5bd74272ca1b54da1fb30e06">llvm::SelectionDAGBuilder::LowerAsSTATEPOINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abce17120537283b4104f8e1a7cad02a2">lowerBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aeed184a32cfc1dd279753d4a633bfba1">lowerBuildVectorViaPacking</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a5043353fac5252fc897dd06360274fe5">llvm::HexagonTargetLowering::LowerCallResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreisellowering-cpp/#a1a9dd0281442f33e9d9c88a3162d0274">LowerCallResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcisellowering-cpp/#aa0dc943f955ef5657bcc9eb702f611fd">lowerCallResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6f6622d37de7bdbf2708835f57864a96">LowerCONCAT_VECTORS_i1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab8b58d0a8c95d411d0f7aa891c9fd3f1">lowerConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a76e5a8c6363a48b3ca4e924a8f59f0e5">llvm::LegalizerHelper::lowerExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#af4e7be374a3346400a32967d91108c3e">llvm::LoongArchTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a6107db1593ae7bb4074d606368898747">llvm::NVPTXTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abae2fc34bf7e289e53e0abf82feea144">llvm::RISCVTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#abd42e7de94d28ca6667b61e1bcba6dce">llvm::VETargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac2d9e284d06499be56d61b876e86dc8a">llvm::AArch64TargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a5e5cf24df0a45159407988a98fe42700">lowerPtrAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a33edc5c19a9e674e389ecc1320464e23">llvm::HexagonTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#aece826681b1fdc9ec7c82f4a9152000f">llvm::LoongArchTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a5f7819dcae52567c11033d63e3d6421a">llvm::NVPTXTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4ce28f633cfe7a89369965cd9792e8fb">llvm::SITargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a3a9a464956d7d22291e5a6a29d4266e5">llvm::SystemZTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a73a391aef4505ecba196737cabb18ca0">llvm::VETargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ae491d50e304bf7057a2f4dfbf1650e56">llvm::XtensaTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a97357df4054a9551eb9a07b609cea109">llvm::SparcTargetLowering::LowerReturn_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#aa76596666bd4af3c0104b7a8fd514db0">llvm::SparcTargetLowering::LowerReturn_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9cca449265297eb5a0bde5f0e48b7c22">lowerShuffleAsBlend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aeefb78459638421a22efc227acbf0a2a">lowerShufflePairAsUNPCKAndPermute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3ae7a219ba4edae3c3b73ed2e34a4b01">lowerShuffleWithUndefHalf</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ae51c8cf31e26c03753e3f6acb6f48d56">llvm::LegalizerHelper::lowerTRUNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aafaf042072012185fe6b59d16b306644">lowerV16F32Shuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a764da3f6d8f5529a23fc52e4705d2fc8">lowerV16I32Shuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac7304188de3005e0d0f0a62cbff5ad31">lowerV16I8Shuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1e7c6d51f5fc88c995098264f649357b">lowerV4X128Shuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae4a4583d15a1549667880c7bfb8d1515">lowerV8F32Shuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a96929c573ae5a98213a4d8c25554e53f">lowerV8I16GeneralSingleInputShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a18af24f5c6174c2b5745fb2df1f6681f">lowerV8I32Shuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#adeacac9b0dabeafe536c99c4c3151fef">llvm::HexagonTargetLowering::LowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04b59de220180462277a0d8d7f146b0e">lowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ac33e82a131d1fbb45282af6f71f1bd61">lowerVECTOR_SHUFFLE_ILVEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#afeb969a79018bac52d21bcfb43705342">lowerVECTOR_SHUFFLE_ILVL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aab2c6ae0788500f10a4e102ab9d31380">lowerVECTOR_SHUFFLE_ILVOD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a294c52ead479abd3003207596dee2f38">lowerVECTOR_SHUFFLE_ILVR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#aa1b6fff8c6938823f859ff9d8f17a823">lowerVECTOR_SHUFFLE_PCKEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a603a3b428c41e07bb96d88e57a7f24e5">lowerVECTOR_SHUFFLE_PCKOD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ab9727a5e10901bbe1944e833c9c529cc">lowerVECTOR_SHUFFLE_SHF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ab8d9e84c7d48cbe98372e43cc9f009d6">lowerVECTOR_SHUFFLE_VSHF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ad4bdd437656a3e83cf59d55f7cb87582">lowerVECTOR_SHUFFLE_XVSHUF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a5c0b59043e612b22bd1b30c674325afa">lowerVECTOR_SHUFFLEAsVSlidedown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a368216c9c116e3f30d8dd352ce1370fc">llvm::makeFollowupLoopID</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#acad221a6df1d4872c6cca80bc913f7b7">makeStatepointExplicit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a9971c8a3647ef1b5439ed7cd18aee749">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a2c8f5eab9499a8b7a3238177f2ecf52c">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::manifest</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a23cdde8b9bdd40fd4a93d3635ca77dc6">llvm::Pattern::match</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0a69bfc728391a45832d24dca6c93abc">matchBinaryPermuteShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a5709dda6e8778748a5159cb8ed2d37f6">llvm::CombinerHelper::matchCombineMergeUnmerge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a17dfad57f1487bb34ef68784a2e878c8">llvm::Intrinsic::matchIntrinsicSignature</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a8ed1d04073cbd814c13097e138d462e6">llvm::CombinerHelper::matchNotCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aa435f2b01aca963d926bd31cd95e7f03">matchPERM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a079f719b6af4bba305e041821a1e3da0">matchScalarReduction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adcfb42fd1c2e2adbd26d6050f7979e05">matchShuffleAsByteRotate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6fbf492764a869e2539fbdaf90b259f3">MatchVectorAllEqualTest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/anonymous-memorytaggingsupport-cpp-/#a8793d0fb7bcb2cf8de89c7be933f24be">llvm::memtag::anonymous{MemoryTaggingSupport.cpp}::maybeReachableFromEachOther</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#af699e5a47a59c1c3b1044c30f999df43">anonymous{ELFObjectWriter.cpp}::ELFWriter::maybeWriteCompression</a>, <a href="/web-llvm/docs/api/classes/llvm/globalmergefunc/#a31ba90bd367677d2bf4065d6e51eca65">llvm::GlobalMergeFunc::merge</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a1dc2ed29bdcb3fedb0639cc8e88a7ecd">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeAssumes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a6118e1e5d926f231bd7f007b2ed1b412">mergeConstants</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a6277ecb456c87743b292a5dd69542a4e">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a627f84abfceb75ffd72119423d0147a4">mergeVectorRegsToResultRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ffccbb574e8a2cf63b8ede89f53090b">llvm::LegalizerHelper::moreElementsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a148f25a7131bb353315edfc43df0c79c">llvm::RISCVInstrInfo::movImm</a>, <a href="/web-llvm/docs/api/classes/llvm/injectorirstrategy/#a22c46265af5b3e456243d03b635ae9bd">llvm::InjectorIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/insertcfgstrategy/#a4a797db667ae87ab16b62a35de4f4a01">llvm::InsertCFGStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/insertfunctionstrategy/#a51a23cfe8db3e31fdc6eeb8547df0d33">llvm::InsertFunctionStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/sinkinstructionstrategy/#a3ca14f887397b546b6b253d3e82ed4ee">llvm::SinkInstructionStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aea9d2b3b2a626fb7c5093f5f8fa9cf95">llvm::LegalizerHelper::narrowScalarAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8a4aeb9640ed05629f69b925f53ae366">llvm::LegalizerHelper::narrowScalarBasic</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aaec7c9b0ed49d3297c833d8d9def42c0">llvm::LegalizerHelper::narrowScalarExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad43f277d8baa4b080bfd1beed8542bd6">llvm::LegalizerHelper::narrowScalarInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8f6f143ae3ebc33b4f3f97e486bf7112">llvm::LegalizerHelper::narrowScalarSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a4e10ba09dea9d13b485ec2a68efb4f98">llvm::sys::unicode::nearestMatchesForCodepointName</a>, <a href="/web-llvm/docs/api/classes/llvm/escapeenumerator/#ac63ecd195310b8a31b445bb613028893">llvm::EscapeEnumerator::Next</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5c2fb6bace55f9b58ed0ba9fe363299e">llvm::Triple::normalize</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/executestage/#a835477504117bd95fb32a9ea60e4b42b">llvm::mca::ExecuteStage::notifyReservedOrReleasedBuffers</a>, <a href="/web-llvm/docs/api/classes/predicate/#aad484130d00678eaec15a32d2f0c1970">Predicate::operator&amp;&amp;</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/callstackidconverter/#acf8ed567dc92ae1b877163bfc0ad4519">llvm::memprof::CallStackIdConverter&lt; MapTy &gt;::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/blockfreqquery/#af8c521993231c6aa85baba8f8c23b828">llvm::orc::BlockFreqQuery::operator()</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorloopcarriedreuse-cpp-/depchain/#a0c73d1d0b9cad8b2456795c88e47b619">anonymous{HexagonVectorLoopCarriedReuse.cpp}::DepChain::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#a125f77300db175faeae41d9a628194d6">llvm::BitTracker::RegisterCell::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a980a91d30111be065234c1dac2f067e1">llvm::raw_ostream::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64targettransforminfo-cpp-/tailfoldingoption/#a5df8b2fca0d3dc356531c2f218468d2f">anonymous{AArch64TargetTransformInfo.cpp}::TailFoldingOption::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad39bccc86684b3407edcd580b5a38143">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#adfc4e95670f6dd96a86182e51411d47b">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/structs/llvm/bittracker/registercell/#ab599ca7f603b5faf8d74dfe154e978ab">llvm::BitTracker::RegisterCell::operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a400590dcfcda901d773ddb593591bf9d">llvm::const_iterator&lt; MemoryLocation &gt;::operator==</a>, <a href="#aaaa3b341d046538bc32d1fa942c14dd0">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::operator[]</a>, <a href="#a620fc60422ca6f659337204be4bb9a75">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::operator[]</a>, <a href="/web-llvm/docs/api/classes/predicate/#a8cc1a53fd1d482890f9da59b0ad880e4">Predicate::operator||</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aef572ae661cf9f5b14651ef952629c10">OptimizeAwayTrappingUsesOfValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64redundantcopyelimination-cpp-/aarch64redundantcopyelimination/#a1ee0cfcd17ed3a5b4826b8a5f93e50e1">anonymous{AArch64RedundantCopyElimination.cpp}::AArch64RedundantCopyElimination::optimizeBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#afd07d19c7174c06cd7c7415f63596839">llvm::slpvectorizer::BoUpSLP::optimizeGatherSequence</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#a3a573419fed83f23b6bf70ac6731dbfa">llvm::VPlanTransforms::optimizeInductionExitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8b1b5c42e2e99bb24a27219f8df7294d">OptimizeNonTrivialIFuncs</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a897d513f6255e5eeaba5074ca4095230">llvm::HexagonFrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a420e13f932ebcdd50a90e807d5e5674f">llvm::SystemZELFFrameLowering::orderFrameObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodaghvx-cpp/#a72008f93dcab17ba9c0e64f267fd0fab">packSegmentMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#aec5e1563ca339dbf7905cf069c364e39">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaPrefix</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a112639954fd036a8748791f74d0db6fb">anonymous{X86AsmBackend.cpp}::X86AsmBackend::padInstructionViaRelaxation</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#ab7cbed44cf5366935e93c0a0182dfd5f">llvm::CallLowering::parametersInCSRMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/packedversion/#a607acfa934a3c0188743a1edac5b3826">llvm::MachO::PackedVersion::parse32</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/packedversion/#a6954336e0b10193d5bea01a716c5f182">llvm::MachO::PackedVersion::parse64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a90003a10d0a38bad6982d3037ffaf2e1">parseAnnotation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#abe6ae134b151b2a3091884f7e3b049e7">llvm::ARM::parseBranchProtection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a6a6dbec2a4e426cbd27aeca7cc4217c3">llvm::SPIRV::parseBuiltinCallArgumentBaseType</a>, <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#aa7b40dda7a09e0c055d6138b404d0789">llvm::DebugCounter::parseChunks</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a7225497318f6c1bd57e8a80d4273031e">llvm::cl::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ae577a9371ea38b78cffc39d0ca5f6623">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseExpression</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab65e752ef8a4ee9e6df01039bfa00b0e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#a1ea0b527a25e96bb74c8217704b22a07">llvm::MCSectionMachO::ParseSectionSpecifier</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a047b7995a79492824633a62540717492">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::peekThroughShuffles</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ac58bff1dbe11572c7b2150fc2ffda1b1">performOrXorChainCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afbc0dc4ba278fb4634893dc0c64b0676">PerformSplittingToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90089c4b79f869ee82ea85c2a737921a">performVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#ae9204e2dfad0e3d0ed7446e8d7bfda5b">llvm::SmallVectorTemplateBase&lt; T, true &gt;::pop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0e767e896620f312f0923938d3727fda">llvm::const_iterator&lt; MemoryLocation &gt;::pop_back_n</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc/#a0f29a553d97c6cbfab2318fb5d22902a">anonymous{PGOInstrumentation.cpp}::PGOUseFunc::populateCoverage</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#ac2358bb1fa4721b99f88e2149d6d127d">anonymous{MachineOutliner.cpp}::MachineOutliner::populateMapper</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a0804b0846b504f0556a8085204f1127b">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::prepare</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ae97bb6b91cff3e18475ab68012287cc2">llvm::SystemZInstrInfo::prepareCompareSwapOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0fa39647aed67bc62e126a8d8812900f">llvm::prepareTempFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a51dffbda74e47e34a64858d09d456108">llvm::InstCombinerImpl::prepareWorklist</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-delinearization-cpp-/#a5c53d773e653f349a53c8796896bfaed">anonymous{Delinearization.cpp}::printDelinearization</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a1007dc3842414831c7641e4b5824e4a0">anonymous{CommandLine.cpp}::HelpPrinter::printHelp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a7170e1b99a9c472642f756b8cf098afa">PrintLoopInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/categorizedhelpprinter/#ab00bf8967de6bcd0ed813dd9ec8b09a9">anonymous{CommandLine.cpp}::CategorizedHelpPrinter::printOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a2f5b0f29c0bc09d86c10acc086657c21">anonymous{CommandLine.cpp}::HelpPrinter::printOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a936ffbef3dd147515d76ff3ad15ba22c">anonymous{CommandLine.cpp}::CommandLineParser::printOptionValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a096c73ed00d089d8655ad2da3963380c">printShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a933376a6efcdf3b5910c326b774eb8b3">processBlockAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a071cd98d76a1c63f215ad16388bfdfe2">llvm::JumpThreadingPass::processBranchOnXOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp/#ad6c7bb71f11814fe88bf73f5c589a9e0">ProcessElementList</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a873cd38481c3ed6a7e21bc016ec10ae2">llvm::logicalview::LVBinaryReader::processLines</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a65eee5509cce98dcc69693ea13bb9220">llvm::logicalview::LVBinaryReader::processLines</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#a1b795b0cd98521a7cf4ab769d9207258">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::processLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopinterchange-cpp-/loopinterchange/#a2a08cef5ef885ecb702cabcedb86c95e">anonymous{LoopInterchange.cpp}::LoopInterchange::processLoopList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a61326cd6384971e828511e500b3367c6">processSwitchesConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a96191c096e61f77ea0a6771263bdb5e1">llvm::JumpThreadingPass::processThreadableEdges</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a611115d09f3dd3ef310f70c87a8ba402">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::propagateShapeBackward</a>, <a href="/web-llvm/docs/api/classes/llvm/swifterrorvaluetracking/#afc960ff953a4a9d9fbf91baf590222d2">llvm::SwiftErrorValueTracking::propagateVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#adf31f040a01939eb7f7b085e5dfc0485">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#a4cd364a560035d8414c3b21b2513b0d4">llvm::SmallVectorTemplateBase&lt; T, true &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingreader/#a6f328f5f8d7e388b876dc55edd2d7da8">llvm::coverage::RawCoverageMappingReader::read</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolremappingreader/#a6b15e282ce11e66f93f7b1a22407547b">llvm::SymbolRemappingReader::read</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a25241903dcf363fdf53dc9e8f1037e7a">llvm::sys::fs::readNativeFileToEOF</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a98a6af42792c32db070dee8826e1412e">llvm::sampleprof::SampleProfileReaderGCC::readOneFunctionProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyexceptioninfo/#a6248704cecd958d5eeb84fa3536fc78c">llvm::WebAssemblyExceptionInfo::recalculate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abca8e2c525d8162fbcbb5b444cf04d21">llvm::RecursivelyDeleteTriviallyDeadInstructionsPermissive</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8eb21f893b8039f4edcc3e3bce0c319e">llvm::LegalizerHelper::reduceLoadStoreWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55412d2c237115c95f20e12ba0d95922">relocationViaAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a41b5be766680970f5843b6bbeb8ee3d6">anonymous{ValueMapper.cpp}::Mapper::remapDbgRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa175634946d91981b87f76ed9a583f27">rematerializeLiveValuesAtUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a56b5a0fa4891dca73946affd4e6e3ffd">removeFromUsedList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/cgdata/stablefunctionmap-cpp/#a172ac12ba3705f1f1e519e50c874d406">removeIdenticalIndexPair</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a87dd1a69c8d8492e78b32708ceacb2c6">llvm::LazyCallGraph::RefSCC::removeInternalRefEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#abcf78af37d56a9b72a49c65428210758">llvm::MemorySSAUpdater::removeMemoryAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#aa00cbe94721ef6343a9a10ab26af3744">removeRedundantBlockingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a4a3e80130d3f25468190ba343064b37e">reorderReuses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14c12bda1f5a9beed612b00f3f98b888">llvm::reorderScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a20d1f65e3dcb870550c1c8340fc7a286">llvm::X86InstrInfo::replaceBranchWithTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphnode/#a61a20bdec19cf182df0c3b23bb1895b7">llvm::CallGraphNode::replaceCallEdge</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a8b47a3cfdac6c8cc7e158e8ee75973d7">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::replaceMulWithMul24</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a705c6c2b8e570441356edb8db2dd8ddb">replaceUndefValuesInPhi</a>, <a href="/web-llvm/docs/api/classes/anonymous-armasmparser-cpp-/armasmparser/#abe395f22cd402da225ebfe07e79bc053">anonymous{ARMAsmParser.cpp}::ARMAsmParser::ReportNearMisses</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a93f4e8afe33c15857b55c643ef09efce">llvm::const_iterator&lt; MemoryLocation &gt;::resize</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#add7c3bdd8428904f63f53569807b8df6">anonymous{RegisterCoalescer.cpp}::JoinVals::resolveConflicts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a8a6fce329f29e0ec830e61c629b70739">resolveSources</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a69ed119a74aa160e44fcd158476e353e">resolveTargetShuffleInputsAndMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a2d7f004a3c47587d6342bd03a5ec9cb1">RestoreSpillList</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a479378216af352a6202281eb9b5b202a">llvm::CallLowering::resultsCompatible</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#af5365132fb67e1e49ed76284c6e0905e">llvm::LanaiInstrInfo::reverseBranchCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-controlheightreduction-cpp-/chr/#ac4b57ee03a4f60d7d9c7800f192771b3">anonymous{ControlHeightReduction.cpp}::CHR::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-dfajumpthreading-cpp-/dfajumpthreading/#a858489f4cff24516d6ac192f2165dce2">anonymous{DFAJumpThreading.cpp}::DFAJumpThreading::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheckelimination/#af56db9cf79e7501bf38278f849774369">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopinterchange-cpp-/loopinterchange/#a377904340b53c8545eb81eb92022c4f4">anonymous{LoopInterchange.cpp}::LoopInterchange::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-twoaddressinstructionpass-cpp-/twoaddressinstructionimpl/#a7bc0a5064c340800de9ce752c881316d">anonymous{TwoAddressInstructionPass.cpp}::TwoAddressInstructionImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionspecializer/#a27893e2167969de71fd88771382a93ad">llvm::FunctionSpecializer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a0d3ab70393b799b3be4875c3334a4f42">llvm::LoopVectorizePass::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#a8f3d27d1b480f6b3c90405707be76295">runMoveAutoInit</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrshiftexpand-cpp-/avrshiftexpand/#a25192a5e79d3f5ef39a4b3d4a7da9fd9">anonymous{AVRShiftExpand.cpp}::AVRShiftExpand::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxloweraggrcopies-cpp-/nvptxloweraggrcopies/#a1e7cbd0783ad9cbbfdf85b5dbaba57f8">anonymous{NVPTXLowerAggrCopies.cpp}::NVPTXLowerAggrCopies::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-armfixcortexa57aes1742098pass-cpp-/armfixcortexa57aes1742098/#a43d2faff17080847be1128de33a8fe54">anonymous{ARMFixCortexA57AES1742098Pass.cpp}::ARMFixCortexA57AES1742098::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-silatebranchlowering-cpp-/silatebranchlowering/#a2f96cc01100e6467c2b124371cf417c0">anonymous{SILateBranchLowering.cpp}::SILateBranchLowering::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ac27e962fff6fda4c4419bc22281f38dd">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-blockextractor-cpp-/blockextractor/#ab929be069dc417044c41ddeca9bec3b7">anonymous{BlockExtractor.cpp}::BlockExtractor::runOnModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a245a901981dbba45d423697bb3351b1b">llvm::salvageDebugInfoForDbgValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a02cf9d6ac96ae27b406798da5c2eb7ea">SalvageDVI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a14321b844507103cd4de1f202c33f455">scaleShuffleElements</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a021e32e2bf67f331d9384a162dc402c2">anonymous{WholeProgramDevirt.cpp}::DevirtModule::scanTypeCheckedLoadUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a2b20fa727cb3be2d7338de943bc81490">selectImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyiseldagtodag-cpp-/cskydagtodagisel/#aa0b3de3815c7ba67bd6b19ef08ac9f1c">anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::selectInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#afa32384c08e0fbd9e4a5f1117c643c22">selectWMMAModsNegAbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#ad7de3dafef31acc6669c022e769750f8">selectWMMAModsNegAbs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/#ae864eac64c3865fde986bea273ae59a8">anonymous{TextStubV5.cpp}::serializeTargets</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc/#a693592fa7e2d0950e30d14f38c333f9b">anonymous{PGOInstrumentation.cpp}::PGOUseFunc::setBranchWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#a1ab33fa6fa7130c1c532556fcbddb32d">setSpecialRefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aaf604b7b4ff087fce0b71852f5ddefbe">setUsedInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a1101a933da1fae1b166dc36e2a384ce1">llvm::SIMachineFunctionInfo::shiftWwmVGPRsToLowestRange</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a3974afc532c6dfeea9fac363c7c0993a">llvm::RISCVTargetLowering::shouldConvertConstantLoadToIntImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af08d593d99b84298decf28611dd32f50">shouldTryInjectBasingOnMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#a1c53e709679ac5205c22134f73456327">shouldUseFrameHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a1a1dd27d36e829a2de3225991dac9c3e">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0083a69883e0f97e111dbff064c60f42">llvm::simplifyLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a30ea9932827054448251050d576b4874">llvm::X86TargetLowering::SimplifyMultipleUseDemandedBitsForTargetNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a38dc339806a701c1f11ec31cf76936ff">simplifySelectInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#adc11c5fbec9bf293b000637357da66e4">simplifySwitchOfPowersOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a0f09c6db065cba05fa4431f921a73715">SimplifyValuePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4611905728c0ddaed9f8964ae8b074a2">simplifyWithOpsReplaced</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7da8333874d1ad28bd987d4e7c474e53">sinkCommonCodeFromPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#abb3297c94836debc08248e7ae3f47582">sinkLifetimeStartMarkers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4a5b1db18197a65d0f6a487f2e236921">sinkRecurrenceUsersAfterPrevious</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a1536feae2abb3570ac032768a53ddd00">sinkScalarOperands</a>, <a href="#ab810710f3a8de47c520c1f6055389b30">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size_in_bytes</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/arraylist/#adf19460a3c702d261e7ffe25d77cabbb">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::sort</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#a2db51bd33669db1b6468d51dd5d6e215">anonymous{AMDGPUExportClustering.cpp}::sortChain</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a27b94c48d58dc48bf80e98e92e6ba7a1">llvm::DominatorTreeBase&lt; BlockT, false &gt;::Split</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a10aa0138f3edcc0641294b19c7fdebbb">llvm::SubtargetFeatures::Split</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33f79ea6e1fd1b8ba93c75519b1c929c">llvm::splitBlockBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a26bed2b570bc6e4d34eda3488f8430c4">SplitBlockImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#adc7bbccb30409488c60813454af8c81d">llvm::coro::AnyRetconABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#ae51f7f2d35223ec01d09e205c757a4df">llvm::coro::AsyncABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a57d1263b6f2a16c765d594a59c2f8130">llvm::CallLowering::splitToValueTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#aeb4b5a7ad5a49f17f8a34890eb6efefe">llvm::StatepointLoweringState::startNewStatepoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a7fcdf2ea020f761f9857bebbc35a2ca3">StoreTailCallArgumentsToStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#a603517a82c194cc3daa912831dff244a">llvm::Regex::sub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregisterbankinfo-cpp/#a0f1b1f36c5069336e43ad70639b7f176">substituteSimpleCopyRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a96fe0cb15ded58bd1824fa4e3daec680">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a36955f44027693881a174e8d3f1d3854">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::SwitchLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a7db30a1144cd370f595ed6c16904db15">llvm::BTFParser::symbolize</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a1c0f17f40e0399c6d151a50e99797e58">llvm::TailDuplicator::tailDuplicateAndUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/timergroup/#a2ca404ac00efb240e891d7f7d86aec02">llvm::TimerGroup::TimerGroup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeviewyaml/#ad026ca61ae553f5da149349b2662e425">llvm::CodeViewYAML::toDebugH</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a5d968bc337af0be1f18813553a046df6">llvm::Twine::toNullTerminatedStringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a67a4cef5addbdc43c571874df4ea020d">llvm::detail::anonymous{APFloat.cpp}::toStringImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#ac521760e9a45f304a4cbe46ed4fff845">llvm::Twine::toStringRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a44ca78ca7013578c50cdd38647811346">transformGlobalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-cpp/#ac9966bce879b21a4a601daab59e25c97">transformInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/phitransaddr/#aa4b823fe521dfaefebd59ddf5f7f6bd7">llvm::PHITransAddr::translateWithInsertion</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5795a74557bb339afa955660ecb76247">llvm::Triple::Triple</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aae26f659b722d1d053b93b5f1735f52f">llvm::const_iterator&lt; MemoryLocation &gt;::truncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#aa541e074a612b8ca4a7291a3b0746b7e">tryBuildVectorShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab73239c9eac42ae767c00ecc64e98dff">llvm::tryDelinearizeFixedSizeImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#ac485f1a06d95a982f897655933212766">tryMergeRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#acd13e2195957a8e92e36d055dde1ffb8">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryToFoldACImm</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad4296b2b81379548b300c4676f0d2125">llvm::InstCombinerImpl::tryToSinkInstructionDbgVariableRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ac48731694e324e56e35cb2b4f20345d0">tryToVectorizeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/mcdc/tvidxbuilder/#a85f4860524d04ca3d92dae7f5b1a9fba">llvm::coverage::mcdc::TVIdxBuilder::TVIdxBuilder</a>, <a href="/web-llvm/docs/api/classes/anonymous-typestreammerger-cpp-/typestreammerger/#ae9228fb82c65a47ff4aa0708502d80b1">anonymous{TypeStreamMerger.cpp}::TypeStreamMerger::TypeStreamMerger</a>, <a href="/web-llvm/docs/api/classes/llvm/inteqclasses/#aa63616e3405270095cb5020333fe06b4">llvm::IntEqClasses::uncompress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#acc20b8effcbe869069ff973354344872">unswitchBestCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a5497581592027b0e7275f3ff54735343">llvm::DominatorTreeBase&lt; BlockT, false &gt;::updateBlockNumbers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#ace004655a04ad52b7fc02fb8e3cf7b0f">updateBranchWeights</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofile-cpp/#a5c3b919b227c332257bcc77ec8c9df00">updateIDTMetaData</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignfloating/#a0206ea336f22470d5fe01f65dae9eb85">anonymous{AttributorAttributes.cpp}::AAAlignFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceablefloating/#a41c5ffc9c348c806bd197076e245aa1a">anonymous{AttributorAttributes.cpp}::AADereferenceableFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a6aaeb440ac0f45225f89b6b83444db1a">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanonnullfloating/#a4b1fa4ad98c736b05369d73702328439">anonymous{AttributorAttributes.cpp}::AANonNullFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoundeffloating/#a6b86977408d6fd3bc77f900143401adb">anonymous{AttributorAttributes.cpp}::AANoUndefFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaunderlyingobjectsimpl/#a5853fd1282daf0510e9eb037ffe23f8a">anonymous{AttributorAttributes.cpp}::AAUnderlyingObjectsImpl::updateImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a40c011ab750e2b4ea0d6b8076345cb0c">llvm::UpgradeModuleFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a227ca4549b5e29e59345b6a9bb74e531">upgradeRetainReleaseMarker</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a5d85b8fd4787153b0ade229c616b7562">ValidateMVEStore</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#ab5464b66f7393d7dbd8c601305cdbc0b">llvm::HexagonShuffler::ValidResourceUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a415df2bffdca7570fb2601009a96ccf5">VectorizePTXValueVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a6dcb5e3d63691e83e0fdc0d67148077a">llvm::MemorySSA::verifyOrderingDominationAndDefUses</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ae8ee3aa50e72940cabb7d758613ce2cf">llvm::SCEVDivision::visitAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a196df57d98a1307c0ced654a8e1d202b">llvm::SelectionDAGBuilder::visitDbgInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae534b46b7607eb604ddd8c66baa8d2d1">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7af99fa2202fcc7db245865dd1bcec1f">llvm::InstCombinerImpl::visitLandingPadInst</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#afab4a1d0e1f34b286eec49ac8bd96ef1">llvm::SCEVDivision::visitMulExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae42afee90ff90eb3b8fa78ad91d8858b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSqrt</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvemitintrinsics-cpp-/spirvemitintrinsics/#a4a4171890acb275f5a66288e91a8d5ca">anonymous{SPIRVEmitIntrinsics.cpp}::SPIRVEmitIntrinsics::visitSwitchInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8b7bc9bbc4a3cf2bca60932ff2d582e">llvm::widenShuffleMaskElts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4373d3025961c2c2eeca56b02d7d009d">llvm::widenShuffleMaskElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abe0c2621dfb4c1e6bcfbaddc38fdf572">widenVectorOpsToi8</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/coveragefilenamessectionwriter/#a244a9bcfc38a346ac3c76bde7edbfca2">llvm::coverage::CoverageFilenamesSectionWriter::write</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdxbc/signature/#a608616d2779ddc0d1ca2669b17119ba2">llvm::mcdxbc::Signature::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#ac4946ac3df4a88e078136a4444ef1185">llvm::objcopy::elf::BinaryWriter::write</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a536ea5f0471772d2cbeb45138b34bb46">anonymous{AsmWriter.cpp}::AssemblyWriter::writeAllMDNodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/ihexsectionwriter/#ac2982fe0f31deef1fc4d20346a6e3daf">llvm::objcopy::elf::IHexSectionWriter::writeData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0096360a382602b21e0e980fb8069d52">llvm::dxil::WriteDXILToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5858c9c8d861a0d36e7c8f99b8faf7fe">llvm::writeIndexToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/profiledata/instrprofwriter-cpp/#afe089e351de37cd105f3fae18a0bd13e">writeMemProfSchema</a>, <a href="/web-llvm/docs/api/classes/llvm/dxcontainerobjectwriter/#aab937b67cb92336a4c82aeae0b8ccbf5">llvm::DXContainerObjectWriter::writeObject</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#aaf1d0c4d37d55950252509e0b0c84501">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeSectionData</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodewriter/#aaaca861df948bd93da0afb6891e9d662">llvm::BitcodeWriter::writeSymtab</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33564097625c6a9b619c60a71343c058">llvm::writeThinLinkBitcodeToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#a9f26efe564d8f7f1afb5f3033156d58d">writeUniversalArchsToStream</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilewriter/#a383a9c6d7b337512fa69de542cec0375">llvm::sampleprof::SampleProfileWriter::writeWithSizeLimitInternal</a>.</p>

</div>
</div>

### size\_in\_bytes() {#ab810710f3a8de47c520c1f6055389b30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_type llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size_in_bytes ()</td>
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



<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### assertSafeToAdd() {#ae0e4f4c34cddd8f514efe4f9e0accf09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Elt, size_t N=1)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether Elt will be invalidated by increasing the size of the vector by N.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#aef6ec04f270e752d22af5ce1457f8827">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToReferenceAfterResize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#a60bcdd74c5b92ca311a77068b177286b">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToAddRange</a>.</p>

</div>
</div>

### assertSafeToAddRange() {#a60bcdd74c5b92ca311a77068b177286b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToAddRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T * From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T * To)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether any part of the range will be invalidated by growing.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#ae0e4f4c34cddd8f514efe4f9e0accf09">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToAdd</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::const_iterator&lt; MemoryLocation &gt;::append</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a59fd5e59ca0c03b061035a6c9de2b39c">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>.</p>

</div>
</div>

### assertSafeToAddRange() {#a00e625603e2d7045b8f43e73115fc6b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ItTy, std::enable_if_t&lt;!std::is_same&lt; std::remove_const_t&lt; ItTy &gt;, T * &gt;::value, bool &gt; = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToAddRange (ItTy, ItTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### assertSafeToReferenceAfterClear() {#a709b8b7b7dd6a5ea1f9e8255b1dd5b13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToReferenceAfterClear (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T * From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T * To)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether any part of the range will be invalidated by clearing.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#aef6ec04f270e752d22af5ce1457f8827">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToReferenceAfterResize</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aaf8c4a3f62d6231ae323b77e21303e1c">llvm::const_iterator&lt; MemoryLocation &gt;::assign</a>.</p>

</div>
</div>

### assertSafeToReferenceAfterClear() {#af71954476a996d6650da3e6481e705dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class ItTy, std::enable_if_t&lt;!std::is_same&lt; std::remove_const_t&lt; ItTy &gt;, T * &gt;::value, bool &gt; = false&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToReferenceAfterClear (ItTy, ItTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

### assertSafeToReferenceAfterResize() {#aef6ec04f270e752d22af5ce1457f8827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToReferenceAfterResize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Elt, size_t NewSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether Elt will be invalidated by resizing the vector to NewSize.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a68e0dd48505f955c8681f11b6957afdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isSafeToReferenceAfterResize</a>.</p>


<p>Referenced by <a href="#ae0e4f4c34cddd8f514efe4f9e0accf09">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToAdd</a> and <a href="#a709b8b7b7dd6a5ea1f9e8255b1dd5b13">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToReferenceAfterClear</a>.</p>

</div>
</div>

### getFirstEl() {#aff209a96323a14068980fd74f1fa53df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::getFirstEl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find the address of the first element.</p>


<p>For this pointer math to be valid with small-size of 0 for T with lots of alignment, it's important that <a href="/web-llvm/docs/api/structs/llvm/smallvectorstorage">SmallVectorStorage</a> is properly-aligned even for small-size of 0.</p>


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a276e8a32e0bbf024aadd9420b8f2d3b3">offsetof</a>.</p>


<p>Referenced by <a href="#a87b74e4076979c8d4ca61387848cf77f">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::grow_pod</a>, <a href="#a02335466a102901ccd2e0d4a29af8910">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isSmall</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#a3642c7a4a7c63961ed43b855b2f65369">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::mallocForGrow</a>, <a href="#a65d2c81df9337e5c2d7532c8cdaa29cc">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::resetToSmall</a> and <a href="#a54ef871baaeb33ef86752839fd32a0bc">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::SmallVectorTemplateCommon</a>.</p>

</div>
</div>

### grow\_pod() {#a87b74e4076979c8d4ca61387848cf77f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::grow_pod (size_t MinSize, size_t TSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#aff209a96323a14068980fd74f1fa53df">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::getFirstEl</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a0fef5db8f0b473292cb9770075050da5">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::grow_pod</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#aacac01d9aebaef1a3abcc7347d3bcd37">llvm::SmallVectorTemplateBase&lt; T, true &gt;::grow</a>.</p>

</div>
</div>

### isRangeInStorage() {#ada19bc367321342a58ed18b2a0e03e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isRangeInStorage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * First, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Last)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if First and Last form a valid (possibly empty) range in this vector's storage.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aa3787c69a41c14127758c359911180aa">llvm::const_iterator&lt; MemoryLocation &gt;::erase</a>.</p>

</div>
</div>

### isReferenceToRange() {#a87abc734ab9fa7907c29680075619395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isReferenceToRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * First, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Last)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if V is an internal reference to the given range.</p>

<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac10d13c57a7adf4a1f140afd5321309bad55b30607c2a9a2616347d6edb789f6b">llvm::Last</a>.</p>


<p>Referenced by <a href="#ac8019ffabda94935c17ae83f97db769d">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isReferenceToStorage</a>.</p>

</div>
</div>

### isReferenceToStorage() {#ac8019ffabda94935c17ae83f97db769d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isReferenceToStorage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * V)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if V is an internal reference to this vector.</p>

<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a> and <a href="#a87abc734ab9fa7907c29680075619395">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isReferenceToRange</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::const_iterator&lt; MemoryLocation &gt;::erase</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a59fd5e59ca0c03b061035a6c9de2b39c">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a520e903dce9cfbdd0d1073fe447ce52e">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a> and <a href="#a68e0dd48505f955c8681f11b6957afdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isSafeToReferenceAfterResize</a>.</p>

</div>
</div>

### isSafeToReferenceAfterResize() {#a68e0dd48505f955c8681f11b6957afdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isSafeToReferenceAfterResize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * Elt, size_t NewSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true unless Elt will be invalidated by resizing the vector to NewSize.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#aa079814a3e516904064e9980a83765c5">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::capacity</a>, <a href="#ac8019ffabda94935c17ae83f97db769d">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isReferenceToStorage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a> and <a href="#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="#aef6ec04f270e752d22af5ce1457f8827">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::assertSafeToReferenceAfterResize</a>.</p>

</div>
</div>

### isSmall() {#a02335466a102901ccd2e0d4a29af8910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isSmall ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this is a smallvector which has not had dynamic memory allocated for it.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#aeae003355ebd5135c415924b38964abd">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::BeginX</a> and <a href="#aff209a96323a14068980fd74f1fa53df">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::getFirstEl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a6aed977bf8ca76ee498836d1fe4cedb6">llvm::const_iterator&lt; MemoryLocation &gt;::assignRemote</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#aa653aeaa776bdaa3656d01a2198d99fd">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::takeAllocationForGrow</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#af56a778d4fe0d873fcc879c78fb733a6">llvm::const_iterator&lt; MemoryLocation &gt;::~SmallVectorImpl</a>.</p>

</div>
</div>

### resetToSmall() {#a65d2c81df9337e5c2d7532c8cdaa29cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::resetToSmall ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Put this vector in a state of being small.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#aeae003355ebd5135c415924b38964abd">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::BeginX</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a7a9ccaffe5ac9115608537c98983b1be">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::Capacity</a>, <a href="#aff209a96323a14068980fd74f1fa53df">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::getFirstEl</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a7b5a03b19133c790a4d6fff66a5d2135">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### reserveForParamAndGetAddressImpl() {#a4ff60fb0f0d249b4623327ef5976867b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class U&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::reserveForParamAndGetAddressImpl (U * This, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Elt, size_t N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reserve enough space to add one element, and return the updated element pointer in case it was a reference to the storage.</p>

<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#aa079814a3e516904064e9980a83765c5">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::capacity</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#aeab77382e7ca9b451524424e268ff264">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::reserveForParamAndGetAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#a89ccedcf373b03d6e115d8b5e56ccebd">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::reserveForParamAndGetAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#a31714b59605e59bf0543a765b3229096">llvm::SmallVectorTemplateBase&lt; T, true &gt;::reserveForParamAndGetAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#a8ada7545d53f82f040ad72cd9b137f00">llvm::SmallVectorTemplateBase&lt; T, true &gt;::reserveForParamAndGetAddress</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
