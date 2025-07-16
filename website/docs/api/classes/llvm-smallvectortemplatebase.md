---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smallvectortemplatebase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SmallVectorTemplateBase` Class Template Reference

<p><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase">SmallVectorTemplateBase</a>&lt;TriviallyCopyable = false&gt; - This is where we put method implementations that are designed to work with non-trivial T's. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;
class llvm::SmallVectorTemplateBase&lt;T, bool&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon">SmallVectorTemplateCommon&lt;T, typename&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the part of <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase">SmallVectorTemplateBase</a> which does not depend on whether the type T is a POD. <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class consists of common code factored out of the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> class to reduce code duplication based on the <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> 'N' template parameter. <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a47fa0eb331582edc3b5c55b5b7af40f3">ValueParamT</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6adf728d043bda4ffe3c759c313fdb61">SmallVectorTemplateCommon&lt; T &gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a59bf49ac292d1f2d6ab5db4be8d98f3d">SmallVectorTemplateBase</a> (size_t Size)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af42bfbc067df27c19ee2fc859df58799">push_back</a> (const T &amp;Elt)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf31f040a01939eb7f7b085e5dfc0485">push_back</a> (T &amp;&amp;Elt)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad97688dfe9cd802e2a0691cbe620218a">pop_back</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf23f35638753badb423928a21b2a561">grow</a> (size_t MinSize=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Grow the allocated memory (without initializing new elements), doubling the size of the allocated memory. <a href="#adf23f35638753badb423928a21b2a561">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3642c7a4a7c63961ed43b855b2f65369">mallocForGrow</a> (size_t MinSize, size_t &amp;NewCapacity)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new allocation big enough for <span class="doxyComputerOutput">MinSize</span> and pass back its size in <span class="doxyComputerOutput">NewCapacity</span>. <a href="#a3642c7a4a7c63961ed43b855b2f65369">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a06264674191b53ea377acb0fbf98c80b">moveElementsForGrow</a> (T *NewElts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move existing elements over to the new allocation <span class="doxyComputerOutput">NewElts</span>, the middle section of <em><a href="#adf23f35638753badb423928a21b2a561">grow()</a></em>. <a href="#a06264674191b53ea377acb0fbf98c80b">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa653aeaa776bdaa3656d01a2198d99fd">takeAllocationForGrow</a> (T *NewElts, size_t NewCapacity)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer ownership of the allocation, finishing up <em><a href="#adf23f35638753badb423928a21b2a561">grow()</a></em>. <a href="#aa653aeaa776bdaa3656d01a2198d99fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeab77382e7ca9b451524424e268ff264">reserveForParamAndGetAddress</a> (const T &amp;Elt, size_t N=1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserve enough space to add one element, and return the updated element pointer in case it was a reference to the storage. <a href="#aeab77382e7ca9b451524424e268ff264">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a89ccedcf373b03d6e115d8b5e56ccebd">reserveForParamAndGetAddress</a> (T &amp;Elt, size_t N=1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserve enough space to add one element, and return the updated element pointer in case it was a reference to the storage. <a href="#a89ccedcf373b03d6e115d8b5e56ccebd">More...</a></p>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6cf8f5418ae17302373eb658de2c4a5">growAndAssign</a> (size_t NumElts, const T &amp;Elt)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... ArgTypes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af0de1c3bdac42cb94cca3cce185c3d8a">growAndEmplaceBack</a> (ArgTypes &amp;&amp;... Args)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2d25f6f9379888156d4dc87f0c70a0da">destroy_range</a> (T *S, T *E)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename It1, typename It2&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acc3e8839b34bcff67f0b39624e0d99ee">uninitialized_move</a> (It1 I, It1 E, It2 Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move the range [I, E) into the uninitialized memory starting with "Dest", constructing elements as needed. <a href="#acc3e8839b34bcff67f0b39624e0d99ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename It1, typename It2&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0ba61356fc2c8d9c14fe55d069a0d648">uninitialized_copy</a> (It1 I, It1 E, It2 Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy the range [I, E) onto the uninitialized memory starting with "Dest", constructing elements as needed. <a href="#a0ba61356fc2c8d9c14fe55d069a0d648">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static T &amp;&amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1f39a810459dda7c8ca8392b4f1d2ab4">forward_value_param</a> (T &amp;&amp;V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abf9c4d6c822e662181d0bd6c5920c455">forward_value_param</a> (const T &amp;V)</td>
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

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3b2b6193837d9e9f181627f194985267">TakesParamByValue</a> = false</td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase">SmallVectorTemplateBase</a>&lt;TriviallyCopyable = false&gt; - This is where we put method implementations that are designed to work with non-trivial T's.</p>


<p>We approximate is_trivially_copyable with trivial move/copy construction and trivial destruction. While the standard doesn't specify that you're allowed copy these types with memcpy, there is no way for the type to observe this. This catches the important case of std::pair&lt;POD, POD&gt;, which is not trivially assignable.</p>


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### ValueParamT {#a47fa0eb331582edc3b5c55b5b7af40f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SmallVectorTemplateBase&lt; T, bool &gt;::ValueParamT =  const T &amp;</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### SmallVectorTemplateCommon&lt; T &gt; {#a6adf728d043bda4ffe3c759c313fdb61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon">SmallVectorTemplateCommon</a>&lt; T &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### SmallVectorTemplateBase() {#a59bf49ac292d1f2d6ab5db4be8d98f3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::SmallVectorTemplateBase (size_t Size)</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a7b5a03b19133c790a4d6fff66a5d2135">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::Size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a54ef871baaeb33ef86752839fd32a0bc">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::SmallVectorTemplateCommon</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd001dbc8a624eecaa020c6d4e3a6b06">llvm::const_iterator&lt; MemoryLocation &gt;::SmallVectorImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### pop\_back() {#ad97688dfe9cd802e2a0691cbe620218a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back ()</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#acf1bb6ad9c13f32082c4e3b1272522fd">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::set_size</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afda2c0f22be043ae42b0ec71b661f565">llvm::MachineInstr::addRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#ac45bdcc05a92d63f2249f476eeb17e77">advanceToNextLeafType</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a1a1c9931dc5cfff031352bf6a5c7c3ff">llvm::MipsInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/annotations/#a0ac05d465c3984a3a3fe146902cf3759">llvm::Annotations::Annotations</a>, <a href="/web-llvm/docs/api/classes/llvm/a57chainingconstraint/#af022d8d0187b3df267d3e7754cb4b80b">llvm::A57ChainingConstraint::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a85cbdd891f1cd43d6c79f7d68a2caf46">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::BuildBlockList</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#afbd7f8e7654d71a5771a4eaa8b622bd2">BuildSubAggregate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3d3da964f7eb14ef2eabf0c4a08ba5">llvm::c_str</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#af1dbaf0e42fc61259e10468caeb7f4b5">CalcNodeSethiUllmanNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a9e6b15b1005dd460a35359f104cb06fe">canRewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/hipstdpar/hipstdpar-cpp/#aaf9c9bd3b96d08e2f7ad45aa3304aa20">checkIfSupported</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/#a7e6c4318cd8d3ae5bbe88df3d4a58490">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::checkNodes</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gac3778bafa67cdae223698e5bba785a76">ComputePostOrders</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad23b52a299ca563f6e6a6c6cece54dcc">llvm::convertUTF8ToUTF16String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aa37537b95a42a73ea04d8dd2803378da">llvm::sys::fs::createUniquePath</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ab34667f1d218ea0b6566dd8f861dfe93">llvm::ScheduleDAGSDNodes::dumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtooffsettable/#a1878d931b7c5cb9a938690f5a73d75a2">llvm::StringToOffsetTable::EmitStringTableDef</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::const_iterator&lt; MemoryLocation &gt;::erase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a587c4289ae52d2bea98482248fac1749">expandFromPrimitiveShadowRecursive</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a2867e9240af1e5a7d2a7aabb385a661d">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::FindRoots</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/runtimefunctioninfo/#aa3d7bedeec36948ecc6bae39a75c5da9">anonymous{OpenMPOpt.cpp}::OMPInformationCache::RuntimeFunctionInfo::foreachUse</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#ae92d755a80dec605503e2ba653765360">llvm::Attributor::getAssumedSimplifiedValues</a>, <a href="/web-llvm/docs/api/classes/llvm/regioninfobase/#a4b3f1bd46bc2567bcc606b0f927b8e97">llvm::RegionInfoBase&lt; Tr &gt;::getCommonRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a814ccfa400b06db7a01885ddcc21196a">llvm::orc::JITDylib::getDFSLinkOrder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a1ec7fd3672feec111d150c08c4cf6a69">llvm::XCOFF::getExtendedTBTableFlagString</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a8cbdb500ba4abd11fd23de4e7a020a2d">llvm::ScheduleDAGSDNodes::getGraphNodeLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aca1828635e30f34e4958afeb5541766e">llvm::Intrinsic::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a8ed485ff9b2526376525b8f792929a31">loadCSE</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/unicode/#a4e10ba09dea9d13b485ec2a68efb4f98">llvm::sys::unicode::nearestMatchesForCodepointName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90896a5c2c14e27297f4fdb0196e24b3">llvm::nonStrictlyPostDominate</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64redundantcopyelimination-cpp-/aarch64redundantcopyelimination/#a1ee0cfcd17ed3a5b4826b8a5f93e50e1">anonymous{AArch64RedundantCopyElimination.cpp}::AArch64RedundantCopyElimination::optimizeBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmparser-cpp-/hexagonasmparser/#ae577a9371ea38b78cffc39d0ca5f6623">anonymous{HexagonAsmParser.cpp}::HexagonAsmParser::parseExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::const_iterator&lt; MemoryLocation &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a6084253c0f3954d2b8479befc2a6be61">llvm::GCOVFunction::propagateCounts</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a49876ad04843c072ef3aab5f0b10dd91">removeEntryFromStack</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a4082748189dc3460ea7130cd8d7790b5">llvm::MemoryDependenceResults::removeInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#aa00cbe94721ef6343a9a10ab26af3744">removeRedundantBlockingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#af2c671e8273bc99e266f62322b29a157">replaceAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a732f3ff01555ec522134bf060270c1ae">rewriteAccessChain</a>, <a href="/web-llvm/docs/api/classes/llvm/hipstdparacceleratorcodeselectionpass/#a3c59b50e60a44b5fa3871d0449aa4744">llvm::HipStdParAcceleratorCodeSelectionPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipsoptimizepiccall-cpp-/optimizepiccall/#af8fb60c334fa1c7571459b115762b09e">anonymous{MipsOptimizePICCall.cpp}::OptimizePICCall::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscviseldagtodag-cpp/#a2bdacd126c6e2d17f0f5a195043c9aa3">selectConstantAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a9ad2ee389fa99a4c02f610183530735c">llvm::VFABI::setVectorVariantNames</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp/#a08fb230c2b93e704a4fd84ef773b6002">sortLocalVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#af6776e5555063ea14c4668a4bcacae27">swapMIOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a5d968bc337af0be1f18813553a046df6">llvm::Twine::toNullTerminatedStringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a83fe54fc062eda7c1086493dd4155f8a">llvm::DominatorTreeBase&lt; BlockT, false &gt;::updateDFSNumbers</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a066fd5533813e5df6d52cb59fc8afd4e">llvm::dwarf_linker::parallel::DependencyTracker::verifyKeepChain</a>.</p>

</div>
</div>

### push\_back() {#af42bfbc067df27c19ee2fc859df58799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Elt)</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#aeab77382e7ca9b451524424e268ff264">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::reserveForParamAndGetAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#acf1bb6ad9c13f32082c4e3b1272522fd">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::set_size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab1c40e35dfc36395c37921107003128b">llvm::adaptNoAliasScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ab7c7120f48a91e5972592b16ee7fd81b">llvm::PMDataManager::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#a58ecc4f607c39abaf338915a04a29922">llvm::opt::ArgList::AddAllArgsTranslated</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#af408665da3f00cec50ecb935ad72e689">addAllGlobalValueUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9a7c63edb94ce4fab2a5bb34dbf6079a">llvm::Instruction::addAnnotationMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ada583c27bb2634195f2964c7e695a0b3">llvm::AttributeList::addAttributeAtIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ac36177cea684b1e36fdbc92d692f69d0">addBasicBlockMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#aaf0f291dde691ba9d8a7667963f6c7fc">addBlockAndPredsToSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a0faf2520b671c3cb14b4f291c873cb88">addBoundsChecking</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#ae6c3c6c5044d97b7a9ec75b6105f68d8">addCallStack</a>, <a href="/web-llvm/docs/api/classes/llvm/scheddfsimpl/#aa1de1afa4c08361317bce0e400922326">llvm::SchedDFSImpl::addConnection</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a9a91b779e07acc1400574b81f1ba1a70">addConstantsToTrack</a>, <a href="/web-llvm/docs/api/classes/anonymous-safepointirverifier-cpp-/cfgdeadness/#a9b52ca5c1374c43bc1800b838514562a">anonymous{SafepointIRVerifier.cpp}::CFGDeadness::addDeadBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a2f56e0c8e37796630334366257d1b7e3">anonymous{LiveDebugVariables.cpp}::UserValue::addDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a35a2c1218102d97a3eae54fac5386699">AddGlue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-cpp/#aaf08c51751e9ec671a84a92af1daab99">addHints</a>, <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a0f682f69a2b53113b0df4e2b9a7e3aae">anonymous{ConstraintElimination.cpp}::State::addInfoFor</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfilebuilder/#ada66402b91631de13ba71849303ce3d5">llvm::pdb::PDBFileBuilder::addInjectedSource</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a84a89ee9844b6cffc3660100168d7bee">llvm::MachineFunction::addLandingPad</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#a179d90bef9279cb2e6d76182e00efc9e">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::addLinkerOpt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp/#aabfb273f4ca75dfebfb11857de8cb75a">addLocIfNotPresent</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a452b3946fae687fe6ab129970b5f9c75">anonymous{LegacyPassManager.cpp}::MPPassManager::addLowerLevelRequiredPass</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a7af7bb833a1702eacc1b0974ee514698">llvm::AMDGPURegisterBankInfo::addMappingFromTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afc4107c92fd8d37e8d0cb596f2a25d98">llvm::MachineInstr::addMemOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a70d8ffa4f0ffa07bd736cb74d178d917">llvm::CallBase::addOperandBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a0b369e991301543c2120405809119d36">llvm::PredicatedScalarEvolution::addPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a68cd8d24134223f2dfaf5f482a56f1fd">addPrepareFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp/#a538047e21679cd2bf4cfd1e73fe022aa">addRange</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#afda2c0f22be043ae42b0ec71b661f565">llvm::MachineInstr::addRegisterDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ac78902263d351fd8540aeb449d9cb53f">llvm::MachineInstr::addRegisterKilled</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerpressure-cpp/#adfcb78856461567d0d6f7012aee7a89a">addRegLanes</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a587ee120f5b142b50860160b9e698d2c">anonymous{MachineVerifier.cpp}::MachineVerifier::addRegWithSubRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6e46200e5b228c903356e02904987051">addReplicateRegions</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#abc2804137403eb0d17a3dbcf9b96d240">llvm::DominatorTreeBase&lt; BlockT, false &gt;::addRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a033bb363914fbd3c2cd990330959036c">addRuntimeUnrollDisableMetaData</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarffile/#a1720ace58baf8676ff6a9cc841556310">llvm::DwarfFile::addScopeLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/synthetictypenamebuilder/#a3fa9676347c5ae75e905430f8e0897ea">llvm::dwarf_linker::parallel::SyntheticTypeNameBuilder::addSignature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55c9054d63d1c6a39e9c09ba13a482fa">llvm::addStringMetadataToLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a5275881bd107ea2567bbcc6170773d4a">llvm::AMDGPUTargetLowering::addTokenForArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a1fb252b26b548e2ed904e02782013abd">llvm::DbgVariableIntrinsic::addVariableLocationOps</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ab6d5d78fdfb9f1254c0471d2a3be0e65">llvm::DbgVariableRecord::addVariableLocationOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a5d2d34710da4cddfc00e2f4eacd2be7d">adjustByValArgAlignment</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ae64d6953a1334207d9e7d9cd2587ee9f">llvm::VPlanTransforms::adjustFixedOrderRecurrences</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a62042f5fd3a2df1b4fab2bfc692b2390">llvm::ARMFrameLowering::adjustForSegmentedStacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a068555b4b66d140162c7d3c2cb16beae">adjustLoadValueTypeImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#af9b4f3c32f38913159a0ab75cb4bf133">llvm::detail::anonymous{APFloat.cpp}::AdjustToPrecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#ac45bdcc05a92d63f2249f476eeb17e77">advanceToNextLeafType</a>, <a href="/web-llvm/docs/api/classes/llvm/statepointloweringstate/#a4841be2489ba10321338a1874b53f249">llvm::StatepointLoweringState::allocateStackSlot</a>, <a href="/web-llvm/docs/api/classes/anonymous-minidumpemitter-cpp-/bloballocator/#af08557fb29f0c4129ff2121db66a7e43">anonymous{MinidumpEmitter.cpp}::BlobAllocator::allocateString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a27e1c2d39aa2a1a6763bfa05cbcb169a">allPathsGoThroughCold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8e68884ca018dde6dfadf535637290d0">allUsesOfLoadAndStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a26f6a2c21d213fbcbe99a2c09d88a2c4">allUsesOfLoadedValueWillTrapIfNull</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-alwaysinliner-cpp-/#af5bb12426b6361914b816365eee4b4fd">anonymous{AlwaysInliner.cpp}::AlwaysInlineImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#afe664f8e39ffc3ae37c49342e39d7423">llvm::coro::Shape::analyze</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a280d02be3ec3eb6527c1ea944d902775">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::analyze</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a249186f7374b6b9ca0ffd254bb5d79f6">llvm::CCState::AnalyzeArgumentsSecondPass</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a492be44ddc8ccbf85c4ef650b6111868">llvm::LanaiInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsinstrinfo/#a1a1c9931dc5cfff031352bf6a5c7c3ff">llvm::MipsInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensainstrinfo/#ac205677cbd92cecf1a6fcddb4798a12d">llvm::XtensaInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvmakecompressible-cpp/#aa29e0988d94a53fecfac0bc63e665d06">analyzeCompressibleUses</a>, <a href="/web-llvm/docs/api/classes/llvm/genericuniformityanalysisimpl/#a171b9161ef5ed4af03f9f2c223ac5dea">llvm::GenericUniformityAnalysisImpl&lt; ContextT &gt;::analyzeControlDivergence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a882dcfc2455d525e78a8bbf46863ace2">analyzeExitPHIsForOutputUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a1c90a7c05cf18d20a847ded8bc3f0dc8">llvm::CCState::analyzeMustTailForwardedRegisters</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#af8967731195e767bf313308f20b640de">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::analyzeVGPRToSGPRCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a521a0263cd32258d251908a3b8ab2f78">llvm::annotateValueSite</a>, <a href="/web-llvm/docs/api/classes/llvm/annotations/#a0ac05d465c3984a3a3fe146902cf3759">llvm::Annotations::Annotations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a1b070d2edba351e90bf5a08b656895a5">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a59a90ba7dd76e41d07e6c1cb792e0db3">appendGlobalSymbolTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#a55acf718f2931a7050c4ed39eb0434e7">llvm::DebugLoc::appendInlinedAt</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a5f48305fa7d23161515c94bca7c2beb6">llvm::DIExpression::appendOpsToArg</a>, <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info/#a143ae0d499f76d9666bc71f160c1285c">llvm::opt::OptTable::Info::appendPrefixes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a253deb4046b74b2df2b5acd762b95d58">llvm::appendReversedLoopsToWorklist</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a9e3defde95d12941aee71bb6f17a7b6e">appendScalableVectorExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/codemetrics-cpp/#ada13d2155f1d7c672e7b7134819fc847">appendSpeculatableOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a8508f3dbb1f9429445f50282297b4f9a">appendToGlobalArray</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ac255b2b7ff59963227ea39e1d176f63a">llvm::DIExpression::appendToStack</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#a08fddb3d382c1c806dee38774e6464d7">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::appendToVectors</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarftypeprinter/#ae18a539636ce8c8644caedf1fa21f041">llvm::DWARFTypePrinter&lt; DieType &gt;::appendUnqualifiedNameAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6030b34ba7d1e280088089c0e269bbed">appendVGScaledOffsetExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuexportclustering-cpp-/exportclustering/#a3432dbdb86f0a5f40c9d3bcfd8633b28">anonymous{AMDGPUExportClustering.cpp}::ExportClustering::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/a57chainingconstraint/#af022d8d0187b3df267d3e7754cb4b80b">llvm::A57ChainingConstraint::apply</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonsubtarget/usroverflowmutation/#af2918620aeda858e99c7fac5f1e9eb16">llvm::HexagonSubtarget::UsrOverflowMutation::apply</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#ae26a44292d42d576349e053e3497c18f">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtAddvToUdotAddv</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-aarch64prelegalizercombiner-cpp-/#a0647544d97241e683cd0d0b7f3f51927">anonymous{AArch64PreLegalizerCombiner.cpp}::applyExtUaddvToUaddlv</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuigrouplp-cpp-/mfmasmallgemmsinglewaveopt/#a568501d2ea6d5786f4981de195297020">anonymous{AMDGPUIGroupLP.cpp}::MFMASmallGemmSingleWaveOpt::applyIGLPStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a6db02afb81ab497196f6c979f040c063">llvm::AMDGPURegisterBankInfo::applyMappingImage</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a66655fdd73a951d10ad6fb804f0fac98">llvm::AMDGPURegisterBankInfo::applyMappingImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a87ac3f636dddf683cf1f9b7f1a60b1ae">llvm::AMDGPURegisterBankInfo::applyMappingLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/waitcntgeneratorgfx12plus/#a30a7745f58a481ca6495b35e202e4cce">anonymous{SIInsertWaitcnts.cpp}::WaitcntGeneratorGFX12Plus::applyPreexistingWaitcnt</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acd1fbb2df257f945afda92919be322f3">llvm::OpenMPIRBuilder::applySimd</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-spirvprelegalizercombiner-cpp-/#a99fb6c2c4ea3a52f8977eeb8d2c2f425">anonymous{SPIRVPreLegalizerCombiner.cpp}::applySPIRVDistance</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ad89ca302de455d3971f751c8d1a5bd58">llvm::MemorySSAUpdater::applyUpdates</a>, <a href="/web-llvm/docs/api/classes/llvm/genericdomtreeupdater/#a28512659006140e4ac78ee3a68043dd5">llvm::GenericDomTreeUpdater&lt; DerivedT, DomTreeT, PostDomTreeT &gt;::applyUpdatesPermissive</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a6cbfa42d7993571ddbfe46d0c37abafb">llvm::CombinerHelper::applyUseVectorTruncate</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#ac66a7135ed298f43f06fedd02fd33f74">llvm::X86TTIImpl::areInlineCompatible</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a83e6ea9ad14301bc03c55827f0689dc0">ARM64FindSegmentsInFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/bdce-cpp/#acc600a6141b4b54703a4ead9c72a3012">bitTrackingDCE</a>, <a href="/web-llvm/docs/api/classes/llvm/criticalantidepbreaker/#a5a71ccecb00de06004fb421a568dd7b4">llvm::CriticalAntiDepBreaker::BreakAntiDependencies</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#aadca3692ce40afeb83b7765b2d7dfc9c">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::build</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a0b52d2ebf631ded594b7311d1f2829e3">llvm::rdf::DataFlowGraph::build</a>, <a href="/web-llvm/docs/api/classes/llvm/switchcg/switchlowering/#a225bed9cd6803933d859e79619abc590">llvm::SwitchCG::SwitchLowering::buildBitTests</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a85cbdd891f1cd43d6c79f7d68a2caf46">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::BuildBlockList</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a96b7ed72c9782cd69b2b9b341cf73112">llvm::MachineIRBuilder::buildBuildVectorConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a1b412464f78908112e627ee7bc54f99d">llvm::memprof::buildCallstackMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aea49493e2ae224d30cda2b3235d180b0">buildClonedLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#afe5225e90ea8896cab9cda7246af413d">buildClonedLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#aae7d70f087262ba4f7657f564ce0ca38">buildCopyFromRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/calllowering-cpp/#a2e9d3565509fb5cd3e136c0fa68ad5b2">buildCopyToRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#ad68c3cafb2cc7ee28ee3c7dff2a45f2e">llvm::MachineIRBuilder::buildDeleteTrailingVectorElements</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac5631975d77a389618f6cdb0035cc561">llvm::buildEnqueueKernel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#af1364d76011b791bbac39ca8470dd2bf">BuildExactSDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/targetlowering-cpp/#a1ca08074fa512b26eb7e8e88833892d9">BuildExactUDIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#ac65c36245c627cb9fb40879101d952a8">buildFatArchList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a86c6fee36a1f17461710c01e694ee8df">buildFrameDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a36d1ac387bd87a2b357d7ca612d7d5f7">buildFromShuffleMostly</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-amdgpusplitmodule-cpp-/splitgraph/#a85511f1d0a02c18e6c6dd590344664a4">llvm::anonymous{AMDGPUSplitModule.cpp}::SplitGraph::buildGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/vplanslp/#a58eaa1512d1998338ab6f9e8e710a46e">llvm::VPlanSlp::buildGraph</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9875dff9496a8c83bc0bcf749858c45b">buildIntrinsicArgTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a01959fee9db67c3a625348ae39489c5e">llvm::AMDGPULegalizerInfo::buildMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a901a49f9b5721ab01d9d371f96e4bcea">llvm::MachineIRBuilder::buildPadVectorWithUndefElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a45b06cc0aa3a6fcbace0aacf3b25a9e6">buildPartialUnswitchConditionalBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#af693d8401a06eab53b8b5b2d6df05243">llvm::AMDGPURegisterBankInfo::buildReadFirstLane</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a72787ab6acfbe504a11ca1d927513356">llvm::LazyCallGraph::buildRefSCCs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#ad069ce26777bd310235dc9e8f7d7e81d">buildRegSequence16</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a5583b4d2c0c7813f44df3fe6d42d20e1">llvm::PPCTargetLowering::BuildSDIVPow2</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af5d3388e53cb2767927dba7c18c64a00">llvm::CombinerHelper::buildSDivUsingMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#afbd7f8e7654d71a5771a4eaa8b622bd2">BuildSubAggregate</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af3b3616540da1859ec9d030a76cad94f">llvm::CombinerHelper::buildUDivUsingMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregcoloring-cpp/#a363e3f71faf094bba68a16bb32f43cff">buildVRegToDbgValueMap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e3d3da964f7eb14ef2eabf0c4a08ba5">llvm::c_str</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#af1dbaf0e42fc61259e10468caeb7f4b5">CalcNodeSethiUllmanNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a0bfeadac5ccd4e56b4c5df9dc6bb8817">calcPredicateUsingBooleans</a>, <a href="/web-llvm/docs/api/classes/llvm/idfcalculatorbase/#a714e5448566006046f747d9ec4df8241">llvm::IDFCalculatorBase&lt; NodeTy, IsPostDom &gt;::calculate</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a20affbb8e81211322b21dd9c967dbafa">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateBinaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#aeef8fd311d28014d31806cb5c9ad523f">llvm::ModuleSummaryIndex::calculateCallGraphRoot</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a9fe92d5d425b0ddab77a3bd58e734a74">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCastInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a28797a7ad88ceb957e31f0bc5802395f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCmpInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bf41f2408094f54097744991c82336a">llvm::calculateCXXStateForAsynchEH</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a7227d9ecc33b8ed7a50b0d4341448c6c">calculateCXXStateNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c5e19523172e41e6a320be6fd748e17">llvm::calculateDbgEntityHistory</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a91466f7a82e967ed765e6d876415a3b7">llvm::LoopVectorizationCostModel::calculateRegisterUsage</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b49442c1c01ddc388c51d7599c0f876">llvm::calculateSEHStateForAsynchEH</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a24d6b4ddc639fabd7fed767dbedfecc2">CalculateTailCallArgDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a246a48082d0e8d3e7ec999f91b584590">callBufferedPrintfArgPush</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a49077c24022f5ec4c84d809abf92e91e">callBufferedPrintfStart</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroelide-cpp-/coroidelider/#adb122f608fe469bd24f486598a4bc881">anonymous{CoroElide.cpp}::CoroIdElider::canCoroBeginEscape</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#aa10cee1a6cc1fbb381e3dab0c92c4cb2">canFoldStoreIntoLibCallOutputPointers</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#ade8a5e3b6a082e4cb8bb4202ae7f652a">canonicalizeDwarfOperations</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86speculativeloadhardening-cpp/#a22244f1af2bc880ef42bfd77068ce13a">canonicalizePHIOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac1639f9e80414a665a5826e6e4ca6095">canonicalizeShuffleMaskWithHorizOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a596a49623f77050eb85eb8f12b88de3e">canReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aea73058623ab7225aabe7a95068784a4">llvm::ScalarEvolution::canReuseInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a9e6b15b1005dd460a35359f104cb06fe">canRewriteGEPAsOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/legalityanalysis/#a5c81ada05bd736617bf16b24329360b8">llvm::sandboxir::LegalityAnalysis::canVectorize</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a496356f8335c794a9b365488ed263ead">llvm::slpvectorizer::BoUpSLP::canVectorizeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a5a32fa3ab512ce8c3afa4e68c2b56765">castBufferRsrcToV4I32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6f4eef604ff06e2b83fabf52e828c709">anonymous{ConstantFolding.cpp}::CastGEPIndices</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#a631b12e0c91c3249444afcf60f3f538c">CC_AArch64_Custom_Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64callingconvention-cpp/#af3f5f44efd30903d2316ec3e8f20cda3">CC_AArch64_Custom_Stack_Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armcallingconv-cpp/#a6790e830edd3f7940cc257f01a794604">CC_ARM_AAPCS_Custom_Aggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#a54bef4de515c1876b876bac86b81975c">CC_LoongArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb12d99088ce4e78fe29e5306ab42c5c">llvm::CC_RISCV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3624679803f9a11d8362aca440f744a6">llvm::CC_SystemZ_I128Indirect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a41dd5c8db0f0898d613b138097515474">CC_X86_32_MCUInReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a4634e79ad97015aa93f2379f619cc6ae">CC_X86_32_RegCall_Assign2Regs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86callingconv-cpp/#a61009b749b466b57d30ec5134bf613bb">CC_X86_64_I128</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#acfe25d0718869b5fc9d85c1f96cec8ef">chainLoadsAndStoresForMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aaaf972edd3d60e198b996c65e05c4a5a">llvm::MachineInstr::changeDebugValuesDefReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97370114df349e0996f133e3402c1595">llvm::changeToUnreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a94cd9c4d5114d65e1cd802c23c080326">llvm::MemorySSAUpdater::changeToUnreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#ac41c50a3b85aa5098391b76548f04e3b">checkDependencies</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#abbea65eed8b9b7cd07f0b8eef53df6f5">llvm::Attributor::checkForAllUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagfast-cpp/#abbaf6b527fda317964759a8917f436cd">CheckForLiveRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a37a1b9361cb4ed78aa4af0973696f7fb">CheckForLiveRegDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#affd5619a70ecc254d62f604150468f1d">CheckForLiveRegDefMasked</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterimpl/#a361f4564a774bbb16b4a27667256c5ad">llvm::SSAUpdaterImpl&lt; UpdaterT &gt;::CheckIfPHIMatches</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#aa1129d2080e1308fd9bd27d20374ace5">TransferTracker::checkInstForNewValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#af1fba45879c49d4839b11ec30afd7532">checkMixedPrecision</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/#a7e6c4318cd8d3ae5bbe88df3d4a58490">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::checkNodes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaglobalvalueinfofloating/#ab7660504ac6ac15f209047da7f39755a">anonymous{AttributorAttributes.cpp}::AAGlobalValueInfoFloating::checkUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af9b65d81d95d19757080cfae034e3d7e">checkVectorTypesForPromotion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afbd48a6ba727670df45deca96345e382">llvm::checkVOPDRegConstraints</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pointertypeanalysis-cpp-/#ac10c52fc6c6c8328779f3175fce68067">anonymous{PointerTypeAnalysis.cpp}::classifyFunctionType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ac3cf098d54027ac28278b060376bdcbd">CleanupConstantGlobalUsers</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a38e9b77a3c8508ea8ff0ba1f5bf81eba">anonymous{DXILOpLowering.cpp}::OpLowerer::cleanupHandleCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a1cc201a5d5dcba96ba22aa38e2eb176e">cleanupHelperInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a03cdd58b24dc91b4e3819e218a399cbf">cleanupSinglePredPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/bdce-cpp/#a54ab652f375db02ea7894a5f9a512d15">clearAssumptionsOfUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#ad75c8e4486e2725285e4f149cc025ef5">llvm::FileCheckPatternContext::clearLocalVars</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp/#a8380bda17afbeb9b1792136a17e55f74">clobberRegEntries</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/scopedaliasmetadatadeepcloner/#a7bc92ff74f9a62146656fbaf0732c09a">anonymous{InlineFunction.cpp}::ScopedAliasMetadataDeepCloner::clone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#aa92016f492dbd1ebc2004235f61e6239">cloneConstantExprWithNewAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#ac1ac18b9f807acbc9846d923ea874524">cloneFrom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af97d9ff977792ae671987a9a95f942f2">llvm::CloneFunctionBodyInto</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#afbf9fd3d3729664031c88766bcefcdf0">anonymous{CloneFunction.cpp}::PruningFunctionCloner::cloneInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af747cc9f106d837a03d08bd395ede216">cloneLoopNest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalscope/#ae713d283078fedb08e45a4e893508866">llvm::DILocalScope::cloneScopeForSubprogram</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblydebugvaluemanager/#a93c989266fe445bd8d6466480699665e">llvm::WebAssemblyDebugValueManager::cloneSink</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a3fe022748964a4bdaca9fa36568ec149">anonymous{ThinLTOBitcodeWriter.cpp}::cloneUsedGlobalVariables</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a2d26c707fd7389b46ad98970d56faf24">clusterSortPtrAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab349dce775a8c8dcd72c24059e8357a2">coerceArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aef5fe3787940afbf550b4cd5ae8ac03f">CollectAddOperandsWithScales</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a8d0c6052d21638f0a385e226db3bd92f">collectAllHeaderMasks</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#ab0236d3f5f443260abf1ccfb1e5cc5a6">anonymous{FunctionAttrs.cpp}::collectArgumentUsesPerBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/openmpirbuilder/outlineinfo/#a218bc49443ef1f05fc8074d872d41fcd">llvm::OpenMPIRBuilder::OutlineInfo::collectBlocks</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-bpfmipeephole-cpp-/#ab0827bed6547378efa61b05fc7958a13">anonymous{BPFMIPeephole.cpp}::collectBPFFastCalls</a>, <a href="/web-llvm/docs/api/classes/anonymous-sioptimizevgprliverange-cpp-/sioptimizevgprliverange/#a5290bdffbf68a26e47345d1bb2abb246">anonymous{SIOptimizeVGPRLiveRange.cpp}::SIOptimizeVGPRLiveRange::collectCandidateRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#a586a0928ddd8c387ebb2032e9f61e55b">collectCastInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a544a0723e20148ceb9a3bb3210f45270">llvm::collectChildrenInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a156ad3625396789011bd7ce3ff5f9364">llvm::collectCmpOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a13dafea5ca0652a4011dd613a8f02494">collectDbgVariableIntrinsics</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a5105322139844c10dc05539f70ff3eca">llvm::MachineInstr::collectDebugValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62219a4c97e27d64593245e4e9187cd1">llvm::collectEphemeralRecipesForVPlan</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#aa9d766b132f29a13565b6b239174bf44">llvm::GCNTTIImpl::collectFlatAddressOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxttiimpl/#a1a813f5d4ac98821dc6efa24abf12ef5">llvm::NVPTXTTIImpl::collectFlatAddressOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a1061b839196c8068b89d05aced41de29">collectHomogenousInstGraphLoopInvariants</a>, <a href="/web-llvm/docs/api/classes/llvm/ddgnode/#af91d9f50a649787e882b7383c7e997d3">llvm::DDGNode::collectInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#aff1b71fb51fbfeefc8cb3c92021ee0de">collectLeaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/typesanitizer-cpp/#a8fe9c2e5d8a275393677c1c46c5f0596">collectMemAccessInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a97b8f22f6c8ebb59fe454ba80d407baa">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::collectMemOpRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a1871554e8a3734782e7f7a145cc17491">collectMemProfCallStacks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a5ae389cc9acc023d9637b1c1d2b76380">collectMultiplyFactors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a37ddbdd8cb4efa5072282498fdc1ac65">collectPromotionCandidates</a>, <a href="/web-llvm/docs/api/classes/llvm/pmdatamanager/#ad3081121743797ac69560ffa5f381ced">llvm::PMDataManager::collectRequiredAndUsedAnalyses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#afee39cae7ff99ef86d9f4ed0ee4282f0">llvm::coro::collectSpillsAndAllocasFromInsts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4062c17e282cb2667cf0d52150c67fea">collectSRATypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#a0f2532bb6e482a8f04b68585b8cfc032">collectTransitivePredecessors</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-ppcmipeephole-cpp-/#a8853b2033702691c17576d5acc430460">anonymous{PPCMIPeephole.cpp}::collectUnprimedAccPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a7737deb6a166cd21dc8465bb48f110b2">collectUnswitchCandidates</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/#a86f06c6063c3a34171f47246e4c94ce8">anonymous{OpenMPOpt.cpp}::OMPInformationCache::collectUses</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a0ac5df8f0304981180d602dacb13512c">llvm::LoopVectorizationCostModel::collectValuesToIgnore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adb4afc63a9a9aa3f185854b0cd009b44">collectVersions</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/registerfile/#a0130b17dd269a2bf18408bf108d2cf84">llvm::mca::RegisterFile::collectWrites</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a3a97fed79c86bf242b0f090e1cb2e6">llvm::colorEHFunclets</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#ad4c63831e91ac3cd309f7cc144519411">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::combineAMXcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0285b9eb9c4a75abb42c7cf0ef0154f1">combineAndnp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aa4c17cc7964441daaea8b4bee6c18f93">CombineBaseUpdate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#af8092b588e16c93a54d21da99af4814c">combineBVOfConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ad45a536ce828d7fe0a889a1666437654">combineConcatVectorOfCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a767fefc1593899bc23f0b03007b0bd76">combineExtractVectorElt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a35be28e9754ada1081edc62f6efc0878">combineFPFusedMultiply</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a5727bfde67259475310b6da6c18027e5">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::combineLdSt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a3ff4156c9862c64e6d354f5413c3da5e">combineOp_VLToVWOp_VL</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a027102ec674270eecc2a1a6ec8588e44">combineOrCmpEqZeroToCtlzSrl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4bfc9dfb6bf7ab5af8b76e28d94162c2">combineRedundantDWordShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1f89a7382459e34a2d36ad281210e6c3">combineSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a7847dc95e3ec6e1cdaa66ac48a0f7985">combineShuffleOfSplatVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a208df5267fac83f34e5dbb36815b17b4">combineToConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8593ba64bae1cbd8bc4243743289dab9">combineX86ShuffleChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ad50f91eadaf7ed9853086b05793ef467">combineX86ShufflesRecursively</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a4ca10cc5976994ee1c01be4b019c1ee6">llvm::FunctionComparator::compare</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mccodeview-cpp/#ab3c3e06f7218bbfcf31026d85093efe7">compressAnnotation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a62f4b8744e4b75d5371fb9a8a471ca26">llvm::computeAccessFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a093b0a333833131b3fb12fb62f915bf1">llvm::EHStreamer::computeActionsTable</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#ab79e380b2ff4d4653bc9a766e1a59220">anonymous{MachineOutliner.cpp}::MachineOutliner::computeAndPublishHashSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a46b279956ad150f9e6ff57d03e1fe539">computeBlocksDominatingExits</a>, <a href="/web-llvm/docs/api/classes/llvm/acceltablebase/#a3ae1aa627fae3bd5a88112c59afb492c">llvm::AccelTableBase::computeBucketCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a0ca5d8ebe6f1e89b62a445fc3137bd2d">computeCalleeSaveRegisterPairs</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a49694eb08442bb35020b9d8dfad6d7e5">llvm::EHStreamer::computeCallSiteTable</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ad59bafaeacd51c2b1e6251488039d29a">llvm::VPInterleaveRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ae8d6a4dd88f6b0c4ac0c4c8a46b024e0">llvm::VPWidenIntrinsicRecipe::computeCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b5d72a4e8c39c8d0ea81cb9c547bc8c">llvm::computeDeadSymbolsAndUpdateIndirectCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineinstr-cpp/#a59a9455b7d095fc190494012b9f0364f">computeExprForSpill</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#af01033da46e9a33a66573433a81eaad0">computeFreeStackSlots</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#a9b06152b51259f884261bba3099e4fc6">computeFunctionSummary</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a5addc8b01ca0cce0a572d5fe3ef86654">anonymous{LiveDebugVariables.cpp}::UserValue::computeIntervals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada9b9cff9a1f422b5426595ae603e681">llvm::computeLegalValueVTs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ssaupdaterbulk-cpp/#ab90f4a46f63bfddff132d20866be2da2">ComputeLiveInBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7b6ae12af3578f7a20ccc11a4458f9f">llvm::computeMinimumValueSizes</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7032e1ab44275cf7331a7898a3713aad">llvm::slpvectorizer::BoUpSLP::computeMinimumValueSizes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a30964550089d42d05a78dbb23e4ca35b">computeParamInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a38a01001593bf75700ee024b15bdf413">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computePolynomialFromPointer</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gac3778bafa67cdae223698e5bba785a76">ComputePostOrders</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6d6c53298316411b939795d6959322f2">ComputePTXValueVTs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e263b9cd2bdbbbaf3d78a2caba5cbf5">llvm::computeSignatureVTs</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#af4a07ae5c460ac08439a1a71d15e0166">llvm::LiveInterval::computeSubRangeUndefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#ade155905429b0a259a1030f418c04ad9">computeUnlikelySuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a23d6b914952799027040a351f501a0ad">llvm::SMSchedule::computeUnpipelineableNodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a729a0bf495324521082c23af4e44775d">llvm::computeValueLLTs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab99618b3d8988b758a67f5a1a6071095">llvm::ComputeValueVTs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b3a32d7d35368cbeb1b917c015486fa">llvm::ComputeValueVTs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4288169d91ab0f0f01405115fd2931a7">llvm::concatenateVectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a993771e7c58c60044cbc4c57f689406e">llvm::RandomIRBuilder::connectToSink</a>, <a href="/web-llvm/docs/api/structs/llvm/constantaggrkeytype/#ae8292a7cecde5084390268d22e3d522e">llvm::ConstantAggrKeyType&lt; ConstantArray &gt;::ConstantAggrKeyType</a>, <a href="/web-llvm/docs/api/structs/llvm/constantexprkeytype/#a35a51401bc41aa572a56b74c20a89409">llvm::ConstantExprKeyType::ConstantExprKeyType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40bb6295bf75ebb0f636376637ed518f">constantFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ad60130f0b45a3ff1e759b010afefb94d">anonymous{ConstantFolding.cpp}::ConstantFoldFixedVectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a904cc16cfe269559a2ff1cc7f06df6d5">llvm::ConstantFoldVectorBinop</a>, <a href="/web-llvm/docs/api/structs/llvm/constantptrauthkeytype/#a44ad5fe712f97b8c81a668457580928c">llvm::ConstantPtrAuthKeyType::ConstantPtrAuthKeyType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp/#a8bba5860a29dd4e3f3bca8f97b4e9199">ConstHasGlobalValuePredicate</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/copyconstrain/#aee8fb987217bee89c0f2059168e834ec">anonymous{MachineScheduler.cpp}::CopyConstrain::constrainLocalCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64conditionalcompares-cpp-/ssaccmpconv/#a8c2c7a46bf3359100068e45134218920">anonymous{AArch64ConditionalCompares.cpp}::SSACCmpConv::convert</a>, <a href="/web-llvm/docs/api/classes/anonymous-earlyifconversion-cpp-/ssaifconv/#a97a97757150c110b5bceb79ae0fedc1f">anonymous{EarlyIfConversion.cpp}::SSAIfConv::convertIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#ad049a79d46df2c25561d90e9d80fb5e3">convertImageAddrToPacked</a>, <a href="/web-llvm/docs/api/classes/llvm/typedinit/#a60ed010e5b9fd39c0775648ac9198887">llvm::TypedInit::convertInitializerBitRange</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ad06dcf793a8b91871327c682d6f3f909">llvm::ShuffleVectorInst::convertShuffleMaskForBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a99b699ca919e40ac78708ea425fbfa98">convertToGuardPredicates</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#ac8f832cfa0e0121c6fd066c0f3b25f5f">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::convertToOptType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a944b77cb28ad77cdf28380c4453f8d02">convertToParamAS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad23b52a299ca563f6e6a6c6cece54dcc">llvm::convertUTF8ToUTF16String</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#acfb266590cdac3ed6480244efcd5899c">llvm::coro::BaseCloner::create</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/binarycoveragereader/#a75f0ba2a248f2f7f77f477bfb8d6dab2">llvm::coverage::BinaryCoverageReader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/globpattern/#ad853cb6a2e5807ae5006c0f5ba1e7b49">llvm::GlobPattern::create</a>, <a href="/web-llvm/docs/api/classes/llvm/intervaltree/#ae65afb93ec69b4bab0c72c8b5ca28f9b">llvm::IntervalTree&lt; LVAddress, LVScope * &gt;::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchpadinst/#a75c9c2542ec4d001768526e388e69046">llvm::sandboxir::CatchPadInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/cleanuppadinst/#a7dd404473a05c6b8da7292d8104e992e">llvm::sandboxir::CleanupPadInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#af9e525905347a63733a094e254637234">llvm::sandboxir::GetElementPtrInst::create</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst/#a58be6f9d5ec9cd6dae7bd79e196fb837">llvm::sandboxir::InvokeInst::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a6f467de3ca984f069ee86b9558388294">anonymous{OffloadWrapper.cpp}::createBinDesc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizevectorops-cpp/#ad378536508f0c71b730daf4da2026076">createBSWAPShuffleMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2cd95c4fd57b9c1804bc70a37ac24574">llvm::createCFAOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a48ebbc1e9c11c52c99229d706238ea8a">llvm::IRBuilderBase::CreateConstrainedFPCall</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ac379895c55a89804f49f1a775828c235">llvm::OpenMPIRBuilder::createCritical</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a89565d08a98c901e24daed37f35cd442">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad301df8bf0c11d0c17113d3c221025d8">createDefCFAExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#af7b1b04b85a4e865d887cbf6f5889a10">createDefCFAOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#ad1b4c0caba0fac3a1486890cd2445040">llvm::EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a35409dbaffc2cf38fefec12e3cf9094d">createFakeIntVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a7ae16889db439f8fbb234fe3de672d11">llvm::VFABI::createFunctionType</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#afc83c1972006a05871f65fdf15ade10f">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::createHvxIntrinsic</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa88371693bc18186386b04e8c45a30e4">llvm::VPlanTransforms::createInterleaveGroups</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aef9c35f13cf93ffcc6bafb8a210d842e">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp/#a7cbecc17bbb64783431627bcf1f433c7">createMIBNode</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a6022d366369fcd539dadfaefc80927db">llvm::MDBuilder::createPCSections</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aeac445a66283c4e567ebd390c058e39d">llvm::IRBuilderBase::CreatePreserveArrayAccessIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a9ec3732ab208437ca6ee8e13438bd0e8">llvm::MachO::createRegexFromGlob</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/region/#a8a8865325da7e23f2f527bb04e1a26d6">llvm::sandboxir::Region::createRegionsFromMD</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#af05ad96486c97ea7158a65507aaee0ef">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::createReplacementValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7504dd988bee776d391c05231515297d">llvm::createReplicatedMask</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ae934d6e99e0516d606ae8e65ff6aed63">llvm::IRBuilderBase::CreateStepVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#acae95016bcdeb105bcbcaaa872893f5f">createTargetLoopWorkshareCall</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0af3c7a02c1325c04c59f857604bd4f3">llvm::OpenMPIRBuilder::createTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3f603d822817256077c95e6573f2b14a">llvm::OpenMPIRBuilder::createTeams</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a1fb67d47830d47e72144d7456dbb7fa0">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createTiledLoops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2bea09503a438b76b5c9253327118af5">llvm::createUnaryMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aa37537b95a42a73ea04d8dd2803378da">llvm::sys::fs::createUniquePath</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7aa8025f73f4e06135e6ba7083ad7aab">createUnreachableSwitchDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a69d0103b83202f0339cfb6b018b3c78a">llvm::IRBuilderBase::CreateVectorReverse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvevptblockpass-cpp/#a173df60eae8081683241de7888b84be8">CreateVPTBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#aa1f2beab8ceaaf066d1523dd523fe25a">llvm::mca::ResourceManager::cycleEvent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ac10429a8c82694552d49e1aba0b85491">DbgVariableRecordsRemoveRedundantDbgInstrsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a961e2695793920fc477be3d95e20babe">DbgVariableRecordsRemoveRedundantDbgInstrsUsingForwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#aa1970a96b57d122e4bb765d0f82e96e6">DbgVariableRecordsRemoveUndefDbgAssignsFromEntryBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue/#a3e5ffea0fa3c8e006a9bb56d22a0aa12">anonymous{LiveDebugVariables.cpp}::DbgVariableValue::DbgVariableValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d97ec8d51a9f56c4a2cff1f7a567b4e">llvm::DecodeBLENDMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3f561be3774824a1538c872d6b111718">llvm::DecodeEXTRQIMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ab29da57c63bb1608298c863ea81696cc">DecodeIITType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a13a4f002f67e507023190d6e72a7c738">llvm::DecodeInsertElementMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a54d9df5550cc72e33765a9213af3a081">llvm::DecodeINSERTPSMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a853d1016b3f70fa9b00fbac31da2cc70">llvm::DecodeINSERTQIMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adcedbc2538f7e9666fa49dcc0a61375e">llvm::DecodeMOVDDUPMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a06757c13e2255f68dcc264f90e297866">llvm::DecodeMOVHLPSMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a623ed11af9d5d9d002106a261964a616">llvm::DecodeMOVLHPSMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee8aa7777eedc7487661fee12bf3e7c6">llvm::DecodeMOVSHDUPMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab771db4c5e178de23b77b6e30fb582c0">llvm::DecodeMOVSLDUPMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp/#a0283fbbacd7e1b520ab58b9b867b1c71">DecodePALIGNRMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab489acbbe8913e85a72c328360e7b80b">llvm::DecodePALIGNRMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afb680fe35fd4d397b7d0674c45861008">llvm::DecodePSHUFBMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4965a0580f1dc82ac2a4d2cfecd8389">llvm::DecodePSHUFBMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6980ab306f3c6b311d1f4bd0153dcd6">llvm::DecodePSHUFHWMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1ea81707249d1e52ad3605e971edbcd9">llvm::DecodePSHUFLWMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad9d7820c2d1fb15b4454f215980469c5">llvm::DecodePSHUFMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfe6c00814a6a08dcd4a68cbd2a934e4">llvm::DecodePSLLDQMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b5002b835149198532fc6ef6685e0b2">llvm::DecodePSRLDQMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e3f414df2509b831cd510b0269fcd81">llvm::DecodePSWAPMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaf783c4560c5874f3a0faa0036b2f00e">llvm::DecodeScalarMoveMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6865b2aae273b40d7284034769da3d8">llvm::DecodeSHUFPMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abd0284b76f8abda19007d5c30d460fc2">llvm::DecodeSubVectorBroadcast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3e2417cd0c0945eb8ea230132174859">llvm::DecodeUNPCKHMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfba7ac64ff238335b6db60849e2fb74">llvm::DecodeUNPCKLMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5190b9dbb3777bd0cbe9b17c1713a4b">llvm::DecodeVALIGNMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a56561a06c5e189905d213a05a0ab9273">llvm::DecodeVPERM2X128Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af62d6d0e38b12746870f6996e60f42d3">llvm::DecodeVPERMIL2PMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5fb0db87ada1b48888e070c009007845">llvm::DecodeVPERMIL2PMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a155c4064200810dc0e257a299014c162">llvm::DecodeVPERMILPMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a19ed1906d1fc3026d1bf29313dfcfa68">llvm::DecodeVPERMILPMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e3f786bc082e1485e1a863aab736513">llvm::DecodeVPERMMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33cfdeaaf372a893845f4283d8b38721">llvm::DecodeVPERMV3Mask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b736243d275dddeb7c434f0b03841bf">llvm::DecodeVPERMVMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2ea0deda81eb9adf593b817b901fc1e">llvm::DecodeVPPERMMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae64455568f4dbe957082221523e72000">llvm::DecodeVPPERMMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3df0419215a6ed24a6c29f8cf25aa4e5">llvm::decodeVSHUF64x2FamilyMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a01ddb8ea0c52fea9a3e87e46a10d00d8">llvm::DecodeZeroExtendMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a117aeb7b7429c5d944a693fbb4d1ac19">llvm::DecodeZeroMoveLowMask</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue/#a45719cda7bb0e20994a03ded88207804">anonymous{LiveDebugVariables.cpp}::DbgVariableValue::decrementLocNosAfterPivot</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#ab389f58bce3bb2dcd1eb8284f46064ee">deduceFunctionAttributeInRPO</a>, <a href="/web-llvm/docs/api/classes/llvm/filecheckpatterncontext/#a7137a381bae270178ff79807b1d096d3">llvm::FileCheckPatternContext::defineCmdlineVariables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#a11e115c0bc63e73df009e5117821d230">llvm::at::deleteAll</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aeabcdff1c388af9ac5a98f1ec4ba2471">deleteDeadBlocksFromLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a13971a178ec8248ecf4b0a903c4db1c6">deleteDeadClonedBlocks</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a32e5e2e67b52bcd45fef4487f664f9ec">anonymous{DeadStoreElimination.cpp}::DSEState::deleteDeadInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74b422e2c15d859ba49911cc329f11d7">llvm::deleteDeadLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a64ecdacbd49f696216e772782a109945">llvm::DeleteDeadPHIs</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#ac0c56f97d07cfa7188e654e794e5032e">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::DeleteUnreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/dependenceinfo/#a49197b24cced248bed2d2c89c641a6dd">llvm::DependenceInfo::depends</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac800803b298b2e26368a3cc770279945">anonymous{ExpandVariadics.cpp}::ExpandVariadics::deriveFixedArityReplacement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22b952b9d905fdd3aaedbc2ebf426339">llvm::detachDeadBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#af2f88cb2b4134972392e4efa778596d6">llvm::ARMFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a7865e2cad3030c3c48b64c9cf1243d46">llvm::SIFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armexpandpseudoinsts-cpp/#ab85ec1f9019bc54f0c9962a347b9dc45">determineGPRegsToClear</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a56db9c3cbc621caf7d84f6982f095392">determineSVEStackObjectOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/vfs/redirectingfilesystem/#a5edc743f072765fe8146c1f597d4bb37">llvm::vfs::RedirectingFileSystem::dir_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/regpressuretracker/#a60e96ac40c51e2ad7e24f9776fda71d1">llvm::RegPressureTracker::discoverLiveInOrOut</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a6c25c8fa1e18bfa4689e9982991c9791">discoverTypeIndices</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a25991c233686a63c58cc75b2fc0d9a5f">discoverTypeIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/connectedvninfoeqclasses/#a5d79e4d110e15056182588d168ac6b2f">llvm::ConnectedVNInfoEqClasses::Distribute</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#adda9f21a68ad40aac3ee4e0bf3afa31d">llvm::BlockFrequencyInfoImplBase::distributeMass</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa9a2aed0d26a4fca41f8fc0986a3f12b">llvm::AsmPrinter::doFinalization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aa59a46776e15b1f1bd597c4e1e769f59">DoInitialMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp/#a755b4fb8450994d9125dbcd317bc4fc0">DoLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp/#ab036d04a80df6b9a9f3dbf42a3884bb8">dropIntrinsicWithUnknownMetadataArgument</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa0f143b8d4693978b984f0639c90e508">llvm::VPlanTransforms::dropPoisonGeneratingRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5dcbbcb6c022f6f2c8b46a3e0a4821b5">llvm::Instruction::dropPoisonGeneratingReturnAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuinsertdelayalu-cpp-/amdgpuinsertdelayalu/delaystate/#aee94f03d721dddddb0e9136561f3b8b8">anonymous{AMDGPUInsertDelayAlu.cpp}::AMDGPUInsertDelayAlu::DelayState::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/#abdb9058a51e2fb5fd61d203dcdfd551a">llvm::AppleAcceleratorTable::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/constraintsystem/#ae3c3559c5cf840283a4b2402fe8e699a">llvm::ConstraintSystem::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#ab34667f1d218ea0b6566dd8f861dfe93">llvm::ScheduleDAGSDNodes::dumpNode</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#a326b69bb87197af5c7e9398da090d754">llvm::SMSchedule::earliestCycleInChain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#aac00cb920a9d9d61a45759a8e4314142">llvm::AMDGPU::eliminateConstantExprUsesOfLDSFromAllInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a61e2de2c4987a7fdaf09251933714262">eliminateConstraints</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a83b0a34d940365e97b9a531c1f13f3b9">eliminateDeadSwitchCases</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looploadelimination-cpp/#a14eeb1cfc5947b2dde03d0d8fd89efc4">eliminateLoadsAcrossLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a311a80924f5342813ae67daa5e5ff444">eliminateSwiftError</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a8356860a8bef082ff15df896ecec7732">eliminateSwiftErrorArgument</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a6f5eb28a130d94e94dff2f9e798617ab">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateTrunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfstringpool/#af442217bf93681bd683a2cb4d7c21e49">llvm::DwarfStringPool::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#ad915c31dcf8d35cf0affa3f8f13a043b">llvm::AtomicInfo::EmitAtomicLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a5df935e7c87e3e1dc8b3d7e1870ee1c9">llvm::AtomicInfo::EmitAtomicLoadLibcall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-x86mccodeemitter-cpp-/#ab04a741cd062f6096b5181ada9b27489">anonymous{X86MCCodeEmitter.cpp}::emitByte</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6c1f3151b66ea2dfd6a8b9cef815d51c">llvm::X86FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1b67472deb590ff2b82c73e3ff4497f4">llvm::AsmPrinter::emitConstantPool</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a8ea1d38f4a65135188eb7409818070e6">emitDarwinBCHeaderAndTrailer</a>, <a href="/web-llvm/docs/api/classes/llvm/instremitter/#a1157b5306838143f5553c67c1c8489c5">llvm::InstrEmitter::EmitDbgInstrRef</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a38c76eebc11caaa9225a4bfe146585a6">anonymous{LiveDebugVariables.cpp}::UserValue::emitDebugValues</a>, <a href="/web-llvm/docs/api/classes/llvm/ehstreamer/#a420cc4a7a63b33a52659768b133b5f1b">llvm::EHStreamer::emitExceptionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a34d2fd0bdbbc9d9560ec44b5fac25d50">llvm::AsmPrinter::emitGlobalGOTEquivs</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a52b44307c581360f228fe357414b2784">llvm::AsmPrinter::emitJumpTableInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a4bf617363cf454c0a6e08bb6e78fe55a">llvm::TargetLoweringObjectFileMachO::emitLinkerDirectives</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siinstrinfo-cpp/#a476adf24d3374520fb31b2785f331d58">emitLoadScalarOpsFromVGPRLoop</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker/#a88fd52c520cef6a03af97c37c308ae78">LiveDebugValues::MLocTracker::emitLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblytargetwasmstreamer/#acd61544675a1873eab270dd83138d509">llvm::WebAssemblyTargetWasmStreamer::emitLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/codeviewdebug-cpp/#a3b4618fc48c7d5c6c6e7df30e56f7ed6">emitNullTerminatedSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#a75f9b9721a2718d692fd3805c713f2ff">emitResourceMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a6f60ed03227dbeb711a3ae9b1f0238e9">llvm::ScheduleDAGSDNodes::EmitSchedule</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a2706d140844a6517f06fd552269a7aba">emitSignedInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilbitcodewriter/#a9973792296d07d67ee9c2a6788dc7bc4">llvm::dxil::DXILBitcodeWriter::emitSignedInt64</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a751f59893007a8fdcc892d81119abc82">llvm::VETargetLowering::emitSjLjDispatchBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a06dab5b53d53c65a118f25ea11570352">llvm::WebAssemblyAsmPrinter::EmitTargetFeatures</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a2841680b34ec9c2c7185a877f8f8b4c8">llvm::OpenMPIRBuilder::emitTargetTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64selectiondaginfo-cpp/#a5e928c317d7fc895a503f4953ac4c7d0">EmitUnrolledSetTag</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineaddr/#ae0f19d1d97309d2c250054dae4569622">llvm::MCDwarfLineAddr::encode</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarfframeemitter/#aa8057040c954e677e4172d5b69650b72">llvm::MCDwarfFrameEmitter::encodeAdvanceLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#aea53ea050c3442abffd1c991f4c7213a">llvm::CodeViewContext::encodeDefRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpumccodeemitter-cpp-/amdgpumccodeemitter/#a57c601613d1b256c59417e392d0575bf">anonymous{AMDGPUMCCodeEmitter.cpp}::AMDGPUMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-bpfmccodeemitter-cpp-/bpfmccodeemitter/#a76f5410dcaece835e30459df0a57c16c">anonymous{BPFMCCodeEmitter.cpp}::BPFMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzmccodeemitter-cpp-/systemzmccodeemitter/#aed7a817b862875cdf57a54465eddd708">anonymous{SystemZMCCodeEmitter.cpp}::SystemZMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-xtensamccodeemitter-cpp-/xtensamccodeemitter/#a6179b7237d97c30ed95f374529652df2">anonymous{XtensaMCCodeEmitter.cpp}::XtensaMCCodeEmitter::encodeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a6d548a27495e0e978c1ef0cc0f185744">llvm::SelectionDAGISel::EnforceNodeIdInvariant</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/deadcodeelimination/#ac9dc6dd66dabbaf46fe4d72655758f4a">llvm::rdf::DeadCodeElimination::erase</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#a1659a196eabbdd653b9a5d529ccfcb6e">anonymous{RegisterCoalescer.cpp}::JoinVals::eraseInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a06358c30f3e98d9e57f4ae9162f33c72">evaluateInDifferentElementOrder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8d6c4616e2c2cc90d58377868eda6102">llvm::examineCFlagsUse</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ab0d48fabf61af227821d568b1c3aa4ca">llvm::VPInterleaveRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidengeprecipe/#a1b84446d2e199358a8406e7c92f51f03">llvm::VPWidenGEPRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintrinsicrecipe/#ad6ab589f9da183bfc7227344c30aab78">llvm::VPWidenIntrinsicRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a533cd1035e03cdca3da433e98e77e430">llvm::AMDGPURegisterBankInfo::executeInWaterfallLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/gimatchtableexecutor/#a0a2955a941402b4280306f0142b21061">llvm::GIMatchTableExecutor::executeMatchTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/legalizedag-cpp/#a07a2d3fcc11565312fcc713d6cf38c6f">ExpandBVWithShuffles</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a42e88a4f9074b20ed76649b6e7f5bbc1">ExpandCryptoAEK</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a2eb27d5b23a26ef2c0d6262a105a1d52">expandFillPPRFromZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/dataflowsanitizer-cpp/#a587c4289ae52d2bea98482248fac1749">expandFromPrimitiveShadowRecursive</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandreductions-cpp-/#ae32d63d2aee7169e45cf696b040ccb66">anonymous{ExpandReductions.cpp}::expandReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/expansioncontext/#aebe5d0c3153807263988efc57d69a509">llvm::cl::ExpansionContext::expandResponseFiles</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ab8ebdf9a381ab517c0225f7f0719cf45">expandSpillPPRToZPRSlotPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a88dfee6623475363a4e46966d8383c0f">llvm::SCEVExpander::expandUnionPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a017054a3231506db436fdd9e8ae20ca0">llvm::expandUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/makeguardsexplicit-cpp/#aeee7951092aa5ce8f95ecb2f03d42893">explicifyGuards</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a021f42abfec39ba02f6b719a449b21db">ExtendUsesToFormExtLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a360a3a3b8e58083592c0767fa8dae8bf">extractLoadMMOs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c32a92de16156166b3fd4de261d20a0">llvm::extractParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9e6be5e780735b6ac4df380430d09808">llvm::extractParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ae42494312d821219695aa74d320fd4fd">extractStoreMMOs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a725f0b87c254902624322397fb9301ef">extractValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af4c0f443e3b75e7b2ffaf53d2ab73fc0">llvm::extractVectorParts</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a78e425f7e61cda2ed4db6054c39beb18">llvm::LegalizerHelper::fewerElementsBitcast</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#abb2458b37415bd3ed547b405507ebc6b">llvm::LegalizerHelper::fewerElementsVectorMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8f6d92157833612e9b4cd0085e181b7e">llvm::LegalizerHelper::fewerElementsVectorMultiEltType</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a60e4161d46b020a55403acd13e31df9a">llvm::LegalizerHelper::fewerElementsVectorPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#addd0c111e12b07d02698a1fdcba59b0d">llvm::LegalizerHelper::fewerElementsVectorReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a1eac84349f5abc12d101036412730c5c">llvm::LegalizerHelper::fewerElementsVectorShuffle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a7af9698ef8e2fd0bdcafe8c664c52e9e">llvm::AMDGPU::fillValidArchListAMDGCN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a1dacc9c15858a08654e406335cfeb803">llvm::AMDGPU::fillValidArchListR600</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aarch64/#a811093fb62359ffb5b991454f462c370">llvm::AArch64::fillValidCPUArchList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a2458a18e9c87222cdc800b024276c921">llvm::ARM::fillValidCPUArchList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/csky/#a280ae1ca5da01930c7d1f757f3946d31">llvm::CSKY::fillValidCPUArchList</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/markupfilter/#ae17194d7c43b1fa4e468363cb9473021">llvm::symbolize::MarkupFilter::filter</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/vregfilter/#a7e8736b28b4391ab04842fa61209e86b">anonymous{MachineVerifier.cpp}::VRegFilter::filterAndAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#acaf17f6b9d9191f5d0bc4fad37af17e9">FilterHelper</a>, <a href="/web-llvm/docs/api/structs/llvm/controlflowhub/#a14e3b2ee272be893fb7d474a5530705c">llvm::ControlFlowHub::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a138b93205c71960aa94763a1081c50e9">llvm::DIBuilder::finalize</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a077981b5798a5d7a95cec16ece863aeb">llvm::finalizeBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp/#a51e2be2d1cd63e7b951c1f25c8eb182b">findAffectedValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/domconditioncache-cpp/#a652d7c63545356df118504293dbd65ef">findAffectedValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21fe87bf00db76089c043fed6a23fb76">llvm::findAllocaForValue</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a537993928c8af5b0d064fcd5ce1dec2f">llvm::CodeExtractor::findAllocas</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a174350306649bc16f97803763bcae8f7">llvm::findArrayDimensions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/delinearization-cpp/#a80f3984cb81d6b8e7810c8b313739043">findArrayDimensionsRec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ccb7187d4b25577a595e8bd49d2eb2c">llvm::FindAvailableLoadedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a0dca3347facf58865b34df5e5df676f0">llvm::MustBeExecutedContextExplorer::findBackwardJoinPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constanthoisting-cpp/#a48a060decf79d58559a8e9e28df764f0">findBestInsertionSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/callbrprepare-cpp/#af435a7273ea649fe0602a1580bfabd4b">FindCallBrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/typemetadatautils-cpp/#a64702c7c3e6913b9076666d4e071b35d">findCallsAtConstantOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#ac43142f662a5dd59c09abd92322a9821">findDbgIntrinsics</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#af5c8e1b8ca1f8eb101829d9fe2062c4e">anonymous{InlineCost.cpp}::CallAnalyzer::findDeadBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6880d6c7da94499220b6d7dfcc3c88d4">llvm::findDefsUsedOutsideOfLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/dependencyanalysis-cpp/#aab3179ea6d16c5998772f644a2a205ac">findDependencies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8148654fcf3528ef06d7a0e28b57b952">llvm::findDevirtualizableCallsForTypeCheckedLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af88f364cd09c715e8853a1027c7180ef">llvm::findDevirtualizableCallsForTypeTest</a>, <a href="/web-llvm/docs/api/classes/llvm/dgnode/#a8560da4ee52510bb0b6bec7c71cf2855">llvm::DGNode&lt; DDGNode, DDGEdge &gt;::findEdgesTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktaggingprera-cpp-/aarch64stacktaggingprera/#a7e7be476481e8e24c35c332a9e6e26ad">anonymous{AArch64StackTaggingPreRA.cpp}::AArch64StackTaggingPreRA::findFirstSlotCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a202c5827957336be308d423d78ff7119">findForkedSCEVs</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#ab0cac3cc09d07bc44ffd388ff8be5e49">llvm::MustBeExecutedContextExplorer::findForwardJoinPoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec1d6e397956b9f5fa62416d0beba785">llvm::FindFunctionBackedges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/breakcriticaledges-cpp/#aa8ede4d4de2237a9b4f534d1be96ac75">findIBRPredecessor</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#a4664ad33bbb85ca296ac1a1d74dffc1f">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::findInductions</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64loadstoreoptimizer-cpp-/aarch64loadstoreopt/#a397a7d129e95cde7da2f0f4a33c82fd9">anonymous{AArch64LoadStoreOptimizer.cpp}::AArch64LoadStoreOpt::findMatchingInsn</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/livedebugvariables-cpp/#a8b1a8fc118e74550d4d11d8740ae10eb">findNextInsertLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a7e5a9b5c5f87a0f7d2227881e84be8a2">findNonImmUse</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a45a66620cecb92a4ffdc36042859c575">llvm::RandomIRBuilder::findOrCreateGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#af30ff2458bb283e423c1fc242a468579">findOrCreatePHIBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8688fe7e12511bba710a19b4aaf027a1">llvm::RandomIRBuilder::findOrCreateSource</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a183245826b2f3e16c86e81e567db9b51">llvm::slpvectorizer::BoUpSLP::findPartiallyOrderedLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/splitmodule-cpp/#a972e26a6789667f85f40893033116590">findPartitions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#ac2afc669f548bdba4b0689a6b961bb63">findPotentialBlockers</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a627bfd890830868bb678904545f95d63">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::findPotentialRemovedFreeCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-36e5fa5b110a1852d0627da33930e4d4/#ac031b6154536f289d3c8962a2d9efd48">llvm::SSAUpdaterTraits&lt; LDVSSAUpdater &gt;::FindPredecessorBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a63fa5eea47d71eee71631388500cc8e5">llvm::DWARFDie::findRecursively</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#ad63451798277c4bce34d6446c9cb75ac">findRefEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa2d8fa2ef0e7ead8200cad6bd101af3e">findRematerializableChainToBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagmi/#a6d0a0b4903e8d4d12c98b0f43fe83878">llvm::ScheduleDAGMI::findRootsAndBiasEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a45d0fa60c81eecbff60c1b2bb673e87b">FindSingleUseMultiplyFactors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a0050ea5bb47a2b75ed9e8239bcd469a6">findStoresToUninstrumentedArgAllocas</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aa2dfd6ae7ded046f5e5e03e0f745d5c3">llvm::MachineInstr::findTiedOperandIdx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affd5ebabccc8fdf81ca6d2eeff2e68c1">llvm::findValuesAffectedByCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#abe0dacfb2237ff8fb43d5ad22ac45d5f">anonymous{CoroFrame.cpp}::FrameTypeBuilder::finish</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#a12d9c2c86e33faf07858a46c4bad9544">finishCallSiteParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a2de70543d073c4a85bf44c845b7305e9">llvm::dwarf_linker::parallel::TypeUnit::finishCloningAndEmit</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#a11f3e864193e615bb8e8bda2cca24ff3">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::finishLayout</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a4b45cdd0366bfaa446ebdb3f00d80496">anonymous{X86AsmBackend.cpp}::X86AsmBackend::finishLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/analysis-cpp/#a455039cd6aa5d034220ca078a6b6c30e">firstRealType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#ad57fd622877d2a50e1a312be6b4a409d">fixFunctionTypeIfPtrArgs</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#aac383495fcc8fae9bf826d4d89467928">anonymous{LowerSwitch.cpp}::FixPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a58bbff4d7e32f5dd0824bc62f221d7a6">FixupMMXIntrinsicTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a69211e2fb3d1eed7ee14964bfc04e261">llvm::FlushFPConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#adbe242b084763cfdb35c7850bd4098b5">llvm::BinOpInit::Fold</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9317f2efaf85a4afc7cde58a2c0d734b">llvm::InstCombinerImpl::foldBinopWithPhiOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a866883cec7ed781fcf1e9cda18b24f5b">llvm::InstCombinerImpl::foldCmpLoadFromIndexedGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#aa6ffa2f1b1c1616547b82d41d8cacb6f">llvm::SelectionDAG::FoldConstantArithmetic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#ade8ad153c39e5550054c7873486dd21d">foldConstantsIntoIntrinsics</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aef28063eb280fec69a391dd35c51666e">llvm::InstCombinerImpl::foldFreezeIntoRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48dfb4cc4f8e3891dcba6f01530f6a95">foldICmpOrXorSubChain</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a727184c28151d2b605686087351b8d7b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldInstOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#ae0bcd8452ba359569789760d5dde2434">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvmergebaseoffset-cpp-/riscvmergebaseoffsetopt/#a0d1f06906824f82f42f2c6c1f15ea91a">anonymous{RISCVMergeBaseOffset.cpp}::RISCVMergeBaseOffsetOpt::foldIntoMemoryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchmergebaseoffset-cpp-/loongarchmergebaseoffsetopt/#a5278ce924df77790e6a938f5065ba5a0">anonymous{LoongArchMergeBaseOffset.cpp}::LoongArchMergeBaseOffsetOpt::foldLargeOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4e1612deb487473177dba9b03302386c">foldMemChr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a50164cfe569a57c0fcc574d0d1fc1863">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a84318f31145b081677697de64401238a">llvm::InstCombinerImpl::foldPHIArgZextsIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a4acb22dc4402babad62f8b4815129809">anonymous{AttributorAttributes.cpp}::followUsesInMBEC</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a7dcc7e60c55b76d16688ee3b04f804e4">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::forallInterferingAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a57d5dcc6c4a3f7dff5df68d2f2791bde">llvm::memtag::forAllReachableExits</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/runtimefunctioninfo/#aa3d7bedeec36948ecc6bae39a75c5da9">anonymous{OpenMPOpt.cpp}::OMPInformationCache::RuntimeFunctionInfo::foreachUse</a>, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#a860821de65f9474bc7c8dd1f1bb9c229">llvm::InformationCache::foreachUse</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a830ba09d5969cd66878b05c17fdf66b6">llvm::ScalarEvolution::forgetBlockAndLoopDispositions</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aa6dc58a1259941c7a17142e6103d059e">llvm::ScalarEvolution::forgetLcssaPhiWithNewPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a804545e5b568edec8b970da32cd37359">llvm::ScalarEvolution::forgetValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1f7831449cd72e78894e3dcda705cd8">llvm::formDedicatedExitBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a3a5bc7f961b5c8fd57d40b09ceca0bba">formLCSSAImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ad15d45b871d3111e8da4f9b394d7c83f">forwardStoredOnceStore</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/ehframecfiblockinspector/#ad58e7c9140c2bee787d0e5f8f253af89">llvm::jitlink::EHFrameCFIBlockInspector::FromEdgeScan</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a3681fb2c471c1278bfd939456c752f22">llvm::MCResourceInfo::gatherResourceInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a605515c2c4d676bb83888309fdaf1af0">llvm::AArch64InstrInfo::genAlternativeCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#ade529e02be44b675f43cf39a564c91ca">genAlternativeDpCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#af160026cdf05f7d7c962d4d490d19add">generateAssignInstrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2d2d83de91f5be342b9beeb36a6e8c2">llvm::generateCoopMatrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a293fb71d9772916004e2e65674d0bed0">GenerateFixedLengthSVETBL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/loongarchmatint/#a1e8bf674882ab22f3fa510916fab18fe">llvm::LoongArchMatInt::generateInstSeq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscvmatint/#a829402a713d109eae3d7945c88f33255">llvm::RISCVMatInt::generateMCInstSeq</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vectorcombine-cpp/#aaba8002e40481888d8e4933ce4487081">generateNewInstTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a7ea4fb4d6b0198f2b6eac325a8d93031">generateReproducer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a07cdd12114b2452d5dc26ab23460bb60">GenerateTBL</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ae86be98f39008a27ba987e282fc8dc2c">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::genericValueTraversal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#af64fc386f3fc81f753830641399254b9">genFNegatedMAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ad7dacfdd99d94fce20ccc2450bf5eb76">genFusedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a731ca5cdf4cb5c12baa91590b3923d51">genIndexedMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a6893512d8a2c2aaf9d6758440d1bc583">genMaddR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a875d4d0bf620bc2515b57e5554a510fb">genNeg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp/#a49570d8463bc060cddd7b65335685002">genShuffleBland</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#a488ce2dad0d4f44659a655e17e0ae184">genShXAddAddShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a012040151268735433380829e4ef0dcd">genSubAdd2SubSub</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a4ac0d01bf5ca24e679de53067c8f6a44">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ad544515efb693b15ac9855c6be03189b">llvm::AttributeList::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantarray/#a65cdb8a376b0aa1971e7e25a558435f8">llvm::sandboxir::ConstantArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantstruct/#a00fe72b32bd949660ddf5975a54231ac">llvm::sandboxir::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo/#a373eb03c4fdd576998906436ebe07001">llvm::LegalizerInfo::getAction</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/replaceablemetadataimpl/#a97f281369b9902c19df7f1f55975065d">llvm::ReplaceableMetadataImpl::getAllArgListUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/replaceablemetadataimpl/#a479e8881bd4b3d464b3e75c4305c44e6">llvm::ReplaceableMetadataImpl::getAllDbgVariableRecordUsers</a>, <a href="/web-llvm/docs/api/structs/anonymous-coroframe-cpp-/framedatainfo/#ae62c7a803203f703a46e17ee5b06ae9c">anonymous{CoroFrame.cpp}::FrameDataInfo::getAllDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/recordkeeper/#a42410e0ce2a641ccb68ba031c667f2ad">llvm::RecordKeeper::getAllDerivedDefinitions</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvsupport-cpp/#a23439311200e3762a6d40848ee6b4728">getAllLexicalIndexes</a>, <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a035358d364bc06dccb54d1cc8c8cd3ce">llvm::SIMachineFunctionInfo::getAllScratchSGPRCopyDstRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a78171da3a30a449d469ccebbff57760e">getAppleRuntimeUnrollPreferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#a1922f0fa6389aaa7596f303e96bd8507">getArgTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a1ffc644bb4865116b0a2f4db014e9bed">llvm::RISCVTTIImpl::getArithmeticReductionCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/linker/irmover-cpp/#ab000b7cbc5e3698d63e257e7e9db5c64">getArrayElements</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/resourcebindinginfo/#a49b774bba229107958382054969b49bc">llvm::dxil::ResourceBindingInfo::getAsMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a957f22748fdfd31dfbe31f71feb5329b">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::getAssumedSimplifiedValues</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#ae92d755a80dec605503e2ba653765360">llvm::Attributor::getAssumedSimplifiedValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/safepointirverifier-cpp/#aa831f0a1520a405a32196cb32ec24084">getBaseType</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#a54182dd4333475d439513da05d634aad">llvm::IRSimilarity::IRSimilarityCandidate::getBasicBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#ae646f74a0d49287f89602e08c3bd8a6c">llvm::HexagonInstrInfo::getBranchingInstrs</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#a401e244b78386047c64edc64f80ba9c0">llvm::AbstractCallSite::getCallbackUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuglobaliseldivergencelowering-cpp-/divergenceloweringhelper/#ae8882b2a7fc8ce50e0ae8a34ffd802c1">anonymous{AMDGPUGlobalISelDivergenceLowering.cpp}::DivergenceLoweringHelper::getCandidatesForLowering</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#ae033ec699e4956dff9206a339674990f">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::getCandidatesForLowering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78051fbc656d31554c97e4746e09a03e">llvm::getCapabilitiesEnabledByExtension</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#a1890db236ee0485fd31d3d99d6ad09b5">getCastsForInductionPHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a9205d579e79767f52c5af57c94d2be74">llvm::omp::getCompoundConstruct</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5fda84b4862d7e084fa4fa2cede8e37f">llvm::SelectionDAG::getConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1abbecb57e09bf906ab1503722015802">getConstantVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abee99e97f96cb26e6b8208e4d6c98fec">getConstantVector</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-utils-cpp-/#a3fb5a21e3d12a4f09da156333cdef568">anonymous{Utils.cpp}::getConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/anonymous-constraintelimination-cpp-/constraintinfo/#a085e72b5a3ed050deb15aa57090c54ba">anonymous{ConstraintElimination.cpp}::ConstraintInfo::getConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/intervaltree/#af47ed4deea972261fe9561c075b8244c">llvm::IntervalTree&lt; LVAddress, LVScope * &gt;::getContaining</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a258e3d0e92c1a4d851ef21a368ceb977">llvm::TargetRegisterInfo::getCoveringSubRegIndexes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a59b9890650c2857c6688596e74fefef1">getDataDeps</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a7bd3c333fa06c8fae17d52a78db3fde2">llvm::GlobalVariable::getDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#aff31f82e78047b9ec0867b80a925d6df">getDebugLocValue</a>, <a href="/web-llvm/docs/api/classes/llvm/dependencegraphinfo/#ac23db8e595427ec7b328492aa7d5749c">llvm::DependenceGraphInfo&lt; NodeType &gt;::getDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a406e4a6b7277aab7efd423ae30a9fb12">llvm::DominatorTreeBase&lt; BlockT, false &gt;::getDescendants</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitdylib/#a814ccfa400b06db7a01885ddcc21196a">llvm::orc::JITDylib::getDFSLinkOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#ae8f7b3435e5d6a7132e2e0aba6b347e7">llvm::Record::getDirectSuperClasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/hexagonmcinstrinfo/#a12bbe632ac24b40e52a6f3dcdef003d5">llvm::HexagonMCInstrInfo::getDuplexPossibilties</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazycallgraph-cpp/#ad7483d245bba8b6658b4dbd429f14313">getEdgeKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afa141935f9c9a1ad9c785d7b6200b119">llvm::getEHScopeMembership</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#af91c6a7b6d4486c1fb8fc021b55d240d">GetEHSpillList</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a84ea0567e15790f68c421dada011ec5f">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/uniquifierdensemapinfo/#a896950a0629ca3b63bbb06660a1e4ad0">anonymous{LoopStrengthReduce.cpp}::UniquifierDenseMapInfo::getEmptyKey</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af46fd5126112a587bb12f09b1c0e385b">llvm::ConstantExpr::getExactLogBase2</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1d9238c61483c12dce660bae4c8cc2d2">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycle/#a408a62c86ed1c263bb09c6d2b7ec09d2">llvm::GenericCycle&lt; ContextT &gt;::getExitingBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a46880fab7a9d5bd439725f2acc59b80d">llvm::LoopBase&lt; BlockT, LoopT &gt;::getExitingBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#a2afc539a04a12d833eecbf55239b77cd">llvm::RegionBase&lt; Tr &gt;::getExitingBlocks</a>, <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/remarkgenerator/#a53d241b242a10e4f387b39e4497054db">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::RemarkGenerator::getExpressionLeaves</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#ad87fbe0fdf89f2880c4b1b40d1115ada">llvm::cl::generic_parser_base::getExtraOptionNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/riscv/#a1db36bbf675fb1aea08484ef62220faf">llvm::RISCV::getFeaturesForCPU</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a9a64d327c5a0be28d5936e30ff02709a">llvm::X86::getFeaturesForCPU</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a1f24abade2ffdb0e55559d552552692c">getFMAPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a0df98b068b652d32c3529381db723b9c">llvm::PPCInstrInfo::getFMAPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a56884e76d8fbf3b9f59ed904d50ba245">getFMULPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a337903856769965870a905f37f63790d">getFNEGPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#aed6416f30361f53101db3f22c2743dbb">getFPFusedMultiplyPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp/#a490cd638a7de440f2f3f6b2a26b4fa0b">getFPSequenceIfElementsMatch</a>, <a href="/web-llvm/docs/api/structs/llvm/x86addressmode/#a593e839307453b63de7b7021e8cc059a">llvm::X86AddressMode::getFullAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a3e40bda8245f90bbe4a72d083b4d8431">llvm::TargetLoweringObjectFileXCOFF::getFunctionEntryPointSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#ac2f8a243eec640b2ebf8e022d57c9411">getFunctionPointerElemType</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6414ec52d659d2e3fcc5dc03510c228a">GetFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ac10dff634cacc4be44046af5ee45f92a">getGEPCosts</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a36523fbc60bf720df4d9f20cfae7bb7f">llvm::DataLayout::getGEPIndicesForOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0e431b29d5cd842ab00f85ec2cdab8b2">getGEPSmallConstantIntOffsetV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a40c78203dbde06b90a40aaa7b3bc6db6">getGFNICtrlMask</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledagsdnodes/#a8cbdb500ba4abd11fd23de4e7a020a2d">llvm::ScheduleDAGSDNodes::getGraphNodeLabel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a1c7b2c4c8824cfb8d35c97f6923c3fe2">getGVNForPHINode</a>, <a href="/web-llvm/docs/api/structs/llvm/machineinstrexpressiontrait/#a3344d356ddabbe21340a4b078300a789">llvm::MachineInstrExpressionTrait::getHashValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8287f8eaeb936bb75dc1bb6ef39fbdd1">llvm::getIndexExpressionsFromGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#a4e71b917adbe7f6e468ec799e77a5fc6">llvm::CallBrInst::getIndirectDests</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a86af5dc1ea8da3e443ba72fcf0f9caf5">llvm::DWARFUnit::getInlinedChainForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a0a4eb676d872db65ea116ed4e983c61b">llvm::LoopBase&lt; BlockT, LoopT &gt;::getInnerLoopsInPreorder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoniseldagtodaghvx-cpp/#a72abb9be89c086c312ae6dc20b96d09c">getInputSegmentList</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#a3f4bf9736903f31820c978bdb1b6810f">llvm::AArch64RegisterBankInfo::getInstrAlternativeMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#ab65adad01ce4004d6fe95c5b740190ab">llvm::AMDGPURegisterBankInfo::getInstrAlternativeMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerbankinfo/#a513e6961f1f77e1fb018daaad0b43157">llvm::X86RegisterBankInfo::getInstrAlternativeMappings</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9ad9f326100ec08e3cde9f430fcb36f1">llvm::RegisterBankInfo::getInstrPossibleMappings</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a264036c4b5fffd4ce40a5414d587d26b">llvm::Intrinsic::getIntrinsicInfoTableEntries</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp/#a80cfcb0bb45d63395feca9afbd3cde5b">getIntSequenceIfElementsMatch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/omp/#a433702fa6f12e3710e21ed0fde2a69b0">llvm::omp::getLeafOrCompositeConstructs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#ae94b800d0b8c1e3423be89c87d447c9c">llvm::WebAssembly::getLibcallSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbcontext/#a1e1f42a6cf8b7f42ef17dbafe0720787">llvm::pdb::PDBContext::getLineInfoForAddressRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollandjam-cpp/#a6cdd2c0576ecaa0a145b8e6e4bc62f6f">getLoadsAndStores</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol/#a3341436fba7ac595892f46c5538fd9e7">llvm::logicalview::LVSymbol::getLocations</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvsymbol/#a3dc712ca9ee1d625cd861bfa57f79a15">llvm::logicalview::LVSymbol::getLocations</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a1230fd674d2609b96527fe65eaf40b1b">llvm::LoopBase&lt; BasicBlock, Loop &gt;::getLoopLatch</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a542a6493b191eb84b5457d35ecd685c5">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopLatches</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a2b5ed0cf8ca9b437a418c50c5ec79a38">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopsInPreorder</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a450c14cda08c142b7777d753ca363cc7">llvm::LoopBase&lt; BlockT, LoopT &gt;::getLoopsInPreorder</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#a485097c9e18d87d37388dc46cecd1dc3">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopsInReverseSiblingPreorder</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a861381cad67866e249c6330631ac0742">llvm::TargetInstrInfo::getMachineCombinerPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a0efa4ac98b741f2ab0520ab1d2f8a115">llvm::X86InstrInfo::getMachineCombinerPatterns</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a054d573171c2fcf38b33a60e412dba7b">getMaddPatterns</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#aad5def33faf75944be159808071d9698">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getMatrix</a>, <a href="/web-llvm/docs/api/classes/llvm/mmrametadata/#a740cc66df7ae1a9b71a8082e2a3e4a9c">llvm::MMRAMetadata::getMD</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#a59f76c736c482a9d03fbb0f5c42b3992">llvm::ProfileSummary::getMD</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a0bdf48ae61b21c555d4c0f6a66df5b2a">getMemcpyLoadsAndStores</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ac976273389caab4360013b109184e0bb">llvm::GCNTTIImpl::getMemcpyLoopResidualLoweringType</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a7ee986b3ced1ba5562ed34c5e633bed2">llvm::TargetTransformInfoImplBase::getMemcpyLoopResidualLoweringType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a623eef1675bd2f33cfacc50b2fec0c71">getMemmoveLoadsAndStores</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a512855a97cf9032c007ca232000a81ba">llvm::AArch64InstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagoninstrinfo/#a515e8a223dcc58a4e478f70ec88d9520">llvm::HexagonInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ad7b408f8f589425b7ba7eb3e3be6e818">llvm::LanaiInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8d30b811118077ff2c35bb08613af26f">llvm::PPCInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#aa04c64c287d0b42c8a1714011a943e3d">llvm::RISCVInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a0c826f5192676a1dfa8468a38b9ce1c3">llvm::SIInstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a4870646ffc5b5a7d4425edd55d6f93de">llvm::X86InstrInfo::getMemOperandsWithOffsetWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a6c8d73add4e552328f931ce1681c494f">llvm::AArch64TTIImpl::getMemoryOpCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondag-cpp/#a167cbac9e2a923fd2d8ecd9661199e3d">getMemsetStores</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a193d4ea30b27a0c86550ae249eefaeaa">llvm::SelectionDAG::getMergeValues</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acdf08ebc749ce91001ea768a16da0605">llvm::SourceMgr::GetMessage</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#a56378412b516c96bbab7cd31b530e0ff">getMinAnalyzeableBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#ab6a37e8549580d302c7c98852a4ddc11">getMiscPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/basicaaresult/#accb256ada9f5d92e5a776e459618cd1d">llvm::BasicAAResult::getModRefInfoMask</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a45a64ff2883d51edeb926ee63a4f64ac">llvm::MDNode::getMostGenericNoaliasAddrspace</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aac6e3a0dec40a6721857cbbd4330039f">llvm::MDNode::getMostGenericRange</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a3192a19c26a2a5fab9a15e9837b0e873">getNegatibleInsts</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/peepholeoptimizer-cpp/#af58cbab9cb762f2d2a4baae6177e30e4">getNewSource</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7d8410ca3fc6fb227416067d3c2535d2">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNonAliasingPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#afd1e9e3a6538d09c27c2984bb63097f9">llvm::DataLayout::getNonIntegralAddressSpaces</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa7240503037f0c0499222a41a5f22d06">llvm::MemoryDependenceResults::getNonLocalCallDependency</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dwarfemitter-cpp-/#ab2dce2d77f65b46dcc8187d9eb10a8bf">anonymous{DWARFEmitter.cpp}::getNonZeroDataSizesFor</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a7391ca35e3a370a408a9b1967b6a9832">llvm::ScalarEvolution::getNotSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#a84ca5b0d9c7fce1c2cfcc14ee488713a">getOffsetFromIndices</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a061144e3e490f8917de9c53163ef8c01">llvm::OpenMPIRBuilder::getOrCreateSrcLocStr</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#abf27ce323516bd289ce53d2e241581fc">llvm::DIBuilder::getOrCreateTypeArray</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a4d95a71faaca9c18ee44f1942b77c716">llvm::WebAssemblyAsmPrinter::getOrCreateWasmSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#a3d3f9a7f2fef13c8261fa2d3175a4cca">getOriginalFunctionType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4d4c97240f140a6a8c3003d0e19798be">getPack</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype/#aab5db3c6664f781ddbc31756ef483cdd">llvm::logicalview::LVType::getParameters</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#a57dd4a8d48a825207a80611dfef6d45e">llvm::LoopNest::getPerfectLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a165430a83d0399a48d8983764c9e60b3">getPHIDeps</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#aa8632acd057dcbe9f0d3e2de9d2f9247">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getPoisonedShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a9d391021d805c83de0c322c3cb0fb355">getPostIndexedLoadStoreOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a605fed3c698bbafcf2d81aa2a1b191af">getPotentialCopiesOfMemoryValue</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a35163c6aad1d90ad97e4534933ea6acb">llvm::logicalview::LVScope::getRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a6415fb68bc55f3a316aa414a5c2c0ab2">llvm::RecurrenceDescriptor::getReductionOpChain</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a69a2253decaa6ee31ae96ec6e0b3de13">llvm::AArch64RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a77b81cc14aafd09d0e380b123cd06d51">llvm::ARMBaseRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a09a1c19b999c807cb52c21541a2c7de4">llvm::PPCRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#ad490ad7663a07141538a6f4049299550">llvm::RISCVRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#afc99d2835eb4b8cde9e81db9abca597c">llvm::TargetRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#aa2b5a0a0f6bf1b5480337a01257df8b6">getRegistersForValue</a>, <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#a03813938f6c7ea6b7e94965a27491ddc">llvm::RegsForValue::getRegsAndSizes</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae26cac7943070f09b4d7fa667d1adf95">llvm::TargetInstrInfo::getRegSequenceInputs</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#aba7f60edec8e7b982c598aa278f9420c">llvm::ARMBaseInstrInfo::getRegSequenceLikeInputs</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph/#a7010e9f697823cc5a40876345bab137e">llvm::rdf::DataFlowGraph::getRelatedRefs</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a90f9184fae65f2af54f3ddc7b02ee0a2">llvm::CCState::getRemainingRegParmsForType</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackerfunction/#abc9a654b8a69fecf6acc17555b12b8b2">anonymous{OpenMPOpt.cpp}::AAICVTrackerFunction::getReplacementValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a175f10e8ec1c2ec4fa24431ac5429a36">llvm::GetReturnInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#a857ca8ebd4e64059aa8774f14445e414">getRVVCalleeSavedInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a55a8ce252bfbfa1af642af05f2c31e10">getSalvageOpsForBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7144f12bd93229efcf87a052ab80d5e6">getSalvageOpsForGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a7b323f2153ac64cdbab7e81c15575c0d">getSalvageOpsForIcmpOp</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/sccinfo/#aa45126829059172e7a55b24547167673">llvm::BranchProbabilityInfo::SccInfo::getSccEnterBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/sccinfo/#adf3e2e7e5049244c18140cf77a7baf2c">llvm::BranchProbabilityInfo::SccInfo::getSccExitBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinescheduler-cpp/#ae1be3a2fc5dfa3281d32b6fb4e4ea6dd">getSchedRegions</a>, <a href="/web-llvm/docs/api/classes/llvm/sddbgvalue/#aaff1dd6fbb54c4d291b0f77343d60a92">llvm::SDDbgValue::getSDNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/windowscheduler/#af78f1d6e142343589981887d2a200d84">llvm::WindowScheduler::getSearchIndexes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a575e3a33ce947932f93b30172ca12f05">llvm::GetShadowBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ac16a7b224b20beeecf5f1665b4bcc65f">llvm::AArch64TTIImpl::getShuffleCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvinstrinfo-cpp/#ae7cbe832617857afaa39866967339d87">getSHXADDPatterns</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/collectdescr/#a4a8f2866e347ea2cf06dd2ba3bb0274a">llvm::sandboxir::CollectDescr::getSingleInput</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aee3b49d7f15550d64c7db0e29a124c6d">llvm::slpvectorizer::BoUpSLP::getSpillCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreframelowering-cpp/#a474e976fb6ef9964e16389ba57edde96">GetSpillList</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a1487d4dfd14eebe24447f52b04bb8f6f">llvm::SelectionDAG::getStackArgumentTokenFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a444be9352256919a844309a35dffa0f8">llvm::SelectionDAG::getStepVector</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a3edef3fa47c611d3d10606591213e57b">llvm::ConstantDataArray::getString</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvisellowering-cpp-/nodeextensionhelper/#a776c5a5c2c4c9c913f9b44e5b0437f69">anonymous{RISCVISelLowering.cpp}::NodeExtensionHelper::getSupportedFoldings</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1dbcb8c600974cd18c1d92bb35364590">llvm::getSymbolicOperandCapabilities</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#ae32520c146488ec59560dd75567ba9b0">anonymous{TextStubV5.cpp}::StubParser::getTargets</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab05ad372d1e6700f8125ad1fee07271b">getTargetShuffleMaskIndices</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-textstubv5-cpp-/stubparser/#a841ed7fbb14a5ba056989d1e19eef248">anonymous{TextStubV5.cpp}::StubParser::getTargetsSection</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#aa1696dc4b990f6a31d2c68455efe907a">llvm::logicalview::LVScope::getTemplateParameterTypes</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/uniquifierdensemapinfo/#ab342fc50b3fc95a5028ba25d3646b3f0">anonymous{LoopStrengthReduce.cpp}::UniquifierDenseMapInfo::getTombstoneKey</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8c1ff7e5e775cdba70261e34245db9e5">llvm::AMDGPU::getTransitiveUsesOfLDS</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a7800714c330f8f3952e8058b090e001b">llvm::slpvectorizer::BoUpSLP::getTreeCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aca1828635e30f34e4958afeb5541766e">llvm::Intrinsic::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constantstruct/#ad3de023aeaed4f2c7173566c0031997a">llvm::sandboxir::ConstantStruct::getTypeForElements</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef86e2e34d31e4595f5a442fe55ecbe9">llvm::ScalarEvolution::getUMinFromMismatchedTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f25f617547597b1772677eaf0e7a8b6">llvm::getUnderlyingObjectAggressive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc66c148bcd950ffcc3ab83989eb70bd">llvm::getUnderlyingObjects</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a317172388c9d0d3c601070d588a104d2">llvm::getUnderlyingObjectsForCodeGen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe4d96949c2b4fda155b9e1914518e3a">llvm::getUniqueExitBlocksHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvframelowering-cpp/#ae435b1b5b5ed85a029acf53fe157d437">getUnmanagedCSI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a944828d894ed9e13fbdfac2652d88745">getUnmergePieces</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a3cc72cfbc837c8e89491b6357c358778">getUnwindDestToken</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a4e19285f051b80099ed8b36c5c94eaf2">getUnwindDestTokenHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/machinessaupdater/#a670da7741129c7d591dc19951ecce6c3">llvm::MachineSSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f6ad5c1831928ee2c6c5058d9580edf">llvm::getValueProfDataFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#a1bf96ea28c04f3533cf028a1d471eae4">getVectorInterleaveFactor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a8adf44ad04562ff150b0e8e352a38d46">llvm::VFABI::getVectorVariantNames</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/virtualfilesystem-cpp/#a5193c36762bd45216d0e979c04df5d49">getVFSEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a9be1c0f1057f7c2a457719a6581ce49b">llvm::SIRegisterInfo::getVRegFlagsOfReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp/#ab6c5507fc91d0ca19adbac9927262086">group2Shuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#a906c320a7c0ac63b48da21eb00618145">llvm::SmallVectorTemplateBase&lt; T, true &gt;::growAndEmplaceBack</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#aaff349708bd2e38bf04c7995bc40db8c">handleBaseClass</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a3dcd2bcf223daced673ed18e4ad47efa">llvm::AMDGPULegalizerInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a5f5e4d60d30f6101d9aedbc3e0e13bc0">llvm::AMDGPURegisterBankInfo::handleD16VData</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a4e84a47e3ca9c1684a752533e2881cd7">handleDanglingVariadicDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a11cc5001079df0a0c9f4e0f16fb2e4a5">handleDataMember</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae9748fb2e4d41aaa8ac80d00b2becc52">llvm::SelectionDAGBuilder::handleDebugValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a3de59e829dffdff466e6c22944ac47a8">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleGenericInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aac69c9cf4e552a52d5065e94dc023f82">HandleInlinedEHPad</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a94631928dd87cd8134a31c5fb3168c70">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleIntrinsicByApplyingToShadow</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a1ab055a13a095bb1fa676e2df11b9024">handleListContinuation</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a4366c809736e919b276b5cda925d17ac">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleLoadInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#aeb0bc3fb3008d1f61c5a1adb0b901c82">HandleMergeInputChains</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#abbb20c80e0c1ab59446de978f898fc1e">handleMethodOverloadList</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aa1a6fbdf0a3311c7b9602dd67e46fef9">llvm::LiveIntervals::handleMoveIntoNewBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/gisel/aarch64calllowering-cpp/#a133ddcbd001fd6de4f055542a6a95595">handleMustTailForwardedRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a57e9d47198c1315b209ae12d935a60d9">handleNestedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dbgentityhistorycalculator-cpp/#a9ee24d91499bcb94c513e7db61664312">handleNewDebugValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a96ae8a0897a355d1c0a04a7eae3f2466">handleOneMethod</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#ae10e279e0a75605e7429e6e3176a7ca2">handleOverloadedMethod</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#aea5dd05a61257355d99f96d8d6dc9f94">handlePhiDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ad0fe28a9dccc66e85a05b9447f4141ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handlePHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#ab36e33dbf8516f7892bd335ff40545e9">handlePointer</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a49114a789143912efbf912250aea8397">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleSelectInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a4826d44e6c44f689b31757f02ad3b76f">handleSSAValueOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#afa937cb598845b69e37a81f67ffd4c7b">handleStaticDataMember</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5698394aeae942bfac76f1f7ac4d31a7">llvm::handleUnreachableTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#a93e8eec2fad7a5df11a2d003d095a6df">handleVFPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typeindexdiscovery-cpp/#ad79c1724545f758ab3046506669b993d">handleVirtualBaseClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#acc4b9161e5bdda1e0f5482ad8b9a64ba">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#aaa5ecbb121a4af66e98e1ddbff7b925d">hasAllNBitUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a44c557dcf96034410cdb25dd01c12dde">hasCallsInBlocksBetween</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#ac3fdb189d1625b937b2aedcf1de64f09">llvm::IRSimilarity::IRInstructionData::hash_value</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a0f31e8ea7a0fea18c2df924e7d6e8de8">hasHardUserWithinLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/registerbankinfo-cpp/#a2e84df1cbf9375ee66f23c5ca414c638">hashValueMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae3c237cad94f54f0d82a18a131709d41">llvm::TargetInstrInfo::hasLoadFromStackSlot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae78f734e49b5ad94836bf32dda101ec6">llvm::hasPartialIVCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#ab250276b651715d29b3ed20467d5f0a0">llvm::SDNode::hasPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6beebf86835d6582b0550cd7731ee9">llvm::SDNode::hasPredecessorHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a5523ffd2d5ced60566f3493c2b48e0e3">hasRegisterDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#a5df2834716ee814af9f2555897ecb932">llvm::TargetInstrInfo::hasStoreToStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a4e0750d12818ab0f8a301e4be935ea72">hoistAndMergeSGPRInits</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#aa3255071e8195c43058f7e265c54677f">llvm::SCEVExpander::hoistIVInc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedc31552ebf0ce116c665da44b4a97a5">hoistLockstepIdenticalDbgVariableRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a697cde840957bbc0b2848a593c3e0d5a">hoistMulAddAssociation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a9396319801f74828cfbd94177f38eabc">hoistPreviousBeforeFORUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a3aaf79ae3bce520f7cb4d573292922e9">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a0cb597b1f0cffe907fa834e9a95fe719">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a753ca373c3a99cb66666a497408ed72f">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a3b776824b1ee93e75dcf982fec706900">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ade9551bcb1121539a279452fec71f9eb">llvm::identifyNoAliasScopesToClone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52e7d51fde3551b3e9cd44aa2e8d8e34">llvm::identifyNoAliasScopesToClone</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/#a7cc7cd380b6ceacc35ef685d5b047d80">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::identifyReductionNodes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a0283d438765cf962a4587624959ebc6b">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::identifyReplacementTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/debughandlerbase/#a457f3c8acd738586fab8d9ac08f44013">llvm::DebugHandlerBase::identifyScopeMarkers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a10bc55b7d7f53073cf539ae7a34a74ef">incDecVectorConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a2f647a3f5093cbe2bc5ff3e9e295289d">llvm::logicalview::LVBinaryReader::includeInlineeLines</a>, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#a65f17f248759abd6b10991fba10a0a59">llvm::ValueEnumerator::incorporateFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#acd8a7753c2685a14185133433c0bbf26">initBranchWeights</a>, <a href="/web-llvm/docs/api/structs/llvm/dxil/moduleshaderflags/#aa992db5c16c5e03bacbeefcae61b8bda">llvm::dxil::ModuleShaderFlags::initialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxproxyregerasure-cpp/#a9d0f767158270855806d4e9899311db5">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a0574a5dd4c78099285b317d60d28a966">anonymous{ExpandVariadics.cpp}::ExpandVariadics::inlinableVariadicFunctionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa730b58924baf8f35394c2e5a0bb3714">anonymous{SampleProfile.cpp}::SampleProfileLoader::inlineHotFunctions</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-5afad16d6df5c47889a55ee752aaf37b/#a9b351a24adf0087ae1f9d5590d0f4e41">llvm::yaml::CustomMappingTraits&lt; GlobalValueSummaryMapTy &gt;::inputOne</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a5457cbda7e9b1866c1c16af5ac330273">insertBitcasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a9ba70601e2398b462375dd8f3e9bc1b2">insertCandidatesWithPendingInjections</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#ad7c5a4356eb729fe374f917da7435a12">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a21fc5eae685ef3e2dce4403a75d5ff2f">llvm::MemorySSAUpdater::insertDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3041264cb7bbcc2793ec52c9829b892a">llvm::insertIfNotContained</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a01b1581633bb40f86d6dc62a1c1a7f72">llvm::LazyCallGraph::RefSCC::insertIncomingRefEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a1e16838ab40f751bc24dfa455620ed06">insertInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a307848f42e24813c2b6a55b8d8959fa4">insertInlineAsmProcess</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a864a2ad11bbf83cf2b910e43d461cd02">insertParsePoints</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0ced274818512cfd52e26d828ec1fcf2">llvm::InsertPreheaderForLoop</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aa1f63192a86614e73a03f83e46813bb8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::InsertReachable</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a953f3ddec823a0c7db75e73dbf550632">llvm::SIInstrInfo::insertSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#ae10045fb6d9eaa95d29bee13a3abfb39">insertSpirvDecorations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a6b7912ea5edc4563fe03afc57fa9b0c6">insertUseHolderAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a75cf62ffe10261611bab4d74598ab0e4">insertVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a73170211689546daae2d8b0676c6d676">instCombineSVENoActiveZero</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a489ae04c136c4b088d849d7d6dc20965">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofiler-cpp-/memprofiler/#aa38dcf9a1b93414e7bd1b956a1d04895">anonymous{MemProfiler.cpp}::MemProfiler::instrumentFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/interleavedaccesspass-cpp/#aba37dfbf85878dd8f544c9bcca63bc48">interleaveLeafValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51d22a1ed809d7cb1c1eb46c820c8226">llvm::intersectAccessGroups</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ad67533111413cc397100c48c82291ec7">llvm::AttributeList::intersectWith</a>, <a href="/web-llvm/docs/api/classes/llvm/machinetracemetrics/ensemble/#a063217bcbb8b81adfdc88feb1a52ddcb">llvm::MachineTraceMetrics::Ensemble::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/outeranalysismanagerproxy/result/#a139e8b7a2de6d6c79a532567dfd2f9ed">llvm::OuterAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs &gt;::Result::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/phivalues/#a1f338cd311db969863e0560bed619bf5">llvm::PhiValues::invalidateValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a5d94ee8aaee00c42c11954aaa6022894">isAllocSiteRemovable</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a35a8d25c6df3f1d3bc5faba32de1dd55">llvm::LazyCallGraph::RefSCC::isAncestorOf</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc/#a024bad6935b15f7080b08b5dfec4eade">llvm::LazyCallGraph::SCC::isAncestorOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a5a7fe53bda3cbce584280a177a18d5ab">isBlockValidForExtraction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af55cf9792d5f9186df02c58b337a1511">llvm::AMDGPU::isClobberedInFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#a203487323e0aa341b6c24f9ef20b5909">llvm::RecurrenceDescriptor::isFixedOrderRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemziseldagtodag-cpp/#a50de01231a46d2b82c41aebd0c413690">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a1c9b0061be648da87d7a9102c0179018">isFusableLoadOpStorePattern</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab0469afc3caef8616d4b1c7501cba1b8">isHorizontalBinOp</a>, <a href="/web-llvm/docs/api/structs/llvm/aanonnull/#ad13f5148dfe5bbfa20ec5cdabfcb8547">llvm::AANonNull::isImpliedByIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a08c9c2fedd8f175884c88275c7987e03">isKnownNonNullFromDominatingCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ace2885fc42e68606f270bfd3180d5f26">isLeakCheckerRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a7a61cf78eb38e383357df8c175aebc3b">isLoadOrMultipleLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#aef5a823f024815a31e9be15d48d037dc">isLoopDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/globalsmodref-cpp/#a1c1b80628be0f97adf568cccacc8e8e3">isNonEscapingGlobalNoAliasWithLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#af278f33f3e54a61566b7fdff3835e980">isObjectSizeLessThanOrEq</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#ae1c9444bcb6b157e8f8c4ec8bf265010">isOnlyCopiedFromConstantMemory</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5804b68ebc77c8751a9cb4e066735450">llvm::isOverflowIntrinsicNoWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ade4086b409f00a755cfc6c0b03f67413">isPointerValueDeadOnEntryToFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a365173e63bd73b3ee58033678429636e">isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a634fa78fa798ed1e2910ecb71b0718c7">llvm::isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/sveintrinsicopts-cpp/#ab3363381f198b25f4ce23364c08ea1f0">isPTruePromoted</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyexceptioninfo-cpp/#a98b83595b3773bb85e07a74292309c7c">isReachableAmongDominated</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaintrafnreachabilityfunction/#aa6f399598404d630b1091693ed0a6f88">anonymous{AttributorAttributes.cpp}::AAIntraFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b369f94d5ebc6e107a988f17b42b3eb">llvm::isSafeToDestroyConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvectorpeephole-cpp/#ad1ace11555e6a74661cd750915d2c2f4">isSafeToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyregstackify-cpp/#a915d3a27fc972595a451b8f2b092bec9">isSafeToMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchoptwinstrs-cpp/#a7b61861295f70647f6dd85931782b93d">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvoptwinstrs-cpp/#a333d3161d9b4420d11b777bd154148bf">isSignExtendedW</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-cpp/#ab27518c8dcc76b28d6bcdd2cb40648fb">IsStoredObjCPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#aa1bdad6ac04deb5b4e5990a020b616c7">isSuccOrder</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/resourcemanager/#a94ebe004dfbba2e68530d0125ed16293">llvm::mca::ResourceManager::issueInstructionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#abeb31ccfc9e083463bbeee472a765160">isValidBaseUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/object/wasmsectionorderchecker/#a0b575c4fbaec067108afa87be8ca0ade">llvm::object::WasmSectionOrderChecker::isValidSectionOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompcontext-cpp/#ad468a923807a048c8f7379f087507651">isVariantApplicableInContextHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#af6735614e085435a0f3bb90aab527213">isVectorPromotionViable</a>, <a href="/web-llvm/docs/api/classes/llvm/smschedule/#ae7d28b348c77e17419b65d3f3d7d55a4">llvm::SMSchedule::latestCycleInChain</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a58d534b072f7d0fa5f54ff569bb745ec">llvm::LazyCallGraph::LazyCallGraph</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a89e5277b1b90b54ea21a51120f9a4206">llvm::AMDGPULegalizerInfo::legalizeBufferLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#ad0be6e871a184d6f7b814515324eee1b">llvm::AMDGPULegalizerInfo::legalizeImageIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a762e3485a3d139ec7ed9d30a7f38f74d">llvm::AMDGPULegalizerInfo::legalizeInsertVectorElt</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#af4667ecbc4447b41863430fb572d8f82">llvm::AMDGPULegalizerInfo::legalizeLaneOp</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a80314c2b261b78cb7335a265f43ba1b5">llvm::Legalizer::legalizeMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulegalizerinfo/#a2645b2c5fc9b404821322ad403c87810">llvm::AMDGPULegalizerInfo::legalizeMul</a>, <a href="/web-llvm/docs/api/classes/anonymous-legalizedag-cpp-/selectiondaglegalize/#a9440e31a32ea6624c0b77e7e45223be9">anonymous{LegalizeDAG.cpp}::SelectionDAGLegalize::LegalizeOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a51e42fbc8748c4097b19ad130cb61959">LinearizeExprTree</a>, <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#ga885e779450ebf60c2aff19031ac6d19a">LLVMBuildCallBr</a>, <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#ga512abf3400ec70c7ee23f71ffe31aa01">LLVMBuildCallWithOperandBundles</a>, <a href="/web-llvm/docs/api/groups/llvmccoreinstructionbuilder/#ga06f14b44cf7e8a098dae6983c5047dbc">LLVMBuildInvokeWithOperandBundles</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluemetadata/#gab79cef5ec6dd638a424edf41f6caaed8">LLVMMDNodeInContext</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga4af207d5a28d38c765a7f33d658df2a5">LLVMOrcExecutionSessionLookup</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-trace-cpp-/#a6b4f89ac434c992939934e78f19cd33e">anonymous{Trace.cpp}::loadFDRLog</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#a304b877a673788ae4edd0e8f5fa1d5d8">TransferTracker::loadInlocs</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#af64654b3c46ec3154963aed1dbb016d2">TransferTracker::loadVarInloc</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#aeb221ffeffa3ec7eaaa8eecf37b0146d">llvm::object::ELFFile&lt; ELFT &gt;::loadVersionMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#ae015be66fae811e0fe4cc32ce868f373">LookupNearestOption</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblymcinstlower/#a62aefd0bed5ed9cd5a154bf4d4074a22">llvm::WebAssemblyMCInstLower::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#afe97e2bc5bd74272ca1b54da1fb30e06">llvm::SelectionDAGBuilder::LowerAsSTATEPOINT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab2689b832f03d85c8c3f2a096b653f75">LowerBITREVERSE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aada7984f8ada9c0d22fe9b269f60f614">LowerBITREVERSE_XOP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abce17120537283b4104f8e1a7cad02a2">lowerBUILD_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aedd54e8f3c3c8ea92b2ecedb4f86c487">LowerBUILD_VECTORvXbf16</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a744d14408c0db57df812858803759ba1">LowerBUILD_VECTORvXi1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a36debfa66256f0f353a0a44c9204eefc">lowerBuildVectorToBitOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aeed184a32cfc1dd279753d4a633bfba1">lowerBuildVectorViaPacking</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aac7b8dff5ac02a4754d7e10dec681511">llvm::SystemZTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac5dad0c030e404ca62ed0f75efdca162">llvm::VETargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ab0d338abd21b7cc0711741b492330a9d">llvm::XtensaTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7791efd93b12280fdad994fb6073933d">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#ab055c9ed89ccbcf823971615232941d1">llvm::SPIRVCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ad97db5ef296bd1bc041ace70b1224812">llvm::SparcTargetLowering::LowerCall_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a796fb7765de0aab1aa00f7a13f5796f9">llvm::SparcTargetLowering::LowerCall_64</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a5043353fac5252fc897dd06360274fe5">llvm::HexagonTargetLowering::LowerCallResult</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9696c62f9eeb556df764837c92b560df">llvm::SITargetLowering::LowerCallResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcoreisellowering-cpp/#a1a9dd0281442f33e9d9c88a3162d0274">LowerCallResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcisellowering-cpp/#aa0dc943f955ef5657bcc9eb702f611fd">lowerCallResult</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#ab8a7c054bcb1baa4c5445edff7c1580e">llvm::HexagonTargetLowering::LowerCONCAT_VECTORS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2763beadd2a14bcdb482f2b66a802019">llvm::lowerConstantIntrinsics</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a5098d901f0c198948883d51adc575bcf">llvm::HexagonTargetLowering::LowerConstantPool</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#a6cf0eec5c3acd7ff97e6e5dec15a97d6">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesFromI1</a>, <a href="/web-llvm/docs/api/classes/anonymous-siloweri1copies-cpp-/vreg1loweringhelper/#adaf0e50d1e23ce068ed74fe079552d51">anonymous{SILowerI1Copies.cpp}::Vreg1LoweringHelper::lowerCopiesToI1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7994fd7ca0d8f8fcf2a9d18d151d0988">llvm::LowerDbgDeclare</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a47c057e00771d3428bba280de009c4c8">lowerDisjointIndicesShuffle</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#a18f228d6b8d87ccfbe0db322ed26a2c6">lowerDSPIntr</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroearly-cpp-/lowerer/#ad856ac9052abe36a0ca7e8909fd18f1b">anonymous{CoroEarly.cpp}::Lowerer::lowerEarlyIntrinsics</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a76e5a8c6363a48b3ca4e924a8f59f0e5">llvm::LegalizerHelper::lowerExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#af4e7be374a3346400a32967d91108c3e">llvm::LoongArchTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a6107db1593ae7bb4074d606368898747">llvm::NVPTXTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/r600targetlowering/#af36f0d9675dc67d62c6cbf827ee7b745">llvm::R600TargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#abae2fc34bf7e289e53e0abf82feea144">llvm::RISCVTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aea6e04371c9e8737432c6687ce4dc62b">llvm::SystemZTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#abd42e7de94d28ca6667b61e1bcba6dce">llvm::VETargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#a77be04627b4e9afad340db307d1dbc3a">llvm::XtensaTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#af4911ff1c4fabd84b05d4529da80021e">llvm::SPIRVCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a405578f0decf5610edec9f350a54e81f">llvm::SparcTargetLowering::LowerFormalArguments_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#ae87be78c50d3026c58e203aa8f0b9164">llvm::SparcTargetLowering::LowerFormalArguments_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerguardintrinsic-cpp/#a6c30165ed98029182d00cb428a64fd29">lowerGuardIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a1692829d8158767fe5ac1809c90a77a3">lowerIncomingStatepointValue</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a743aa32715279bdb86b53f20065950c9">llvm::LegalizerHelper::lowerInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#aa3168bc53fc117710cec207cc6f60518">llvm::ARMTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab5881269962ffb5a6c2d4c5be45efbce">llvm::X86TargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac2d9e284d06499be56d61b876e86dc8a">llvm::AArch64TargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a3dbdbf556532f2d39ea38114cb7a5a23">lowerLaneOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a36b39e8a1384a23b9899d2c9e2e08e72">lowerLocalAllocas</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a505cc141300c7ce5f68734af974b0961">LowerMemOpCallTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae3b5afe10336a33630e00f86fab07c87">LowerMUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#a36764d140de2314a0f15b203f0556112">llvm::coro::anonymous{SpillUtils.cpp}::lowerNonLocalAlloca</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41052a5d27c665c41207f349f1a45af2">llvm::lowerObjectSizeCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a93d553082403c1d952f2e3c7d9d41926">llvm::RISCVTargetLowering::LowerOperation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a5e5cf24df0a45159407988a98fe42700">lowerPtrAnnotation</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a33edc5c19a9e674e389ecc1320464e23">llvm::HexagonTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#aece826681b1fdc9ec7c82f4a9152000f">llvm::LoongArchTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a5f7819dcae52567c11033d63e3d6421a">llvm::NVPTXTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a141bf09f97adbbe9f512fb1141f37090">llvm::RISCVTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a4ce28f633cfe7a89369965cd9792e8fb">llvm::SITargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#a3a9a464956d7d22291e5a6a29d4266e5">llvm::SystemZTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a73a391aef4505ecba196737cabb18ca0">llvm::VETargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetlowering/#ae491d50e304bf7057a2f4dfbf1650e56">llvm::XtensaTargetLowering::LowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a97357df4054a9551eb9a07b609cea109">llvm::SparcTargetLowering::LowerReturn_32</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#aa76596666bd4af3c0104b7a8fd514db0">llvm::SparcTargetLowering::LowerReturn_64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a52e4483d03d2add97c23c0c74c7ede61">lowerShuffleAsBitBlend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9cca449265297eb5a0bde5f0e48b7c22">lowerShuffleAsBlend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aeefb78459638421a22efc227acbf0a2a">lowerShufflePairAsUNPCKAndPermute</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#abac7927a227a6c370e26ee82af77567d">llvm::LegalizerHelper::lowerShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/statepointlowering-cpp/#a9029ef3db44eac67782fd8ccb7796a0c">lowerStatepointMetaArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1d727a45696ad380a24b7fd8445182d8">LowerUINT_TO_FP_i64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae317d23ba6ba8b97b454aa39a07b5074">LowerUnalignedLoadRetParam</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a2b01b00892f78bc1a75f271e3b9042f5">llvm::AMDGPUTargetLowering::lowerUnhandledCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a96929c573ae5a98213a4d8c25554e53f">lowerV8I16GeneralSingleInputShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a24dd4520150ae503a82945677a5fb566">llvm::HexagonTargetLowering::LowerVASTART</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#adeacac9b0dabeafe536c99c4c3151fef">llvm::HexagonTargetLowering::LowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a04b59de220180462277a0d8d7f146b0e">lowerVECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/loongarch/loongarchisellowering-cpp/#ad4bdd437656a3e83cf59d55f7cb87582">lowerVECTOR_SHUFFLE_XVSHUF</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a6b5025511ed198dfe7a49b67cf6d57ca">LowerVECTOR_SHUFFLEUsingMovs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ab23bf20bdfd42429185273b8841ea16d">LowerVECTOR_SHUFFLEv8i8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a6afe3df9ee811541f6b2dc67f5fe53e5">LowerVectorArith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a18b1fa269a5cff8ff05a92e60a39427b">LowerVectorCTLZInRegLUT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a2e64ed34d142c2680648d09c25ee51e4">LowerVectorCTPOPInRegLUT</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies/#a97298a7350df5e0302d0678065f5a1e2">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::lowerVGPR2SGPRCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af501c536e39e504d53df2c0fa3d83f6d">LowervXi8MulWithUNPCK</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerwidenablecondition-cpp/#adb00c4c46ce23c327d6cf77f723255ee">lowerWidenableCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a74212fb91857a365ae5c6c85a0646d97">makeDstOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a368216c9c116e3f30d8dd352ce1370fc">llvm::makeFollowupLoopID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8a1ae2e1de53a840bee516d1f5bb173">llvm::makePostTransformationMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#acad221a6df1d4872c6cca80bc913f7b7">makeStatepointExplicit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#a508aceda7d46a30692b5bb3531e16dba">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aauniformworkgroupsizefunction/#a7e545ca98465fdb21ed037cb8cd05f06">anonymous{AMDGPUAttributor.cpp}::AAUniformWorkGroupSizeFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadenormalfpmathfunction/#a3930112816f97f9c7a92b22d4e332107">anonymous{AttributorAttributes.cpp}::AADenormalFPMathFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a2c8f5eab9499a8b7a3238177f2ecf52c">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a4f2bae254fbc6babdf14612c7b20b512">anonymous{MachineOutliner.cpp}::InstructionMapper::mapToIllegalUnsigned</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/instructionmapper/#a0ad5905b935c2e08e68fa162f6950233">anonymous{MachineOutliner.cpp}::InstructionMapper::mapToLegalUnsigned</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a7d5502a6047fb27d6c33ea2820608c2c">anonymous{ValueMapper.cpp}::Mapper::mapValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp/#af31ca6130fc1fdac86bfb75b1acac4ac">markTails</a>, <a href="/web-llvm/docs/api/classes/llvm/regex/#ae787b71e8d775a2b662d04e913489d8d">llvm::Regex::match</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae88fdd4a40851c70c1f04282174034c2">llvm::CombinerHelper::matchCastOfBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#aab86990eacd037e1c72749c3342d410e">llvm::CombinerHelper::matchHoistLogicOpWithSameOpcodeHands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#ab97e7bb67059e0b2b6b66c4a784b5106">matchIndexAsShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#a265a1edd4b8035734cda280bb91b390d">matchIntrinsicType</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a8ed1d04073cbd814c13097e138d462e6">llvm::CombinerHelper::matchNotCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aa435f2b01aca963d926bd31cd95e7f03">matchPERM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a079f719b6af4bba305e041821a1e3da0">matchScalarReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a3df1d9d3afbfe5db4027289cf28d4726">llvm::CombinerHelper::matchShuffleUndefRHS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6fbf492764a869e2539fbdaf90b259f3">MatchVectorAllEqualTest</a>, <a href="/web-llvm/docs/api/classes/llvm/mclebfragment/#a44b3e83dbf45812c9af06f7b1b24c739">llvm::MCLEBFragment::MCLEBFragment</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a0d9ff571e6ceb5df2eb4d8a4d3011245">llvm::rdf::CodeNode::members_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>, <a href="/web-llvm/docs/api/classes/llvm/globalmergefunc/#a31ba90bd367677d2bf4065d6e51eca65">llvm::GlobalMergeFunc::merge</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a1dc2ed29bdcb3fedb0639cc8e88a7ecd">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeAssumes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a528aff11b730581c8d7cfae0e5fb6254">mergeBlocksIntoPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a6118e1e5d926f231bd7f007b2ed1b412">mergeConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a2711d3bc7c6c769a8f34c7fc3937169d">llvm::Instruction::mergeDIAssignID</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a6277ecb456c87743b292a5dd69542a4e">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::mergeLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad9d19d00519eec89a553d376d72c9520">mergeNestedCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4b251734aba716917922f4ab216436c1">mergeReplicateRegionsIntoSuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a2ffccbb574e8a2cf63b8ede89f53090b">llvm::LegalizerHelper::moreElementsVector</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5877bd47049087f890aed4f0f501ec3f">llvm::SelectionDAG::MorphNodeTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a76f2308b91faa139968810fd02d26891">moveLCSSAPhis</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#afe809699537758032938bea41ea44bb7">llvm::PeelingModuloScheduleExpander::moveStageBetweenBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a023f82db84f5e5ed13398308496689e7">llvm::mustExecuteUBIfPoisonOnPathTo</a>, <a href="/web-llvm/docs/api/classes/llvm/injectorirstrategy/#a22c46265af5b3e456243d03b635ae9bd">llvm::InjectorIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/insertcfgstrategy/#a4a797db667ae87ab16b62a35de4f4a01">llvm::InsertCFGStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/insertfunctionstrategy/#a51a23cfe8db3e31fdc6eeb8547df0d33">llvm::InsertFunctionStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/insertphistrategy/#a55f9b306ebb441abea69179650c2a4ad">llvm::InsertPHIStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/instdeleterirstrategy/#a5d0250802fc18f3e96531f43c6280c18">llvm::InstDeleterIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/shuffleblockstrategy/#a3bad39b7c7fd81aa15068f082eb6f0a6">llvm::ShuffleBlockStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/sinkinstructionstrategy/#a3ca14f887397b546b6b253d3e82ed4ee">llvm::SinkInstructionStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a6701d040466d73f3dc51481d3186c294">llvm::LegalizerHelper::narrowScalar</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aea9d2b3b2a626fb7c5093f5f8fa9cf95">llvm::LegalizerHelper::narrowScalarAddSub</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8a4aeb9640ed05629f69b925f53ae366">llvm::LegalizerHelper::narrowScalarBasic</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#aaec7c9b0ed49d3297c833d8d9def42c0">llvm::LegalizerHelper::narrowScalarExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#ad43f277d8baa4b080bfd1beed8542bd6">llvm::LegalizerHelper::narrowScalarInsert</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizerhelper/#a8f6f143ae3ebc33b4f3f97e486bf7112">llvm::LegalizerHelper::narrowScalarSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa91449ed55cd3c525a3438252573527a">llvm::narrowShuffleMaskElts</a>, <a href="/web-llvm/docs/api/classes/llvm/escapeenumerator/#ac63ecd195310b8a31b445bb613028893">llvm::EscapeEnumerator::Next</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90896a5c2c14e27297f4fdb0196e24b3">llvm::nonStrictlyPostDominate</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5c2fb6bace55f9b58ed0ba9fe363299e">llvm::Triple::normalize</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a759daba99f9b665ac7274d0dfe70ce09">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::normalizeReturnBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#a1e5a795e237da6e01636980c98b645ab">nullifySetjmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#a9ace593776041510de450a2eccc56eeb">operandWithNewAddressSpaceOrCreatePoison</a>, <a href="/web-llvm/docs/api/classes/predicate/#ae14f1b1c7777993a81b49f9db0c10659">Predicate::operator!</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/blockfreqquery/#af8c521993231c6aa85baba8f8c23b828">llvm::orc::BlockFreqQuery::operator()</a>, <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/lockstepreverseiterator/#add4e11e58e765474930767db18feb623">anonymous{GVNSink.cpp}::LockstepReverseIterator::operator--</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#ae812aaa917422c3c4b067cda1b1d7019">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::optimizeAMXCastFromPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aef572ae661cf9f5b14651ef952629c10">OptimizeAwayTrappingUsesOfValue</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseinstrinfo/#a12cb817575a9c4141e5a1268e6821503">llvm::ARMBaseInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ac3660ab4e1d66ed8457df619aa1bfec1">llvm::LanaiInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#a8118d9f62c345028220579c9d1ca4061">llvm::PPCInstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp/#a8949a90af3c69d31f132d6933c4d5914">optimizeDwarfOperations</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#afd07d19c7174c06cd7c7415f63596839">llvm::slpvectorizer::BoUpSLP::optimizeGatherSequence</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#aa26fba7384acba48becbf2f67547c437">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::optimizeLdStInterleave</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/liveregoptimizer/#aa50432deded202fb241ca2c204e8137a">anonymous{AMDGPULateCodeGenPrepare.cpp}::LiveRegOptimizer::optimizeLiveType</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#afbc1088fd64459bec1157940aa59eb69">llvm::X86InstrInfo::optimizeLoadInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuimageintrinsicoptimizer-cpp/#a0751e03131065414fffaa087c9e084cb">optimizeSection</a>, <a href="/web-llvm/docs/api/structs/anonymous-smepeepholeopt-cpp-/smepeepholeopt/#a5c603866e25916faea1af9c83ee89286">anonymous{SMEPeepholeOpt.cpp}::SMEPeepholeOpt::optimizeStartStopPairs</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/optimizeuses/#a195658a43b30378309ff4e62455dc137">llvm::MemorySSA::OptimizeUses::optimizeUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a370295a9498306cec66248f1c1fd8416">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::optimizeVectElement</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86cmovconversion-cpp/#aba46d9b0861c1e010f4bb946e5806415">packCmovGroup</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a0022aa73e6337684561159d1f7929966">packImage16bitOpsToDwords</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a2defa148ce873ae253cf3c3a1688ce13">packImage16bitOpsToDwords</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a6dba756ac7230f1732b09161ca525bdd">padEltsToUndef</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a9d7f3f2b0dc486075d4d462b7d744174">anonymous{MIParser.cpp}::MIParser::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/coffdirectiveparser/#a456d81f6b7c9b1824cc89be84e5e7960">llvm::jitlink::COFFDirectiveParser::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/yamlmemprofreader/#aa050d96fe18573b4d459a769f576f1dc">llvm::memprof::YAMLMemProfReader::parse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a90003a10d0a38bad6982d3037ffaf2e1">parseAnnotation</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#abba3a1b37c8d40cefcab729ee016441d">parseBackslash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#a9249200d14424808c822103928fe7fdc">llvm::SPIRV::parseBuiltinTypeNameToTargetExtType</a>, <a href="/web-llvm/docs/api/classes/llvm/debugcounter/#aa7b40dda7a09e0c055d6138b404d0789">llvm::DebugCounter::parseChunks</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a7225497318f6c1bd57e8a80d4273031e">llvm::cl::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/guardutils-cpp/#af7534ff6924d87e8750acd2d12a707c3">parseCondition</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-metarenamer-cpp-/#afa80d009777b085fbd5703e90769d652">anonymous{MetaRenamer.cpp}::parseExcludedPrefixes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/msp430/msp430isellowering-cpp/#ac48599976d79c3e82a4f1d76f5451482">ParseFunctionArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/elfattributeparser/#abf2d289101e52d2729fd86ac7ca68772">llvm::ELFAttributeParser::parseIndexList</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a63d8077ac333f927273b1e014644cf89">anonymous{PassBuilder.cpp}::parseInternalizeGVs</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#ae1c0498b0c1e685f7decf651532fc0d9">anonymous{MIParser.cpp}::MIParser::parseMDNodeVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a6779c29e343b8e71d97734686a3eabd2">anonymous{AsmParser.cpp}::AsmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#ae48dce9460eac00f49a306f8d48fdf11">anonymous{MasmParser.cpp}::MasmParser::parseMSInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoninstrinfo-cpp/#ab72dca1e43d1dae61c5f16bd623723fd">parseOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmparser-cpp-/amdgpuasmparser/#ab65e752ef8a4ee9e6df01039bfa00b0e">anonymous{AMDGPUAsmParser.cpp}::AMDGPUAsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0cd181d3140028362e24cdc5d675ac16">llvm::MIRParserImpl::parseRegisterInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/yamlparser-cpp/#a8f168615fb43a51a70c57eee12a86038">parseScalarValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machoobjectfile-cpp/#a488ef72cdaf48278d8a1117a6833bad2">parseSegmentLoadCommand</a>, <a href="/web-llvm/docs/api/classes/anonymous-miparser-cpp-/miparser/#a70c970df35e9a1ebde9a6371fb8a6bc6">anonymous{MIParser.cpp}::MIParser::parseShuffleMaskOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4816bb91a3b2d18ae4231a09325e06b7">llvm::parseWidenableGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#adc90ef1bf034dfb4446b910d3795d218">llvm::PeelingModuloScheduleExpander::peelPrologAndEpilogs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#af84a0dc03b9bdd1ccfd5f88dae1a4aab">performBUILD_VECTORCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a90b1ef73daf047e3bc666006c9e35a77">performBuildShuffleExtendCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a0048548b4f1cc9455cf3af293d2b52bf">performCONCAT_VECTORSCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#ae8ade4269715b02714b67bdf1a0b9ba5">llvm::AMDGPUTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#ab4ccdcee4c7a2e0892715d0a8094b86e">llvm::PPCTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a2d89f95e0a2a13c2a42e9ef5805e6e11">llvm::RISCVTargetLowering::PerformDAGCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6408862dee3fedb95b41b72c9b8edeb6">performExtBinopLoadFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae60f4de0d1e0dac32141edcacb8d20c3">performLOADCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a589928ae94c1e14b50e374c6a1146c60">llvm::ARMTargetLowering::PerformMVEExtCombine</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a35a55a457bfc044d33bdeb4811532531">llvm::ARMTargetLowering::PerformMVETruncCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a77f2232fb1d07b3f88edaef89e94e673">PerformMVEVLDCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a2fbb20906245b5a07551c13da1409712">performNEONPostLDSTCombine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aae35ec9b920ff3bb892cd872877a89fe">llvm::performOptimizedStructLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#abdbf7e16d7027d0bbbc9d4e8bf100840">performPostLD1Combine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#af99f8aa9b9d9dddc47ec39b12a1eb02d">PerformSplittingMVEEXTToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#ae17716da714991550ba9ea6f4747831a">PerformSplittingMVETruncToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a91f43e00f77d44c412e9b3675ce35253">PerformSplittingToNarrowingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#afbc0dc4ba278fb4634893dc0c64b0676">PerformSplittingToWideningLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#aba237afe216b870806584d3e96e575b4">PerformTruncatingStoreCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a6d8fbde7afd8f90c51d6001d0144b1c8">performVecReduceAddCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a8544593225835a30146f86a3187740e7">PerformVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#a90089c4b79f869ee82ea85c2a737921a">performVECTOR_SHUFFLECombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#a040e9492b947241650ac7f528bd75c25">PerformVQDMULHCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a92cef83bd2aaa8850f69f2cb852b3fe8">placeSources</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aca6160bb3d669e9ce01f91b124e7e0a1">llvm::LoopVectorizationPlanner::plan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a89d936a98d65c79ddb962452b2d670bd">llvm::PointerMayBeCaptured</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc/#a0f29a553d97c6cbfab2318fb5d22902a">anonymous{PGOInstrumentation.cpp}::PGOUseFunc::populateCoverage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiloplowering-cpp/#a5761cea08563e881215f9511be699d06">populateOperands</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartition/#a9feb888b40cb5010ca125c921f15c0f8">anonymous{LoopDistribute.cpp}::InstPartition::populateUsedSet</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a385464d789381c250f924d62222498f3">predictValueUseListOrder</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/valueenumerator-cpp/#a0446dc9c4c3fd1116f5510fab7d64a43">predictValueUseListOrderImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/dxilwriter/dxilvalueenumerator-cpp/#a0446dc9c4c3fd1116f5510fab7d64a43">predictValueUseListOrderImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a0804b0846b504f0556a8085204f1127b">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::prepare</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#ae97bb6b91cff3e18475ab68012287cc2">llvm::SystemZInstrInfo::prepareCompareSwapOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a51dffbda74e47e34a64858d09d456108">llvm::InstCombinerImpl::prepareWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#ac6859ef2a1c57ce668658e21fe90bfad">llvm::TargetRegisterInfo::prependOffsetExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ad7ad4b4d9c6fc993c58ff56612f4031b">llvm::AsmPrinter::preprocessXXStructorList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagisel-cpp/#a8b32e4502abf6ca6e3e14df151cff6a8">preserveFakeUses</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraph/#a1a066faade450399db380381c68e8b32">llvm::CallGraph::print</a>, <a href="/web-llvm/docs/api/classes/llvm/physicalregisterusageinfo/#aaa2c354cf7353f24dac62741d54bc98b">llvm::PhysicalRegisterUsageInfo::print</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/dependencygraph/#aa8602ab3d40d78dfbf826e154ac3fb8d">llvm::sandboxir::DependencyGraph::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#a5d394830d4143542278afee43f527b48">printNoMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a91f729b936911342abb6b606e0606cdc">llvm::Pattern::printVariableDefs</a>, <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a42ba71cba0e3d5e1b4e5395fd080016d">llvm::AlignmentFromAssumptionsPass::processAssumption</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcearlyreturn-cpp-/ppcearlyreturn/#ae036500138a9ae1567af6b28547cf045">anonymous{PPCEarlyReturn.cpp}::PPCEarlyReturn::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemzelimcompare-cpp-/systemzelimcompare/#adc7ada58edab4877f99340bad212ecbf">anonymous{SystemZElimCompare.cpp}::SystemZElimCompare::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a933376a6efcdf3b5910c326b774eb8b3">processBlockAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a071cd98d76a1c63f215ad16388bfdfe2">llvm::JumpThreadingPass::processBranchOnXOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a4357c88d173a81e047c07756ff94ada0">processConstantStringArg</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/dxcontainerpsvinfo-cpp/#ad6c7bb71f11814fe88bf73f5c589a9e0">ProcessElementList</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a471ef961ae64095de93c59dea0a3262f">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::processFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#a3f176ff8abd35fbe2f043c22d088302e">llvm::PPCFrameLowering::processFunctionBeforeFrameFinalized</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvbinaryreader/#a65eee5509cce98dcc69693ea13bb9220">llvm::logicalview::LVBinaryReader::processLines</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#a1b795b0cd98521a7cf4ab769d9207258">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::processLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a53ef6f5be8cd25a33229fe16aca9d537">processPhiNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a406a444512ca2224d325c9a217c31547">processPSInputArgs</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a914ea1510476a800508ae70d159bd8c0">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::processStaticAllocas</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a61326cd6384971e828511e500b3367c6">processSwitchesConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a96191c096e61f77ea0a6771263bdb5e1">llvm::JumpThreadingPass::processThreadableEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a53602f27c06fcab4b6b5d552984a5ad7">promoteArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae529107c3b550f7e2fe6128a26c8f1da">llvm::promoteCallWithVTableCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a6952450f0726bd9c26d303743522e227">promoteSingleBlockAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/gcovfunction/#a6084253c0f3954d2b8479befc2a6be61">llvm::GCOVFunction::propagateCounts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ad9245aac1330cef52005ed7a9f789c37">propagateMetadata</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a611115d09f3dd3ef310f70c87a8ba402">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::propagateShapeBackward</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#adf1371d869d3a7468c48401a2a321b26">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::propagateShapeForward</a>, <a href="/web-llvm/docs/api/classes/llvm/swifterrorvaluetracking/#afc960ff953a4a9d9fbf91baf590222d2">llvm::SwiftErrorValueTracking::propagateVRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a94cf1c59ca73ea330872deb639013cb9">llvm::LiveIntervals::pruneValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-registercoalescer-cpp-/joinvals/#aa3fe888e13e687c808085c0cfba933c3">anonymous{RegisterCoalescer.cpp}::JoinVals::pruneValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a8c47deb9ff88d1453a3fde3200347a95">PushDefUseChildren</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a1be30af6ed42477abe149692b7b8a44c">PushLoopPHIs</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ad50c0551a73d70d5bd769557bdbec3d7">anonymous{DeadStoreElimination.cpp}::DSEState::pushMemUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/thumb1framelowering-cpp/#a24366f8644cf1d6492c2abf2999311a1">pushRegsToStack</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/rawcoveragemappingreader/#a6f328f5f8d7e388b876dc55edd2d7da8">llvm::coverage::RawCoverageMappingReader::read</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstacklookuptrait/#ab21c89705e7c11df348a65bd90437bf6">llvm::memprof::CallStackLookupTrait::ReadData</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadertext/#aa8f17958c50ff564f5817c64850da276">llvm::sampleprof::SampleProfileReaderText::readImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ac5b6ac3924041b35531d4e9bf66c3df4">llvm::SIInstrInfo::readlaneVGPRToSGPR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a4fd75ce06ed3355a2eca1dc0d0ed858e">llvm::memprof::anonymous{MemProfReader.cpp}::readMemInfoBlocksV3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#abcd60615b324b6305d230736760acf69">llvm::memprof::anonymous{MemProfReader.cpp}::readMemInfoBlocksV4</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#ac7cd1bb8cb4a4e4e1ec44f5097cb071f">readMemprof</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereadergcc/#a98a6af42792c32db070dee8826e1412e">llvm::sampleprof::SampleProfileReaderGCC::readOneFunctionProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a4a29d1708d93d41d894ef8c0c57f0961">llvm::memprof::anonymous{MemProfReader.cpp}::readSegmentEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#aa386dbcb508e02e5910438040aed2cac">llvm::BinaryStreamReader::readSLEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab9f41a80bcb29a219eff47dfac886cce">llvm::BinaryStreamReader::readULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#ab6717ca91fe3922480a18f3e4250e611">llvm::object::MachOObjectFile::ReadULEB128s</a>, <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo/#ae5e0c947b38bdebad23286c7764b5249">llvm::TargetInstrInfo::reassociateOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fixupvectorconstants-cpp/#ae0a656fd896bd17cb7c911a16ac2e4e4">rebuildConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#ab79f3dcf9607c6a8908cda57cc964f49">rebuildLoopAfterUnswitch</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyexceptioninfo/#a6248704cecd958d5eeb84fa3536fc78c">llvm::WebAssemblyExceptionInfo::recalculate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c402f49fa595af618c5ad1500565d92">llvm::recognizeBSwapOrBitReverseIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/livevariables/#a9e0695dc8fb597f66ca702309da941f7">llvm::LiveVariables::recomputeForSingleDefVirtReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a0c9b0aa6fff67d00a95f47fc121491e5">recomputeLoopBlockSet</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a75ab07a3bb2b992b551be9596d21f0fd">llvm::reconstructFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a94825933fbeecbda802a1c22c46a524d">llvm::AArch64TargetLowering::ReconstructShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af2093ca4a132848caa9d8acc509df1b2">ReconstructShuffleWithRuntimeMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#ac177889afcc13c9ef882fd160c11e851">recordCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/importedfunctionsinliningstatistics/#a869c36ec45c584dfa6f3d914d230b15f">llvm::ImportedFunctionsInliningStatistics::recordInline</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ab5d43362c1fefd60d9bfcc1e28ba4688">recursivelyDeleteDeadRecipes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1de454f8f11d343f01bde5f057af057e">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1106b8a15061e8494873e10bb8a364e5">llvm::RecursivelyDeleteTriviallyDeadInstructions</a>, <a href="/web-llvm/docs/api/classes/transfertracker/#ac1753e9184a776f25f017ac1022f2a13">TransferTracker::redefVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeredundantdebugvalues-cpp/#ab500564693e7d4da8ba1c02c723a057a">reduceDbgValsBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/removeredundantdebugvalues-cpp/#a0cb9f41d03e7efefe10150f7941cdd16">reduceDbgValsForwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a6860a87b20545e2f53641a1bf33f6c4c">reduceSwitchRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55412d2c237115c95f20e12ba0d95922">relocationViaAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a41b5be766680970f5843b6bbeb8ee3d6">anonymous{ValueMapper.cpp}::Mapper::remapDbgRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/dbgvariablevalue/#a6879f5553ba1cadd0154a0a332127be4">anonymous{LiveDebugVariables.cpp}::DbgVariableValue::remapLocNos</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a765f84a0c5289fe4fc72c224abc2e4ac">llvm::SIInstrInfo::reMaterialize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a0650e5c5d027b7ef00c23a7921c114db">rematerializeLiveValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#aa175634946d91981b87f76ed9a583f27">rematerializeLiveValuesAtUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a35c103b5fb70a66a1cb5da3b56f588a1">llvm::sys::path::remove_dots</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/delinearization-cpp/#a161de17b2db4a6bdb9b4ce1ea13da113">removeConstantFactors</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a97b7a3d43f4f6eb3ab16554f56bd0cc4">llvm::LazyCallGraph::removeDeadFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a92c8c043c2a2d8db5b6cf9767394b747">llvm::SelectionDAG::RemoveDeadNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afa91c37999052160d434c5bf803257c9">llvm::SelectionDAG::RemoveDeadNodes</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuexportclustering-cpp-/#ac88025eb8866478014f41b34cd29b593">anonymous{AMDGPUExportClustering.cpp}::removeExportDependencies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a6b42b6fca05063155c689008d30a2751">llvm::AMDGPU::removeFnAttrFromReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a56b5a0fa4891dca73946affd4e6e3ffd">removeFromUsedList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#aceb0dbb192df1147bd5191db4c960ec1">removeGEPBuiltinsInFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a4082748189dc3460ea7130cd8d7790b5">llvm::MemoryDependenceResults::removeInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#aa8ccbcf19b9150f2872f794ecdc53d3e">llvm::slpvectorizer::BoUpSLP::removeInstructionsAndOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a87dd1a69c8d8492e78b32708ceacb2c6">llvm::LazyCallGraph::RefSCC::removeInternalRefEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">llvm::SCCPSolver::removeNonFeasibleEdges</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#ab28699e21ef7b0aa06794bee56959a32">anonymous{CommandLine.cpp}::CommandLineParser::removeOption</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a36fe1ed1682023b7fb3c4699f9009d31">removePAICalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86avoidstoreforwardingblocks-cpp/#aa00cbe94721ef6343a9a10ab26af3744">removeRedundantBlockingStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a2373ebe62ac37c5f7d838e9ca92a7f2e">removeRedundantDbgInstrsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#aceb315f70b8f69369df84d79274ef420">removeRedundantDbgInstrsUsingForwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#ad959466c7f8b886a2caa4967c46d48db">removeRedundantDbgLocsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a72b4d4469e68630addc74e567526f261">removeRedundantDbgLocsUsingForwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/lowerallowcheckpass-cpp/#aeab949c1d2a96004a9076b8b2176ca74">removeUbsanTraps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a579e878e02e34bf9699e3d82da2bc070">removeUndefDbgAssignsFromEntryBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4e75fd1680471e758ffbca9f8d893884">removeUndefDbgLocsFromEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a05377ec092a5d076c82dd3285317e6fa">llvm::opt::Arg::render</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#ab3635230226f6d60dad04b8e83d848fd">llvm::slpvectorizer::BoUpSLP::VLOperands::reorder</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a2eb73a15ea2a5105bd2cec95863d7113">llvm::slpvectorizer::BoUpSLP::reorderBottomToTop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#af2c671e8273bc99e266f62322b29a157">replaceAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ab7f8d142b901597abdf51e5e51a5605f">ReplaceAddWithADDP</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a9c14a49c489d623a8174f48b368cd3e8">llvm::DIExpression::replaceArg</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphnode/#a61a20bdec19cf182df0c3b23bb1895b7">llvm::CallGraphNode::replaceCallEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a635463dc5e146744799163c2f820e51b">llvm::SCEVExpander::replaceCongruentIVs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#abf799de7147065c0e7f525e1b6009dde">llvm::coro::replaceCoroFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblymemintrinsicresults-cpp/#abd14b1720a6213a3a1251afdbd671c62">replaceDominatedUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a801d960feba2403acf8dbd07ee3f34b6">replaceExtractElements</a>, <a href="/web-llvm/docs/api/classes/llvm/debugloc/#aac09dfae0aafa3f07db67a5813f454ae">llvm::DebugLoc::replaceInlinedAtSubprogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a43333bc4548cbb52de14105bc979c0e0">ReplaceINTRINSIC_W_CHAIN</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a287ee23f262c0a9deb16096da9d34e7a">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceIVUserWithLoopInvariant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a1d84356309e55a4722a2739dd3c655e4">ReplaceLoadVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a649ac561acbab510055b0e8f48ca0617">replaceLoopPHINodesWithPreheaderValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a8b47a3cfdac6c8cc7e158e8ee75973d7">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::replaceMulWithMul24</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/#ad1a825a151b1c9b01a9054f14eb518d2">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::replaceNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a99f0584edf9a13120df821e7f77d9731">llvm::LegalizationArtifactCombiner::replaceRegOrBuildCopy</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a705c6c2b8e570441356edb8db2dd8ddb">replaceUndefValuesInPhi</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a07714583aa2bea29cd0284d5340dd844">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::replaceUseWithTableLookup</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a9f66dfca05bfb9a4f5bddbad1ad043e6">llvm::DbgVariableIntrinsic::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a3d995a069d73ebebbd6a4aace342ef76">llvm::DbgVariableIntrinsic::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a61ce6eff43abf1cde49ddc11a5567646">llvm::DbgVariableRecord::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae0ac412244054beacd97e316ded0fed3">llvm::DbgVariableRecord::replaceVariableLocationOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfabstractmemberaccess-cpp/#a36be37a99f7cf2fdd84b942e5dafba1b">replaceWithGEP</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopearray/#a1ea12d2cfc5954a2e0e3770f62d6b127">llvm::logicalview::LVScopeArray::resolveExtra</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp/#ace668daeea976eec3d2c6fc32117acd8">resolveRecordTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a6bb67693444e665aa7e34c718f4d9166">llvm::CondOpInit::resolveReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#a967db113515bd01d32db6a426d7c73c1">llvm::DagInit::resolveReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/vardefinit/#a8615ac7b8e15f3b975c37d5da0b06f8f">llvm::VarDefInit::resolveReferences</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a8a6fce329f29e0ec830e61c629b70739">resolveSources</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a69ed119a74aa160e44fcd158476e353e">resolveTargetShuffleInputsAndMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a196b104079c33f7ccd4ad4816376b9a7">restorePreTransformState</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a732f3ff01555ec522134bf060270c1ae">rewriteAccessChain</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk/#a60fac14032181eef9fe2f3e790ce9c28">llvm::SSAUpdaterBulk::RewriteAllUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/materializationutils-cpp/#aba618c16a34739af0506ba1082d209a3">rewriteMaterializableInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcorelowerthreadlocal-cpp/#ae5532112c4ead645d90e6fe4e5092f5f">rewriteNonInstructionUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a0647ca6021ca57224016effde79d4d7e">rewritePHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2cadcdd1750ca8ba3197c1266052c059">rewritePHIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/statepointstate/#a660b805a48ac0e274df10b25ee8c3497">anonymous{FixupStatepointCallerSaved.cpp}::StatepointState::rewriteStatepoint</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/amdgpulowerbufferfatpointers/#a00d87849a4eb6524d910ab07f0fd968f">anonymous{AMDGPULowerBufferFatPointers.cpp}::AMDGPULowerBufferFatPointers::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotealloca-cpp-/amdgpupromoteallocaimpl/#a17b2c2b9161a29f3fa9a80e1cb5351c1">anonymous{AMDGPUPromoteAlloca.cpp}::AMDGPUPromoteAllocaImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuremoveincompatiblefunctions-cpp-/amdgpuremoveincompatiblefunctions/#a8d8058631456eb8173e42f7af6f4555f">anonymous{AMDGPURemoveIncompatibleFunctions.cpp}::AMDGPURemoveIncompatibleFunctions::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a0633351128ad7c6f0e5bf0522edeef79">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a9db16f6b49d380b76183877d54b42c5c">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-dfajumpthreading-cpp-/dfajumpthreading/#a858489f4cff24516d6ac192f2165dce2">anonymous{DFAJumpThreading.cpp}::DFAJumpThreading::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheckelimination/#af56db9cf79e7501bf38278f849774369">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-linkmodules-cpp-/modulelinker/#a589fd28f47f98110e06d544523d59977">anonymous{LinkModules.cpp}::ModuleLinker::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-stackcoloring-cpp-/stackcoloring/#a97d6b0d6fae6fc47e5e354e6c3382938">anonymous{StackColoring.cpp}::StackColoring::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-stacksafetyanalysis-cpp-/stacksafetylocalanalysis/#aaed4fd903e016ae19555330092b0e3fc">anonymous{StackSafetyAnalysis.cpp}::StackSafetyLocalAnalysis::run</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfaspacecastsimplifypass/#a76364c57022d89ac618f1b1e22bef6e2">llvm::BPFASpaceCastSimplifyPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/cgscctofunctionpassadaptor/#a44a083f826f2f2a189d3979eb43dd5ed">llvm::CGSCCToFunctionPassAdaptor::run</a>, <a href="/web-llvm/docs/api/structs/llvm/corosplitpass/#a47f6589634ad33a13369ace133b9f4b2">llvm::CoroSplitPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functionspecializer/#a27893e2167969de71fd88771382a93ad">llvm::FunctionSpecializer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/genericcycleinfocompute/#a8af31f91b7b3fe098e8966229069b1ae">llvm::GenericCycleInfoCompute&lt; ContextT &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/hipstdparacceleratorcodeselectionpass/#a3c59b50e60a44b5fa3871d0449aa4744">llvm::HipStdParAcceleratorCodeSelectionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/kcfipass/#a19dcb564cb3c8a4de327c6f9cabed5b3">llvm::KCFIPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loadandstorepromoter/#ac1da68baf80229b2d8af34499eb1c73f">llvm::LoadAndStorePromoter::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loweremutlspass/#aa02b6a6722504e6fb7a176a81fc5d49c">llvm::LowerEmuTLSPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/memderefprinterpass/#a9643b91d2f4e79487e5b260eb11fef74">llvm::MemDerefPrinterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/postorderfunctionattrspass/#a8312d250d0f7b4407b4bad97293e5865">llvm::PostOrderFunctionAttrsPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/stacklifetimeprinterpass/#a7d1ec1183162820291a3dcc9a0e81d45">llvm::StackLifetimePrinterPass::run</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a82285f7a23214e4a8931017af62e2d24">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runDFS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loopversioning-cpp-/#aed4891b5f4ab2e016fc238f42dfd939e">anonymous{LoopVersioning.cpp}::runImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/placesafepointspass/#adcb87ee7d8b9f08bc82da9cae1c74429">llvm::PlaceSafepointsPass::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a62c6882e8be05d55fb7e7f743f43d902">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#aca9bbb9fc2968bbb644730c5c2567409">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/instsimplifypass-cpp/#a49359723de1a046072e8cc931068d43f">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#ae64f9cd0977a8b47570154312540d7d2">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdistribute-cpp/#ae2710e7a8aa8c356be9fd34647605cad">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#a8f3d27d1b480f6b3c90405707be76295">runMoveAutoInit</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-avrshiftexpand-cpp-/avrshiftexpand/#a25192a5e79d3f5ef39a4b3d4a7da9fd9">anonymous{AVRShiftExpand.cpp}::AVRShiftExpand::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a66256b4fc858af974d6bea00a0d0639b">anonymous{CFGuard.cpp}::CFGuardImpl::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvegatherscatterlowering-cpp-/mvegatherscatterlowering/#ab630c640ea64fe3d2d7a1733d6bf7dc2">anonymous{MVEGatherScatterLowering.cpp}::MVEGatherScatterLowering::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxatomiclower-cpp-/nvptxatomiclower/#a707795edc1a2d6427fa4ba627e4b3d7a">anonymous{NVPTXAtomicLower.cpp}::NVPTXAtomicLower::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-nvptxloweraggrcopies-cpp-/nvptxloweraggrcopies/#a1e7cbd0783ad9cbbfdf85b5dbaba57f8">anonymous{NVPTXLowerAggrCopies.cpp}::NVPTXLowerAggrCopies::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvgatherscatterlowering-cpp-/riscvgatherscatterlowering/#a463122d7144f83fbbc69c99609fd2599">anonymous{RISCVGatherScatterLowering.cpp}::RISCVGatherScatterLowering::runOnFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/rewritestatepointsforgc/#ad69716246dabb743839cafceb902ef46">llvm::RewriteStatepointsForGC::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-looppredication-cpp-/looppredication/#a037f8481d5dc0c43741972ede1461d86">anonymous{LoopPredication.cpp}::LoopPredication::runOnLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64pointerauth-cpp-/aarch64pointerauth/#aa8ea77f095d6c1c056af51e7a652e5bd">anonymous{AArch64PointerAuth.cpp}::AArch64PointerAuth::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a9ab07fceeb056e44371448f9650b9ae5">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64speculationhardening-cpp-/aarch64speculationhardening/#af74e0cf10108e72a325bb16d56926dec">anonymous{AArch64SpeculationHardening.cpp}::AArch64SpeculationHardening::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuregbanklegalize-cpp-/amdgpuregbanklegalize/#ad1210df2e489436f417f18f10180ea44">anonymous{AMDGPURegBankLegalize.cpp}::AMDGPURegBankLegalize::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguardlongjmp-cpp-/cfguardlongjmp/#a17b3d486f52582c92dec4b050aedb70a">anonymous{CFGuardLongjmp.cpp}::CFGuardLongjmp::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-fixupstatepointcallersaved-cpp-/fixupstatepointcallersaved/#a3c8b04474d6af8577024260b88fb8352">anonymous{FixupStatepointCallerSaved.cpp}::FixupStatepointCallerSaved::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcncreatevopd-cpp-/gcncreatevopd/#adf788b42829ee3420f6efa016dd27281">anonymous{GCNCreateVOPD.cpp}::GCNCreateVOPD::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcnnsareassign-cpp-/gcnnsareassign/#a98d8aaed2e429cfec371c300cb8244c2">anonymous{GCNNSAReassign.cpp}::GCNNSAReassign::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a9f05c8e7366bb0f541cdc6c03b929ddd">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcpreemitpeephole-cpp-/ppcpreemitpeephole/#accbe3daa3b618020c7f900a4ca110f91">anonymous{PPCPreEmitPeephole.cpp}::PPCPreEmitPeephole::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-pseudoprobeinserter-cpp-/pseudoprobeinserter/#acf62b36239ac36c52ffc9a58a18332ab">anonymous{PseudoProbeInserter.cpp}::PseudoProbeInserter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-siinsertwaitcnts-cpp-/siinsertwaitcnts/#aab6a5b3788b7384e1928f2ccd79f26b7">anonymous{SIInsertWaitcnts.cpp}::SIInsertWaitcnts::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-silatebranchlowering-cpp-/silatebranchlowering/#a2f96cc01100e6467c2b124371cf417c0">anonymous{SILateBranchLowering.cpp}::SILateBranchLowering::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblycleancodeaftertrap-cpp-/webassemblycleancodeaftertrap/#a02a6d4c45d72193f89b19418a71f7ab5">anonymous{WebAssemblyCleanCodeAfterTrap.cpp}::WebAssemblyCleanCodeAfterTrap::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyregcoloring-cpp-/webassemblyregcoloring/#ac27e962fff6fda4c4419bc22281f38dd">anonymous{WebAssemblyRegColoring.cpp}::WebAssemblyRegColoring::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86callframeoptimization-cpp-/x86callframeoptimization/#a34c8c51043678dd60c9e23f012f2e8a5">anonymous{X86CallFrameOptimization.cpp}::X86CallFrameOptimization::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86cmovconversion-cpp-/x86cmovconverterpass/#a2b90fb87402f7118da2019ae5b84f0b1">anonymous{X86CmovConversion.cpp}::X86CmovConverterPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fixupsetcc-cpp-/x86fixupsetccpass/#a88ff40585130ceeb06ea67057cc33b5d">anonymous{X86FixupSetCC.cpp}::X86FixupSetCCPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86returnthunks-cpp-/x86returnthunks/#ab4a10d58e295ec66ff8c9c1d3eeb0529">anonymous{X86ReturnThunks.cpp}::X86ReturnThunks::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a356f9de405c2904f7ad73659a2f378a0">llvm::Legalizer::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-blockextractor-cpp-/blockextractor/#ab929be069dc417044c41ddeca9bec3b7">anonymous{BlockExtractor.cpp}::BlockExtractor::runOnModule</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#acc9692a75fb5d96db7c08693239df76e">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::runOnModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sccp-cpp/#a1b81143fa40d877b5cfe5496cbf3ced9">runSCCP</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a6b01145051cf194d0efb2b7ae241f24c">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::runSemiNCA</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa3fa258f0e297563fcec4bb619d2a759">llvm::MachineFunction::salvageCopySSAImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26be1141b23850a2b4eb78021d99e862">llvm::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a582354e8d5806847614742270d2ece1d">llvm::SelectionDAG::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a02cf9d6ac96ae27b406798da5c2eb7ea">SalvageDVI</a>, <a href="/web-llvm/docs/api/classes/anonymous-hwaddresssanitizer-cpp-/hwaddresssanitizer/#abe3ea5f5ad2a17b7552318e8ffb3b0bb">anonymous{HWAddressSanitizer.cpp}::HWAddressSanitizer::sanitizeFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-threadsanitizer-cpp-/threadsanitizer/#a41fe353d57c56ba3f43b66143ff436b0">anonymous{ThreadSanitizer.cpp}::ThreadSanitizer::sanitizeFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-typesanitizer-cpp-/typesanitizer/#a063b446da637b4357deed499cbbe11fe">anonymous{TypeSanitizer.cpp}::TypeSanitizer::sanitizeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a5c0f04dd919f2fa52e52f277a68b1ac1">scalarize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a6b532a3420c46c6194f80f8590cd7689">scalarize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ae002ed884c63140cccb45d854b6bd013">scalarizeBinOpOfSplats</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ade0519245a3e86cb20548e200f65863e">scalarizeExtEltFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aeda6315d246cafab6d912b425d4e7218">scalarizeVectorStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af38c031cd1488ca8f80ada31b3df9eac">llvm::scaleProfData</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagfast-cpp-/scheduledaglinearize/#ac5dfad52f2ec0adbc920cf686c615e00">anonymous{ScheduleDAGFast.cpp}::ScheduleDAGLinearize::Schedule</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a77bc2aad31cb4ad41441222b28c8080c">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a624f21782a600e972eacbae3e4818fcc">llvm::SelectionDAGISel::SelectCodeCommon</a>, <a href="/web-llvm/docs/api/classes/anonymous-cskyiseldagtodag-cpp-/cskydagtodagisel/#aa0b3de3815c7ba67bd6b19ef08ac9f1c">anonymous{CSKYISelDAGToDAG.cpp}::CSKYDAGToDAGISel::selectInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvprelegalizer-cpp/#a2d4e715bbecedf15f5f072b1be7efdb5">selectOpBitcasts</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#a6f1fe32957cb698200b26a3a96e0145c">anonymous{RegAllocBasic.cpp}::RABasic::selectOrSplit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstructionselector-cpp/#afa32384c08e0fbd9e4a5f1117c643c22">selectWMMAModsNegAbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#ad7de3dafef31acc6669c022e769750f8">selectWMMAModsNegAbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#add9d8e7cc38ac083f42ce6873a8defdd">separateNestedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ae8d11752355845a0e271111de7be7d3a">llvm::LoopVectorizationCostModel::setCostBasedWideningDecision</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#addb1364902bd813841491d91970ce02b">llvm::SUnit::setDepthDirty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codegen/#ac12e315180fb16cb5874fb41526ca453">llvm::codegen::setFunctionAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86interleavedaccess-cpp/#adcbb3fbae2a0dfe66454040a45525a95">setGroupSize</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#a5ba3791568e29a8d9214ec7dad855a56">llvm::SUnit::setHeightDirty</a>, <a href="/web-llvm/docs/api/classes/llvm/pmtoplevelmanager/#a5eab64f06a4196bd59b9b19251eefddb">llvm::PMTopLevelManager::setLastUser</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad272ce4631595e235e560baf59dc1ffd">llvm::setProfMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#aac66fb1c2d35d04a9d0af5abca7898b3">setRequiredFeatureString</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aaf604b7b4ff087fce0b71852f5ddefbe">setUsedInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ab0cdc36a4979b9142f43af9308cd7bfb">shiftAmountKnownInRange</a>, <a href="/web-llvm/docs/api/structs/llvm/aamdnodes/#a25af03cf36c07d235f487e525e5dcd07">llvm::AAMDNodes::shiftTBAAStruct</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#ac6c9b791cef5925e123539fb2934316b">shouldCombineToPostInc</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64simdinstropt-cpp-/aarch64simdinstropt/#a3b87d9f9d3ea5fcffea02f2f8e9bb55f">anonymous{AArch64SIMDInstrOpt.cpp}::AArch64SIMDInstrOpt::shouldExitEarly</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a6d3df5d0193e146b79c3c48601641c43">shouldSplitOnPredicatedArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsseisellowering-cpp/#ac326b52d617d41f386c715d297f96a72">shouldTransformMulToShiftsAddsSubs</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#ac7446b2819c44bf459763351b5bcc29b">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a42083019e0bdb164e55da49ab9f4d717">llvm::LiveIntervals::shrinkToUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker/#ac632fa4ac33de997f4fc1b02b416462c">anonymous{CodeGenPrepare.cpp}::SimplificationTracker::Simplify</a>, <a href="/web-llvm/docs/api/classes/anonymous-instcombineaddsub-cpp-/faddcombine/#a47fa84ad65315d095fa4153566cbd0b6">anonymous{InstCombineAddSub.cpp}::FAddCombine::simplify</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpchain/#a6bb3a89ac6216b60c21d8815fb2fa220">anonymous{MergeICmps.cpp}::BCECmpChain::simplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a5d4c970d99f3ffebfe1e07a3be697b09">anonymous{InlineCost.cpp}::CallAnalyzer::simplifyCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a7118a8527081192cbd8b839926fb95d4">simplifyCommonValuePhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a5681faab09fa140f67d47577193f2665">llvm::X86TargetLowering::SimplifyDemandedVectorEltsForTargetShuffle</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a7df35706e1cddf8fa5565622850e1fc7">anonymous{InlineCost.cpp}::CallAnalyzer::simplifyInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0083a69883e0f97e111dbff064c60f42">llvm::simplifyLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinstsimplify-cpp/#ac7156f23f48b5eb96ead0522896d7574">simplifyLoopInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a842c12e686e91a515dfd30a4bf70d740">simplifyRecipe</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a38dc339806a701c1f11ec31cf76936ff">simplifySelectInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#adc11c5fbec9bf293b000637357da66e4">simplifySwitchOfPowersOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4611905728c0ddaed9f8964ae8b074a2">simplifyWithOpsReplaced</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#adbe56869c99b539068e8a442d8738dae">simplifyX86extrq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a158032a7de947df4dc475c236414f0a2">simplifyX86insertq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a2784f2480fde374684ff993c8ae92991">simplifyX86pack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#abf44819ee45fe0465818d5244da90f68">simplifyX86pmadd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#afbcb72ff3dcc4f5818f711ca564b9dc1">simplifyX86varShift</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblydebugvaluemanager/#ad2a3fa939dc037b3b74f989e50cd208d">llvm::WebAssemblyDebugValueManager::sink</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7da8333874d1ad28bd987d4e7c474e53">sinkCommonCodeFromPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#abb3297c94836debc08248e7ae3f47582">sinkLifetimeStartMarkers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a925d8eaf1d93c7d13870ae5948c48140">sinkLoopInvariantInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a6e78c58ee832ea1775655021854401e6">sinkMinMaxInBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a4a5b1db18197a65d0f6a487f2e236921">sinkRecurrenceUsersAfterPrevious</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a0a5c60e5cebd520f95b9813fd9807016">llvm::InnerLoopVectorizer::sinkScalarOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa725413bc28036ce9c795a24503f654b">llvm::coro::sinkSpillUsesAfterCoroBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonshuffler-cpp/#a714f31724f5b3410c7a947afeeb1b0f1">SlotMaskToText</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#aca7c31a6dcc095ed3c2831f6876c6dc0">SoleWriteToDeadLocal</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ac4e11266d1da4632ff23afce04d8499f">SolveLinEquationWithOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/arraylist/#adf19460a3c702d261e7ffe25d77cabbb">llvm::dwarf_linker::parallel::ArrayList&lt; T, ItemsGroupSize &gt;::sort</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblycfgsort-cpp/#ab52c873c8169af2a8b1256ace3fe7a7c">sortBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfcompileunit-cpp/#a08fb230c2b93e704a4fd84ef773b6002">sortLocalVars</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractdependencegraphbuilder/#a2ca7af382aa1a34576aee355f364447c">llvm::AbstractDependenceGraphBuilder&lt; GraphType &gt;::sortNodesTopologically</a>, <a href="/web-llvm/docs/api/classes/anonymous-mipselfobjectwriter-cpp-/mipselfobjectwriter/#a5fb8605e7260a242de5a25e2b3add57d">anonymous{MipsELFObjectWriter.cpp}::MipsELFObjectWriter::sortRelocs</a>, <a href="/web-llvm/docs/api/classes/anonymous-silowersgprspills-cpp-/silowersgprspills/#a27a647930b9f60f83868035dcd46fca8">anonymous{SILowerSGPRSpills.cpp}::SILowerSGPRSpills::spillCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/anonymous-regallocbasic-cpp-/rabasic/#ab2d41fa069e7edcedf9949fa64aa6e30">anonymous{RegAllocBasic.cpp}::RABasic::spillInterferences</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af34178528cc721dfa273965733da1f37">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::split</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpblock/#afd6e09a5b9048b42dd46cc648d2b86c4">anonymous{MergeICmps.cpp}::BCECmpBlock::split</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuregisterbankinfo/#a909ca36ce602ebf9224694d163064009">llvm::AMDGPURegisterBankInfo::split64BitValueForMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silatebranchlowering-cpp/#a93b418512ed9bd239b221724374df852">splitBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33f79ea6e1fd1b8ba93c75519b1c929c">llvm::splitBlockBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a26bed2b570bc6e4d34eda3488f8430c4">SplitBlockImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#adc7bbccb30409488c60813454af8c81d">llvm::coro::AnyRetconABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#ae51f7f2d35223ec01d09e205c757a4df">llvm::coro::AsyncABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#aa80aaa82844ab5560ece045eee7b34ac">llvm::MachineBasicBlock::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/dinode/#a63a4694d7a6c8da554e27cf83c212670">llvm::DINode::splitFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a61553b705fc9be3d8d0a18a8af1bc152">llvm::SplitModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0409fb04e071cd7a523f022dffec2a3">SplitOpsAndApply</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#aaa24ed1e70b01f73a7f60f6c3d6c83a4">llvm::VETargetLowering::splitPackedLoadStore</a>, <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#aeffc1bb4ebe64a8ad3478e1253683847">llvm::LiveIntervals::splitSeparateComponents</a>, <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#ac796b9abfdee3add2549c94b5f3ddf11">llvm::VETargetLowering::splitVectorOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af376f4f0e0b55e40407912678b736863">SRAGlobal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afc25b6ced427069b5c1eb63b71add7a8">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6d633885803976c586a2b6f4d5d1af23">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1ddc20ccf70d1b20fcafbf3c6230a3ab">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a77755b0953ade3c85d715efcd0185c8a">llvm::stableHashValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#ad435005d9876513f43056c258958554a">stashEntryDbgValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a7fcdf2ea020f761f9857bebbc35a2ca3">StoreTailCallArgumentsToStackSlot</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a09a156bd41fe293ee8743b4beca76960">stripDeadDebugInfoImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/stripgcrelocates-cpp/#a5d9143fec81c7c1bea9330ccc664f45c">stripGCRelocates</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a2bf12026ed9de594d2117077b422c24d">stripNonValidDataFromBody</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/liveinterval-cpp/#aeb309e71b02f8298a437ec465645fe99">stripValuesNotDefiningMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a7223c62dc4b1db59861cb3a7e225a387">llvm::coro::suppressCoroAllocs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcinstrinfo-cpp/#af6776e5555063ea14c4668a4bcacae27">swapMIOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a2957918db7f91f405b11d92c1ebf3b0f">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToCall</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#a96fe0cb15ded58bd1824fa4e3daec680">llvm::LazyCallGraph::RefSCC::switchInternalEdgeToRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/btfparser/#a7db30a1144cd370f595ed6c16904db15">llvm::BTFParser::symbolize</a>, <a href="/web-llvm/docs/api/classes/llvm/tailduplicator/#a1c0f17f40e0399c6d151a50e99797e58">llvm::TailDuplicator::tailDuplicateAndUpdate</a>, <a href="/web-llvm/docs/api/classes/anonymous-hotcoldsplitting-cpp-/outliningregion/#a631ea87e33f8e50c1b90ae334ceea4c8">anonymous{HotColdSplitting.cpp}::OutliningRegion::takeSingleEntrySubRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#aff28c3d477d3a7870ec643381f186ed4">llvm::cl::TokenizeGNUCommandLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a3b42fd69f84c0ceef44857e925613ee4">llvm::cl::TokenizeWindowsCommandLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#af896b229210e1e59c2d9f66112fc48d3">llvm::cl::TokenizeWindowsCommandLineFull</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp/#aaa5adc2409ac3c78b33d4813ff31ae6e">tokenizeWindowsCommandLineImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a8d80076c6887cc447e544881292a3ad0">llvm::cl::TokenizeWindowsCommandLineNoCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elffile/#abf0867b6082e1e0408b1b5d8301f27e2">llvm::object::ELFFile&lt; ELFT &gt;::toMappedAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a5d968bc337af0be1f18813553a046df6">llvm::Twine::toNullTerminatedStringRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/anonymous-apfloat-cpp-/#a67a4cef5addbdc43c571874df4ea020d">llvm::detail::anonymous{APFloat.cpp}::toStringImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/macho/machowriter/#ace4d95a09224c0956cada6a3a7319e3a">llvm::objcopy::macho::MachOWriter::totalSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ea82b63a4aa1e4c73df257ffc9b7ec6">llvm::toTypedFunPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph/#ad0477be3c74794e35bec0c8f16e8a8ef">llvm::jitlink::LinkGraph::transferBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#afce558f34a90609d76e4c2f45ab5650c">llvm::SelectionDAG::transferDbgValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#aebda974c30b92d0f6ffca66705d27f35">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::transform</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a1fc58ffd013616b9e729a33f68ab1d01">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::transformAllAMXCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a44ca78ca7013578c50cdd38647811346">transformGlobalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxildatascalarization-cpp/#ab9bfb7e130ccc022600bc9c1aea8bba0">transformInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a5f39858b5d6d72b92c138916c64c90ba">transformRecipestoEVLRecipes</a>, <a href="/web-llvm/docs/api/classes/llvm/looptraversal/#a87cd9704fc800af5dddb87f26badfb3a">llvm::LoopTraversal::traverse</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerkernelarguments-cpp-/preloadkernelarginfo/#a7a5253091344c2d534f5afd16941e25d">anonymous{AMDGPULowerKernelArguments.cpp}::PreloadKernelArgInfo::tryAllocImplicitArgPreloadSGPRs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp/#aa541e074a612b8ca4a7291a3b0746b7e">tryBuildVectorShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#af4696dcc1ada21996da960c711f26ee1">llvm::LegalizationArtifactCombiner::tryCombineAnyExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armisellowering-cpp/#acbb9ce3311488486de6d14930b30c5ed">TryCombineBaseUpdate</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#aaaa5a895e6a8003daae912a9bf636040">llvm::LegalizationArtifactCombiner::tryCombineExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a16774c131664a3e4cbc7ebc236f49c9e">tryCombineFromSVBoolBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a3eb465a2b7eef72ebd92bf15445c5903">llvm::LegalizationArtifactCombiner::tryCombineInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/artifactvaluefinder/#aba0755f8db842bb12cb51ef2f3977bac">llvm::LegalizationArtifactCombiner::ArtifactValueFinder::tryCombineMergeLike</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a5ccd1c1459e615587ee51ab55dea54bc">llvm::LegalizationArtifactCombiner::tryCombineSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a525b60970cc862aa413d171d805704d4">llvm::LegalizationArtifactCombiner::tryCombineTrunc</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a3cff897f0ed479f872425600e0800701">llvm::LegalizationArtifactCombiner::tryCombineZExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a4394b9bd9afc3ae5f5477e8c265d8b0e">tryConstantFoldCall</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilopbuilder/#a871def99cd40b0a7df2e3f22387198cc">llvm::dxil::DXILOpBuilder::tryCreateOp</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a37fe954e0b01502acccf9b29943e9164">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryEvaluateFunctionsWithArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/lib/target/amdgpu/mctargetdesc/amdgpumcexpr-cpp/#a8ea312e62fba190b14afa1c6cbe79453">tryFoldHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a3140a2195ea3bf00ed638bd5a2a13b35">llvm::LegalizationArtifactCombiner::tryFoldImplicitDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#aac5e465289c9bc7adb88b6b682fdf85b">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66436eae766ca32356bb075ec31ac449">llvm::tryFoldSPUpdateIntoPushPop</a>, <a href="/web-llvm/docs/api/classes/llvm/legalizationartifactcombiner/#a1bc5915736e0e4317a049e55fa502667">llvm::LegalizationArtifactCombiner::tryFoldUnmergeCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#adb1dafd461988f3d8e687eabb99e108d">anonymous{SampleProfile.cpp}::SampleProfileLoader::tryInlineCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvelaneinterleavingpass-cpp/#a9268090caaf5e5a96fa54337cb50f47b">tryInterleave</a>, <a href="/web-llvm/docs/api/structs/anonymous-systemzisellowering-cpp-/generalshuffle/#a00bde9b9e580aea387c2e0456964dbbf">anonymous{SystemZISelLowering.cpp}::GeneralShuffle::tryPrepareForUnpack</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#ae8ee5af33e0f1b85755cf5a1e4951793">tryToElideArgumentCopy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-riscvexpandatomicpseudoinsts-cpp-/#aa167eef8fffa86a11c06e11e5cfbc692">anonymous{RISCVExpandAtomicPseudoInsts.cpp}::tryToFoldBNEOnCmpXchgResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/dagcombiner-cpp/#a1500f3720744fec61e14c6b3c3b5477f">tryToFoldExtendOfConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa6739b4a0bc5d6540e53c1688aefeed4">llvm::InstCombinerImpl::tryToSinkInstructionDbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad4296b2b81379548b300c4676f0d2125">llvm::InstCombinerImpl::tryToSinkInstructionDbgVariableRecords</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#ac48731694e324e56e35cb2b4f20345d0">tryToVectorizeSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/mcdc/tvidxbuilder/#a85f4860524d04ca3d92dae7f5b1a9fba">llvm::coverage::mcdc::TVIdxBuilder::TVIdxBuilder</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmtypecheck/#ad05058e6bb44815e9906be40ff6bb88d">llvm::WebAssemblyAsmTypeCheck::typeCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/inteqclasses/#aa63616e3405270095cb5020333fe06b4">llvm::IntEqClasses::uncompress</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a755fb78188a206380ebf96d5211b1696">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a768c85ec7c5044117192b9fc18395231">llvm::X86InstrInfo::unfoldMemoryOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuglobaliselutils-cpp/#a77201c8a4e20790e0e3a45b9e4b02d22">unmergeReadAnyLane</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a5e2b7ac5f48193117a340aa15b085719">llvm::OpenMPIRBuilder::unrollLoopPartial</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a305a3a4874c597243cd5ba04af01339e">llvm::SelectionDAG::UnrollVectorOp</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a5a8d860cc5c733afd761c1e292b5a0aa">llvm::SelectionDAG::UnrollVectorOverflowOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyisellowering-cpp/#a57e07229bb762532f34ea34c656dc6eb">unrollVectorShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#a775d8b54712dddd880b29ca02e8f1ee6">anonymous{StructuralHash.cpp}::StructuralHashImpl::update</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/cgsccpassmanager-cpp/#a490117b63072462d035a6933fdb94c1f">updateCGAndAnalysisManagerForPass</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a776852734c11ae705971ee8d39e589c6">llvm::AArch64RegisterInfo::UpdateCustomCalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortreebase/#a83fe54fc062eda7c1086493dd4155f8a">llvm::DominatorTreeBase&lt; BlockT, false &gt;::updateDFSNumbers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ab2e6fc08d8f586e4979511620c12ffa8">updateDVIWithLocations</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignfloating/#a0206ea336f22470d5fe01f65dae9eb85">anonymous{AttributorAttributes.cpp}::AAAlignFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgescallsite/#a827970be0131200af76c14c9e1a24b15">anonymous{AttributorAttributes.cpp}::AACallEdgesCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceablefloating/#a41c5ffc9c348c806bd197076e245aa1a">anonymous{AttributorAttributes.cpp}::AADereferenceableFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaglobalvalueinfofloating/#ad2836a92e1e5443f5318dc46446a9197">anonymous{AttributorAttributes.cpp}::AAGlobalValueInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a6aaeb440ac0f45225f89b6b83444db1a">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofpclassfloating/#a9c2d1fb920f390ee52852043fb2a2741">anonymous{AttributorAttributes.cpp}::AANoFPClassFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/windowscheduler/#a94fa9430a250a99da03c75e55f605349">llvm::WindowScheduler::updateLiveIntervals</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/prologepiloginserter-cpp/#ab462c5bbf745633740ccfb2920040000">updateLiveness</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a35a60230fc7fed1d9eca1f2a89098364">updateLoopMetadataDebugLocationsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a6eb3ac91456a9880aecf25dc8e3cbaa5">updatePhysDepsDownwards</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinetracemetrics-cpp/#a79107186b863ddb50f8bfdb721aa41d8">updatePhysDepsUpwards</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a26d6acb7d8248e5d25f190b5d8fecbd3">llvm::JumpThreadingPass::updateSSA</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a11a3a1f0710cf8260033c8eb18800175">llvm::DwarfCompileUnit::updateSubprogramScopeDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#a5d85b8fd4787153b0ade229c616b7562">ValidateMVEStore</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#ab5464b66f7393d7dbd8c601305cdbc0b">llvm::HexagonShuffler::ValidResourceUsage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf8d332ecf62a0b283e3795bdbd45d79">llvm::valTypesFromMVTs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a406d93c10bd410f7ef8af5c00b037b8b">valueIsOnlyUsedLocallyOrStoredToOneGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a1fad5ec2eef05d1c11eec0ee147eabab">vectorToScalarBitmask</a>, <a href="/web-llvm/docs/api/classes/llvm/genericconvergenceverifier/#aa4780afea204d004b4ce95dd76dbca7f">llvm::GenericConvergenceVerifier&lt; ContextT &gt;::verify</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a066fd5533813e5df6d52cb59fc8afd4e">llvm::dwarf_linker::parallel::DependencyTracker::verifyKeepChain</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#a6dcb5e3d63691e83e0fdc0d67148077a">llvm::MemorySSA::verifyOrderingDominationAndDefUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a49a46654ca2c32ce99be52de089052f8">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Visit</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#afd8404fba4a01a50928ea2d51954afb7">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::visit</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxtype/#ac270a700d1efd59267c89e1539ff7e3e">anonymous{X86LowerAMXType.cpp}::X86LowerAMXType::visit</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ae8ee3aa50e72940cabb7d758613ce2cf">llvm::SCEVDivision::visitAddExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a1cbb1fa4211e94aed86925b13569004a">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitBinaryOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a18b0f192065386f9e0bc793a08bbf3ff">visitDomSubTree</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aee075a4b7e853e004ad694f7ef959f28">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a679f36556ace611ccc56580cb497973a">llvm::InstCombinerImpl::visitExtractValueInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a22bc54f319e33d248b169116b757a143">llvm::InstCombinerImpl::visitGEPOfGEP</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a32bd3fc6040488f54b8fb322216218a5">DataScalarizerVisitor::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxasmprinter-cpp/#ab0cd64194576d6d882ceabaf9b3a2c29">VisitGlobalVariableForEmission</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7af99fa2202fcc7db245865dd1bcec1f">llvm::InstCombinerImpl::visitLandingPadInst</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#afab4a1d0e1f34b286eec49ac8bd96ef1">llvm::SCEVDivision::visitMulExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a99bbdbd6641e69bcad8fda4bf1726525">visitPointers</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/#a778d0494c2f8dec95d60160b1ce89a07">llvm::LazyCallGraph::visitReferences</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#ad71ead87ca8f3fc5edfb6173a970f792">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitStoreInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvemitintrinsics-cpp-/spirvemitintrinsics/#a4a4171890acb275f5a66288e91a8d5ca">anonymous{SPIRVEmitIntrinsics.cpp}::SPIRVEmitIntrinsics::visitSwitchInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86volatiletiledata/#aeb433ec9d181eb8f489c857b23c55535">anonymous{X86LowerAMXType.cpp}::X86VolatileTileData::volatileTileData</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86volatiletiledata/#a4f767b83cb14d5a70423c68254648c18">anonymous{X86LowerAMXType.cpp}::X86VolatileTileData::volatileTilePHI</a>, <a href="/web-llvm/docs/api/structs/anonymous-tailrecursionelimination-cpp-/allocaderivedvaluetracker/#adf48fa3a2373efca5ac054e8bff29b20">anonymous{TailRecursionElimination.cpp}::AllocaDerivedValueTracker::walk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac8b7bc9bbc4a3cf2bca60932ff2d582e">llvm::widenShuffleMaskElts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4373d3025961c2c2eeca56b02d7d009d">llvm::widenShuffleMaskElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#abe0c2621dfb4c1e6bcfbaddc38fdf572">widenVectorOpsToi8</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600machinecfgstructurizer-cpp-/r600machinecfgstructurizer/#a23b20ed1597d31f0d73ce282f0db4db6">anonymous{R600MachineCFGStructurizer.cpp}::R600MachineCFGStructurizer::wrapup</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdxbc/signature/#a608616d2779ddc0d1ca2669b17119ba2">llvm::mcdxbc::Signature::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/elf/binarywriter/#ac4946ac3df4a88e078136a4444ef1185">llvm::objcopy::elf::BinaryWriter::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a0850c8a2472500d4a79b9f48495a1d2f">writeFunctionHeapProfileRecords</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#af9d2c5b5d2afb86f9cdaef1946b79f6c">llvm::object::writeImportLibrary</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a27e478bd5208561e8eb16ec550509761">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeObject</a>, <a href="/web-llvm/docs/api/classes/llvm/dxcontainerobjectwriter/#aab937b67cb92336a4c82aeae0b8ccbf5">llvm::DXContainerObjectWriter::writeObject</a>, <a href="/web-llvm/docs/api/classes/anonymous-gcovprofiling-cpp-/gcovblock/#a3787e4ce279b3a05f9b758b63cee5165">anonymous{GCOVProfiling.cpp}::GCOVBlock::writeOut</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#ad8b12ebb23f57815dfdaa7a14562aa5f">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::writePerModuleGlobalValueSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/dxil/dxilbitcodewriter/#a56bf1b8486ba52a5e85a2613e8e10c52">llvm::dxil::DXILBitcodeWriter::writeStringRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#ad375d674219d643fe0ba85db2b7f172a">writeStringRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a2a76e869a218e271ec68f8a68968fde2">llvm::InstrProfWriter::writeText</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a0fcb5b0c8740137c1ba7ea67bc4e1986">writeTypeIdCompatibleVtableSummaryRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#ac5a65c8b873ba60af3d6927d70551cc4">writeTypeIdSummaryRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#ae4770e119c132809f74cc6faaf62698e">writeWholeProgramDevirtResolution</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp/#a96b4150a46b836d772425ab620d97e23">writeWholeProgramDevirtResolutionByArg</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a5d9383a7827bb76858af4b9dd1a7e0ee">llvm::LLVMContextImpl::~LLVMContextImpl</a>.</p>

</div>
</div>

### push\_back() {#adf31f040a01939eb7f7b085e5dfc0485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back (T &amp;&amp; Elt)</td>
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



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#aeab77382e7ca9b451524424e268ff264">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::reserveForParamAndGetAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#acf1bb6ad9c13f32082c4e3b1272522fd">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::set_size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### grow() {#adf23f35638753badb423928a21b2a561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateBase&lt; T, TriviallyCopyable &gt;::grow (size_t MinSize=0)</td>
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

<p>Grow the allocated memory (without initializing new elements), doubling the size of the allocated memory.</p>


<p>Guarantees space for at least one more element, or MinSize more elements if specified.</p>


<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="#a3642c7a4a7c63961ed43b855b2f65369">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::mallocForGrow</a>, <a href="#a06264674191b53ea377acb0fbf98c80b">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::moveElementsForGrow</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#aa653aeaa776bdaa3656d01a2198d99fd">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::takeAllocationForGrow</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#aa671e144c1a4aa0196cf9333fc17054d">llvm::SmallVectorTemplateBase&lt; T, true &gt;::growAndAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad39bccc86684b3407edcd580b5a38143">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#adfc4e95670f6dd96a86182e51411d47b">llvm::SmallVectorImpl&lt; T &gt;::operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::const_iterator&lt; MemoryLocation &gt;::reserve</a>.</p>

</div>
</div>

### growAndAssign() {#ab6cf8f5418ae17302373eb658de2c4a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateBase&lt; T, bool &gt;::growAndAssign (size_t NumElts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Elt)</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#a2d25f6f9379888156d4dc87f0c70a0da">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::destroy_range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#a3642c7a4a7c63961ed43b855b2f65369">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::mallocForGrow</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#acf1bb6ad9c13f32082c4e3b1272522fd">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::set_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#aa653aeaa776bdaa3656d01a2198d99fd">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::takeAllocationForGrow</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::const_iterator&lt; MemoryLocation &gt;::assign</a>.</p>

</div>
</div>

### growAndEmplaceBack() {#af0de1c3bdac42cb94cca3cce185c3d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... ArgTypes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T &amp; llvm::SmallVectorTemplateBase&lt; T, bool &gt;::growAndEmplaceBack (ArgTypes &amp;&amp;... Args)</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#acd9e771a3296c6b24146955754620557">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::back</a>, <a href="#a3642c7a4a7c63961ed43b855b2f65369">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::mallocForGrow</a>, <a href="#a06264674191b53ea377acb0fbf98c80b">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::moveElementsForGrow</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#acf1bb6ad9c13f32082c4e3b1272522fd">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::set_size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#aa653aeaa776bdaa3656d01a2198d99fd">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::takeAllocationForGrow</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::const_iterator&lt; MemoryLocation &gt;::emplace_back</a>.</p>

</div>
</div>

### mallocForGrow() {#a3642c7a4a7c63961ed43b855b2f65369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * llvm::SmallVectorTemplateBase&lt; T, TriviallyCopyable &gt;::mallocForGrow (size_t MinSize, size_t &amp; NewCapacity)</td>
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

<p>Create a new allocation big enough for <span class="doxyComputerOutput">MinSize</span> and pass back its size in <span class="doxyComputerOutput">NewCapacity</span>.</p>


<p>This is the first section of <em><a href="#adf23f35638753badb423928a21b2a561">grow()</a></em>.</p>


<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#aff209a96323a14068980fd74f1fa53df">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::getFirstEl</a>, <a href="#a3642c7a4a7c63961ed43b855b2f65369">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::mallocForGrow</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#adf23f35638753badb423928a21b2a561">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::grow</a>, <a href="#ab6cf8f5418ae17302373eb658de2c4a5">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::growAndAssign</a>, <a href="#af0de1c3bdac42cb94cca3cce185c3d8a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::growAndEmplaceBack</a> and <a href="#a3642c7a4a7c63961ed43b855b2f65369">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::mallocForGrow</a>.</p>

</div>
</div>

### moveElementsForGrow() {#a06264674191b53ea377acb0fbf98c80b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateBase&lt; T, TriviallyCopyable &gt;::moveElementsForGrow (T * NewElts)</td>
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

<p>Move existing elements over to the new allocation <span class="doxyComputerOutput">NewElts</span>, the middle section of <em><a href="#adf23f35638753badb423928a21b2a561">grow()</a></em>.</p>

<p>Definition at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#a2d25f6f9379888156d4dc87f0c70a0da">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::destroy_range</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#acc3e8839b34bcff67f0b39624e0d99ee">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::uninitialized_move</a>.</p>


<p>Referenced by <a href="#adf23f35638753badb423928a21b2a561">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::grow</a> and <a href="#af0de1c3bdac42cb94cca3cce185c3d8a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::growAndEmplaceBack</a>.</p>

</div>
</div>

### reserveForParamAndGetAddress() {#aeab77382e7ca9b451524424e268ff264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * llvm::SmallVectorTemplateBase&lt; T, bool &gt;::reserveForParamAndGetAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; Elt, size_t N=1)</td>
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

<p>Reserve enough space to add one element, and return the updated element pointer in case it was a reference to the storage.</p>

<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a4ff60fb0f0d249b4623327ef5976867b">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::reserveForParamAndGetAddressImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#acf1f3ec6174852d235b520ae37b9a13c">llvm::const_iterator&lt; MemoryLocation &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a520e903dce9cfbdd0d1073fe447ce52e">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>, <a href="#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#adf31f040a01939eb7f7b085e5dfc0485">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#a4cd364a560035d8414c3b21b2513b0d4">llvm::SmallVectorTemplateBase&lt; T, true &gt;::push_back</a>.</p>

</div>
</div>

### reserveForParamAndGetAddress() {#a89ccedcf373b03d6e115d8b5e56ccebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * llvm::SmallVectorTemplateBase&lt; T, bool &gt;::reserveForParamAndGetAddress (T &amp; Elt, size_t N=1)</td>
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

<p>Reserve enough space to add one element, and return the updated element pointer in case it was a reference to the storage.</p>

<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a4ff60fb0f0d249b4623327ef5976867b">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::reserveForParamAndGetAddressImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### takeAllocationForGrow() {#aa653aeaa776bdaa3656d01a2198d99fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateBase&lt; T, TriviallyCopyable &gt;::takeAllocationForGrow (T * NewElts, size_t NewCapacity)</td>
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

<p>Transfer ownership of the allocation, finishing up <em><a href="#adf23f35638753badb423928a21b2a561">grow()</a></em>.</p>

<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a02335466a102901ccd2e0d4a29af8910">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::isSmall</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorbase/#a435b1238f81c19cd3bd557fe9af58ed9">llvm::SmallVectorBase&lt; SmallVectorSizeType&lt; T &gt; &gt;::set_allocation_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#adf23f35638753badb423928a21b2a561">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::grow</a>, <a href="#ab6cf8f5418ae17302373eb658de2c4a5">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::growAndAssign</a> and <a href="#af0de1c3bdac42cb94cca3cce185c3d8a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::growAndEmplaceBack</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### destroy\_range() {#a2d25f6f9379888156d4dc87f0c70a0da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateBase&lt; T, bool &gt;::destroy_range (T * S, T * E)</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a38c50aa8e3e9588f4f968c2e03a0cee0">llvm::const_iterator&lt; MemoryLocation &gt;::assign</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a6aed977bf8ca76ee498836d1fe4cedb6">llvm::const_iterator&lt; MemoryLocation &gt;::assignRemote</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::const_iterator&lt; MemoryLocation &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aa3787c69a41c14127758c359911180aa">llvm::const_iterator&lt; MemoryLocation &gt;::erase</a>, <a href="#ab6cf8f5418ae17302373eb658de2c4a5">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::growAndAssign</a>, <a href="#a06264674191b53ea377acb0fbf98c80b">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::moveElementsForGrow</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector/#acd1bf4a3cc2b247cdeac15790a9e6a1e">llvm::SmallVector&lt; BitWord &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad39bccc86684b3407edcd580b5a38143">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#adfc4e95670f6dd96a86182e51411d47b">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aae26f659b722d1d053b93b5f1735f52f">llvm::const_iterator&lt; MemoryLocation &gt;::truncate</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvector/#a548541a1080f84a4dbde718332e55ba5">llvm::SmallVector&lt; BitWord &gt;::~SmallVector</a>.</p>

</div>
</div>

### forward\_value\_param() {#a1f39a810459dda7c8ca8392b4f1d2ab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T &amp;&amp; llvm::SmallVectorTemplateBase&lt; T, bool &gt;::forward_value_param (T &amp;&amp; V)</td>
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



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#af622128e353515efebccad40eae495cb">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>.</p>

</div>
</div>

### forward\_value\_param() {#abf9c4d6c822e662181d0bd6c5920c455}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T &amp; llvm::SmallVectorTemplateBase&lt; T, bool &gt;::forward_value_param (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; V)</td>
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



<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### uninitialized\_copy() {#a0ba61356fc2c8d9c14fe55d069a0d648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename It1, typename It2&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateBase&lt; T, bool &gt;::uninitialized_copy (It1 I, It1 E, It2 Dest)</td>
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

<p>Copy the range [I, E) onto the uninitialized memory starting with "Dest", constructing elements as needed.</p>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::const_iterator&lt; MemoryLocation &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a59fd5e59ca0c03b061035a6c9de2b39c">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad39bccc86684b3407edcd580b5a38143">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#abd962b7b01f49ce61ea41ee10c49e313">llvm::SmallVectorImpl&lt; T &gt;::swap</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase-d7d249fb8bb1e1b13d21e8212052041a/#a0cafa3478518c4efd802d20a275df803">llvm::SmallVectorTemplateBase&lt; T, true &gt;::uninitialized_move</a>.</p>

</div>
</div>

### uninitialized\_move() {#acc3e8839b34bcff67f0b39624e0d99ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename It1, typename It2&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SmallVectorTemplateBase&lt; T, bool &gt;::uninitialized_move (It1 I, It1 E, It2 Dest)</td>
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

<p>Move the range [I, E) into the uninitialized memory starting with "Dest", constructing elements as needed.</p>

<p>Definition at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a59fd5e59ca0c03b061035a6c9de2b39c">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a520e903dce9cfbdd0d1073fe447ce52e">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>, <a href="#a06264674191b53ea377acb0fbf98c80b">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::moveElementsForGrow</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#adfc4e95670f6dd96a86182e51411d47b">llvm::SmallVectorImpl&lt; T &gt;::operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### TakesParamByValue {#a3b2b6193837d9e9f181627f194985267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, bool = (std::is_trivially_copy_constructible&lt;T&gt;::value) &amp;&amp; (std::is_trivially_move_constructible&lt;T&gt;::value) &amp;&amp; std::is_trivially_destructible&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SmallVectorTemplateBase&lt; T, bool &gt;::TakesParamByValue = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">SmallVector.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a520e903dce9cfbdd0d1073fe447ce52e">llvm::const_iterator&lt; MemoryLocation &gt;::insert</a>.</p>

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
