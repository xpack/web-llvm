---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/missingtraits
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `missingTraits` Struct Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename T, typename Context&gt;
struct llvm::yaml::missingTraits&lt;T, Context&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::integral_constant&lt; bool, !has_ScalarEnumerationTraits&lt; T &gt;::value &amp;&amp;!has_ScalarBitSetTraits&lt; T &gt;::value &amp;&amp;!has_ScalarTraits&lt; T &gt;::value &amp;&amp;!has_BlockScalarTraits&lt; T &gt;::value &amp;&amp;!has_TaggedScalarTraits&lt; T &gt;::value &amp;&amp;!has_MappingTraits&lt; T, Context &gt;::value &amp;&amp;!has_SequenceTraits&lt; T &gt;::value &amp;&amp;!has_CustomMappingTraits&lt; T &gt;::value &amp;&amp;!has_DocumentListTraits&lt; T &gt;::value &amp;&amp;!has_PolymorphicTraits&lt; T &gt;::value &gt;</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
