---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/yaml/io
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IO` Class



## Declaration

<div class="doxyDeclaration">
class llvm::yaml::IO { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">llvm/Support/YAMLTraits.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/input">Input</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/yaml/input">Input</a> class is used to parse a yaml document into in-memory structs and vectors. <a href="/web-llvm/docs/api/classes/llvm/yaml/input/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/yaml/output">Output</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/yaml/output">Output</a> class is used to generate a yaml document from in-memory structs and vectors. <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a69e8083e27fcd02a6573b3d648f8d">IO</a> (void *Ctxt=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44861ff225d351615179f0f24cb8d7f6">~IO</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f9abe4cc7cc808cb6025ed882bcbb7d">outputting</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7606d9073cec3c4258e965ccd8827766">beginSequence</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75123fbfb5cd9f7a0d4b1609adb21b79">preflightElement</a> (unsigned, void *&amp;)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e4053aaf4164b5b2b6cc0db618d4c4c">postflightElement</a> (void *)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1782a23b031d87cc94d10da1952094e6">endSequence</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0036ce961c87517653c815a8c219cc42">canElideEmptySequence</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40361f81f3a6b8982e20531e1349e708">beginFlowSequence</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf1e34d55c27fb21a58001b473f5a37a">preflightFlowElement</a> (unsigned, void *&amp;)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0784e00190e5d6bd871eecf099ffce6e">postflightFlowElement</a> (void *)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bfd0a4269a738cbedca0c48d9b02091">endFlowSequence</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48aefe64f43e923bdcaddcc2ea3eaf0c">mapTag</a> (StringRef Tag, bool Default=false)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58c7948b7ff9af875b80da34cd9bf0ba">beginMapping</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e90d28d3637f28d8d217a65f9bdeff0">endMapping</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd531806848796190ff4d06de6fac044">preflightKey</a> (const char *, bool, bool, bool &amp;, void *&amp;)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae7af838aa2a9d5cc45d90bc4b03b50a">postflightKey</a> (void *)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1ca4f897adb4845e0f5456540bbdc7b">keys</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac67d3ebb9431543cd9cb5902d3da3b27">beginFlowMapping</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab68bc8ef2a0be572df29977bcbf830eb">endFlowMapping</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a6a43d15012c805a384c43c9113312a">beginEnumScalar</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7de66f027ae46a8654fffdb2b785ea95">matchEnumScalar</a> (const char *, bool)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad860aaca596742002904ee7bbf316a03">matchEnumFallback</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29ae0ad5bf678770c2c64cef6efb9532">endEnumScalar</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad455644379fb5d07ae27b6cd69e3c567">beginBitSetScalar</a> (bool &amp;)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a953aeebd71524f02d96ae78ffb9c3843">bitSetMatch</a> (const char *, bool)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0feb972994c2a6bb5cdd9447dab65c7">endBitSetScalar</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a38e6ed5f6a97b39548f7c7d09f3714">scalarString</a> (StringRef &amp;, QuotingType)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad760801f423112b2768ba40cb0006048">blockScalarString</a> (StringRef &amp;)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad841c6d5843b30251e2b871bb25d1e2c">scalarTag</a> (std::string &amp;)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a388c981224806a01d8de4172d5322d3d">NodeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c1fbf5f364c6ea410467c08ba59cc5">getNodeKind</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a930906994b5dc96a35696936fe705c15">setError</a> (const Twine &amp;)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80d90bfd4320ba8fab1652f723724220">error</a> ()=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ae9ac11c898a51356d250572fefcdb8">setAllowUnknownKeys</a> (bool Allow)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ade062563b4463f8f0f8fe1f2f56a0b2e">enumCase</a> (T &amp;Val, const char *Str, const T ConstVal)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9aecc50bd75a5c7bfd968714c5fda955">enumCase</a> (T &amp;Val, const char *Str, const uint32_t ConstVal)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FBT, typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac656ce8032e2f91b5320566fde65dba1">enumFallback</a> (T &amp;Val)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b1cefca27a7a232f423b506994e1761">bitSetCase</a> (T &amp;Val, const char *Str, const T ConstVal)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a245f9ba1195df0e9b09e606d6907e325">bitSetCase</a> (T &amp;Val, const char *Str, const uint32_t ConstVal)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0f5f896777fd657ea3616bffb395c7b0">maskedBitSetCase</a> (T &amp;Val, const char *Str, T ConstVal, T Mask)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a62234ee099d9ced6fc2eb528d23a9f5f">maskedBitSetCase</a> (T &amp;Val, const char *Str, uint32_t ConstVal, uint32_t Mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9602206972cc02cc749acfca45487271">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13c50e14628f82f4e0853bfef8ebddd1">setContext</a> (void *)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76b59883a4b23c1cb5c5f55eac119f0d">mapRequired</a> (const char *Key, T &amp;Val)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename Context&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4995c1d3cda7a94e8dc0df1230f4abd6">mapRequired</a> (const char *Key, T &amp;Val, Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27dee5b4ee79b39bc614889a4186bbf5">mapOptional</a> (const char *Key, T &amp;Val)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename DefaultT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae9ca4bb0cca2cc006c3c29fc0d9c109d">mapOptional</a> (const char *Key, T &amp;Val, const DefaultT &amp;Default)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename Context&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1407aaef6dfdc3eef37f9d9c4d5379f3">mapOptionalWithContext</a> (const char *Key, T &amp;Val, Context &amp;Ctx) -&gt; std::enable_if_t&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/has-sequencetraits">has_SequenceTraits</a>&lt; T &gt;::value, void &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename Context&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae8b7b8d8ebd2ace3bc51631229a465da">mapOptionalWithContext</a> (const char *Key, std::optional&lt; T &gt; &amp;Val, Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename Context&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afc380816d3af033375acc783cb3f9239">mapOptionalWithContext</a> (const char *Key, T &amp;Val, Context &amp;Ctx) -&gt; std::enable_if_t&lt;!<a href="/web-llvm/docs/api/structs/llvm/yaml/has-sequencetraits">has_SequenceTraits</a>&lt; T &gt;::value, void &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename Context, typename DefaultT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afd9a22f6dc3465b6f4c0fdaecc6afc17">mapOptionalWithContext</a> (const char *Key, T &amp;Val, const DefaultT &amp;Default, Context &amp;Ctx)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename Context&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a435c6acbe5dc9ee162525d5aafb92ea4">processKeyWithDefault</a> (const char *Key, std::optional&lt; T &gt; &amp;Val, const std::optional&lt; T &gt; &amp;DefaultValue, bool Required, Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename Context&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7892b4697e8187f6ff4d9fc1d6cd8205">processKeyWithDefault</a> (const char *Key, T &amp;Val, const T &amp;DefaultValue, bool Required, Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, typename Context&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad8eb050745796eca52c54d9399a01d8a">processKey</a> (const char *Key, T &amp;Val, bool Required, Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7fd504435fef4f3eae05e0f2359bc94">Ctxt</a></td>
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


<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IO() {#af6a69e8083e27fcd02a6573b3d648f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IO::IO (void * Ctxt=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/yaml/input/#a7ce204b21e8b3fcedb406b542ba72a48">llvm::yaml::Input::Input</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/input/#a86258e41539d20c5f42e0d0d91a0dc4b">llvm::yaml::Input::Input</a> and <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#a1413b0510ed00e919f44f307422e54a5">llvm::yaml::Output::Output</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~IO() {#a44861ff225d351615179f0f24cb8d7f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IO::~IO ()</td>
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



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### beginBitSetScalar() {#ad455644379fb5d07ae27b6cd69e3c567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::yaml::IO::beginBitSetScalar (bool &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a4ba3a0874e73b8628af755dd0a13ce31">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### beginEnumScalar() {#a7a6a43d15012c805a384c43c9113312a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::beginEnumScalar ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a315c7135a7dd2656de0c8bdb497c5116">llvm::yaml::yamlize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ad3e98f0d068b418a4d8547fff1864c3f">llvm::yaml::yamlizeMappingEnumInput</a>.</p>

</div>
</div>

### beginFlowMapping() {#ac67d3ebb9431543cd9cb5902d3da3b27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::beginFlowMapping ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 803 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a64bede48cd18859ff82b9eabca55ef50">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### beginFlowSequence() {#a40361f81f3a6b8982e20531e1349e708}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::yaml::IO::beginFlowSequence ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a825281c7367bc1781088c59974fc87e4">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### beginMapping() {#a58c7948b7ff9af875b80da34cd9bf0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::beginMapping ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a64bede48cd18859ff82b9eabca55ef50">llvm::yaml::yamlize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a9b2287bff14bbe0d31a7972882b9164a">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### beginSequence() {#a7606d9073cec3c4258e965ccd8827766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::yaml::IO::beginSequence ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a825281c7367bc1781088c59974fc87e4">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### bitSetCase() {#a2b1cefca27a7a232f423b506994e1761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::bitSetCase (T &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T ConstVal)</td>
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



<p>Definition at line 852 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="#a953aeebd71524f02d96ae78ffb9c3843">bitSetMatch</a>, <a href="#a3f9abe4cc7cc808cb6025ed882bcbb7d">outputting</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarbitsettraits-993672d22acaaab6ee27cb233dd69975/#a196ffdbe53062ebd6b7e76b8bb3000d0">llvm::yaml::ScalarBitSetTraits&lt; TBDFlags &gt;::bitset</a>.</p>

</div>
</div>

### bitSetCase() {#a245f9ba1195df0e9b09e606d6907e325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::bitSetCase (T &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t ConstVal)</td>
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



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="#a953aeebd71524f02d96ae78ffb9c3843">bitSetMatch</a>, <a href="#a3f9abe4cc7cc808cb6025ed882bcbb7d">outputting</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### bitSetMatch() {#a953aeebd71524f02d96ae78ffb9c3843}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::yaml::IO::bitSetMatch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, bool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 812 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="#a2b1cefca27a7a232f423b506994e1761">bitSetCase</a>, <a href="#a245f9ba1195df0e9b09e606d6907e325">bitSetCase</a>, <a href="#a0f5f896777fd657ea3616bffb395c7b0">maskedBitSetCase</a> and <a href="#a62234ee099d9ced6fc2eb528d23a9f5f">maskedBitSetCase</a>.</p>

</div>
</div>

### blockScalarString() {#ad760801f423112b2768ba40cb0006048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::blockScalarString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 816 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a1e5c76544c98f93394c90bccf4d4de9d">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### canElideEmptySequence() {#a0036ce961c87517653c815a8c219cc42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::yaml::IO::canElideEmptySequence ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="#a1407aaef6dfdc3eef37f9d9c4d5379f3">mapOptionalWithContext</a>.</p>

</div>
</div>

### endBitSetScalar() {#ae0feb972994c2a6bb5cdd9447dab65c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::endBitSetScalar ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a4ba3a0874e73b8628af755dd0a13ce31">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### endEnumScalar() {#a29ae0ad5bf678770c2c64cef6efb9532}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::endEnumScalar ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a315c7135a7dd2656de0c8bdb497c5116">llvm::yaml::yamlize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ad3e98f0d068b418a4d8547fff1864c3f">llvm::yaml::yamlizeMappingEnumInput</a>.</p>

</div>
</div>

### endFlowMapping() {#ab68bc8ef2a0be572df29977bcbf830eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::endFlowMapping ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a64bede48cd18859ff82b9eabca55ef50">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### endFlowSequence() {#a4bfd0a4269a738cbedca0c48d9b02091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::endFlowSequence ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a825281c7367bc1781088c59974fc87e4">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### endMapping() {#a6e90d28d3637f28d8d217a65f9bdeff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::endMapping ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a64bede48cd18859ff82b9eabca55ef50">llvm::yaml::yamlize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a9b2287bff14bbe0d31a7972882b9164a">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### endSequence() {#a1782a23b031d87cc94d10da1952094e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::endSequence ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a825281c7367bc1781088c59974fc87e4">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### enumCase() {#ade062563b4463f8f0f8fe1f2f56a0b2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::enumCase (T &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T ConstVal)</td>
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



<p>Definition at line 826 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="#a7de66f027ae46a8654fffdb2b785ea95">matchEnumScalar</a>, <a href="#a3f9abe4cc7cc808cb6025ed882bcbb7d">outputting</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-69929af6cb0f628c9906d0c2676a45ca/#a84a788bb26e6bc5582f3caf1ef2f87fe">llvm::yaml::ScalarEnumerationTraits&lt; AccessQualifier &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-c3f0627b2d0b2102223da86415647a5e/#a19ed14a12e569dc2a4185e49176ff73f">llvm::yaml::ScalarEnumerationTraits&lt; AddressSpaceQualifier &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-10ef208f3d63d089cbcc9d4b50f9af34/#aac7f7cf222c7382eba3bf50131f8d364">llvm::yaml::ScalarEnumerationTraits&lt; AMXProgModelEnum &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-f153b28368f6ef8adf9af0478c703e5e/#a5ccd35b5b020b4c4a34623a2a5e59e57">llvm::yaml::ScalarEnumerationTraits&lt; COFFYAML::COMDATType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-563ea2a03de3562c3bbf4300620f3cb7/#a5bff560ce7d8158439fee24717b5393b">llvm::yaml::ScalarEnumerationTraits&lt; COFFYAML::WeakExternalCharacteristics &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-8fb8b57592e4588457ac6f7bdf4d36ab/#afa131c31486c50c63d43be15bb447f66">llvm::yaml::ScalarEnumerationTraits&lt; FixedMachineStackObject::ObjectType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-7b9e6a6903edfdcf1f6beb970b564541/#ac940d0eec4c6144d822383e4b5b13181">llvm::yaml::ScalarEnumerationTraits&lt; IFSSymbolType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-6c436b1618a02cc24d12fe47a209589a/#a9c334072251349baee0519d00270589a">llvm::yaml::ScalarEnumerationTraits&lt; MachineJumpTableInfo::JTEntryKind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-01feb6d5da899885ae2848d0d62efe34/#ac7a2acebc523320338286959779ca069">llvm::yaml::ScalarEnumerationTraits&lt; MachineStackObject::ObjectType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-94c7e519dd2a8039d05ccfd3fb97e482/#a03080ad70d90c892572399a4a49f4924">llvm::yaml::ScalarEnumerationTraits&lt; TargetStackID::Value &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-cb982a4278d633df1fa7e595287fbea4/#a86215a20af284803dc8a59e5599fe407">llvm::yaml::ScalarEnumerationTraits&lt; TypeTestResolution::Kind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-fe1e7f03e5f9aec4973cd7f04de657ff/#a3deea300be0c33a80a9c047ff87b1efb">llvm::yaml::ScalarEnumerationTraits&lt; ValueKind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-4262e13cde8e51594115a897d5fb2957/#a7e32f08f244871eb8f62b81745f2c04f">llvm::yaml::ScalarEnumerationTraits&lt; ValueType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-85e7c71b9d2f031a9eccdddedc4edff0/#ada281d0854d77dab9efdbb484c3680be">llvm::yaml::ScalarEnumerationTraits&lt; WholeProgramDevirtResolution::ByArg::Kind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-ab2365c220ee82b5427b4643d8d93868/#af19382e70e2902d46d03b51e881f31ae">llvm::yaml::ScalarEnumerationTraits&lt; WholeProgramDevirtResolution::Kind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-1aaa53c6453c4dbce93aac46dbbc846f/#a22eec2426c6e02dbe8a1f81c6c409c4c">llvm::yaml::ScalarEnumerationTraits&lt; xray::RecordTypes &gt;::enumeration</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-bcfc4ec6a379303ccd103c5ceab89b03/#a0163c05f1cbadc6cd96a7d2f045d792c">llvm::yaml::ScalarEnumerationTraits&lt; xray::SledEntry::FunctionKinds &gt;::enumeration</a>.</p>

</div>
</div>

### enumCase() {#a9aecc50bd75a5c7bfd968714c5fda955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::enumCase (T &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t ConstVal)</td>
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



<p>Definition at line 834 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="#a7de66f027ae46a8654fffdb2b785ea95">matchEnumScalar</a>, <a href="#a3f9abe4cc7cc808cb6025ed882bcbb7d">outputting</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### enumFallback() {#ac656ce8032e2f91b5320566fde65dba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FBT, typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::enumFallback (T &amp; Val)</td>
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



<p>Definition at line 841 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="#ad860aaca596742002904ee7bbf316a03">matchEnumFallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a315c7135a7dd2656de0c8bdb497c5116">llvm::yaml::yamlize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-94e8e447f390dd6b82d280bca04ba962/#ac64b020141a4a6671d1c41f77a75bc02">llvm::yaml::ScalarEnumerationTraits&lt; MachO::BindOpcode &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-c8c492424b6b376facd083c58ff62739/#a4c4c1f9808b43043ed0178afe8dfcf78">llvm::yaml::ScalarEnumerationTraits&lt; MachO::LoadCommandType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-535fd44a5daab6c6897d34135e2af96b/#ab6cebb6941744e5b218338aac929f6f4">llvm::yaml::ScalarEnumerationTraits&lt; MachO::RebaseOpcode &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-83c78b24ee4d0d13494c64d4d4cade21/#a5c9ec931b10650f5151ed4b47a18c7b9">llvm::yaml::ScalarEnumerationTraits&lt; object::ImageKind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-52748f3f5fc9dcda07f1b515b337b87f/#aa0ce64bd19b2715b33951eaf75802bdd">llvm::yaml::ScalarEnumerationTraits&lt; object::OffloadKind &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-17eba4c8aa8e438ae8d3e218f98c9403/#a0a014903a32f145516aa7fb2b5e7cf73">llvm::yaml::ScalarEnumerationTraits&lt; WasmYAML::RelocType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-f198651d9f0383590aef569382e0fdcb/#a4da318299c6766c9c7f2ee6210228361">llvm::yaml::ScalarEnumerationTraits&lt; XCOFF::DwarfSectionSubtypeFlags &gt;::enumeration</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-50ae04bf469790ba6dee903817607680/#a3e1f63d55dda4d3b4c1eac2678c7e4a3">llvm::yaml::ScalarEnumerationTraits&lt; XCOFF::SymbolType &gt;::enumeration</a>.</p>

</div>
</div>

### error() {#a80d90bfd4320ba8fab1652f723724220}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::error_code llvm::yaml::IO::error ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 822 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c60b4e663ab4824f4f644e9f43c15901/#a38fe4de7a843977864cf28fde93a24a0">llvm::yaml::MappingTraits&lt; MachOYAML::Section &gt;::validate</a>.</p>

</div>
</div>

### getContext() {#a9602206972cc02cc749acfca45487271}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * IO::getContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-454a2a2b1a47ec9d4c922b4916225c88/#a89b21a8f2ece6eb884f32d9c0a793378">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD::denormalize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-v4-266563df95186142f944822c118e1d06/#aedcce29e87024ad031150e8912907dfa">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD_V4::denormalize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ca178affa2c5542ad6152857e8646a0e/#a8aa2ce258589aa8cf35e95ac4450547a">llvm::yaml::MappingTraits&lt; ArchYAML::Archive &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-90fa4b4bf1f65b5e4684b9a1c116c7f5/#a97458d286b2cbcb3fdfaab5b757f23c4">llvm::yaml::MappingTraits&lt; ArchYAML::Archive::Child &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9c3ed3171d9efe654f3a3a3f77e7db56/#a6215697818a46a18abcef5d8b0ef8ab7">llvm::yaml::MappingTraits&lt; Argument &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-90cc610844b061ef8678004e270b8243/#a53ddd05cd3b095c73952a90b866a45a4">llvm::yaml::MappingTraits&lt; COFFYAML::Relocation &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-e89d132bf3d28337bd8aaf7baaae73c5/#aa7279d3ef5ee1c69db6bb265aa706e58">llvm::yaml::MappingTraits&lt; COFFYAML::SectionDataEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f9e1428063165dff1316b1b637868894/#a50f092a891c4873f55a91fc98c04e7b9">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5cb422d9af45ce1249f0a09b1805d16a/#ab48301a67608f48551f5bccb93cf4402">llvm::yaml::MappingTraits&lt; DXContainerYAML::ResourceBindInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-fba39fbf2cc2c6e13e34c6c86e26a783/#a45425409cac1e451158a9f003dfbe867">llvm::yaml::MappingTraits&lt; ExportSection &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-92aabbe7726b20f7d861a1bb8a979e9a/#a60b8756dcd66445c4f61cf46596474c7">llvm::yaml::MappingTraits&lt; MachOYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-db8cb737cc7fc384da8655be2604695f/#abd5e07a8b119579c42a2dcdd0686395b">llvm::yaml::MappingTraits&lt; MachOYAML::UniversalBinary &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-d529a49f37e7337d1700531e004f69d5/#a259032a648d87807fa178ce67bcdcbe3">llvm::yaml::MappingTraits&lt; OffloadYAML::Binary &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-959faf53a4be9dd561f02b273168cbb5/#a3f8f028aa8d17fdae9a8bd22426205af">llvm::yaml::MappingTraits&lt; OffloadYAML::Binary::Member &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5fee2f384a38ab733b31562b8d41f672/#a1bf914c09910bf2045cfb3ef0c1be439">llvm::yaml::MappingTraits&lt; OffloadYAML::Binary::StringEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-e04ef8402fe6e5256544f3aa0cee17c3/#a92a38bb7828b1553781c36e6a8b2bda2">llvm::yaml::MappingTraits&lt; RemarkLocation &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f2d65b616a08104c2021962f48e2455/#ab031e9be9223cf40d60bc665956918d6">llvm::yaml::MappingTraits&lt; remarks::Remark * &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-31f56d02e9ae3cab7c6017d1111afe46/#ac0d56e0cfd3aa559dd8e7255488e3c31">llvm::yaml::MappingTraits&lt; std::unique_ptr&lt; XCOFFYAML::AuxSymbolEnt &gt; &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-de1eedd893d80fd446e954170f116efc/#a340720991c26524cf0bbe66bf194138b">llvm::yaml::MappingTraits&lt; UndefinedSection &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits/normalizedtbd-v4-266563df95186142f944822c118e1d06/#af4e0a994d0feae8ef45c2bdb1c16ead2">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::NormalizedTBD_V4::NormalizedTBD_V4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a47c3b2e1c47efa6dea510fdea8711d18">llvm::yaml::yamlize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a1e5c76544c98f93394c90bccf4d4de9d">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### getNodeKind() {#a08c1fbf5f364c6ea410467c08ba59cc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual NodeKind llvm::yaml::IO::getNodeKind ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a576858066d9d05d80349d8e8f7725a38">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### keys() {#af1ca4f897adb4845e0f5456540bbdc7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::vector&lt; StringRef &gt; llvm::yaml::IO::keys ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-35fb56b6eed5c6961763c71ac116b491/#afe6743f808968eb3d08882ac6956108e">llvm::yaml::MappingTraits&lt; SIArgument &gt;::mapping</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a9b2287bff14bbe0d31a7972882b9164a">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### mapOptional() {#a27dee5b4ee79b39bc614889a4186bbf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::mapOptional (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, T &amp; Val)</td>
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



<p>Definition at line 892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="#a1407aaef6dfdc3eef37f9d9c4d5379f3">mapOptionalWithContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#affc0c3c5461939dc116f399779fa2a16">llvm::yaml::auxSymMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aded39f8b0259eaa22d99db5f4fe31917">llvm::yaml::auxSymMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ad21ab8a05235b26d1b001cf4434bb26d">llvm::yaml::auxSymMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ab5d583e3fa744ba9bcdda45fe38517f2">llvm::yaml::auxSymMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#afce37e8c36b189aa6870bd9349d8f5b2">llvm::yaml::auxSymMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a451aae0511cda50c58c537adfa941869">llvm::yaml::auxSymMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a37cdddb131960ec91b78bcf18bdb157b">llvm::yaml::auxSymMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6e3f3fcc4f35e5481a9efbaeff0ae472">llvm::yaml::commonSectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#af867a0ecbdece4680f684fef345a0752">llvm::yaml::commonSectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ab17e24dea5cbae98d84d4f791b1c7f4d">llvm::yaml::fillMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a3ab6c04f2e78400d2906909e1fecc223">llvm::yaml::groupSectionMapping</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlcrossmoduleexportssubsection/#abe4c42b91bb1b2bfec6771dcb62ba7d9">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCrossModuleExportsSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlcrossmoduleimportssubsection/#aea44b4a1cd95048cb31d8de0a0a94673">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCrossModuleImportsSubsection::map</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/leafrecordimpl/#ad0e73ecece9b5d8ac59b1ca96a412e8f">llvm::CodeViewYAML::detail::LeafRecordImpl&lt; FieldListRecord &gt;::map</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/symbolrecordimpl/#a11724097bf3be24b922ed78b9f10e8ea">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::map</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f9e1428063165dff1316b1b637868894/#af36b5d7a005d7098498bdaf44c8d66df">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapKeysToValues</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f9e1428063165dff1316b1b637868894/#a2697a94da66ab22f86dc0d115073aaa2">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapKeysToValuesV4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a64e732b505355c4653160551165f32a9">llvm::yaml::mapLoadCommandData&lt; MachO::build_version_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a23f46d0a26e819554dc11cd876ae7585">llvm::yaml::mapLoadCommandData&lt; MachO::dylib_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a89177ee1b521d6f0d46774bdd45468c1">llvm::yaml::mapLoadCommandData&lt; MachO::dylinker_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2a96f3232d8c1fb48aa7ff6b6adb503a">llvm::yaml::mapLoadCommandData&lt; MachO::rpath_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aac99fb9cd351c3277e29c808a54707ab">llvm::yaml::mapLoadCommandData&lt; MachO::segment_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a141797e2ace547979ea5798ffac93f34">llvm::yaml::mapLoadCommandData&lt; MachO::segment_command_64 &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a600e2473c4498418aa4cf64f292eceb4">llvm::yaml::mapLoadCommandData&lt; MachO::sub_client_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#afe633d1b6694f192485e34b94103039f">llvm::yaml::mapLoadCommandData&lt; MachO::sub_framework_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a251680a62d3832be4e53545b1d3eb804">llvm::yaml::mapLoadCommandData&lt; MachO::sub_library_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a0538fcaf6d6e95c13afc817d0ec2b83d">llvm::yaml::mapLoadCommandData&lt; MachO::sub_umbrella_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ac68d4a92295ed0bbacd23e46871f6465">llvm::yaml::mapLoadConfig</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ac66c8f8f6dfc16caca781cd3381ea81e">llvm::yaml::mapLoadConfigMember</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp/#adc210e8e8538ef4c96983ea197f9820d">mapOptional</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp/#a83771fdaf8b35fdf9499c4b86ebdef85">mapOptionalAs</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-b5c3ea6f2c54b3efe3a201fbbefc911f/#a04d0982984ccdd15e1d32616fb4c77d7">llvm::yaml::MappingTraits&lt; AArch64FunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ca178affa2c5542ad6152857e8646a0e/#a8aa2ce258589aa8cf35e95ac4450547a">llvm::yaml::MappingTraits&lt; ArchYAML::Archive &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-90fa4b4bf1f65b5e4684b9a1c116c7f5/#a97458d286b2cbcb3fdfaab5b757f23c4">llvm::yaml::MappingTraits&lt; ArchYAML::Archive::Child &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9c3ed3171d9efe654f3a3a3f77e7db56/#a6215697818a46a18abcef5d8b0ef8ab7">llvm::yaml::MappingTraits&lt; Argument &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-09c1e2242983c1cfa2dfc4d5564c025c/#ad2dd68e90612561db8cf4454708b9b0b">llvm::yaml::MappingTraits&lt; ARMFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-698d41c33e934b305ab621e594cd8f06/#a0ad0a9c3605a1677d2a8111d04449cdd">llvm::yaml::MappingTraits&lt; CallSiteInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-d2afca7929a5563e0e07bd99287f6885/#a6a86ffce1b2a3aa7fb021fca07fd95cf">llvm::yaml::MappingTraits&lt; CallSiteYAML &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-7055c0c2640173b3724e9c62224256c1/#a86a030942830be562ff4a7b69ad83eba">llvm::yaml::MappingTraits&lt; COFF::AuxiliarySectionDefinition &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f6e476d934cf5e16a51a30c9b54fa913/#a01f0f9de9e0e2772d2f39f17362e086f">llvm::yaml::MappingTraits&lt; COFF::header &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-402280c10610ffb0f50951d8e51b9978/#aa3fcfb4f16c63e6dd688f036b5b3857b">llvm::yaml::MappingTraits&lt; COFFYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-bb031e57b62776ac89d1a671932c0d62/#abcc106d67a20f42b39a79a6a9374ca89">llvm::yaml::MappingTraits&lt; COFFYAML::PEHeader &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-90cc610844b061ef8678004e270b8243/#a53ddd05cd3b095c73952a90b866a45a4">llvm::yaml::MappingTraits&lt; COFFYAML::Relocation &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-7f0c312c2230757842e61e1addb0e9d5/#a7f9a133db3867ba212fc52ceb391bbc3">llvm::yaml::MappingTraits&lt; COFFYAML::Section &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-e89d132bf3d28337bd8aaf7baaae73c5/#aa7279d3ef5ee1c69db6bb265aa706e58">llvm::yaml::MappingTraits&lt; COFFYAML::SectionDataEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-703aff89e8d1b0611383f83a5fa6b5c1/#af82a4a5cfe5e5746add85034e4816e09">llvm::yaml::MappingTraits&lt; COFFYAML::Symbol &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-885f5efd8aec28c006a70140ab038f65/#a387df4d45febf5aea69e378aab8b9b17">llvm::yaml::MappingTraits&lt; DXContainerYAML::DXILProgram &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f99cb68cf622192289c6bc988cc0aab5/#a22d34fe8370fada9bfd323eb08e12482">llvm::yaml::MappingTraits&lt; DXContainerYAML::FileHeader &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3b721b8815ba6becf2a368b5cccf1c8a/#ab8dd8ee758a10a249bfaca4dad686ac8">llvm::yaml::MappingTraits&lt; DXContainerYAML::Part &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-fba39fbf2cc2c6e13e34c6c86e26a783/#a45425409cac1e451158a9f003dfbe867">llvm::yaml::MappingTraits&lt; ExportSection &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-1b7fae5933cc0a2e56c4029c697ed017/#a9b904859b3ce95ddde8bf33d2427a4c7">llvm::yaml::MappingTraits&lt; FixedMachineStackObject &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-53ae3e3da76d4a953c54bf91fcf8ff03/#a4767e18dc386d5993f57f42bc8b5ae0e">llvm::yaml::MappingTraits&lt; FunctionSummary::ConstVCall &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f2ddc008bab5e4ac6df6d73193250556/#a71b31abecdffbe3d3820359ed8b0221a">llvm::yaml::MappingTraits&lt; FunctionSummary::VFuncId &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-73076b6eb9c9391d098f1623686f6b0d/#aacec8ea10f36647b4110e9c525174adf">llvm::yaml::MappingTraits&lt; FunctionYAML &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f3113c193c7b0aca5c5ed956d8ef3f5/#a2bd2e72ee6929cd494e56244b26b69ce">llvm::yaml::MappingTraits&lt; GlobalValueSummaryYaml &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4c0c2ba5ea16381e76eaa75aa0e1667e/#a1823d39a4ef233f11786c2092adc819e">llvm::yaml::MappingTraits&lt; HSAMD::Metadata &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-cfbb7858c1e7d174f3d93467b6338aa4/#af7b8d0ec0cf82438183368cf23a50c53">llvm::yaml::MappingTraits&lt; IFSStub &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-290f6e03be84d1caf4845fe858339f16/#ab27cc874395f57318996f37b89ed1e19">llvm::yaml::MappingTraits&lt; IFSStubTriple &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c1d09893298cc48ef746676f4461db29/#a8858480739569eb5b1ac627b1d1ca035">llvm::yaml::MappingTraits&lt; IFSSymbol &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-1398a6b6fb6ae3999465e099db67ed1f/#ad56a0501c61d827c50e1e236611738a3">llvm::yaml::MappingTraits&lt; IFSTarget &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/yaml/mappingtraits-d0a21960fd2ccf1b3e3800d718552a33/#aa71902f2ed6e7ae7f62ec27c05e31f0d">llvm::yaml::MappingTraits&lt; InstrProfCorrelator::Probe &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3f18e02f49b29247efabd35c84c79b5f/#a28c9fd78eecc77a2b93ffb47781c1db9">llvm::yaml::MappingTraits&lt; Kernel::Attrs::Metadata &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4e22e69130e105506350a3b6540489e4/#ad64be885239ee345bdf0fdeae343740e">llvm::yaml::MappingTraits&lt; Kernel::DebugProps::Metadata &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-b96b1c4665796fbba3d6ae995b6a497c/#ac943927a71a1ac35f2204993692b7b35">llvm::yaml::MappingTraits&lt; MachineConstantPoolValue &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f897c6484796b76878843226270e7ef4/#af727873876a528f6d4f8464e19c7eb00">llvm::yaml::MappingTraits&lt; MachineFunctionLiveIn &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-98613eb6f1b3a16ac358d1c592a05caa/#a2f5a3872a6acae70c06ad00c327599b8">llvm::yaml::MappingTraits&lt; MachineJumpTable &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-97314bd1ddf3100593f73343764b5bbb/#a19ef80c76d4b46cabbb4967bbb2c00c9">llvm::yaml::MappingTraits&lt; MachineJumpTable::Entry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-fbc0fe608c154d81aa634476ad4f2c26/#a4336c7728ddeb8b766e7e621ea29844b">llvm::yaml::MappingTraits&lt; MachineStackObject &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-897880b4eccfde32b5cfc7a082415580/#a44c822afd21dad7c229964438a6f9317">llvm::yaml::MappingTraits&lt; MachOYAML::BindOpcode &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-d5c3b8b9fb5d6fc3a6f2099a48ea49c8/#a59f87c012f454b624f809a8d8c6ad2f3">llvm::yaml::MappingTraits&lt; MachOYAML::ExportEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-a09aeaaed6d86e5e2fba37aa09756a0c/#a7aa8fdc9789c3f0beef0e5580a3fd0e5">llvm::yaml::MappingTraits&lt; MachOYAML::FatArch &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-536762a2a2a330085e4350c4efc0f811/#a86a309d4a6b8f8cdc62f9b3fefe01ba5">llvm::yaml::MappingTraits&lt; MachOYAML::LoadCommand &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-92aabbe7726b20f7d861a1bb8a979e9a/#a60b8756dcd66445c4f61cf46596474c7">llvm::yaml::MappingTraits&lt; MachOYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-a6aa2c56528fc0d77c07288c9acf90a6/#a0478462338ae415289db13534defc81e">llvm::yaml::MappingTraits&lt; MachOYAML::RebaseOpcode &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c60b4e663ab4824f4f644e9f43c15901/#a31343c405eee0fa6bfdaad896057e8bd">llvm::yaml::MappingTraits&lt; MachOYAML::Section &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-229898081ab1ae62ec808414e8cc9435/#a10ab4f820b351ea57b6fa5079aef8042">llvm::yaml::MappingTraits&lt; ModuleSummaryIndex &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-aac8086185ecf2f698d67f8b9a28de32/#a36ecd5ec3fdcb48b569f7bbe6a874db3">llvm::yaml::MappingTraits&lt; object::coff_load_config_code_integrity &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-d529a49f37e7337d1700531e004f69d5/#a259032a648d87807fa178ce67bcdcbe3">llvm::yaml::MappingTraits&lt; OffloadYAML::Binary &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-959faf53a4be9dd561f02b273168cbb5/#a3f8f028aa8d17fdae9a8bd22426205af">llvm::yaml::MappingTraits&lt; OffloadYAML::Binary::Member &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-abac9beb8acb5d9f1ea4c46f433105af/#a0f54595f23ee762bbce57bfa7995a309">llvm::yaml::MappingTraits&lt; RISCVMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/yaml/mappingtraits-c80c041ffea20cc7706c9989a8e15935/#ac64bd6bac87ad00b7909c9edb5f7f3fb">llvm::yaml::MappingTraits&lt; SerializableCtxRepresentation &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-35fb56b6eed5c6961763c71ac116b491/#afe6743f808968eb3d08882ac6956108e">llvm::yaml::MappingTraits&lt; SIArgument &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-681c4c5501468f74165b2beff3cc6c2f/#a0f9426840a4215cc87afb6e93ede9c9e">llvm::yaml::MappingTraits&lt; SIArgumentInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ae88fe955e45e71c5b431db963315283/#af012311acd92ea9c93c84f48d4b002dc">llvm::yaml::MappingTraits&lt; SIMachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-e04af5a7e9a7e6429c317f65059acd5d/#a5375c5d577f84cf80808edad654056f9">llvm::yaml::MappingTraits&lt; SIMode &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c43122d721b9a4d881223154d1cdc967/#a36a2613668ee046bf272e1591a5378c0">llvm::yaml::MappingTraits&lt; SymbolSection &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-6b7e56206de5417b61b501a03fcc04bd/#a9a6a7499bb609851662697044aa117a5">llvm::yaml::MappingTraits&lt; TypeIdSummary &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-19754de8db6a5803cd6e0257923ca0a9/#ab2aaf9aa4fa74f208892a8f2543c1e79">llvm::yaml::MappingTraits&lt; TypeTestResolution &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-de1eedd893d80fd446e954170f116efc/#a340720991c26524cf0bbe66bf194138b">llvm::yaml::MappingTraits&lt; UndefinedSection &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-efae7fb4ddc27ed2c2f2cd5628dc6fc8/#aa074c0fa3578716addcfca558a7e5e25">llvm::yaml::MappingTraits&lt; VirtualRegisterDefinition &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-18dd91fe8ed180bcb5ae4a900ca9e2b6/#a5bab3721e5b76c2b713804fbb8d9a458">llvm::yaml::MappingTraits&lt; WasmYAML::DataSegment &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-658f0a3a0ab10b474df42279c343445f/#aabc7cedd43fe30e4017edf849453b910">llvm::yaml::MappingTraits&lt; WasmYAML::ElemSegment &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a8cc2d97c22481f18d450e52e5b23c9/#a3d99c06ba93604da2fd5d5d0ce95ff7f">llvm::yaml::MappingTraits&lt; WasmYAML::InitExpr &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-b101e278cfd19acff0878e4ffc3cfc38/#a3342e89c505696a0f1d23ebd2e867c7d">llvm::yaml::MappingTraits&lt; WasmYAML::Limits &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-56be91309e2d2f416502e1d5c0410440/#ad7776daeaa751325e740ae77009b0e10">llvm::yaml::MappingTraits&lt; WasmYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-a6d73d2aff871e597704ca3f6564d5ee/#a38bf7037a4b5397f90d5a7802499ab6b">llvm::yaml::MappingTraits&lt; WasmYAML::Relocation &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3893a56453e0d2967d45a2698063e0bc/#ad8de3589d429d71d64908ba67d607f5d">llvm::yaml::MappingTraits&lt; WasmYAML::SymbolInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-2ef46f95f3a96c9dc966ec79c81b019c/#a4b42fffcb4fe29140c9073f3270807a2">llvm::yaml::MappingTraits&lt; WebAssemblyFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-2365973b01ec74a29165da4ca33e275f/#a5216c56829df976d43ea4f010b06aff8">llvm::yaml::MappingTraits&lt; WholeProgramDevirtResolution &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-7ad99ec350487a043ea3bd282a0833a8/#a0f306d3f2c21090ca669a66d649cd2e9">llvm::yaml::MappingTraits&lt; WholeProgramDevirtResolution::ByArg &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-2c1f3ef599da661be4a16b76efac9d4d/#af1a46f5c6fca7d2712fc224c67883766">llvm::yaml::MappingTraits&lt; X86MachineFunctionInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-279a65779daddb00595175d16f35a7d0/#a585d535a30002087266d7c0c4a3e7e3d">llvm::yaml::MappingTraits&lt; XCOFFYAML::AuxiliaryHeader &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-0623262a209065c4fd959afbda1f4d79/#ab82853e2b9baee49785263d9f9d05791">llvm::yaml::MappingTraits&lt; XCOFFYAML::FileHeader &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9a97fefb264971a269a93b1d608d1b76/#a7de92a91d153d641f42e391f93e80cf5">llvm::yaml::MappingTraits&lt; XCOFFYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-dfba42665bef7f6b5a1f2e4ec83de072/#a0dde9e91bce97e1f9ba6890c58a1bfc2">llvm::yaml::MappingTraits&lt; XCOFFYAML::Relocation &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-d08eacf025a3d0af23be81695ae7fcb2/#ab62bc619b692314c92d226b78367a8a0">llvm::yaml::MappingTraits&lt; XCOFFYAML::Section &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f8b15e59abd5a9e6d92175f62c435b58/#a88b3e51a3911cb6153efd56699743b69">llvm::yaml::MappingTraits&lt; XCOFFYAML::StringTable &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-2071d701e28d595a2e2108c265292c46/#ab4c51355237ed3422ebb4d8c0f7079d9">llvm::yaml::MappingTraits&lt; XCOFFYAML::Symbol &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-cfd1a00248475bbbc64042c45bfce2c3/#ae483e8256cda9692f0ebd566b9e98ee5">llvm::yaml::MappingTraits&lt; xray::YAMLXRayRecord &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ddb6890c751d9293f1c4ab8e9b8d5c91/#a00af62ce640a2d547a7f00aee3dcf5d0">llvm::yaml::MappingTraits&lt; xray::YAMLXRaySledEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#abfdf1e9171811abf703f9a03c1534569">mapRemarkHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a589ba45a5490ef34fda7d35463e0fc7c">llvm::yaml::sectionHeaderTableMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a92007707b6f7ea99f7681e423a367c23">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ac27d4819f11d0babe89c4328f2077b86">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2388e9a2ff9970eb125e790d406a121d">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#af69a7051b28632b2ec1f42c1a0179ab5">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a752549e6bb7e1f5655f786b49eb9e7af">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a1ecc2a9dbffcb08b283b0a711245cfb3">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a9b68a6ae2cad1fd36a3c1529a679ebe9">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aeb9fd85ec36dfbf7d45a17d91da0ba06">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6c67241819c960cfc2841bed188a0f84">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a7992634d2899a331d8ab670fe65c4677">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ad9afc329619de4b2210062475a5ce152">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a10dd80ee8620881ae1b6a44368a9e914">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ae4c9af2e2a58c73013845cc6a0d1e525">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a93b312d6832bd4216633b4ad3b05bcad">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aca3d37ad5e4f06225dc812df1ac518cc">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a9ae64f72ad427e18cbefa9d40485b929">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ad6712ed858676530dc34d3189ea57005">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#afc6efffb18f111f04fda96cae4040319">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ade1843f6d246c2280f125823b4fadec7">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#adba3601f626cf253940f926b749cf219">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ad40367541ed975a2535a74d93bc57130">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a922a8008e34a7d47c4b75511b801860a">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a7e9644f3c73e783fcf4acb30f12d483a">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a351fe91d1b4e88371b3ad42047fcd0ff">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a37b0085405bdfe477a0b122a7454075b">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ab7dcad6583834e8d59168f00e0d091ba">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a7bb1c99e40abde1bf7814977643c9711">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a41ad59473a1c06747d5660baf5f3dfdc">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6a5b498a0de9f1b7836d9a85a1e6c6d9">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aec34ee51363791d2d2dfddfc71a10076">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2e4314daa5425f3688418e5c678352c8">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#acab61d6d96f0902fe7417b0b90eb2818">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#affa0c65c09dfa404be2579672fb740ea">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp/#abcbaca580f80b88f64b1baf6af9abce8">streamMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp/#a5a05da0184dda537b6b887e52a313801">streamMapping</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp/#a93526b59404b99a68fb85f496ebaaf55">streamMapping</a>.</p>

</div>
</div>

### mapOptional() {#ae9ca4bb0cca2cc006c3c29fc0d9c109d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename DefaultT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::mapOptional (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, T &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DefaultT &amp; Default)</td>
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



<p>Definition at line 898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="#a1407aaef6dfdc3eef37f9d9c4d5379f3">mapOptionalWithContext</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### mapOptionalWithContext() {#a1407aaef6dfdc3eef37f9d9c4d5379f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename Context&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt; has_SequenceTraits&lt; T &gt;::value, void &gt; llvm::yaml::IO::mapOptionalWithContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, T &amp; Val, Context &amp; Ctx)</td>
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



<p>Definition at line 905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="#a0036ce961c87517653c815a8c219cc42">canElideEmptySequence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f9e1428063165dff1316b1b637868894/#a2697a94da66ab22f86dc0d115073aaa2">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapKeysToValuesV4</a>, <a href="#a27dee5b4ee79b39bc614889a4186bbf5">mapOptional</a> and <a href="#ae9ca4bb0cca2cc006c3c29fc0d9c109d">mapOptional</a>.</p>

</div>
</div>

### mapOptionalWithContext() {#ae8b7b8d8ebd2ace3bc51631229a465da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename Context&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::mapOptionalWithContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, std::optional&lt; T &gt; &amp; Val, Context &amp; Ctx)</td>
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



<p>Definition at line 913 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### mapOptionalWithContext() {#afc380816d3af033375acc783cb3f9239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename Context&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::enable_if_t&lt;!has_SequenceTraits&lt; T &gt;::value, void &gt; llvm::yaml::IO::mapOptionalWithContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, T &amp; Val, Context &amp; Ctx)</td>
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



<p>Definition at line 921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### mapOptionalWithContext() {#afd9a22f6dc3465b6f4c0fdaecc6afc17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename Context, typename DefaultT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::mapOptionalWithContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, T &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> DefaultT &amp; Default, Context &amp; Ctx)</td>
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



<p>Definition at line 926 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### mapRequired() {#a76b59883a4b23c1cb5c5f55eac119f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::mapRequired (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, T &amp; Val)</td>
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



<p>Definition at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6e3f3fcc4f35e5481a9efbaeff0ae472">llvm::yaml::commonSectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#af867a0ecbdece4680f684fef345a0752">llvm::yaml::commonSectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ab17e24dea5cbae98d84d4f791b1c7f4d">llvm::yaml::fillMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a518a80d50b5aeabdfa82f7a855d1730a">llvm::yaml::getStringValue</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-548ede8a22318ab04d09996146381986/#ac381405048a902237a88a1b7fcfd60d2">llvm::yaml::CustomMappingTraits&lt; BBNumberMap &gt;::inputOne</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-5afad16d6df5c47889a55ee752aaf37b/#a9b351a24adf0087ae1f9d5590d0f4e41">llvm::yaml::CustomMappingTraits&lt; GlobalValueSummaryMapTy &gt;::inputOne</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-401b2ef41e753181da578a4bc695ba1b/#abf5f8779105cfae23fe3239d741aada2">llvm::yaml::CustomMappingTraits&lt; IdHashNodeStableMapTy &gt;::inputOne</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-1891178988d22eff531bcad89e9cff02/#a34ec269fe6e9ba13368b8560acd8ea67">llvm::yaml::CustomMappingTraits&lt; MapDocNode &gt;::inputOne</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-3b1424a9b3a8aa6ce5718fd632001add/#a353f6537d00c4e23bd68620ea018050d">llvm::yaml::CustomMappingTraits&lt; std::map&lt; std::vector&lt; uint64_t &gt;, WholeProgramDevirtResolution::ByArg &gt; &gt;::inputOne</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-e6cd0f782800ff452527a9711839c949/#a2394e82dace4aa52c8852567306ade54">llvm::yaml::CustomMappingTraits&lt; std::map&lt; uint64_t, WholeProgramDevirtResolution &gt; &gt;::inputOne</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-2f4f225abb34192a09a7e667de1c62d8/#a82f01bbe42ee34025935c92328063566">llvm::yaml::CustomMappingTraits&lt; TypeIdSummaryMapTy &gt;::inputOne</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/stdmapstringcustommappingtraitsimpl/#a559d43e1081ed898ddc0330e671c467b">llvm::yaml::StdMapStringCustomMappingTraitsImpl&lt; T &gt;::inputOne</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlchecksumssubsection/#a4fd9e953fc65bb6eb24a23270758c612">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLChecksumsSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlcoffsymbolrvasubsection/#a813eda26a59da796314ee403cdefa90d">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCoffSymbolRVASubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlframedatasubsection/#ae234910ba90c89b6f2dbb2835cf03fbe">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLFrameDataSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlinlineelinessubsection/#ace20ec2d7d85a079299177381e40085e">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLInlineeLinesSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamllinessubsection/#a8efa51377803505ae716afed2cc15b37">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLLinesSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlstringtablesubsection/#ab5b415716a684d78e05f79e6eea02628">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLStringTableSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlsymbolssubsection/#a8235ba0894c15d0aebaef9b7f16d90b9">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLSymbolsSubsection::map</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/leafrecordimpl/#ac46481c11df87a432bb06cc1fac6667b">llvm::CodeViewYAML::detail::LeafRecordImpl&lt; FieldListRecord &gt;::map</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/leafrecordimpl-832f6a201a493b7c1e0caf0ea997f0f9/#a73a8b0b37888982f82a7a7050b54327d">llvm::CodeViewYAML::detail::LeafRecordImpl&lt; FieldListRecord &gt;::map</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/memberrecordimpl/#a6de15c0079b767221feb17760e12caea">llvm::CodeViewYAML::detail::MemberRecordImpl&lt; T &gt;::map</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/symbolrecordimpl/#aba52465c1cff9a9455fb23f909ea5e7c">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::map</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/unknownsymbolrecord/#a706f3a14442a38ad2ae15efa1aaaa3b8">llvm::CodeViewYAML::detail::UnknownSymbolRecord::map</a>, <a href="/web-llvm/docs/api/structs/llvm/dxcontaineryaml/psvinfo/#aef40b4410af614b5a4771ef2dfc5df47">llvm::DXContainerYAML::PSVInfo::mapInfoForVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f9e1428063165dff1316b1b637868894/#af36b5d7a005d7098498bdaf44c8d66df">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapKeysToValues</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f9e1428063165dff1316b1b637868894/#a2697a94da66ab22f86dc0d115073aaa2">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapKeysToValuesV4</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp/#a02f0c453e9a72b7bb391a936c4eba8a8">mapLeafRecordImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp/#aa054019d38a18172c3592ab3bfae2930">mapMemberRecordImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingcontexttraits-cff0e97a7da12ad5e5aa4c1c9cc38a63/#a59f3dfc6cf9b8903675d9c53d4a4a75a">llvm::yaml::MappingContextTraits&lt; MetadataSection, MetadataSection::Option &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9c3ed3171d9efe654f3a3a3f77e7db56/#a6215697818a46a18abcef5d8b0ef8ab7">llvm::yaml::MappingTraits&lt; Argument &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3af05eceb84db8df1f34d5629071ce73/#a15007847e9928e403f5c8c4f538d6b4f">llvm::yaml::MappingTraits&lt; CalledGlobal &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-698d41c33e934b305ab621e594cd8f06/#a0ad0a9c3605a1677d2a8111d04449cdd">llvm::yaml::MappingTraits&lt; CallSiteInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ab95244a46e66b72286acd8e897060bd/#a65107de69ce6a8428a3eaf88d1b0739f">llvm::yaml::MappingTraits&lt; CallSiteInfo::ArgRegPair &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-d2afca7929a5563e0e07bd99287f6885/#a6a86ffce1b2a3aa7fb021fca07fd95cf">llvm::yaml::MappingTraits&lt; CallSiteYAML &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-68af909a89305de89be7696ed8bb3b43/#ad87e984933dccb08d92dba05fc31ce54">llvm::yaml::MappingTraits&lt; COFF::AuxiliarybfAndefSymbol &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-eeebdb8b0ebc9ac147899284d6a831ed/#a7b00e598ef558b818e3047e7900e13ef">llvm::yaml::MappingTraits&lt; COFF::AuxiliaryCLRToken &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-577ae9e7be84a071123f7ad493f8d89a/#a0633753b466e0af09fc18414101f96f2">llvm::yaml::MappingTraits&lt; COFF::AuxiliaryFunctionDefinition &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-7055c0c2640173b3724e9c62224256c1/#a86a030942830be562ff4a7b69ad83eba">llvm::yaml::MappingTraits&lt; COFF::AuxiliarySectionDefinition &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c52f8fe6306fcb09416770618415092d/#ae3c16222132021653253467f968f23f4">llvm::yaml::MappingTraits&lt; COFF::AuxiliaryWeakExternal &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a739e2d34e532e9b8c201285c7d31cf/#ae5abae6e148bde37f99e83d62bb7645a">llvm::yaml::MappingTraits&lt; COFF::DataDirectory &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f6e476d934cf5e16a51a30c9b54fa913/#a01f0f9de9e0e2772d2f39f17362e086f">llvm::yaml::MappingTraits&lt; COFF::header &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-402280c10610ffb0f50951d8e51b9978/#aa3fcfb4f16c63e6dd688f036b5b3857b">llvm::yaml::MappingTraits&lt; COFFYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-90cc610844b061ef8678004e270b8243/#a53ddd05cd3b095c73952a90b866a45a4">llvm::yaml::MappingTraits&lt; COFFYAML::Relocation &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-7f0c312c2230757842e61e1addb0e9d5/#a7f9a133db3867ba212fc52ceb391bbc3">llvm::yaml::MappingTraits&lt; COFFYAML::Section &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-703aff89e8d1b0611383f83a5fa6b5c1/#af82a4a5cfe5e5746add85034e4816e09">llvm::yaml::MappingTraits&lt; COFFYAML::Symbol &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-b299b7d7ca0369d08bc51e6731e8ffa5/#a888bb21b4c91d9e9665ef45542bdbd47">llvm::yaml::MappingTraits&lt; DebugValueSubstitution &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-885f5efd8aec28c006a70140ab038f65/#a387df4d45febf5aea69e378aab8b9b17">llvm::yaml::MappingTraits&lt; DXContainerYAML::DXILProgram &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f99cb68cf622192289c6bc988cc0aab5/#a22d34fe8370fada9bfd323eb08e12482">llvm::yaml::MappingTraits&lt; DXContainerYAML::FileHeader &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-33c76fd6643c2355a88e2127513f86e9/#a1184f102696294ce3ed806a15245881b">llvm::yaml::MappingTraits&lt; DXContainerYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3b721b8815ba6becf2a368b5cccf1c8a/#ab8dd8ee758a10a249bfaca4dad686ac8">llvm::yaml::MappingTraits&lt; DXContainerYAML::Part &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5cb422d9af45ce1249f0a09b1805d16a/#ab48301a67608f48551f5bccb93cf4402">llvm::yaml::MappingTraits&lt; DXContainerYAML::ResourceBindInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-61405dbaf80cbfeb9b35252e15b74075/#a6209dd3fc33d4f89bdec94a74177dd00">llvm::yaml::MappingTraits&lt; DXContainerYAML::ShaderHash &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4bb822c4c7139da7fb5d757424751407/#ac5dde3201998982cefe1644559b55d9e">llvm::yaml::MappingTraits&lt; DXContainerYAML::Signature &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5846170c20e5db658888cb79e6c9ffc2/#a1b133a0cc7119db93698f71fd2a576d9">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureElement &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4e87224926d2f0c7ee72b6ac900e6c3c/#a5c98b4ef3410184e3cfc287901bd6a51">llvm::yaml::MappingTraits&lt; DXContainerYAML::SignatureParameter &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-de5da78e04e86953291cd676869ba5cb/#ab54dc925fbe0c2607f5c38cc788bd41e">llvm::yaml::MappingTraits&lt; DXContainerYAML::VersionTuple &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-1193f5caaf8a56a5fcb5035b3efe7a37/#a89f8acc09d3a09a5dbc20b7cc265cfb1">llvm::yaml::MappingTraits&lt; EntryValueObject &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-fba39fbf2cc2c6e13e34c6c86e26a783/#a45425409cac1e451158a9f003dfbe867">llvm::yaml::MappingTraits&lt; ExportSection &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-1b7fae5933cc0a2e56c4029c697ed017/#a9b904859b3ce95ddde8bf33d2427a4c7">llvm::yaml::MappingTraits&lt; FixedMachineStackObject &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5e4c8f3ada171203904dfc07ddf3a94f/#a61bcfb8b0274edff52ade8d261d91c47">llvm::yaml::MappingTraits&lt; FunctionsYAML &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-73076b6eb9c9391d098f1623686f6b0d/#aacec8ea10f36647b4110e9c525174adf">llvm::yaml::MappingTraits&lt; FunctionYAML &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24588379b8be1521d75b9125ce41c383/#a2590440f6997b9501f9816f8ef59d02e">llvm::yaml::MappingTraits&lt; HashNodeStable &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4c0c2ba5ea16381e76eaa75aa0e1667e/#a1823d39a4ef233f11786c2092adc819e">llvm::yaml::MappingTraits&lt; HSAMD::Metadata &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-cfbb7858c1e7d174f3d93467b6338aa4/#af7b8d0ec0cf82438183368cf23a50c53">llvm::yaml::MappingTraits&lt; IFSStub &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-290f6e03be84d1caf4845fe858339f16/#ab27cc874395f57318996f37b89ed1e19">llvm::yaml::MappingTraits&lt; IFSStubTriple &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c1d09893298cc48ef746676f4461db29/#a8858480739569eb5b1ac627b1d1ca035">llvm::yaml::MappingTraits&lt; IFSSymbol &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-faeb58024f36b42df58eecfd50daee68/#ae791cc48a6fcfcc4150c253bc8fdf9cf">llvm::yaml::MappingTraits&lt; IndexPairHash &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/yaml/mappingtraits-9adf2879f180c85a6b2884cc05556860/#a367a7fb3b10e84af986b0086e487390d">llvm::yaml::MappingTraits&lt; InstrProfCorrelator::CorrelationData &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/yaml/mappingtraits-d0a21960fd2ccf1b3e3800d718552a33/#aa71902f2ed6e7ae7f62ec27c05e31f0d">llvm::yaml::MappingTraits&lt; InstrProfCorrelator::Probe &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a5a7f9d9a9d207887d2b710d015b864/#a5128e6bbd41aad13b403df00985c937a">llvm::yaml::MappingTraits&lt; Kernel::Arg::Metadata &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-11a2b6dfa7f757480b342e43e05a8606/#a78a19c05dcd370eff160c0179bbf9b52">llvm::yaml::MappingTraits&lt; Kernel::CodeProps::Metadata &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-b95221c93f9ba2a2f9ebf06ed546f7f9/#ade7480f72242d0e0dcac52522f0f7c49">llvm::yaml::MappingTraits&lt; LocalVariableAddrGap &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f5a18f41c6e98f60bc6f9460255be40b/#a90595bea854cf4d9cab1aac4c1fc9b28">llvm::yaml::MappingTraits&lt; LocalVariableAddrRange &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-b96b1c4665796fbba3d6ae995b6a497c/#ac943927a71a1ac35f2204993692b7b35">llvm::yaml::MappingTraits&lt; MachineConstantPoolValue &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f897c6484796b76878843226270e7ef4/#af727873876a528f6d4f8464e19c7eb00">llvm::yaml::MappingTraits&lt; MachineFunctionLiveIn &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-98613eb6f1b3a16ac358d1c592a05caa/#a2f5a3872a6acae70c06ad00c327599b8">llvm::yaml::MappingTraits&lt; MachineJumpTable &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-97314bd1ddf3100593f73343764b5bbb/#a19ef80c76d4b46cabbb4967bbb2c00c9">llvm::yaml::MappingTraits&lt; MachineJumpTable::Entry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-fbc0fe608c154d81aa634476ad4f2c26/#a4336c7728ddeb8b766e7e621ea29844b">llvm::yaml::MappingTraits&lt; MachineStackObject &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-e2cae0c26c2b7f8d0e45b2e91ad8cb05/#a05d124d322ad21e400f07171008d2099">llvm::yaml::MappingTraits&lt; MachO::build_tool_version &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3514e0f08cded766dfc7055c4bb05cde/#aba5aa3bf986f32debb4603556c165e52">llvm::yaml::MappingTraits&lt; MachO::dylib &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-962461c991d9b670db3419342be969de/#abbcaabdf74d26151967de665185ec3f0">llvm::yaml::MappingTraits&lt; MachO::fvmlib &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-36a3614380b042bbb74bb39227ee9497/#aa2fc101fb6adae4492fdebed054a2065">llvm::yaml::MappingTraits&lt; MachO::section &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-94bed83b4ce6d0cfadfab701243201b4/#a70054ea6e8c2e0a05431d7fc8688d2fc">llvm::yaml::MappingTraits&lt; MachO::section_64 &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-897880b4eccfde32b5cfc7a082415580/#a44c822afd21dad7c229964438a6f9317">llvm::yaml::MappingTraits&lt; MachOYAML::BindOpcode &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f5321774c66dba563b1c64633c4fcd6e/#a9b1e3bada1049255f12aa8620e0e242b">llvm::yaml::MappingTraits&lt; MachOYAML::DataInCodeEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-d5c3b8b9fb5d6fc3a6f2099a48ea49c8/#a59f87c012f454b624f809a8d8c6ad2f3">llvm::yaml::MappingTraits&lt; MachOYAML::ExportEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-a09aeaaed6d86e5e2fba37aa09756a0c/#a7aa8fdc9789c3f0beef0e5580a3fd0e5">llvm::yaml::MappingTraits&lt; MachOYAML::FatArch &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5cd2185e5c3ab1fdf6468e7eef5eccce/#ad8a74335fc21ebe9955720960bdc6cb9">llvm::yaml::MappingTraits&lt; MachOYAML::FatHeader &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5b7b9d67dd6ab4dfb0380ee62dd5c983/#a711533a53359c245e8d87a2ac5f7799e">llvm::yaml::MappingTraits&lt; MachOYAML::FileHeader &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-536762a2a2a330085e4350c4efc0f811/#a86a309d4a6b8f8cdc62f9b3fefe01ba5">llvm::yaml::MappingTraits&lt; MachOYAML::LoadCommand &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-0cbfe390439d3481c2aa8e64afdf2a46/#a8840ffc784b5ce7dfc7d8080d74c59a5">llvm::yaml::MappingTraits&lt; MachOYAML::NListEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-92aabbe7726b20f7d861a1bb8a979e9a/#a60b8756dcd66445c4f61cf46596474c7">llvm::yaml::MappingTraits&lt; MachOYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-a6aa2c56528fc0d77c07288c9acf90a6/#a0478462338ae415289db13534defc81e">llvm::yaml::MappingTraits&lt; MachOYAML::RebaseOpcode &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-eb15815308b06ee03d1582ea39cb1df5/#ae38807f7e5755aaf37ac713ab4a53ef4">llvm::yaml::MappingTraits&lt; MachOYAML::Relocation &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c60b4e663ab4824f4f644e9f43c15901/#a31343c405eee0fa6bfdaad896057e8bd">llvm::yaml::MappingTraits&lt; MachOYAML::Section &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-db8cb737cc7fc384da8655be2604695f/#abd5e07a8b119579c42a2dcdd0686395b">llvm::yaml::MappingTraits&lt; MachOYAML::UniversalBinary &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-25c2d3f99a78b3a71c8f54cd9f25a292/#a881ae41fc687976e3aeaf6a49ea62873">llvm::yaml::MappingTraits&lt; memprof::AllMemProfData &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ba5ce804e6c326207b8d589f90ec6a56/#a48b7a9eb5757a5e3a20d209b7227a597">llvm::yaml::MappingTraits&lt; memprof::AllocationInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-022d2d1f6e3978de7ed0860a7b55be69/#a9362001da41fb80a0382a439f2fb7d75">llvm::yaml::MappingTraits&lt; memprof::Frame &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ea7d45673a77363a3aeaba941797ff7e/#ae2e2ca8721dda0f1ee80a5811b55c326">llvm::yaml::MappingTraits&lt; memprof::GUIDMemProfRecordPair &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-d529a49f37e7337d1700531e004f69d5/#a259032a648d87807fa178ce67bcdcbe3">llvm::yaml::MappingTraits&lt; OffloadYAML::Binary &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5fee2f384a38ab733b31562b8d41f672/#a1bf914c09910bf2045cfb3ef0c1be439">llvm::yaml::MappingTraits&lt; OffloadYAML::Binary::StringEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-e04ef8402fe6e5256544f3aa0cee17c3/#a92a38bb7828b1553781c36e6a8b2bda2">llvm::yaml::MappingTraits&lt; RemarkLocation &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/yaml/mappingtraits-c80c041ffea20cc7706c9989a8e15935/#ac64bd6bac87ad00b7909c9edb5f7f3fb">llvm::yaml::MappingTraits&lt; SerializableCtxRepresentation &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-35fb56b6eed5c6961763c71ac116b491/#afe6743f808968eb3d08882ac6956108e">llvm::yaml::MappingTraits&lt; SIArgument &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-439bf5e7e3b0fd8d74c44c0528994dcc/#ad9ab9d9e787706a39f099bd416e067ad">llvm::yaml::MappingTraits&lt; StableFunction &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3c2e817e9c1f87ea483f1b3fe8f114e6/#a740fa91ae223f3049041dc18ed78d67d">llvm::yaml::MappingTraits&lt; std::unique_ptr&lt; WasmYAML::Section &gt; &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-31f56d02e9ae3cab7c6017d1111afe46/#ac0d56e0cfd3aa559dd8e7255488e3c31">llvm::yaml::MappingTraits&lt; std::unique_ptr&lt; XCOFFYAML::AuxSymbolEnt &gt; &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c43122d721b9a4d881223154d1cdc967/#a36a2613668ee046bf272e1591a5378c0">llvm::yaml::MappingTraits&lt; SymbolSection &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-e50390af0267dfb1d37784ddc1c0d21e/#ab6956c83eb92473dce378721bea9671a">llvm::yaml::MappingTraits&lt; UmbrellaSection &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-de1eedd893d80fd446e954170f116efc/#a340720991c26524cf0bbe66bf194138b">llvm::yaml::MappingTraits&lt; UndefinedSection &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-5b8e12b7ad1e0164aaa21319554c9b4a/#a2925cf2f2c146fd995c026d33a72c3a5">llvm::yaml::MappingTraits&lt; UUIDv4 &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-efae7fb4ddc27ed2c2f2cd5628dc6fc8/#aa074c0fa3578716addcfca558a7e5e25">llvm::yaml::MappingTraits&lt; VirtualRegisterDefinition &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-fae3d0d66d6ff18e457b5df05b880f4a/#a09ebd151e520a2630f0fbaefb08accad">llvm::yaml::MappingTraits&lt; WasmYAML::Comdat &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f08deec90527b78a9bc70703195e78cd/#a748a37b4161d94b1f692cfa9e8917c74">llvm::yaml::MappingTraits&lt; WasmYAML::ComdatEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-18dd91fe8ed180bcb5ae4a900ca9e2b6/#a5bab3721e5b76c2b713804fbb8d9a458">llvm::yaml::MappingTraits&lt; WasmYAML::DataSegment &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f7c06f2fecbf5381db4e21f582702b2c/#a276e00d7c811f394734757f9805a0e3b">llvm::yaml::MappingTraits&lt; WasmYAML::DylinkExportInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-eddac8dc3c990dc0ad15f5117f66967c/#abed2912855aa4df0be5d9b2b1e31a809">llvm::yaml::MappingTraits&lt; WasmYAML::DylinkImportInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-658f0a3a0ab10b474df42279c343445f/#aabc7cedd43fe30e4017edf849453b910">llvm::yaml::MappingTraits&lt; WasmYAML::ElemSegment &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-cbc247842cdccef8d0f55ca9ba04880b/#ab1c239694abd7b0f2331fe09f2bce115">llvm::yaml::MappingTraits&lt; WasmYAML::Export &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3ac48d48792f1672f1e8b8d34a81d436/#aa91d1467dc16bacb0eef6ff18b8b5fa1">llvm::yaml::MappingTraits&lt; WasmYAML::FeatureEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-98949e2eb679ad24084eff74746444b2/#af429bebd65cabacd8e87892c0eea4ec7">llvm::yaml::MappingTraits&lt; WasmYAML::FileHeader &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-25e5469bc027e8f8f4904e9e4cabbf4d/#a8225f9ebef9cfcd1e0db09f69cc1cbfb">llvm::yaml::MappingTraits&lt; WasmYAML::Function &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-be029080bc5fc807607df223e73b82af/#a733be4c05e14fe0c172debcdef8a1963">llvm::yaml::MappingTraits&lt; WasmYAML::Global &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-752a2c1a96cb61864d74afd2caa50efb/#a7cfe0ed67b2e22fccdca3274847ad9bf">llvm::yaml::MappingTraits&lt; WasmYAML::Import &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4a8cc2d97c22481f18d450e52e5b23c9/#a3d99c06ba93604da2fd5d5d0ce95ff7f">llvm::yaml::MappingTraits&lt; WasmYAML::InitExpr &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3f8721b09083cf05349364aec87cd1fa/#a785daec44a9f909d60f132f0254b1bdf">llvm::yaml::MappingTraits&lt; WasmYAML::InitFunction &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-b101e278cfd19acff0878e4ffc3cfc38/#a3342e89c505696a0f1d23ebd2e867c7d">llvm::yaml::MappingTraits&lt; WasmYAML::Limits &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-fffacf721f3e982d160ffbd7c9248d4d/#a9051bc2940505d6b7ff51d5b87be42b7">llvm::yaml::MappingTraits&lt; WasmYAML::LocalDecl &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-07604be6f78b986244916a4a5468c1e9/#abbf52193f26259ea038e094628429ab4">llvm::yaml::MappingTraits&lt; WasmYAML::NameEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-56be91309e2d2f416502e1d5c0410440/#ad7776daeaa751325e740ae77009b0e10">llvm::yaml::MappingTraits&lt; WasmYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-babd39467e94414948696cd1ceee5028/#aa016a97f5b767693ad358aa0b8ad2f06">llvm::yaml::MappingTraits&lt; WasmYAML::ProducerEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-a6d73d2aff871e597704ca3f6564d5ee/#a38bf7037a4b5397f90d5a7802499ab6b">llvm::yaml::MappingTraits&lt; WasmYAML::Relocation &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-6b6454f6ec29a329a2e3831f76196710/#a21edb8d772bf6606e95cde9b242a30da">llvm::yaml::MappingTraits&lt; WasmYAML::SegmentInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-1e357c368ccc4f59f6cd3b0877b4d60d/#a8de5f4ef9d27a5dbeb60eb509f93907a">llvm::yaml::MappingTraits&lt; WasmYAML::Signature &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3893a56453e0d2967d45a2698063e0bc/#ad8de3589d429d71d64908ba67d607f5d">llvm::yaml::MappingTraits&lt; WasmYAML::SymbolInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-d2b434555882febb3ad69517a99f3e04/#a0e4bb51534cb7f6f34b17959978da77e">llvm::yaml::MappingTraits&lt; WasmYAML::Table &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9a97fefb264971a269a93b1d608d1b76/#a7de92a91d153d641f42e391f93e80cf5">llvm::yaml::MappingTraits&lt; XCOFFYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9dee834dcf7b808eb71b432821aa5538/#aad1e6d9b029894aaffcca684b0d6939a">llvm::yaml::MappingTraits&lt; xray::YAMLXRayFileHeader &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-cfd1a00248475bbbc64042c45bfce2c3/#ae483e8256cda9692f0ebd566b9e98ee5">llvm::yaml::MappingTraits&lt; xray::YAMLXRayRecord &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ddb6890c751d9293f1c4ab8e9b8d5c91/#a00af62ce640a2d547a7f00aee3dcf5d0">llvm::yaml::MappingTraits&lt; xray::YAMLXRaySledEntry &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-0a8ae11da86889b023036b811da60ea2/#ac7a1dff90d2a6eab2361e6a0d1348465">llvm::yaml::MappingTraits&lt; xray::YAMLXRayTrace &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#abfdf1e9171811abf703f9a03c1534569">mapRemarkHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp/#a48ead60c2e2a82a450482eac1e7f72e0">mapRequiredAs</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp/#a40f025c89c1dd1b8036e86f07018de8d">mapSymbolRecordImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-548ede8a22318ab04d09996146381986/#a15f35e9a48f126008d1546522cbf0dcc">llvm::yaml::CustomMappingTraits&lt; BBNumberMap &gt;::output</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-5afad16d6df5c47889a55ee752aaf37b/#a58feee17d62f568809450f6c7e1d6f55">llvm::yaml::CustomMappingTraits&lt; GlobalValueSummaryMapTy &gt;::output</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-401b2ef41e753181da578a4bc695ba1b/#a87e07a421046458e0be7197ed8bf9de1">llvm::yaml::CustomMappingTraits&lt; IdHashNodeStableMapTy &gt;::output</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-1891178988d22eff531bcad89e9cff02/#a956f2978b565a4ffaf49796a8f0d498c">llvm::yaml::CustomMappingTraits&lt; MapDocNode &gt;::output</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-3b1424a9b3a8aa6ce5718fd632001add/#ac6432ffbc54f668270400f8dcf59b26d">llvm::yaml::CustomMappingTraits&lt; std::map&lt; std::vector&lt; uint64_t &gt;, WholeProgramDevirtResolution::ByArg &gt; &gt;::output</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-e6cd0f782800ff452527a9711839c949/#a249daf5101a60965d5b142fbb314b4bb">llvm::yaml::CustomMappingTraits&lt; std::map&lt; uint64_t, WholeProgramDevirtResolution &gt; &gt;::output</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-2f4f225abb34192a09a7e667de1c62d8/#a2e5dd7d379101cff8c5c4d2e333cbbb6">llvm::yaml::CustomMappingTraits&lt; TypeIdSummaryMapTy &gt;::output</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/stdmapstringcustommappingtraitsimpl/#ae3208985b5565491a3849e9480346303">llvm::yaml::StdMapStringCustomMappingTraitsImpl&lt; T &gt;::output</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a7992634d2899a331d8ab670fe65c4677">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a688ec845f068f220a4f17d17fd23b4f8">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aa7d9d9e76f10d029f519234313d8bfd6">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a217f74332f63adecd249b71722313f44">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ad3884367a3666f1afadb607557bc8898">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#adba3601f626cf253940f926b749cf219">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ab7dcad6583834e8d59168f00e0d091ba">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a41ad59473a1c06747d5660baf5f3dfdc">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6a5b498a0de9f1b7836d9a85a1e6c6d9">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a188ba7160f72f9ae787bc1d15175ba1e">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#af9cab6d0a37efae2ace5db6c8bef3e3a">llvm::yaml::setStringValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp/#a3b9df7cce2ce25a34c9b36ba598eac98">streamMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp/#a6e0c51257a5402ca76a110321f767cb3">streamMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp/#af20f31bb5d8a4e90eefda9d08d91a85e">streamMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp/#ae2ad5492db606630fad3834ce68bc2d8">streamMapping</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/minidumpyaml-cpp/#a5a05da0184dda537b6b887e52a313801">streamMapping</a>.</p>

</div>
</div>

### mapRequired() {#a4995c1d3cda7a94e8dc0df1230f4abd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename Context&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::mapRequired (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, T &amp; Val, Context &amp; Ctx)</td>
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



<p>Definition at line 888 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### mapTag() {#a48aefe64f43e923bdcaddcc2ea3eaf0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::yaml::IO::mapTag (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Tag, bool Default=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlchecksumssubsection/#a4fd9e953fc65bb6eb24a23270758c612">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLChecksumsSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlcoffsymbolrvasubsection/#a813eda26a59da796314ee403cdefa90d">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCoffSymbolRVASubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlcrossmoduleexportssubsection/#abe4c42b91bb1b2bfec6771dcb62ba7d9">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCrossModuleExportsSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlcrossmoduleimportssubsection/#aea44b4a1cd95048cb31d8de0a0a94673">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLCrossModuleImportsSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlframedatasubsection/#ae234910ba90c89b6f2dbb2835cf03fbe">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLFrameDataSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlinlineelinessubsection/#ace20ec2d7d85a079299177381e40085e">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLInlineeLinesSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamllinessubsection/#a8efa51377803505ae716afed2cc15b37">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLLinesSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlstringtablesubsection/#ab5b415716a684d78e05f79e6eea02628">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLStringTableSubsection::map</a>, <a href="/web-llvm/docs/api/structs/anonymous-codeviewyamldebugsections-cpp-/yamlsymbolssubsection/#a8235ba0894c15d0aebaef9b7f16d90b9">anonymous{CodeViewYAMLDebugSections.cpp}::YAMLSymbolsSubsection::map</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f9e1428063165dff1316b1b637868894/#a2697a94da66ab22f86dc0d115073aaa2">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapKeysToValuesV4</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ca178affa2c5542ad6152857e8646a0e/#a8aa2ce258589aa8cf35e95ac4450547a">llvm::yaml::MappingTraits&lt; ArchYAML::Archive &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-402280c10610ffb0f50951d8e51b9978/#aa3fcfb4f16c63e6dd688f036b5b3857b">llvm::yaml::MappingTraits&lt; COFFYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f9e1428063165dff1316b1b637868894/#a50f092a891c4873f55a91fc98c04e7b9">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-33c76fd6643c2355a88e2127513f86e9/#a1184f102696294ce3ed806a15245881b">llvm::yaml::MappingTraits&lt; DXContainerYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-cfbb7858c1e7d174f3d93467b6338aa4/#af7b8d0ec0cf82438183368cf23a50c53">llvm::yaml::MappingTraits&lt; IFSStub &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-290f6e03be84d1caf4845fe858339f16/#ab27cc874395f57318996f37b89ed1e19">llvm::yaml::MappingTraits&lt; IFSStubTriple &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-92aabbe7726b20f7d861a1bb8a979e9a/#a60b8756dcd66445c4f61cf46596474c7">llvm::yaml::MappingTraits&lt; MachOYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-db8cb737cc7fc384da8655be2604695f/#abd5e07a8b119579c42a2dcdd0686395b">llvm::yaml::MappingTraits&lt; MachOYAML::UniversalBinary &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-d529a49f37e7337d1700531e004f69d5/#a259032a648d87807fa178ce67bcdcbe3">llvm::yaml::MappingTraits&lt; OffloadYAML::Binary &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f2d65b616a08104c2021962f48e2455/#ab031e9be9223cf40d60bc665956918d6">llvm::yaml::MappingTraits&lt; remarks::Remark * &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-56be91309e2d2f416502e1d5c0410440/#ad7776daeaa751325e740ae77009b0e10">llvm::yaml::MappingTraits&lt; WasmYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9a97fefb264971a269a93b1d608d1b76/#a7de92a91d153d641f42e391f93e80cf5">llvm::yaml::MappingTraits&lt; XCOFFYAML::Object &gt;::mapping</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f9e1428063165dff1316b1b637868894/#a3a2af5f0ae3f3bee5f2c87b4139c6111">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::setFileTypeForInput</a>.</p>

</div>
</div>

### maskedBitSetCase() {#a0f5f896777fd657ea3616bffb395c7b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::maskedBitSetCase (T &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str, T ConstVal, T Mask)</td>
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



<p>Definition at line 867 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="#a953aeebd71524f02d96ae78ffb9c3843">bitSetMatch</a>, <a href="#a3f9abe4cc7cc808cb6025ed882bcbb7d">outputting</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### maskedBitSetCase() {#a62234ee099d9ced6fc2eb528d23a9f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::maskedBitSetCase (T &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str, uint32_t ConstVal, uint32_t Mask)</td>
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



<p>Definition at line 873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>References <a href="#a953aeebd71524f02d96ae78ffb9c3843">bitSetMatch</a>, <a href="#a3f9abe4cc7cc808cb6025ed882bcbb7d">outputting</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### matchEnumFallback() {#ad860aaca596742002904ee7bbf316a03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::yaml::IO::matchEnumFallback ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-7b9e6a6903edfdcf1f6beb970b564541/#ac940d0eec4c6144d822383e4b5b13181">llvm::yaml::ScalarEnumerationTraits&lt; IFSSymbolType &gt;::enumeration</a>, <a href="#ac656ce8032e2f91b5320566fde65dba1">enumFallback</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ad3e98f0d068b418a4d8547fff1864c3f">llvm::yaml::yamlizeMappingEnumInput</a>.</p>

</div>
</div>

### matchEnumScalar() {#a7de66f027ae46a8654fffdb2b785ea95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::yaml::IO::matchEnumScalar (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, bool)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="#ade062563b4463f8f0f8fe1f2f56a0b2e">enumCase</a> and <a href="#a9aecc50bd75a5c7bfd968714c5fda955">enumCase</a>.</p>

</div>
</div>

### outputting() {#a3f9abe4cc7cc808cb6025ed882bcbb7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::yaml::IO::outputting ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="#a2b1cefca27a7a232f423b506994e1761">bitSetCase</a>, <a href="#a245f9ba1195df0e9b09e606d6907e325">bitSetCase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a6e3f3fcc4f35e5481a9efbaeff0ae472">llvm::yaml::commonSectionMapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/sequencetraits-86907747ebbd2cfef93622e3f0326e4e/#a11fec855b4f71be143610ae6e86a56fb">llvm::yaml::SequenceTraits&lt; ArrayRef&lt; T &gt; &gt;::element</a>, <a href="#ade062563b4463f8f0f8fe1f2f56a0b2e">enumCase</a>, <a href="#a9aecc50bd75a5c7bfd968714c5fda955">enumCase</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/scalarenumerationtraits-7b9e6a6903edfdcf1f6beb970b564541/#ac940d0eec4c6144d822383e4b5b13181">llvm::yaml::ScalarEnumerationTraits&lt; IFSSymbolType &gt;::enumeration</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/unknownsymbolrecord/#a706f3a14442a38ad2ae15efa1aaaa3b8">llvm::CodeViewYAML::detail::UnknownSymbolRecord::map</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp/#a02f0c453e9a72b7bb391a936c4eba8a8">mapLeafRecordImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamltypes-cpp/#aa054019d38a18172c3592ab3bfae2930">mapMemberRecordImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9c3ed3171d9efe654f3a3a3f77e7db56/#a6215697818a46a18abcef5d8b0ef8ab7">llvm::yaml::MappingTraits&lt; Argument &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f9e1428063165dff1316b1b637868894/#a50f092a891c4873f55a91fc98c04e7b9">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-4c0c2ba5ea16381e76eaa75aa0e1667e/#a1823d39a4ef233f11786c2092adc819e">llvm::yaml::MappingTraits&lt; HSAMD::Metadata &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f4d9b6842bdae57db58da7af3602f037/#a587d9bdb751367010682b1147723230c">llvm::yaml::MappingTraits&lt; Kernel::Metadata &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-470ce6396ef6911e4c1c02cfed7dc14b/#ad73933ac202c87f434c78bcb044f09fc">llvm::yaml::MappingTraits&lt; MachOYAML::LinkEditData &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-92aabbe7726b20f7d861a1bb8a979e9a/#a60b8756dcd66445c4f61cf46596474c7">llvm::yaml::MappingTraits&lt; MachOYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-229898081ab1ae62ec808414e8cc9435/#a10ab4f820b351ea57b6fa5079aef8042">llvm::yaml::MappingTraits&lt; ModuleSummaryIndex &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-e04ef8402fe6e5256544f3aa0cee17c3/#a92a38bb7828b1553781c36e6a8b2bda2">llvm::yaml::MappingTraits&lt; RemarkLocation &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9f2d65b616a08104c2021962f48e2455/#ab031e9be9223cf40d60bc665956918d6">llvm::yaml::MappingTraits&lt; remarks::Remark * &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-35fb56b6eed5c6961763c71ac116b491/#afe6743f808968eb3d08882ac6956108e">llvm::yaml::MappingTraits&lt; SIArgument &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-3c2e817e9c1f87ea483f1b3fe8f114e6/#a740fa91ae223f3049041dc18ed78d67d">llvm::yaml::MappingTraits&lt; std::unique_ptr&lt; WasmYAML::Section &gt; &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-31f56d02e9ae3cab7c6017d1111afe46/#ac0d56e0cfd3aa559dd8e7255488e3c31">llvm::yaml::MappingTraits&lt; std::unique_ptr&lt; XCOFFYAML::AuxSymbolEnt &gt; &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-658f0a3a0ab10b474df42279c343445f/#aabc7cedd43fe30e4017edf849453b910">llvm::yaml::MappingTraits&lt; WasmYAML::ElemSegment &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-b101e278cfd19acff0878e4ffc3cfc38/#a3342e89c505696a0f1d23ebd2e867c7d">llvm::yaml::MappingTraits&lt; WasmYAML::Limits &gt;::mapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/codeviewyamlsymbols-cpp/#a40f025c89c1dd1b8036e86f07018de8d">mapSymbolRecordImpl</a>, <a href="#a0f5f896777fd657ea3616bffb395c7b0">maskedBitSetCase</a>, <a href="#a62234ee099d9ced6fc2eb528d23a9f5f">maskedBitSetCase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aeb803606db5e73c05a10f7f4e6982830">llvm::yaml::ResetAuxSym</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aeb9fd85ec36dfbf7d45a17d91da0ba06">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a10dd80ee8620881ae1b6a44368a9e914">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a825281c7367bc1781088c59974fc87e4">llvm::yaml::yamlize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a64bede48cd18859ff82b9eabca55ef50">llvm::yaml::yamlize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a47c3b2e1c47efa6dea510fdea8711d18">llvm::yaml::yamlize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a1e5c76544c98f93394c90bccf4d4de9d">llvm::yaml::yamlize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ad3e98f0d068b418a4d8547fff1864c3f">llvm::yaml::yamlizeMappingEnumInput</a>.</p>

</div>
</div>

### postflightElement() {#a9e4053aaf4164b5b2b6cc0db618d4c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::postflightElement (void *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a825281c7367bc1781088c59974fc87e4">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### postflightFlowElement() {#a0784e00190e5d6bd871eecf099ffce6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::postflightFlowElement (void *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a825281c7367bc1781088c59974fc87e4">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### postflightKey() {#aae7af838aa2a9d5cc45d90bc4b03b50a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::postflightKey (void *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### preflightElement() {#a75123fbfb5cd9f7a0d4b1609adb21b79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::yaml::IO::preflightElement (unsigned, void *&amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a825281c7367bc1781088c59974fc87e4">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### preflightFlowElement() {#adf1e34d55c27fb21a58001b473f5a37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::yaml::IO::preflightFlowElement (unsigned, void *&amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a825281c7367bc1781088c59974fc87e4">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### preflightKey() {#abd531806848796190ff4d06de6fac044}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::yaml::IO::preflightKey (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, bool, bool, bool &amp;, void *&amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### scalarString() {#a8a38e6ed5f6a97b39548f7c7d09f3714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::scalarString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp;, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2e9b09c50b4fff3bad8cba23daef8757">QuotingType</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a47c3b2e1c47efa6dea510fdea8711d18">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### scalarTag() {#ad841c6d5843b30251e2b871bb25d1e2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::scalarTag (std::string &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a4d406d084644dcdfcc7239d65e1ca863">llvm::yaml::yamlize</a>.</p>

</div>
</div>

### setAllowUnknownKeys() {#a5ae9ac11c898a51356d250572fefcdb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IO::setAllowUnknownKeys (bool Allow)</td>
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



<p>Declaration at line 823 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### setContext() {#a13c50e14628f82f4e0853bfef8ebddd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IO::setContext (void * Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-ca178affa2c5542ad6152857e8646a0e/#a8aa2ce258589aa8cf35e95ac4450547a">llvm::yaml::MappingTraits&lt; ArchYAML::Archive &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f6e476d934cf5e16a51a30c9b54fa913/#a01f0f9de9e0e2772d2f39f17362e086f">llvm::yaml::MappingTraits&lt; COFF::header &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-24dae25eef0cf89bd251b2ce9cf3fa24/#a6808d9de67d634c84c6549cc53e365bb">llvm::yaml::MappingTraits&lt; DXContainerYAML::PSVInfo &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-92aabbe7726b20f7d861a1bb8a979e9a/#a60b8756dcd66445c4f61cf46596474c7">llvm::yaml::MappingTraits&lt; MachOYAML::Object &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-db8cb737cc7fc384da8655be2604695f/#abd5e07a8b119579c42a2dcdd0686395b">llvm::yaml::MappingTraits&lt; MachOYAML::UniversalBinary &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-d529a49f37e7337d1700531e004f69d5/#a259032a648d87807fa178ce67bcdcbe3">llvm::yaml::MappingTraits&lt; OffloadYAML::Binary &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-56be91309e2d2f416502e1d5c0410440/#ad7776daeaa751325e740ae77009b0e10">llvm::yaml::MappingTraits&lt; WasmYAML::Object &gt;::mapping</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-9a97fefb264971a269a93b1d608d1b76/#a7de92a91d153d641f42e391f93e80cf5">llvm::yaml::MappingTraits&lt; XCOFFYAML::Object &gt;::mapping</a>.</p>

</div>
</div>

### setError() {#a930906994b5dc96a35696936fe705c15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::yaml::IO::setError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/isresizablebase-1894ccc07fdcdbf1d7beb00bbf18f805/#ae3d6a0023f0fd821361a82d72c2c6a8d">llvm::yaml::IsResizableBase&lt; T, false &gt;::element</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-5afad16d6df5c47889a55ee752aaf37b/#a9b351a24adf0087ae1f9d5590d0f4e41">llvm::yaml::CustomMappingTraits&lt; GlobalValueSummaryMapTy &gt;::inputOne</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-401b2ef41e753181da578a4bc695ba1b/#abf5f8779105cfae23fe3239d741aada2">llvm::yaml::CustomMappingTraits&lt; IdHashNodeStableMapTy &gt;::inputOne</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-2c5234ca03a917e6445ab40c7b8c2ed0/#a0b5c2b3b5adffd6b2ca4eaed69b1b117">llvm::yaml::CustomMappingTraits&lt; memprof::PortableMemInfoBlock &gt;::inputOne</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-3b1424a9b3a8aa6ce5718fd632001add/#a353f6537d00c4e23bd68620ea018050d">llvm::yaml::CustomMappingTraits&lt; std::map&lt; std::vector&lt; uint64_t &gt;, WholeProgramDevirtResolution::ByArg &gt; &gt;::inputOne</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-e6cd0f782800ff452527a9711839c949/#a2394e82dace4aa52c8852567306ade54">llvm::yaml::CustomMappingTraits&lt; std::map&lt; uint64_t, WholeProgramDevirtResolution &gt; &gt;::inputOne</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ac68d4a92295ed0bbacd23e46871f6465">llvm::yaml::mapLoadConfig</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-7f0c312c2230757842e61e1addb0e9d5/#a7f9a133db3867ba212fc52ceb391bbc3">llvm::yaml::MappingTraits&lt; COFFYAML::Section &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-f9e1428063165dff1316b1b637868894/#a50f092a891c4873f55a91fc98c04e7b9">llvm::yaml::MappingTraits&lt; const InterfaceFile * &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-cfbb7858c1e7d174f3d93467b6338aa4/#af7b8d0ec0cf82438183368cf23a50c53">llvm::yaml::MappingTraits&lt; IFSStub &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-290f6e03be84d1caf4845fe858339f16/#ab27cc874395f57318996f37b89ed1e19">llvm::yaml::MappingTraits&lt; IFSStubTriple &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-35fb56b6eed5c6961763c71ac116b491/#afe6743f808968eb3d08882ac6956108e">llvm::yaml::MappingTraits&lt; SIArgument &gt;::mapping</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-31f56d02e9ae3cab7c6017d1111afe46/#ac0d56e0cfd3aa559dd8e7255488e3c31">llvm::yaml::MappingTraits&lt; std::unique_ptr&lt; XCOFFYAML::AuxSymbolEnt &gt; &gt;::mapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a10dd80ee8620881ae1b6a44368a9e914">llvm::yaml::sectionMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a64bede48cd18859ff82b9eabca55ef50">llvm::yaml::yamlize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a47c3b2e1c47efa6dea510fdea8711d18">llvm::yaml::yamlize</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a1e5c76544c98f93394c90bccf4d4de9d">llvm::yaml::yamlize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### processKey() {#ad8eb050745796eca52c54d9399a01d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename Context&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::processKey (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, T &amp; Val, bool Required, Context &amp; Ctx)</td>
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



<p>Definition at line 958 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### processKeyWithDefault() {#a435c6acbe5dc9ee162525d5aafb92ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename Context&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::processKeyWithDefault (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, std::optional&lt; T &gt; &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; T &gt; &amp; DefaultValue, bool Required, Context &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 936 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

### processKeyWithDefault() {#a7892b4697e8187f6ff4d9fc1d6cd8205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, typename Context&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::IO::processKeyWithDefault (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Key, T &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T &amp; DefaultValue, bool Required, Context &amp; Ctx)</td>
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



<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Ctxt {#aa7fd504435fef4f3eae05e0f2359bc94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::yaml::IO::Ctxt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 968 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/yamltraits-h">YAMLTraits.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/yamltraits-cpp">YAMLTraits.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
