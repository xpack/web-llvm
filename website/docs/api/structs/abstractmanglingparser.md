---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/abstractmanglingparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AbstractManglingParser` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;typename Derived, typename Alloc&gt;
struct AbstractManglingParser&lt;Derived, Alloc&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">llvm/Demangle/ItaniumDemangle.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1520018fbee9a2889452cd7f161d380f">TemplateParamList</a> = <a href="/web-llvm/docs/api/classes/podsmallvector">PODSmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/node">Node</a> *, 8 &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa493f84f85dacf77dc2ecc4486d3cefe">AbstractManglingParser</a> (const char *First_, const char *Last_)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Derived &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a01bdc82f9718d4dd242186d0f57494be">getDerived</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b63851387bacae895fc85aff9a16a25">reset</a> (const char *First_, const char *Last_)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a722c2b4e37700cadbb7aa93542a2e1be">make</a> (Args &amp;&amp;... args)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class It&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/nodearray">NodeArray</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9f5a19c97b7d16ce2d6b911af8848e0f">makeNodeArray</a> (It begin, It end)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/nodearray">NodeArray</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae9e402b53d087f61d69de824b26483ac">popTrailingNodeArray</a> (size_t FromPosition)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad71a4d2931be91da3148fe3279cbed2b">consumeIf</a> (std::string_view S)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9addf9a0d1c44c3fbbe1c3d8a0ae83a2">consumeIf</a> (char C)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a86496230b54123c7809ff85935781c2a">consume</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aac3534ca8248ab03a5f4551d4076e411">look</a> (unsigned Lookahead=0) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a207aeee46de5b6c65992ac90f49b4593">numLeft</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::string_view</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a883d2cd34f663f0e86b120a77b9d6b">parseNumber</a> (bool AllowNegative=false)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7">Qualifiers</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a49ba5be8a9728ffa9518c27eda867f23">parseCVQualifiers</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab3cc1c2c83fddd665c43fdc006f419f9">parsePositiveInteger</a> (size_t *Out)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::string_view</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae83a62e754488540dc738e5b99d4c6f3">parseBareSourceName</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a75901a36174c858ff110c053b914a27a">parseSeqId</a> (size_t *Out)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a02e452afde6029066747c56b284c763e">parseSubstitution</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ddb8dda77894478155c13d71b74b49b">parseTemplateParam</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a42f63ed33efd48464560c7a2808c2110">parseTemplateParamDecl</a> (TemplateParamList *Params)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a397daba3d04112848d396591f8a67753">parseTemplateArgs</a> (bool TagTemplates=false)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad258b236255eaee1b5cf564889c97b9a">parseTemplateArg</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3368e1fa5fcd0aa5f68d7fb8ed916ba8">isTemplateParamDecl</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abb0edf66fe4cd9578df27e196bccf0b3">parseExpr</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the &lt;expression&gt; production. <a href="#abb0edf66fe4cd9578df27e196bccf0b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4fd4b15af7b5cb130b37082befbeca0c">parsePrefixExpr</a> (std::string_view Kind, Node::Prec Prec)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7823503d1a5405fbf8f1fffa46ebd0ff">parseBinaryExpr</a> (std::string_view Kind, Node::Prec Prec)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6cfcb654afef6b93a5d88956c198e2b7">parseIntegerLiteral</a> (std::string_view Lit)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab438097f6264945733cb782df179497a">parseExprPrimary</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Float&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1854a21eaab3d2bc78f248dea1549288">parseFloatingLiteral</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aebac0668cd2ccba8a810347afcd18188">parseFunctionParam</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2455cf780fc263477c2e51423b24b17d">parseConversionExpr</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a926563f39f6be3c9955f9da1426357c7">parseBracedExpr</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76df0d66308455708c032df20fc9fd44">parseFoldExpr</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a52cdd8479cc1563c89ce1d6e773954eb">parsePointerToMemberConversionExpr</a> (Node::Prec Prec)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1f3e98e28c753d1afa3ea8e1e90d4cd8">parseSubobjectExpr</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b75300a1f35f873c5413c3218c0ceea">parseConstraintExpr</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaa6cc7d6a5e9794e8853e726139a3215">parseRequiresExpr</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a40f2d5dba46e399d7c3e735456d0ae83">parseType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the &lt;type&gt; production. <a href="#a40f2d5dba46e399d7c3e735456d0ae83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8d2caa022ed2433c546a336a45aca7d9">parseFunctionType</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae51d6fdacbdc3d6de3e603bc6431fd0c">parseVectorType</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0e2d8d884d04dea062a8b4674e3f8f75">parseDecltype</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a43a8f40fc5176d4dba331c94c3519b90">parseArrayType</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a56fa502a58ecd777afe64aa07106185f">parsePointerToMemberType</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1dbf725d9afd4914b38afda91265e94e">parseClassEnumType</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab75e1a82e3ca70f21faf74933f2471b0">parseQualifiedType</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7597c6329192eea9889ca9669a7387f1">parseEncoding</a> (bool ParseParams=true)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa90c51147e7955d521e24fbf9d4cddb8">parseCallOffset</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3c60ed5c7679aa84ef460dce84cd4777">parseSpecialName</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5ad59b207f4802698845060996de7039">resolveForwardTemplateRefs</a> (NameState &amp;State)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a760fd5933f1f67ecfe8008ed713ab5b4">parseName</a> (NameState *State=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the &lt;name&gt; production&gt; <a href="#a760fd5933f1f67ecfe8008ed713ab5b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa0d666ea75f1150667fa90343823c5f4">parseLocalName</a> (NameState *State)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afaf6f6bc14e6958548705d184de98385">parseOperatorName</a> (NameState *State)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a00b461f41241f99015a6dd2ea2e08425">parseModuleNameOpt</a> (ModuleName *&amp;Module)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad9d8e005bfc2e208e217c9af2c0948a0">parseUnqualifiedName</a> (NameState *State, Node *Scope, ModuleName *Module)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afca1629c8e841245333f3fb9724a12d9">parseUnnamedTypeName</a> (NameState *State)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ace6000853f038505e58f9c498b85d60b">parseSourceName</a> (NameState *State)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad14e711f8193cc40f52cff65679632e9">parseUnscopedName</a> (NameState *State, bool *isSubstName)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac6781c18ea73250ec27554caee355867">parseNestedName</a> (NameState *State)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba055fbad743818420d549a22f343b33">parseCtorDtorName</a> (Node *&amp;SoFar, NameState *State)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac07d70593ff94177a2b659dfd61140fc">parseAbiTags</a> (Node *N)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo">OperatorInfo</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af04580d21e34e26a738a01750324ab0b">parseOperatorEncoding</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5163ef18f80446740383bc2b0a438346">parseUnresolvedName</a> (bool Global)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the &lt;unresolved-name&gt; production. <a href="#a5163ef18f80446740383bc2b0a438346">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a21ebcedc82bc3c4ed4e359a83711a166">parseSimpleId</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1e0ba4c5707057104f3330333ee2d004">parseBaseUnresolvedName</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af1d226f20e5973a826cfad43af1f5a10">parseUnresolvedType</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9dddb655d2ce0f547b732172cc0876f8">parseDestructorName</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/node">Node</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a880f69acceab7bea831caf07b7ac88b8">parse</a> (bool ParseParams=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Top-level entry point into the parser. <a href="#a880f69acceab7bea831caf07b7ac88b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a860222ba391900387ee2cb4436de6c35">First</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad469a27bf47c652db0a483eda3d92dde">Last</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/podsmallvector">PODSmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/node">Node</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a24a860d924997390b4deb34b6bedb014">Names</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/podsmallvector">PODSmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/node">Node</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14568f28904fc376515d84ac11c3525f">Subs</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a1520018fbee9a2889452cd7f161d380f">TemplateParamList</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a82e5920b3e1f823bdde8266961e80282">OuterTemplateParams</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/podsmallvector">PODSmallVector</a>&lt; <a href="#a1520018fbee9a2889452cd7f161d380f">TemplateParamList</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aec9744ac3abf5d2716bb11e45c9cf917">TemplateParams</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/podsmallvector">PODSmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/forwardtemplatereference">ForwardTemplateReference</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a229ec0a06959ee93e9e5f24e3682b086">ForwardTemplateRefs</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad2facd968f12de1854d4a721a2dfc44e">TryToParseTemplateArgs</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a501dd094510fbe0374e96899a5bbc1ae">PermitForwardTemplateReferences</a> = false</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1f03ac22bac5634ce6b7db97c3cbd22a">HasIncompleteTemplateParameterTracking</a> = false</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad176052ede893f358d8bdac88b4217fd">ParsingLambdaParamsAtLevel</a> = (size_t)-1</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#accb905d272c3ae3dfc91b0959ba13b2e">NumSyntheticTemplateParameters</a>[3] = {}</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Alloc</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1c50663a20673e10d6e60d5686d1db84">ASTAllocator</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo">OperatorInfo</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b2101383b3f36e0198f035592926a35">Ops</a>[]</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Derived, typename Alloc&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#affe3131b4c58615ae6b038d03b971088">NumOps</a></td>
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


<p>Definition at line 2728 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### TemplateParamList {#a1520018fbee9a2889452cd7f161d380f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using AbstractManglingParser&lt; Derived, Alloc &gt;::TemplateParamList =  PODSmallVector&lt;Node *, 8&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AbstractManglingParser() {#aa493f84f85dacf77dc2ecc4486d3cefe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AbstractManglingParser&lt; Derived, Alloc &gt;::AbstractManglingParser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * First_, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Last_)</td>
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



<p>Definition at line 2808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a> and <a href="#ad469a27bf47c652db0a483eda3d92dde">AbstractManglingParser&lt; Derived, Alloc &gt;::Last</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate/#a5ea3bdd076ba31ca6e06cb40948f11da">AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::NameState</a>, <a href="/web-llvm/docs/api/classes/abstractmanglingparser/savetemplateparams/#aac4de22d84dce442e281e48067265353">AbstractManglingParser&lt; Derived, Alloc &gt;::SaveTemplateParams::SaveTemplateParams</a> and <a href="/web-llvm/docs/api/classes/abstractmanglingparser/scopedtemplateparamlist/#a702222f4cfb0fa82353225f0a8e88d9b">AbstractManglingParser&lt; Derived, Alloc &gt;::ScopedTemplateParamList::ScopedTemplateParamList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### consume() {#a86496230b54123c7809ff85935781c2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char AbstractManglingParser&lt; Derived, Alloc &gt;::consume ()</td>
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



<p>Definition at line 2863 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a> and <a href="#ad469a27bf47c652db0a483eda3d92dde">AbstractManglingParser&lt; Derived, Alloc &gt;::Last</a>.</p>

</div>
</div>

### consumeIf() {#ad71a4d2931be91da3148fe3279cbed2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf (std::string_view S)</td>
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



<p>Definition at line 2847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#ad469a27bf47c652db0a483eda3d92dde">AbstractManglingParser&lt; Derived, Alloc &gt;::Last</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/stringviewextras-h/#a5336c02c81ff675028496f2f2409d30a">starts_with</a>.</p>


<p>Referenced by <a href="#a880f69acceab7bea831caf07b7ac88b8">AbstractManglingParser&lt; Derived, Alloc &gt;::parse</a>, <a href="#ac07d70593ff94177a2b659dfd61140fc">AbstractManglingParser&lt; Derived, Alloc &gt;::parseAbiTags</a>, <a href="#a43a8f40fc5176d4dba331c94c3519b90">AbstractManglingParser&lt; Derived, Alloc &gt;::parseArrayType</a>, <a href="#a1e0ba4c5707057104f3330333ee2d004">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBaseUnresolvedName</a>, <a href="#aa90c51147e7955d521e24fbf9d4cddb8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCallOffset</a>, <a href="#a1dbf725d9afd4914b38afda91265e94e">AbstractManglingParser&lt; Derived, Alloc &gt;::parseClassEnumType</a>, <a href="#a2455cf780fc263477c2e51423b24b17d">AbstractManglingParser&lt; Derived, Alloc &gt;::parseConversionExpr</a>, <a href="#aba055fbad743818420d549a22f343b33">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCtorDtorName</a>, <a href="#a49ba5be8a9728ffa9518c27eda867f23">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCVQualifiers</a>, <a href="#a0e2d8d884d04dea062a8b4674e3f8f75">AbstractManglingParser&lt; Derived, Alloc &gt;::parseDecltype</a>, <a href="#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>, <a href="#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>, <a href="#ab438097f6264945733cb782df179497a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExprPrimary</a>, <a href="#a1854a21eaab3d2bc78f248dea1549288">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFloatingLiteral</a>, <a href="#a76df0d66308455708c032df20fc9fd44">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFoldExpr</a>, <a href="#aebac0668cd2ccba8a810347afcd18188">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFunctionParam</a>, <a href="#a8d2caa022ed2433c546a336a45aca7d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFunctionType</a>, <a href="#a6cfcb654afef6b93a5d88956c198e2b7">AbstractManglingParser&lt; Derived, Alloc &gt;::parseIntegerLiteral</a>, <a href="#aa0d666ea75f1150667fa90343823c5f4">AbstractManglingParser&lt; Derived, Alloc &gt;::parseLocalName</a>, <a href="#a00b461f41241f99015a6dd2ea2e08425">AbstractManglingParser&lt; Derived, Alloc &gt;::parseModuleNameOpt</a>, <a href="#ac6781c18ea73250ec27554caee355867">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNestedName</a>, <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>, <a href="#afaf6f6bc14e6958548705d184de98385">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorName</a>, <a href="#a52cdd8479cc1563c89ce1d6e773954eb">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePointerToMemberConversionExpr</a>, <a href="#a56fa502a58ecd777afe64aa07106185f">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePointerToMemberType</a>, <a href="#ab75e1a82e3ca70f21faf74933f2471b0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseQualifiedType</a>, <a href="#aaa6cc7d6a5e9794e8853e726139a3215">AbstractManglingParser&lt; Derived, Alloc &gt;::parseRequiresExpr</a>, <a href="#a3c60ed5c7679aa84ef460dce84cd4777">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSpecialName</a>, <a href="#a1f3e98e28c753d1afa3ea8e1e90d4cd8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubobjectExpr</a>, <a href="#a02e452afde6029066747c56b284c763e">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubstitution</a>, <a href="#ad258b236255eaee1b5cf564889c97b9a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArg</a>, <a href="#a397daba3d04112848d396591f8a67753">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArgs</a>, <a href="#a3ddb8dda77894478155c13d71b74b49b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParam</a>, <a href="#a42f63ed33efd48464560c7a2808c2110">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParamDecl</a>, <a href="#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a>, <a href="#afca1629c8e841245333f3fb9724a12d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnnamedTypeName</a>, <a href="#ad9d8e005bfc2e208e217c9af2c0948a0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnqualifiedName</a>, <a href="#a5163ef18f80446740383bc2b0a438346">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnresolvedName</a>, <a href="#ad14e711f8193cc40f52cff65679632e9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnscopedName</a> and <a href="#ae51d6fdacbdc3d6de3e603bc6431fd0c">AbstractManglingParser&lt; Derived, Alloc &gt;::parseVectorType</a>.</p>

</div>
</div>

### consumeIf() {#a9addf9a0d1c44c3fbbe1c3d8a0ae83a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf (char C)</td>
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



<p>Definition at line 2855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a> and <a href="#ad469a27bf47c652db0a483eda3d92dde">AbstractManglingParser&lt; Derived, Alloc &gt;::Last</a>.</p>

</div>
</div>

### getDerived() {#a01bdc82f9718d4dd242186d0f57494be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Derived &amp; AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived ()</td>
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



<p>Definition at line 2811 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a880f69acceab7bea831caf07b7ac88b8">AbstractManglingParser&lt; Derived, Alloc &gt;::parse</a>, <a href="#a43a8f40fc5176d4dba331c94c3519b90">AbstractManglingParser&lt; Derived, Alloc &gt;::parseArrayType</a>, <a href="#a1e0ba4c5707057104f3330333ee2d004">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBaseUnresolvedName</a>, <a href="#a7823503d1a5405fbf8f1fffa46ebd0ff">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBinaryExpr</a>, <a href="#a926563f39f6be3c9955f9da1426357c7">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBracedExpr</a>, <a href="#a1dbf725d9afd4914b38afda91265e94e">AbstractManglingParser&lt; Derived, Alloc &gt;::parseClassEnumType</a>, <a href="#a2b75300a1f35f873c5413c3218c0ceea">AbstractManglingParser&lt; Derived, Alloc &gt;::parseConstraintExpr</a>, <a href="#a2455cf780fc263477c2e51423b24b17d">AbstractManglingParser&lt; Derived, Alloc &gt;::parseConversionExpr</a>, <a href="#aba055fbad743818420d549a22f343b33">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCtorDtorName</a>, <a href="#a0e2d8d884d04dea062a8b4674e3f8f75">AbstractManglingParser&lt; Derived, Alloc &gt;::parseDecltype</a>, <a href="#a9dddb655d2ce0f547b732172cc0876f8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseDestructorName</a>, <a href="#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>, <a href="#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>, <a href="#ab438097f6264945733cb782df179497a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExprPrimary</a>, <a href="#a76df0d66308455708c032df20fc9fd44">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFoldExpr</a>, <a href="#a8d2caa022ed2433c546a336a45aca7d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFunctionType</a>, <a href="#aa0d666ea75f1150667fa90343823c5f4">AbstractManglingParser&lt; Derived, Alloc &gt;::parseLocalName</a>, <a href="#a00b461f41241f99015a6dd2ea2e08425">AbstractManglingParser&lt; Derived, Alloc &gt;::parseModuleNameOpt</a>, <a href="#a760fd5933f1f67ecfe8008ed713ab5b4">AbstractManglingParser&lt; Derived, Alloc &gt;::parseName</a>, <a href="#ac6781c18ea73250ec27554caee355867">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNestedName</a>, <a href="#afaf6f6bc14e6958548705d184de98385">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorName</a>, <a href="#a52cdd8479cc1563c89ce1d6e773954eb">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePointerToMemberConversionExpr</a>, <a href="#a56fa502a58ecd777afe64aa07106185f">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePointerToMemberType</a>, <a href="#a4fd4b15af7b5cb130b37082befbeca0c">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePrefixExpr</a>, <a href="#ab75e1a82e3ca70f21faf74933f2471b0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseQualifiedType</a>, <a href="#aaa6cc7d6a5e9794e8853e726139a3215">AbstractManglingParser&lt; Derived, Alloc &gt;::parseRequiresExpr</a>, <a href="#a21ebcedc82bc3c4ed4e359a83711a166">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSimpleId</a>, <a href="#a3c60ed5c7679aa84ef460dce84cd4777">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSpecialName</a>, <a href="#a1f3e98e28c753d1afa3ea8e1e90d4cd8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubobjectExpr</a>, <a href="#a02e452afde6029066747c56b284c763e">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubstitution</a>, <a href="#ad258b236255eaee1b5cf564889c97b9a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArg</a>, <a href="#a397daba3d04112848d396591f8a67753">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArgs</a>, <a href="#a42f63ed33efd48464560c7a2808c2110">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParamDecl</a>, <a href="#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a>, <a href="#afca1629c8e841245333f3fb9724a12d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnnamedTypeName</a>, <a href="#ad9d8e005bfc2e208e217c9af2c0948a0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnqualifiedName</a>, <a href="#a5163ef18f80446740383bc2b0a438346">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnresolvedName</a>, <a href="#af1d226f20e5973a826cfad43af1f5a10">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnresolvedType</a>, <a href="#ad14e711f8193cc40f52cff65679632e9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnscopedName</a> and <a href="#ae51d6fdacbdc3d6de3e603bc6431fd0c">AbstractManglingParser&lt; Derived, Alloc &gt;::parseVectorType</a>.</p>

</div>
</div>

### isTemplateParamDecl() {#a3368e1fa5fcd0aa5f68d7fb8ed916ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::isTemplateParamDecl ()</td>
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



<p>Definition at line 2885 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Reference <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>.</p>


<p>Referenced by <a href="#ad258b236255eaee1b5cf564889c97b9a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArg</a> and <a href="#afca1629c8e841245333f3fb9724a12d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnnamedTypeName</a>.</p>

</div>
</div>

### look() {#aac3534ca8248ab03a5f4551d4076e411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char AbstractManglingParser&lt; Derived, Alloc &gt;::look (unsigned Lookahead=0)</td>
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



<p>Definition at line 2865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a> and <a href="#ad469a27bf47c652db0a483eda3d92dde">AbstractManglingParser&lt; Derived, Alloc &gt;::Last</a>.</p>


<p>Referenced by <a href="#a3368e1fa5fcd0aa5f68d7fb8ed916ba8">AbstractManglingParser&lt; Derived, Alloc &gt;::isTemplateParamDecl</a>, <a href="#a880f69acceab7bea831caf07b7ac88b8">AbstractManglingParser&lt; Derived, Alloc &gt;::parse</a>, <a href="#a43a8f40fc5176d4dba331c94c3519b90">AbstractManglingParser&lt; Derived, Alloc &gt;::parseArrayType</a>, <a href="#a1e0ba4c5707057104f3330333ee2d004">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBaseUnresolvedName</a>, <a href="#a926563f39f6be3c9955f9da1426357c7">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBracedExpr</a>, <a href="#aba055fbad743818420d549a22f343b33">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCtorDtorName</a>, <a href="#a9dddb655d2ce0f547b732172cc0876f8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseDestructorName</a>, <a href="#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>, <a href="#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>, <a href="#ab438097f6264945733cb782df179497a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExprPrimary</a>, <a href="#a76df0d66308455708c032df20fc9fd44">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFoldExpr</a>, <a href="#a760fd5933f1f67ecfe8008ed713ab5b4">AbstractManglingParser&lt; Derived, Alloc &gt;::parseName</a>, <a href="#ac6781c18ea73250ec27554caee355867">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNestedName</a>, <a href="#afaf6f6bc14e6958548705d184de98385">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorName</a>, <a href="#ab3cc1c2c83fddd665c43fdc006f419f9">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePositiveInteger</a>, <a href="#ab75e1a82e3ca70f21faf74933f2471b0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseQualifiedType</a>, <a href="#a75901a36174c858ff110c053b914a27a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSeqId</a>, <a href="#a21ebcedc82bc3c4ed4e359a83711a166">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSimpleId</a>, <a href="#a3c60ed5c7679aa84ef460dce84cd4777">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSpecialName</a>, <a href="#a02e452afde6029066747c56b284c763e">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubstitution</a>, <a href="#ad258b236255eaee1b5cf564889c97b9a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArg</a>, <a href="#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a>, <a href="#afca1629c8e841245333f3fb9724a12d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnnamedTypeName</a>, <a href="#ad9d8e005bfc2e208e217c9af2c0948a0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnqualifiedName</a>, <a href="#a5163ef18f80446740383bc2b0a438346">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnresolvedName</a>, <a href="#af1d226f20e5973a826cfad43af1f5a10">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnresolvedType</a>, <a href="#ad14e711f8193cc40f52cff65679632e9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnscopedName</a> and <a href="#ae51d6fdacbdc3d6de3e603bc6431fd0c">AbstractManglingParser&lt; Derived, Alloc &gt;::parseVectorType</a>.</p>

</div>
</div>

### make() {#a722c2b4e37700cadbb7aa93542a2e1be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::make (Args &amp;&amp;... args)</td>
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



<p>Definition at line 2827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a>, <a href="#a1c50663a20673e10d6e60d5686d1db84">AbstractManglingParser&lt; Derived, Alloc &gt;::ASTAllocator</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a880f69acceab7bea831caf07b7ac88b8">AbstractManglingParser&lt; Derived, Alloc &gt;::parse</a>, <a href="#ac07d70593ff94177a2b659dfd61140fc">AbstractManglingParser&lt; Derived, Alloc &gt;::parseAbiTags</a>, <a href="#a43a8f40fc5176d4dba331c94c3519b90">AbstractManglingParser&lt; Derived, Alloc &gt;::parseArrayType</a>, <a href="#a1e0ba4c5707057104f3330333ee2d004">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBaseUnresolvedName</a>, <a href="#a7823503d1a5405fbf8f1fffa46ebd0ff">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBinaryExpr</a>, <a href="#a926563f39f6be3c9955f9da1426357c7">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBracedExpr</a>, <a href="#a1dbf725d9afd4914b38afda91265e94e">AbstractManglingParser&lt; Derived, Alloc &gt;::parseClassEnumType</a>, <a href="#a2455cf780fc263477c2e51423b24b17d">AbstractManglingParser&lt; Derived, Alloc &gt;::parseConversionExpr</a>, <a href="#aba055fbad743818420d549a22f343b33">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCtorDtorName</a>, <a href="#a0e2d8d884d04dea062a8b4674e3f8f75">AbstractManglingParser&lt; Derived, Alloc &gt;::parseDecltype</a>, <a href="#a9dddb655d2ce0f547b732172cc0876f8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseDestructorName</a>, <a href="#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>, <a href="#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>, <a href="#ab438097f6264945733cb782df179497a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExprPrimary</a>, <a href="#a1854a21eaab3d2bc78f248dea1549288">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFloatingLiteral</a>, <a href="#a76df0d66308455708c032df20fc9fd44">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFoldExpr</a>, <a href="#aebac0668cd2ccba8a810347afcd18188">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFunctionParam</a>, <a href="#a8d2caa022ed2433c546a336a45aca7d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFunctionType</a>, <a href="#a6cfcb654afef6b93a5d88956c198e2b7">AbstractManglingParser&lt; Derived, Alloc &gt;::parseIntegerLiteral</a>, <a href="#aa0d666ea75f1150667fa90343823c5f4">AbstractManglingParser&lt; Derived, Alloc &gt;::parseLocalName</a>, <a href="#a00b461f41241f99015a6dd2ea2e08425">AbstractManglingParser&lt; Derived, Alloc &gt;::parseModuleNameOpt</a>, <a href="#a760fd5933f1f67ecfe8008ed713ab5b4">AbstractManglingParser&lt; Derived, Alloc &gt;::parseName</a>, <a href="#ac6781c18ea73250ec27554caee355867">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNestedName</a>, <a href="#afaf6f6bc14e6958548705d184de98385">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorName</a>, <a href="#a52cdd8479cc1563c89ce1d6e773954eb">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePointerToMemberConversionExpr</a>, <a href="#a56fa502a58ecd777afe64aa07106185f">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePointerToMemberType</a>, <a href="#a4fd4b15af7b5cb130b37082befbeca0c">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePrefixExpr</a>, <a href="#ab75e1a82e3ca70f21faf74933f2471b0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseQualifiedType</a>, <a href="#aaa6cc7d6a5e9794e8853e726139a3215">AbstractManglingParser&lt; Derived, Alloc &gt;::parseRequiresExpr</a>, <a href="#a21ebcedc82bc3c4ed4e359a83711a166">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSimpleId</a>, <a href="#ace6000853f038505e58f9c498b85d60b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSourceName</a>, <a href="#a3c60ed5c7679aa84ef460dce84cd4777">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSpecialName</a>, <a href="#a1f3e98e28c753d1afa3ea8e1e90d4cd8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubobjectExpr</a>, <a href="#a02e452afde6029066747c56b284c763e">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubstitution</a>, <a href="#ad258b236255eaee1b5cf564889c97b9a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArg</a>, <a href="#a397daba3d04112848d396591f8a67753">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArgs</a>, <a href="#a3ddb8dda77894478155c13d71b74b49b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParam</a>, <a href="#a42f63ed33efd48464560c7a2808c2110">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParamDecl</a>, <a href="#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a>, <a href="#afca1629c8e841245333f3fb9724a12d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnnamedTypeName</a>, <a href="#ad9d8e005bfc2e208e217c9af2c0948a0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnqualifiedName</a>, <a href="#a5163ef18f80446740383bc2b0a438346">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnresolvedName</a>, <a href="#ad14e711f8193cc40f52cff65679632e9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnscopedName</a> and <a href="#ae51d6fdacbdc3d6de3e603bc6431fd0c">AbstractManglingParser&lt; Derived, Alloc &gt;::parseVectorType</a>.</p>

</div>
</div>

### makeNodeArray() {#a9f5a19c97b7d16ce2d6b911af8848e0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class It&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeArray AbstractManglingParser&lt; Derived, Alloc &gt;::makeNodeArray (It begin, It end)</td>
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



<p>Definition at line 2831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a1c50663a20673e10d6e60d5686d1db84">AbstractManglingParser&lt; Derived, Alloc &gt;::ASTAllocator</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>.</p>


<p>Referenced by <a href="#a2455cf780fc263477c2e51423b24b17d">AbstractManglingParser&lt; Derived, Alloc &gt;::parseConversionExpr</a> and <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a>.</p>

</div>
</div>

### numLeft() {#a207aeee46de5b6c65992ac90f49b4593}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t AbstractManglingParser&lt; Derived, Alloc &gt;::numLeft ()</td>
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



<p>Definition at line 2871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a> and <a href="#ad469a27bf47c652db0a483eda3d92dde">AbstractManglingParser&lt; Derived, Alloc &gt;::Last</a>.</p>


<p>Referenced by <a href="#a880f69acceab7bea831caf07b7ac88b8">AbstractManglingParser&lt; Derived, Alloc &gt;::parse</a>, <a href="#ae83a62e754488540dc738e5b99d4c6f3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBareSourceName</a>, <a href="#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>, <a href="#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>, <a href="#a1854a21eaab3d2bc78f248dea1549288">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFloatingLiteral</a>, <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>, <a href="#af04580d21e34e26a738a01750324ab0b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorEncoding</a> and <a href="#ace6000853f038505e58f9c498b85d60b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSourceName</a>.</p>

</div>
</div>

### parse() {#a880f69acceab7bea831caf07b7ac88b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parse (bool ParseParams=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Top-level entry point into the parser.</p>

<p>Definition at line 3033 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#ad469a27bf47c652db0a483eda3d92dde">AbstractManglingParser&lt; Derived, Alloc &gt;::Last</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#a207aeee46de5b6c65992ac90f49b4593">AbstractManglingParser&lt; Derived, Alloc &gt;::numLeft</a> and <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>.</p>

</div>
</div>

### parseAbiTags() {#ac07d70593ff94177a2b659dfd61140fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseAbiTags (<a href="/web-llvm/docs/api/classes/node">Node</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2960 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#ae83a62e754488540dc738e5b99d4c6f3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBareSourceName</a>.</p>

</div>
</div>

### parseArrayType() {#a43a8f40fc5176d4dba331c94c3519b90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseArrayType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2911 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a> and <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>.</p>

</div>
</div>

### parseBareSourceName() {#ae83a62e754488540dc738e5b99d4c6f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string_view AbstractManglingParser&lt; Alloc, Derived &gt;::parseBareSourceName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2876 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>, <a href="#a207aeee46de5b6c65992ac90f49b4593">AbstractManglingParser&lt; Derived, Alloc &gt;::numLeft</a> and <a href="#ab3cc1c2c83fddd665c43fdc006f419f9">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePositiveInteger</a>.</p>


<p>Referenced by <a href="#ac07d70593ff94177a2b659dfd61140fc">AbstractManglingParser&lt; Derived, Alloc &gt;::parseAbiTags</a>, <a href="#ab75e1a82e3ca70f21faf74933f2471b0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseQualifiedType</a> and <a href="#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a>.</p>

</div>
</div>

### parseBaseUnresolvedName() {#a1e0ba4c5707057104f3330333ee2d004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseBaseUnresolvedName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3028 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a> and <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>.</p>

</div>
</div>

### parseBinaryExpr() {#a7823503d1a5405fbf8f1fffa46ebd0ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseBinaryExpr (std::string_view Kind, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220b">Node::Prec</a> Prec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2893 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### parseBracedExpr() {#a926563f39f6be3c9955f9da1426357c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseBracedExpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2899 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a> and <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>.</p>

</div>
</div>

### parseCallOffset() {#aa90c51147e7955d521e24fbf9d4cddb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Alloc, Derived &gt;::parseCallOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2917 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a> and <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>.</p>


<p>Referenced by <a href="#a3c60ed5c7679aa84ef460dce84cd4777">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSpecialName</a>.</p>

</div>
</div>

### parseClassEnumType() {#a1dbf725d9afd4914b38afda91265e94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseClassEnumType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2913 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a> and <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>.</p>

</div>
</div>

### parseConstraintExpr() {#a2b75300a1f35f873c5413c3218c0ceea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseConstraintExpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2903 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a> and <a href="#a1f03ac22bac5634ce6b7db97c3cbd22a">AbstractManglingParser&lt; Derived, Alloc &gt;::HasIncompleteTemplateParameterTracking</a>.</p>

</div>
</div>

### parseConversionExpr() {#a2455cf780fc263477c2e51423b24b17d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseConversionExpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2898 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#a9f5a19c97b7d16ce2d6b911af8848e0f">AbstractManglingParser&lt; Derived, Alloc &gt;::makeNodeArray</a>, <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a>, <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a> and <a href="#ad2facd968f12de1854d4a721a2dfc44e">AbstractManglingParser&lt; Derived, Alloc &gt;::TryToParseTemplateArgs</a>.</p>

</div>
</div>

### parseCtorDtorName() {#aba055fbad743818420d549a22f343b33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseCtorDtorName (<a href="/web-llvm/docs/api/classes/node">Node</a> *&amp; SoFar, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate">NameState</a> * State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2958 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="/web-llvm/docs/api/classes/node/#aae5cdb3eedc870de0873aed823149a3a">Node::getKind</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a> and <a href="#a760fd5933f1f67ecfe8008ed713ab5b4">AbstractManglingParser&lt; Derived, Alloc &gt;::parseName</a>.</p>

</div>
</div>

### parseCVQualifiers() {#a49ba5be8a9728ffa9518c27eda867f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Qualifiers AbstractManglingParser&lt; Alloc, Derived &gt;::parseCVQualifiers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2874 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7ad6035faf42d8a83f52624853a1ade2ea">QualConst</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7adc7b331ccab83e31a327816731dc82f2">QualNone</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7a6b9478659a0508affa81b92965259e51">QualRestrict</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7a2dada893b2fc28c908763cf4599e5a07">QualVolatile</a>.</p>


<p>Referenced by <a href="#aebac0668cd2ccba8a810347afcd18188">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFunctionParam</a>, <a href="#a8d2caa022ed2433c546a336a45aca7d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFunctionType</a>, <a href="#ac6781c18ea73250ec27554caee355867">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNestedName</a> and <a href="#ab75e1a82e3ca70f21faf74933f2471b0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseQualifiedType</a>.</p>

</div>
</div>

### parseDecltype() {#a0e2d8d884d04dea062a8b4674e3f8f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseDecltype ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2910 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a> and <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>.</p>

</div>
</div>

### parseDestructorName() {#a9dddb655d2ce0f547b732172cc0876f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseDestructorName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a> and <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>.</p>

</div>
</div>

### parseEncoding() {#a7597c6329192eea9889ca9669a7387f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding (bool ParseParams=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2916 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a5f02c7d98f9ea50a2abb5c2741c54f23">consume</a>, <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate/#a2d879e40930e72c6173c3846c7532220">AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::CtorDtorConversion</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate/#aa16e7c8207657635dc4567fa53bf675e">AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::CVQualifiers</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate/#a1cbd863f8c3ce436ff907d6d8ebfba21">AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::EndsWithTemplateArgs</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate/#a1403a1c9219dd4e4e7c57f1a7dfcf076">AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::HasExplicitObjectParameter</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a>, <a href="#a207aeee46de5b6c65992ac90f49b4593">AbstractManglingParser&lt; Derived, Alloc &gt;::numLeft</a>, <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate/#aac8fbdf60e6b213206626e6052532695">AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::ReferenceQualifier</a> and <a href="#a5ad59b207f4802698845060996de7039">AbstractManglingParser&lt; Derived, Alloc &gt;::resolveForwardTemplateRefs</a>.</p>

</div>
</div>

### parseExpr() {#abb0edf66fe4cd9578df27e196bccf0b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the &lt;expression&gt; production.</p>

<p>Definition at line 2891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a1c5a6bdc17969975557376df54a1f3fe">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Array</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a3ec036af4b1d3fb2d5d01b2609079d26">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Binary</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a6abf7dc083c709c6a96a34b77bf1967f">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Call</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a82810709402fac6d09282fe7fa8b67ab">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::CCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a0d3c1740500bb5a83638a2d5b78b26de">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Conditional</a>, <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7abd5ae9124fe4a8f5d2f58d3c33f71216">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Del</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h/#ae4a4b6b609be6808e094304ae8d981f7">DEMANGLE_UNREACHABLE</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a33bf2208b2c609d6d2dc569cfa879fdd">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Member</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a8045981e92d3b85c5ae925bcee4708df">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::NamedCast</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7ac599331c223b8dd2e853d9a7d6c6c66a">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::NameOnly</a>, <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a157a47aaf824edda98811cfc0169be06">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::New</a>, <a href="#a207aeee46de5b6c65992ac90f49b4593">AbstractManglingParser&lt; Derived, Alloc &gt;::numLeft</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a104bd83845d4703c8afd6b355f0a51e8">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::OfIdOp</a>, <a href="#af04580d21e34e26a738a01750324ab0b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorEncoding</a>, <a href="#a52cdd8479cc1563c89ce1d6e773954eb">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePointerToMemberConversionExpr</a>, <a href="#aaa6cc7d6a5e9794e8853e726139a3215">AbstractManglingParser&lt; Derived, Alloc &gt;::parseRequiresExpr</a>, <a href="#a1f3e98e28c753d1afa3ea8e1e90d4cd8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubobjectExpr</a>, <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a38e71f87e3a772db24bb8ac2bf2b5266">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Postfix</a>, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220bae5cc2a8a065c6272466ee0277ccc417f">Node::Postfix</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a433cbf2e47751906275610c69911564f">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Prefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/nodearray/#a607e39e72989ee5d314bb8f47ebd0e2c">NodeArray::size</a>, <a href="#ad2facd968f12de1854d4a721a2dfc44e">AbstractManglingParser&lt; Derived, Alloc &gt;::TryToParseTemplateArgs</a> and <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220ba19c6e8d6e2caeaff0ac8881e05c25010">Node::Unary</a>.</p>

</div>
</div>

### parseExprPrimary() {#ab438097f6264945733cb782df179497a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseExprPrimary ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a1854a21eaab3d2bc78f248dea1549288">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFloatingLiteral</a>, <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>, <a href="#afca1629c8e841245333f3fb9724a12d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnnamedTypeName</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### parseFloatingLiteral() {#a1854a21eaab3d2bc78f248dea1549288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Float&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Alloc, Derived &gt;::parseFloatingLiteral ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2896 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a1960c14773241d6a238d2db593abe552">C</a>, <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a207aeee46de5b6c65992ac90f49b4593">AbstractManglingParser&lt; Derived, Alloc &gt;::numLeft</a>.</p>


<p>Referenced by <a href="#ab438097f6264945733cb782df179497a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExprPrimary</a>.</p>

</div>
</div>

### parseFoldExpr() {#a76df0d66308455708c032df20fc9fd44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseFoldExpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a3ec036af4b1d3fb2d5d01b2609079d26">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Binary</a>, <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a33bf2208b2c609d6d2dc569cfa879fdd">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Member</a>, <a href="#af04580d21e34e26a738a01750324ab0b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorEncoding</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### parseFunctionParam() {#aebac0668cd2ccba8a810347afcd18188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseFunctionParam ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#a49ba5be8a9728ffa9518c27eda867f23">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCVQualifiers</a> and <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>.</p>

</div>
</div>

### parseFunctionType() {#a8d2caa022ed2433c546a336a45aca7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseFunctionType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2908 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8eda1aae950c29f9ecb1c243fd467c11e459">FrefQualLValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8eda74a742e365bc15a3ee3b9a2a4b0e79f3">FrefQualNone</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8edafbc3331ba3ee5c71530408d486058abe">FrefQualRValue</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a>, <a href="#a49ba5be8a9728ffa9518c27eda867f23">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCVQualifiers</a>, <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### parseIntegerLiteral() {#a6cfcb654afef6b93a5d88956c198e2b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseIntegerLiteral (std::string_view Lit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a> and <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>.</p>

</div>
</div>

### parseLocalName() {#aa0d666ea75f1150667fa90343823c5f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseLocalName (<a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate">NameState</a> * State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2950 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#ad469a27bf47c652db0a483eda3d92dde">AbstractManglingParser&lt; Derived, Alloc &gt;::Last</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ab2d8c90e39c84aa00b246cf61e67ef96">parse_discriminator</a> and <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>.</p>

</div>
</div>

### parseModuleNameOpt() {#a00b461f41241f99015a6dd2ea2e08425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::parseModuleNameOpt (<a href="/web-llvm/docs/api/structs/modulename">ModuleName</a> *&amp; Module)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecheckdebugify-cpp/#a85892acfa8970627e9bd9c9815f15c25">Module</a> and <a href="#a14568f28904fc376515d84ac11c3525f">AbstractManglingParser&lt; Derived, Alloc &gt;::Subs</a>.</p>


<p>Referenced by <a href="#a3c60ed5c7679aa84ef460dce84cd4777">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSpecialName</a> and <a href="#ad9d8e005bfc2e208e217c9af2c0948a0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnqualifiedName</a>.</p>

</div>
</div>

### parseName() {#a760fd5933f1f67ecfe8008ed713ab5b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseName (<a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate">NameState</a> * State=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the &lt;name&gt; production&gt;</p>

<p>Definition at line 2949 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a> and <a href="#a14568f28904fc376515d84ac11c3525f">AbstractManglingParser&lt; Derived, Alloc &gt;::Subs</a>.</p>


<p>Referenced by <a href="#aba055fbad743818420d549a22f343b33">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCtorDtorName</a>.</p>

</div>
</div>

### parseNestedName() {#ac6781c18ea73250ec27554caee355867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseNestedName (<a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate">NameState</a> * State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2957 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8eda1aae950c29f9ecb1c243fd467c11e459">FrefQualLValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8eda74a742e365bc15a3ee3b9a2a4b0e79f3">FrefQualNone</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a9fef0832b445332ae7862de6f08ac8edafbc3331ba3ee5c71530408d486058abe">FrefQualRValue</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="/web-llvm/docs/api/classes/node/#aae5cdb3eedc870de0873aed823149a3a">Node::getKind</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecheckdebugify-cpp/#a85892acfa8970627e9bd9c9815f15c25">Module</a>, <a href="#a49ba5be8a9728ffa9518c27eda867f23">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCVQualifiers</a> and <a href="#a14568f28904fc376515d84ac11c3525f">AbstractManglingParser&lt; Derived, Alloc &gt;::Subs</a>.</p>

</div>
</div>

### parseNumber() {#a7a883d2cd34f663f0e86b120a77b9d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string_view AbstractManglingParser&lt; Alloc, Derived &gt;::parseNumber (bool AllowNegative=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2873 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a> and <a href="#a207aeee46de5b6c65992ac90f49b4593">AbstractManglingParser&lt; Derived, Alloc &gt;::numLeft</a>.</p>


<p>Referenced by <a href="#a880f69acceab7bea831caf07b7ac88b8">AbstractManglingParser&lt; Derived, Alloc &gt;::parse</a>, <a href="#a43a8f40fc5176d4dba331c94c3519b90">AbstractManglingParser&lt; Derived, Alloc &gt;::parseArrayType</a>, <a href="#aa90c51147e7955d521e24fbf9d4cddb8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCallOffset</a>, <a href="#ab438097f6264945733cb782df179497a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExprPrimary</a>, <a href="#aebac0668cd2ccba8a810347afcd18188">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFunctionParam</a>, <a href="#a6cfcb654afef6b93a5d88956c198e2b7">AbstractManglingParser&lt; Derived, Alloc &gt;::parseIntegerLiteral</a>, <a href="#aa0d666ea75f1150667fa90343823c5f4">AbstractManglingParser&lt; Derived, Alloc &gt;::parseLocalName</a>, <a href="#a3c60ed5c7679aa84ef460dce84cd4777">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSpecialName</a>, <a href="#a1f3e98e28c753d1afa3ea8e1e90d4cd8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubobjectExpr</a>, <a href="#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a>, <a href="#afca1629c8e841245333f3fb9724a12d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnnamedTypeName</a> and <a href="#ae51d6fdacbdc3d6de3e603bc6431fd0c">AbstractManglingParser&lt; Derived, Alloc &gt;::parseVectorType</a>.</p>

</div>
</div>

### parseOperatorEncoding() {#af04580d21e34e26a738a01750324ab0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo * AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorEncoding ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3023 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a207aeee46de5b6c65992ac90f49b4593">AbstractManglingParser&lt; Derived, Alloc &gt;::numLeft</a>, <a href="#affe3131b4c58615ae6b038d03b971088">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a> and <a href="#a9b2101383b3f36e0198f035592926a35">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>.</p>


<p>Referenced by <a href="#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>, <a href="#a76df0d66308455708c032df20fc9fd44">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFoldExpr</a> and <a href="#afaf6f6bc14e6958548705d184de98385">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorName</a>.</p>

</div>
</div>

### parseOperatorName() {#afaf6f6bc14e6958548705d184de98385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorName (<a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate">NameState</a> * State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2951 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a82810709402fac6d09282fe7fa8b67ab">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::CCast</a>, <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7a33bf2208b2c609d6d2dc569cfa879fdd">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Member</a>, <a href="#af04580d21e34e26a738a01750324ab0b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorEncoding</a>, <a href="#a501dd094510fbe0374e96899a5bbc1ae">AbstractManglingParser&lt; Derived, Alloc &gt;::PermitForwardTemplateReferences</a>, <a href="#ad2facd968f12de1854d4a721a2dfc44e">AbstractManglingParser&lt; Derived, Alloc &gt;::TryToParseTemplateArgs</a> and <a href="/web-llvm/docs/api/structs/abstractmanglingparser/operatorinfo/#aafe8a42a8411e57f7e90ed1b1fcbd0a7ac65df57a19d87c23245c988c0caefc8a">AbstractManglingParser&lt; Derived, Alloc &gt;::OperatorInfo::Unnameable</a>.</p>

</div>
</div>

### parsePointerToMemberConversionExpr() {#a52cdd8479cc1563c89ce1d6e773954eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parsePointerToMemberConversionExpr (<a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220b">Node::Prec</a> Prec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2901 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a> and <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>.</p>


<p>Referenced by <a href="#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>.</p>

</div>
</div>

### parsePointerToMemberType() {#a56fa502a58ecd777afe64aa07106185f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parsePointerToMemberType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2912 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a> and <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>.</p>

</div>
</div>

### parsePositiveInteger() {#ab3cc1c2c83fddd665c43fdc006f419f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Alloc, Derived &gt;::parsePositiveInteger (size_t * Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2875 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a5f02c7d98f9ea50a2abb5c2741c54f23">consume</a> and <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>.</p>


<p>Referenced by <a href="#ae83a62e754488540dc738e5b99d4c6f3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBareSourceName</a>, <a href="#ace6000853f038505e58f9c498b85d60b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSourceName</a> and <a href="#a3ddb8dda77894478155c13d71b74b49b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParam</a>.</p>

</div>
</div>

### parsePrefixExpr() {#a4fd4b15af7b5cb130b37082befbeca0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parsePrefixExpr (std::string_view Kind, <a href="/web-llvm/docs/api/classes/node/#aa85c347c913d5d69761682997e60220b">Node::Prec</a> Prec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a> and <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>.</p>

</div>
</div>

### parseQualifiedType() {#ab75e1a82e3ca70f21faf74933f2471b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseQualifiedType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#ad469a27bf47c652db0a483eda3d92dde">AbstractManglingParser&lt; Derived, Alloc &gt;::Last</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#ae83a62e754488540dc738e5b99d4c6f3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBareSourceName</a>, <a href="#a49ba5be8a9728ffa9518c27eda867f23">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCVQualifiers</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#af9f0d130cd1298575a79aee97e5b53b7adc7b331ccab83e31a327816731dc82f2">QualNone</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/stringviewextras-h/#a5336c02c81ff675028496f2f2409d30a">starts_with</a>.</p>

</div>
</div>

### parseRequiresExpr() {#aaa6cc7d6a5e9794e8853e726139a3215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseRequiresExpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a>, <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a88ee8e4eea43084bd8964682683da88caa1fa27779242b4902f7ae3bdd5c6d508">Type</a>.</p>


<p>Referenced by <a href="#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>.</p>

</div>
</div>

### parseSeqId() {#a75901a36174c858ff110c053b914a27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Alloc, Derived &gt;::parseSeqId (size_t * Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2878 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a> and <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>.</p>


<p>Referenced by <a href="#a3c60ed5c7679aa84ef460dce84cd4777">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSpecialName</a> and <a href="#a02e452afde6029066747c56b284c763e">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubstitution</a>.</p>

</div>
</div>

### parseSimpleId() {#a21ebcedc82bc3c4ed4e359a83711a166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseSimpleId ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a> and <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>.</p>

</div>
</div>

### parseSourceName() {#ace6000853f038505e58f9c498b85d60b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseSourceName (<a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate">NameState</a> * State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2955 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#a207aeee46de5b6c65992ac90f49b4593">AbstractManglingParser&lt; Derived, Alloc &gt;::numLeft</a>, <a href="#ab3cc1c2c83fddd665c43fdc006f419f9">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePositiveInteger</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/stringviewextras-h/#a5336c02c81ff675028496f2f2409d30a">starts_with</a>.</p>

</div>
</div>

### parseSpecialName() {#a3c60ed5c7679aa84ef460dce84cd4777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseSpecialName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2918 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecheckdebugify-cpp/#a85892acfa8970627e9bd9c9815f15c25">Module</a>, <a href="#aa90c51147e7955d521e24fbf9d4cddb8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCallOffset</a>, <a href="#a00b461f41241f99015a6dd2ea2e08425">AbstractManglingParser&lt; Derived, Alloc &gt;::parseModuleNameOpt</a>, <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a> and <a href="#a75901a36174c858ff110c053b914a27a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSeqId</a>.</p>

</div>
</div>

### parseSubobjectExpr() {#a1f3e98e28c753d1afa3ea8e1e90d4cd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubobjectExpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a>, <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a> and <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a>.</p>


<p>Referenced by <a href="#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>.</p>

</div>
</div>

### parseSubstitution() {#a02e452afde6029066747c56b284c763e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubstitution ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54eda3ea9a0394aab44aadd148cfafa5c6693">allocator</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54eda7a4f49a6af0ccc6be090f967fde97f4e">basic_string</a>, <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54eda79abd8cf35895c560cc4d955c5355dbe">iostream</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab2d5d0d1cb71d3cef4032b3cad9fcb77">istream</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54eda28ddb00d829f83a7197c5c48a97a9e0d">ostream</a>, <a href="#a75901a36174c858ff110c053b914a27a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSeqId</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">string</a> and <a href="#a14568f28904fc376515d84ac11c3525f">AbstractManglingParser&lt; Derived, Alloc &gt;::Subs</a>.</p>

</div>
</div>

### parseTemplateArg() {#ad258b236255eaee1b5cf564889c97b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#a3368e1fa5fcd0aa5f68d7fb8ed916ba8">AbstractManglingParser&lt; Derived, Alloc &gt;::isTemplateParamDecl</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a> and <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a>.</p>

</div>
</div>

### parseTemplateArgs() {#a397daba3d04112848d396591f8a67753}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArgs (bool TagTemplates=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="/web-llvm/docs/api/classes/node/#aae5cdb3eedc870de0873aed823149a3a">Node::getKind</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a>, <a href="#a82e5920b3e1f823bdde8266961e80282">AbstractManglingParser&lt; Derived, Alloc &gt;::OuterTemplateParams</a>, <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a> and <a href="#aec9744ac3abf5d2716bb11e45c9cf917">AbstractManglingParser&lt; Derived, Alloc &gt;::TemplateParams</a>.</p>

</div>
</div>

### parseTemplateParam() {#a3ddb8dda77894478155c13d71b74b49b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParam ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h/#ac71d1b2a381f0070e426cf362f0ef7e2">DEMANGLE_ASSERT</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a229ec0a06959ee93e9e5f24e3682b086">AbstractManglingParser&lt; Derived, Alloc &gt;::ForwardTemplateRefs</a>, <a href="/web-llvm/docs/api/classes/node/#aae5cdb3eedc870de0873aed823149a3a">Node::getKind</a>, <a href="#a1f03ac22bac5634ce6b7db97c3cbd22a">AbstractManglingParser&lt; Derived, Alloc &gt;::HasIncompleteTemplateParameterTracking</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#ab3cc1c2c83fddd665c43fdc006f419f9">AbstractManglingParser&lt; Derived, Alloc &gt;::parsePositiveInteger</a>, <a href="#ad176052ede893f358d8bdac88b4217fd">AbstractManglingParser&lt; Derived, Alloc &gt;::ParsingLambdaParamsAtLevel</a>, <a href="#a501dd094510fbe0374e96899a5bbc1ae">AbstractManglingParser&lt; Derived, Alloc &gt;::PermitForwardTemplateReferences</a> and <a href="#aec9744ac3abf5d2716bb11e45c9cf917">AbstractManglingParser&lt; Derived, Alloc &gt;::TemplateParams</a>.</p>

</div>
</div>

### parseTemplateParamDecl() {#a42f63ed33efd48464560c7a2808c2110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParamDecl (<a href="#a1520018fbee9a2889452cd7f161d380f">TemplateParamList</a> * Params)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#a1f03ac22bac5634ce6b7db97c3cbd22a">AbstractManglingParser&lt; Derived, Alloc &gt;::HasIncompleteTemplateParameterTracking</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a88ee8e4eea43084bd8964682683da88ca8627a9054b6f456c6e15d7a0d57a9030">NonType</a>, <a href="#accb905d272c3ae3dfc91b0959ba13b2e">AbstractManglingParser&lt; Derived, Alloc &gt;::NumSyntheticTemplateParameters</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/abstractmanglingparser/scopedtemplateparamlist/#a140b14da5ef0bf0f4f48f9aa8d57d837">AbstractManglingParser&lt; Derived, Alloc &gt;::ScopedTemplateParamList::params</a>, <a href="#a42f63ed33efd48464560c7a2808c2110">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParamDecl</a>, <a href="#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a>, <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a>, <a href="/web-llvm/docs/api/classes/podsmallvector/#a377ddf1320dc6c97a5143ee43add19bc">PODSmallVector&lt; T, N &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a88ee8e4eea43084bd8964682683da88ca278c491bdd8a53618c149c4ac790da34">Template</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a88ee8e4eea43084bd8964682683da88caa1fa27779242b4902f7ae3bdd5c6d508">Type</a>.</p>


<p>Referenced by <a href="#a42f63ed33efd48464560c7a2808c2110">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParamDecl</a>.</p>

</div>
</div>

### parseType() {#a40f2d5dba46e399d7c3e735456d0ae83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the &lt;type&gt; production.</p>

<p>Definition at line 2907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h/#a5b2ab89559cfa9c7fbfd635bec59e42d">DEMANGLE_FALLTHROUGH</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ab67ef02b75c3226cfe0b2791e2b48b06a74accfde3d3f8e8a27c326eba229d16c">LValue</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#ae83a62e754488540dc738e5b99d4c6f3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBareSourceName</a>, <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>, <a href="#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ab67ef02b75c3226cfe0b2791e2b48b06ac756c8b5e0e5217b000321397a40be7e">RValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a14568f28904fc376515d84ac11c3525f">AbstractManglingParser&lt; Derived, Alloc &gt;::Subs</a> and <a href="#ad2facd968f12de1854d4a721a2dfc44e">AbstractManglingParser&lt; Derived, Alloc &gt;::TryToParseTemplateArgs</a>.</p>


<p>Referenced by <a href="#a42f63ed33efd48464560c7a2808c2110">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParamDecl</a> and <a href="#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a>.</p>

</div>
</div>

### parseUnnamedTypeName() {#afca1629c8e841245333f3fb9724a12d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnnamedTypeName (<a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate">NameState</a> * State)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2954 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="/web-llvm/docs/api/classes/nodearray/#a4be77753e259000aa41e1e284d1e193a">NodeArray::empty</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#a3368e1fa5fcd0aa5f68d7fb8ed916ba8">AbstractManglingParser&lt; Derived, Alloc &gt;::isTemplateParamDecl</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/abstractmanglingparser/scopedtemplateparamlist/#a140b14da5ef0bf0f4f48f9aa8d57d837">AbstractManglingParser&lt; Derived, Alloc &gt;::ScopedTemplateParamList::params</a>, <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>, <a href="#ad176052ede893f358d8bdac88b4217fd">AbstractManglingParser&lt; Derived, Alloc &gt;::ParsingLambdaParamsAtLevel</a>, <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="#aec9744ac3abf5d2716bb11e45c9cf917">AbstractManglingParser&lt; Derived, Alloc &gt;::TemplateParams</a>.</p>


<p>Referenced by <a href="#ab438097f6264945733cb782df179497a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExprPrimary</a>.</p>

</div>
</div>

### parseUnqualifiedName() {#ad9d8e005bfc2e208e217c9af2c0948a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnqualifiedName (<a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate">NameState</a> * State, <a href="/web-llvm/docs/api/classes/node">Node</a> * Scope, <a href="/web-llvm/docs/api/structs/modulename">ModuleName</a> * Module)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2953 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecheckdebugify-cpp/#a85892acfa8970627e9bd9c9815f15c25">Module</a>, <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a>, <a href="#a00b461f41241f99015a6dd2ea2e08425">AbstractManglingParser&lt; Derived, Alloc &gt;::parseModuleNameOpt</a> and <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a>.</p>

</div>
</div>

### parseUnresolvedName() {#a5163ef18f80446740383bc2b0a438346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnresolvedName (bool Global)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the &lt;unresolved-name&gt; production.</p>

<p>Definition at line 3026 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h/#ac71d1b2a381f0070e426cf362f0ef7e2">DEMANGLE_ASSERT</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a> and <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>.</p>

</div>
</div>

### parseUnresolvedType() {#af1d226f20e5973a826cfad43af1f5a10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnresolvedType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a> and <a href="#a14568f28904fc376515d84ac11c3525f">AbstractManglingParser&lt; Derived, Alloc &gt;::Subs</a>.</p>

</div>
</div>

### parseUnscopedName() {#ad14e711f8193cc40f52cff65679632e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnscopedName (<a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate">NameState</a> * State, bool * isSubstName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2956 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="/web-llvm/docs/api/classes/node/#aae5cdb3eedc870de0873aed823149a3a">Node::getKind</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinecheckdebugify-cpp/#a85892acfa8970627e9bd9c9815f15c25">Module</a>.</p>

</div>
</div>

### parseVectorType() {#ae51d6fdacbdc3d6de3e603bc6431fd0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node * AbstractManglingParser&lt; Derived, Alloc &gt;::parseVectorType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2909 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#a01bdc82f9718d4dd242186d0f57494be">AbstractManglingParser&lt; Derived, Alloc &gt;::getDerived</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a> and <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>.</p>

</div>
</div>

### popTrailingNodeArray() {#ae9e402b53d087f61d69de824b26483ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeArray AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray (size_t FromPosition)</td>
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



<p>Definition at line 2839 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/demangleconfig-h/#ac71d1b2a381f0070e426cf362f0ef7e2">DEMANGLE_ASSERT</a>, <a href="#a9f5a19c97b7d16ce2d6b911af8848e0f">AbstractManglingParser&lt; Derived, Alloc &gt;::makeNodeArray</a> and <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a>.</p>


<p>Referenced by <a href="#a2455cf780fc263477c2e51423b24b17d">AbstractManglingParser&lt; Derived, Alloc &gt;::parseConversionExpr</a>, <a href="#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>, <a href="#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>, <a href="#a8d2caa022ed2433c546a336a45aca7d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFunctionType</a>, <a href="#aaa6cc7d6a5e9794e8853e726139a3215">AbstractManglingParser&lt; Derived, Alloc &gt;::parseRequiresExpr</a>, <a href="#a1f3e98e28c753d1afa3ea8e1e90d4cd8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubobjectExpr</a>, <a href="#ad258b236255eaee1b5cf564889c97b9a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArg</a>, <a href="#a397daba3d04112848d396591f8a67753">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArgs</a>, <a href="#a42f63ed33efd48464560c7a2808c2110">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParamDecl</a>, <a href="#afca1629c8e841245333f3fb9724a12d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnnamedTypeName</a> and <a href="#ad9d8e005bfc2e208e217c9af2c0948a0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnqualifiedName</a>.</p>

</div>
</div>

### reset() {#a1b63851387bacae895fc85aff9a16a25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AbstractManglingParser&lt; Derived, Alloc &gt;::reset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * First_, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Last_)</td>
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



<p>Definition at line 2813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="#a1c50663a20673e10d6e60d5686d1db84">AbstractManglingParser&lt; Derived, Alloc &gt;::ASTAllocator</a>, <a href="#a860222ba391900387ee2cb4436de6c35">AbstractManglingParser&lt; Derived, Alloc &gt;::First</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad469a27bf47c652db0a483eda3d92dde">AbstractManglingParser&lt; Derived, Alloc &gt;::Last</a>, <a href="#a24a860d924997390b4deb34b6bedb014">AbstractManglingParser&lt; Derived, Alloc &gt;::Names</a>, <a href="#accb905d272c3ae3dfc91b0959ba13b2e">AbstractManglingParser&lt; Derived, Alloc &gt;::NumSyntheticTemplateParameters</a>, <a href="#ad176052ede893f358d8bdac88b4217fd">AbstractManglingParser&lt; Derived, Alloc &gt;::ParsingLambdaParamsAtLevel</a>, <a href="#a501dd094510fbe0374e96899a5bbc1ae">AbstractManglingParser&lt; Derived, Alloc &gt;::PermitForwardTemplateReferences</a>, <a href="#a14568f28904fc376515d84ac11c3525f">AbstractManglingParser&lt; Derived, Alloc &gt;::Subs</a>, <a href="#aec9744ac3abf5d2716bb11e45c9cf917">AbstractManglingParser&lt; Derived, Alloc &gt;::TemplateParams</a> and <a href="#ad2facd968f12de1854d4a721a2dfc44e">AbstractManglingParser&lt; Derived, Alloc &gt;::TryToParseTemplateArgs</a>.</p>

</div>
</div>

### resolveForwardTemplateRefs() {#a5ad59b207f4802698845060996de7039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::resolveForwardTemplateRefs (<a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate">NameState</a> &amp; State)</td>
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



<p>Definition at line 2934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a229ec0a06959ee93e9e5f24e3682b086">AbstractManglingParser&lt; Derived, Alloc &gt;::ForwardTemplateRefs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aec9744ac3abf5d2716bb11e45c9cf917">AbstractManglingParser&lt; Derived, Alloc &gt;::TemplateParams</a>.</p>


<p>Referenced by <a href="#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ASTAllocator {#a1c50663a20673e10d6e60d5686d1db84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Alloc AbstractManglingParser&lt; Derived, Alloc &gt;::ASTAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a722c2b4e37700cadbb7aa93542a2e1be">AbstractManglingParser&lt; Derived, Alloc &gt;::make</a>, <a href="#a9f5a19c97b7d16ce2d6b911af8848e0f">AbstractManglingParser&lt; Derived, Alloc &gt;::makeNodeArray</a> and <a href="#a1b63851387bacae895fc85aff9a16a25">AbstractManglingParser&lt; Derived, Alloc &gt;::reset</a>.</p>

</div>
</div>

### First {#a860222ba391900387ee2cb4436de6c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* AbstractManglingParser&lt; Derived, Alloc &gt;::First</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#aa493f84f85dacf77dc2ecc4486d3cefe">AbstractManglingParser&lt; Derived, Alloc &gt;::AbstractManglingParser</a>, <a href="#a86496230b54123c7809ff85935781c2a">AbstractManglingParser&lt; Derived, Alloc &gt;::consume</a>, <a href="#a9addf9a0d1c44c3fbbe1c3d8a0ae83a2">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a207aeee46de5b6c65992ac90f49b4593">AbstractManglingParser&lt; Derived, Alloc &gt;::numLeft</a>, <a href="#a880f69acceab7bea831caf07b7ac88b8">AbstractManglingParser&lt; Derived, Alloc &gt;::parse</a>, <a href="#ae83a62e754488540dc738e5b99d4c6f3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBareSourceName</a>, <a href="#a926563f39f6be3c9955f9da1426357c7">AbstractManglingParser&lt; Derived, Alloc &gt;::parseBracedExpr</a>, <a href="#aba055fbad743818420d549a22f343b33">AbstractManglingParser&lt; Derived, Alloc &gt;::parseCtorDtorName</a>, <a href="#ab438097f6264945733cb782df179497a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExprPrimary</a>, <a href="#a1854a21eaab3d2bc78f248dea1549288">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFloatingLiteral</a>, <a href="#a76df0d66308455708c032df20fc9fd44">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFoldExpr</a>, <a href="#aa0d666ea75f1150667fa90343823c5f4">AbstractManglingParser&lt; Derived, Alloc &gt;::parseLocalName</a>, <a href="#ac6781c18ea73250ec27554caee355867">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNestedName</a>, <a href="#a7a883d2cd34f663f0e86b120a77b9d6b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNumber</a>, <a href="#af04580d21e34e26a738a01750324ab0b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorEncoding</a>, <a href="#afaf6f6bc14e6958548705d184de98385">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorName</a>, <a href="#ab75e1a82e3ca70f21faf74933f2471b0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseQualifiedType</a>, <a href="#a75901a36174c858ff110c053b914a27a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSeqId</a>, <a href="#ace6000853f038505e58f9c498b85d60b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSourceName</a>, <a href="#a3c60ed5c7679aa84ef460dce84cd4777">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSpecialName</a>, <a href="#a02e452afde6029066747c56b284c763e">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubstitution</a>, <a href="#ad258b236255eaee1b5cf564889c97b9a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArg</a>, <a href="#a3ddb8dda77894478155c13d71b74b49b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParam</a>, <a href="#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a> and <a href="#a1b63851387bacae895fc85aff9a16a25">AbstractManglingParser&lt; Derived, Alloc &gt;::reset</a>.</p>

</div>
</div>

### ForwardTemplateRefs {#a229ec0a06959ee93e9e5f24e3682b086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PODSmallVector&lt;ForwardTemplateReference *, 4&gt; AbstractManglingParser&lt; Derived, Alloc &gt;::ForwardTemplateRefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2797 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/abstractmanglingparser/namestate/#a5ea3bdd076ba31ca6e06cb40948f11da">AbstractManglingParser&lt; Derived, Alloc &gt;::NameState::NameState</a>, <a href="#a3ddb8dda77894478155c13d71b74b49b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParam</a> and <a href="#a5ad59b207f4802698845060996de7039">AbstractManglingParser&lt; Derived, Alloc &gt;::resolveForwardTemplateRefs</a>.</p>

</div>
</div>

### HasIncompleteTemplateParameterTracking {#a1f03ac22bac5634ce6b7db97c3cbd22a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::HasIncompleteTemplateParameterTracking = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a2b75300a1f35f873c5413c3218c0ceea">AbstractManglingParser&lt; Derived, Alloc &gt;::parseConstraintExpr</a>, <a href="#a3ddb8dda77894478155c13d71b74b49b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParam</a> and <a href="#a42f63ed33efd48464560c7a2808c2110">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParamDecl</a>.</p>

</div>
</div>

### Last {#ad469a27bf47c652db0a483eda3d92dde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* AbstractManglingParser&lt; Derived, Alloc &gt;::Last</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#aa493f84f85dacf77dc2ecc4486d3cefe">AbstractManglingParser&lt; Derived, Alloc &gt;::AbstractManglingParser</a>, <a href="#a86496230b54123c7809ff85935781c2a">AbstractManglingParser&lt; Derived, Alloc &gt;::consume</a>, <a href="#a9addf9a0d1c44c3fbbe1c3d8a0ae83a2">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#ad71a4d2931be91da3148fe3279cbed2b">AbstractManglingParser&lt; Derived, Alloc &gt;::consumeIf</a>, <a href="#aac3534ca8248ab03a5f4551d4076e411">AbstractManglingParser&lt; Derived, Alloc &gt;::look</a>, <a href="#a207aeee46de5b6c65992ac90f49b4593">AbstractManglingParser&lt; Derived, Alloc &gt;::numLeft</a>, <a href="#a880f69acceab7bea831caf07b7ac88b8">AbstractManglingParser&lt; Derived, Alloc &gt;::parse</a>, <a href="#aa0d666ea75f1150667fa90343823c5f4">AbstractManglingParser&lt; Derived, Alloc &gt;::parseLocalName</a>, <a href="#ab75e1a82e3ca70f21faf74933f2471b0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseQualifiedType</a> and <a href="#a1b63851387bacae895fc85aff9a16a25">AbstractManglingParser&lt; Derived, Alloc &gt;::reset</a>.</p>

</div>
</div>

### Names {#a24a860d924997390b4deb34b6bedb014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PODSmallVector&lt;Node *, 32&gt; AbstractManglingParser&lt; Derived, Alloc &gt;::Names</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a2455cf780fc263477c2e51423b24b17d">AbstractManglingParser&lt; Derived, Alloc &gt;::parseConversionExpr</a>, <a href="#a7597c6329192eea9889ca9669a7387f1">AbstractManglingParser&lt; Derived, Alloc &gt;::parseEncoding</a>, <a href="#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>, <a href="#a8d2caa022ed2433c546a336a45aca7d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseFunctionType</a>, <a href="#aaa6cc7d6a5e9794e8853e726139a3215">AbstractManglingParser&lt; Derived, Alloc &gt;::parseRequiresExpr</a>, <a href="#a1f3e98e28c753d1afa3ea8e1e90d4cd8">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubobjectExpr</a>, <a href="#ad258b236255eaee1b5cf564889c97b9a">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArg</a>, <a href="#a397daba3d04112848d396591f8a67753">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArgs</a>, <a href="#a42f63ed33efd48464560c7a2808c2110">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParamDecl</a>, <a href="#afca1629c8e841245333f3fb9724a12d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnnamedTypeName</a>, <a href="#ad9d8e005bfc2e208e217c9af2c0948a0">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnqualifiedName</a>, <a href="#ae9e402b53d087f61d69de824b26483ac">AbstractManglingParser&lt; Derived, Alloc &gt;::popTrailingNodeArray</a> and <a href="#a1b63851387bacae895fc85aff9a16a25">AbstractManglingParser&lt; Derived, Alloc &gt;::reset</a>.</p>

</div>
</div>

### NumSyntheticTemplateParameters {#accb905d272c3ae3dfc91b0959ba13b2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned AbstractManglingParser&lt; Derived, Alloc &gt;::NumSyntheticTemplateParameters[3] = {}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a42f63ed33efd48464560c7a2808c2110">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParamDecl</a> and <a href="#a1b63851387bacae895fc85aff9a16a25">AbstractManglingParser&lt; Derived, Alloc &gt;::reset</a>.</p>

</div>
</div>

### OuterTemplateParams {#a82e5920b3e1f823bdde8266961e80282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TemplateParamList AbstractManglingParser&lt; Derived, Alloc &gt;::OuterTemplateParams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a397daba3d04112848d396591f8a67753">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArgs</a>.</p>

</div>
</div>

### ParsingLambdaParamsAtLevel {#ad176052ede893f358d8bdac88b4217fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t AbstractManglingParser&lt; Derived, Alloc &gt;::ParsingLambdaParamsAtLevel = (size_t)-1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a3ddb8dda77894478155c13d71b74b49b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParam</a>, <a href="#afca1629c8e841245333f3fb9724a12d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnnamedTypeName</a> and <a href="#a1b63851387bacae895fc85aff9a16a25">AbstractManglingParser&lt; Derived, Alloc &gt;::reset</a>.</p>

</div>
</div>

### PermitForwardTemplateReferences {#a501dd094510fbe0374e96899a5bbc1ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::PermitForwardTemplateReferences = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#afaf6f6bc14e6958548705d184de98385">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorName</a>, <a href="#a3ddb8dda77894478155c13d71b74b49b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParam</a> and <a href="#a1b63851387bacae895fc85aff9a16a25">AbstractManglingParser&lt; Derived, Alloc &gt;::reset</a>.</p>

</div>
</div>

### Subs {#a14568f28904fc376515d84ac11c3525f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PODSmallVector&lt;Node *, 32&gt; AbstractManglingParser&lt; Derived, Alloc &gt;::Subs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2740 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a00b461f41241f99015a6dd2ea2e08425">AbstractManglingParser&lt; Derived, Alloc &gt;::parseModuleNameOpt</a>, <a href="#a760fd5933f1f67ecfe8008ed713ab5b4">AbstractManglingParser&lt; Derived, Alloc &gt;::parseName</a>, <a href="#ac6781c18ea73250ec27554caee355867">AbstractManglingParser&lt; Derived, Alloc &gt;::parseNestedName</a>, <a href="#a02e452afde6029066747c56b284c763e">AbstractManglingParser&lt; Derived, Alloc &gt;::parseSubstitution</a>, <a href="#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a>, <a href="#af1d226f20e5973a826cfad43af1f5a10">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnresolvedType</a> and <a href="#a1b63851387bacae895fc85aff9a16a25">AbstractManglingParser&lt; Derived, Alloc &gt;::reset</a>.</p>

</div>
</div>

### TemplateParams {#aec9744ac3abf5d2716bb11e45c9cf917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PODSmallVector&lt;TemplateParamList *, 4&gt; AbstractManglingParser&lt; Derived, Alloc &gt;::TemplateParams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a397daba3d04112848d396591f8a67753">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateArgs</a>, <a href="#a3ddb8dda77894478155c13d71b74b49b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseTemplateParam</a>, <a href="#afca1629c8e841245333f3fb9724a12d9">AbstractManglingParser&lt; Derived, Alloc &gt;::parseUnnamedTypeName</a>, <a href="#a1b63851387bacae895fc85aff9a16a25">AbstractManglingParser&lt; Derived, Alloc &gt;::reset</a>, <a href="#a5ad59b207f4802698845060996de7039">AbstractManglingParser&lt; Derived, Alloc &gt;::resolveForwardTemplateRefs</a> and <a href="/web-llvm/docs/api/classes/abstractmanglingparser/scopedtemplateparamlist/#a702222f4cfb0fa82353225f0a8e88d9b">AbstractManglingParser&lt; Derived, Alloc &gt;::ScopedTemplateParamList::ScopedTemplateParamList</a>.</p>

</div>
</div>

### TryToParseTemplateArgs {#ad2facd968f12de1854d4a721a2dfc44e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AbstractManglingParser&lt; Derived, Alloc &gt;::TryToParseTemplateArgs = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#a2455cf780fc263477c2e51423b24b17d">AbstractManglingParser&lt; Derived, Alloc &gt;::parseConversionExpr</a>, <a href="#abb0edf66fe4cd9578df27e196bccf0b3">AbstractManglingParser&lt; Derived, Alloc &gt;::parseExpr</a>, <a href="#afaf6f6bc14e6958548705d184de98385">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorName</a>, <a href="#a40f2d5dba46e399d7c3e735456d0ae83">AbstractManglingParser&lt; Derived, Alloc &gt;::parseType</a> and <a href="#a1b63851387bacae895fc85aff9a16a25">AbstractManglingParser&lt; Derived, Alloc &gt;::reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### NumOps {#affe3131b4c58615ae6b038d03b971088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</td>
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



<p>Definition at line 3022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#af04580d21e34e26a738a01750324ab0b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorEncoding</a>.</p>

</div>
</div>

### Ops {#a9b2101383b3f36e0198f035592926a35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Derived, typename Alloc&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OperatorInfo AbstractManglingParser&lt; Derived, Alloc &gt;::Ops[]</td>
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



<p>Definition at line 3021 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a>.</p>


<p>Referenced by <a href="#af04580d21e34e26a738a01750324ab0b">AbstractManglingParser&lt; Derived, Alloc &gt;::parseOperatorEncoding</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h">ItaniumDemangle.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
