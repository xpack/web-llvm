---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/irposition
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `IRPosition` Struct Reference

<p>Helper to describe and deal with positions in the LLVM-IR. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::IRPosition { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base struct for all "concrete attribute" deductions. <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c0bf0d84bda6e0ec2d44d83850a328a">CallBaseContext</a> = <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind : char { <a href="#a53f576f97e0dfa8314afb16bd74a76d0">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The positions we distinguish in the IR. <a href="#a53f576f97e0dfa8314afb16bd74a76d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#aa8ead3291dbfc9e4fd79c301675bea2d">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The encoding of the <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> is a combination of a pointer and two encoding bits. <a href="#aa8ead3291dbfc9e4fd79c301675bea2d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af247a28fd83cea9873d310162110439f">IRPosition</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor available to create invalid positions implicitly. <a href="#af247a28fd83cea9873d310162110439f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bdb1c175975c7b217961699ccc77341">IRPosition</a> (void *Ptr, const CallBaseContext *CBContext=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Private constructor for special values only! <a href="#a0bdb1c175975c7b217961699ccc77341">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae38bce8519927031b00cf74edf7604dd">IRPosition</a> (Value &amp;AnchorVal, Kind PK, const CallBaseContext *CBContext=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> anchored at <span class="doxyComputerOutput">AnchorVal</span> with kind/argument numbet <span class="doxyComputerOutput">PK</span>. <a href="#ae38bce8519927031b00cf74edf7604dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac02b38a827832b09e3a9d3ea8e004213">IRPosition</a> (Use &amp;U, Kind PK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> for the use <span class="doxyComputerOutput">U</span>. <a href="#ac02b38a827832b09e3a9d3ea8e004213">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800fdefc42edd314b247d662316b5cb1">operator==</a> (const IRPosition &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3348a66521dda8655c4e19128bddb12a">operator!=</a> (const IRPosition &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a38c565f80b4b9de4b17af8b043382d">operator void *</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a5a38c565f80b4b9de4b17af8b043382d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f40f87a556db81bd2403007b83acce7">getAnchorValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value this abstract attribute is anchored with. <a href="#a9f40f87a556db81bd2403007b83acce7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a054de50dbf11b87063f6a32f3bccee80">getAssociatedFunction</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the associated function, if any. <a href="#a054de50dbf11b87063f6a32f3bccee80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a265735d2c2edc0a1a03611e7aadd24cd">getAssociatedArgument</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the associated argument, if any. <a href="#a265735d2c2edc0a1a03611e7aadd24cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8dd312c8d0f11d5519b3d5e264ac5f9">isFnInterfaceKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the position refers to a function interface, that is the function scope, the function return, or an argument. <a href="#ac8dd312c8d0f11d5519b3d5e264ac5f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79c71e9c03aff7ec01197395cab4e521">isFunctionScope</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a function or call site position. <a href="#a79c71e9c03aff7ec01197395cab4e521">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa339f4513a2704e8e2dadb6a92faab3">getAnchorScope</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> surrounding the anchor value. <a href="#afa339f4513a2704e8e2dadb6a92faab3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cdc54db452dfdce67b7f0713f822f71">getCtxI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the context instruction, if any. <a href="#a5cdc54db452dfdce67b7f0713f822f71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96130007e2acc25ee2ed2dd8f08f3e18">getAssociatedValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value this abstract attribute is associated with. <a href="#a96130007e2acc25ee2ed2dd8f08f3e18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">getAssociatedType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type this abstract attribute is associated with. <a href="#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4930f70e8a125f3d0a45a777adc3b305">getCalleeArgNo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the callee argument number of the associated value if it is an argument or call site argument, otherwise a negative value. <a href="#a4930f70e8a125f3d0a45a777adc3b305">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac74aa0fe9252fce4caabf80617085afa">getCallSiteArgNo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the call site argument number of the associated value if it is an argument or call site argument, otherwise a negative value. <a href="#ac74aa0fe9252fce4caabf80617085afa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a40b5fffb32c10d26633893df3b21ea">getAttrIdx</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index in the attribute list for this position. <a href="#a1a40b5fffb32c10d26633893df3b21ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7a3b4198c15b98d1689f769b8f07126">getAttrListAnchor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value attributes are attached to. <a href="#ab7a3b4198c15b98d1689f769b8f07126">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4081fd08df96363717c46a40ea774794">getAttrList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attributes associated with this function or call site scope. <a href="#a4081fd08df96363717c46a40ea774794">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a167c9f2ddb243187bdd2313de8586458">setAttrList</a> (const AttributeList &amp;AttrList) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the attributes associated with this function or call site scope. <a href="#a167c9f2ddb243187bdd2313de8586458">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7547d953171225ca4aea8c69ccabb7c">getNumArgs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of arguments associated with this function or call site scope. <a href="#ae7547d953171225ca4aea8c69ccabb7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9854202d54cc31542b08f1822ceee85d">getArg</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return theargument <span class="doxyComputerOutput">ArgNo</span> associated with this function or call site scope. <a href="#a9854202d54cc31542b08f1822ceee85d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a53f576f97e0dfa8314afb16bd74a76d0">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea16db681aa18f4eded0015e284fdfe5">getPositionKind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the associated position kind. <a href="#aea16db681aa18f4eded0015e284fdfe5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fa1cd6176ec069f35692b6748d057c7">isAnyCallSitePosition</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec15d884ee42b3559536c100446d54a7">isArgumentPosition</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the position is an argument or call site argument. <a href="#aec15d884ee42b3559536c100446d54a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae11c0e8ba89a3f9a29a09466e9aaaf10">stripCallBaseContext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the same position without the call base context. <a href="#ae11c0e8ba89a3f9a29a09466e9aaaf10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3c0bf0d84bda6e0ec2d44d83850a328a">CallBaseContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e5f6784c446af664c5c0f6ab3c9fa26">getCallBaseContext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the call base context from the position. <a href="#a8e5f6784c446af664c5c0f6ab3c9fa26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e87ff0b4410e061ceac8ca9fc7e46b1">hasCallBaseContext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the position has any call base context. <a href="#a1e87ff0b4410e061ceac8ca9fc7e46b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a018464cb036d2011ae48b568d0451df4">getArgNo</a> (bool CallbackCalleeArgIfApplicable) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the callee argument number of the associated value if it is an argument or call site argument. <a href="#a018464cb036d2011ae48b568d0451df4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc36b7035d1e165c8738c36823a815e">verify</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify internal invariants. <a href="#adcc36b7035d1e165c8738c36823a815e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca0130086cc6ea1961e712c469542ff3">getAsValuePtr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the underlying pointer as <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, valid for all positions but IRP_CALL_SITE_ARGUMENT. <a href="#aca0130086cc6ea1961e712c469542ff3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc11ff1c9d0746ed2a3b9950a669bf66">getAsUsePtr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the underlying pointer as <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *, valid only for IRP_CALL_SITE_ARGUMENT positions. <a href="#adc11ff1c9d0746ed2a3b9950a669bf66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c77fe669c7a0558225ef0aabc45dd35">isReturnPosition</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the encoding bits describe a returned or call site returned position. <a href="#a4c77fe669c7a0558225ef0aabc45dd35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fb5f4ad8a22f0fd74a9b59b3d510270">getEncodingBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the encoding bits. <a href="#a8fb5f4ad8a22f0fd74a9b59b3d510270">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointerintpair">PointerIntPair</a>&lt; void *, NumEncodingBits, char &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1deaa31948458d3cf5ee3a4a3b16772">Enc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The pointer with the encoding bits. <a href="#ad1deaa31948458d3cf5ee3a4a3b16772">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3c0bf0d84bda6e0ec2d44d83850a328a">CallBaseContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71eeb7bb75e2694ec61deee92c2f5a05">CBContext</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a71eeb7bb75e2694ec61deee92c2f5a05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bee165465962ee97307066da4f0fb13">value</a> (const Value &amp;V, const CallBaseContext *CBContext=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a position describing the value of <span class="doxyComputerOutput">V</span>. <a href="#a3bee165465962ee97307066da4f0fb13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a67bf6ab49ae2630d14e3159ef51cf4">inst</a> (const Instruction &amp;I, const CallBaseContext *CBContext=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a position describing the instruction <span class="doxyComputerOutput">I</span>. <a href="#a4a67bf6ab49ae2630d14e3159ef51cf4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8936a7eb7c9151c46513b192053afb2e">function</a> (const Function &amp;F, const CallBaseContext *CBContext=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a position describing the function scope of <span class="doxyComputerOutput">F</span>. <a href="#a8936a7eb7c9151c46513b192053afb2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2422bd05c002b7bb1686feaa13f08acd">returned</a> (const Function &amp;F, const CallBaseContext *CBContext=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a position describing the returned value of <span class="doxyComputerOutput">F</span>. <a href="#a2422bd05c002b7bb1686feaa13f08acd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67ee5b213c199841ee5f2d0a338e466e">argument</a> (const Argument &amp;Arg, const CallBaseContext *CBContext=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a position describing the argument <span class="doxyComputerOutput">Arg</span>. <a href="#a67ee5b213c199841ee5f2d0a338e466e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeef35bb007616add7418161b0313b56b">callsite_function</a> (const CallBase &amp;CB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a position describing the function scope of <span class="doxyComputerOutput">CB</span>. <a href="#aeef35bb007616add7418161b0313b56b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b55f73ab4057a8c3da9f32bd582f4b">callsite_returned</a> (const CallBase &amp;CB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a position describing the returned value of <span class="doxyComputerOutput">CB</span>. <a href="#a22b55f73ab4057a8c3da9f32bd582f4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c17a71e75898bbc42578a1c0b94c6b6">callsite_argument</a> (const CallBase &amp;CB, unsigned ArgNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a position describing the argument of <span class="doxyComputerOutput">CB</span> at position <span class="doxyComputerOutput">ArgNo</span>. <a href="#a4c17a71e75898bbc42578a1c0b94c6b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a882f8f4551f4267174aa36b7e3b68a97">callsite_argument</a> (AbstractCallSite ACS, unsigned ArgNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a position describing the argument of <span class="doxyComputerOutput">ACS</span> at position <span class="doxyComputerOutput">ArgNo</span>. <a href="#a882f8f4551f4267174aa36b7e3b68a97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad441c7387fd01e3cf86c9d16d9305495">function_scope</a> (const IRPosition &amp;IRP, const CallBaseContext *CBContext=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a position with function scope matching the "context" of <span class="doxyComputerOutput">IRP</span>. <a href="#ad441c7387fd01e3cf86c9d16d9305495">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a808f522f0e55d169bdbde1bcd6be6810">isReturnPosition</a> (char EncodingBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">EncodingBits</span> describe a returned or call site returned position. <a href="#a808f522f0e55d169bdbde1bcd6be6810">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75747cfadac3aa9128cb081adf37190a">EmptyKey</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> key values. <a href="#a75747cfadac3aa9128cb081adf37190a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515f72643916067816c01b28240e49d5">TombstoneKey</a></td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593d823cf50de540a86b8c87a391d932">NumEncodingBits</a> = ...</td>
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

<p>Helper to describe and deal with positions in the LLVM-IR.</p>


<p>A position in the IR is described by an anchor value and an "offset" that could be the argument number, for call sites and arguments, or an indicator of the "position kind". The kinds, specified in the <a href="#a53f576f97e0dfa8314afb16bd74a76d0">Kind</a> enum below, include the locations in the attribute list, i.a., function scope and return value, as well as a distinction between call sites and functions. Finally, there are floating values that do not have a corresponding attribute list position.</p>


<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CallBaseContext {#a3c0bf0d84bda6e0ec2d44d83850a328a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IRPosition::CallBaseContext =  CallBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#aa8ead3291dbfc9e4fd79c301675bea2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The encoding of the <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> is a combination of a pointer and two encoding bits.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENC_VALUE<a id="aa8ead3291dbfc9e4fd79c301675bea2da176ac1b747062e64d7cf7205ec3c7cb4"></a></td>
<td class="doxyEnumItemDescription"> (= 0b00)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENC_RETURNED_VALUE<a id="aa8ead3291dbfc9e4fd79c301675bea2da76b773d79f7049fa224677962173b828"></a></td>
<td class="doxyEnumItemDescription"> (= 0b01)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENC_FLOATING_FUNCTION<a id="aa8ead3291dbfc9e4fd79c301675bea2daa36674f12341cd90ab2a3d364fefc595"></a></td>
<td class="doxyEnumItemDescription"> (= 0b10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ENC_CALL_SITE_ARGUMENT_USE<a id="aa8ead3291dbfc9e4fd79c301675bea2da43b324dce05b5022d34d408b243e19c4"></a></td>
<td class="doxyEnumItemDescription"> (= 0b11)</td>
</tr>

</table>
</dd>
</dl>


<p>The values of the encoding bits are defined in the enum below. The pointer is either a Value* (for the first three encoding bit combinations) or Use* (for ENC_CALL_SITE_ARGUMENT_USE).</p>


<p>{</p>


<p>Definition at line 1052 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### Kind {#a53f576f97e0dfa8314afb16bd74a76d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::IRPosition::Kind : char</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The positions we distinguish in the IR.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRP_INVALID<a id="a53f576f97e0dfa8314afb16bd74a76d0afd1465681c30be50be67dcf938d73f5f"></a></td>
<td class="doxyEnumItemDescription">An invalid position</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRP_FLOAT<a id="a53f576f97e0dfa8314afb16bd74a76d0ae11f9a858d0a751bf2f9ea534be9457e"></a></td>
<td class="doxyEnumItemDescription">A position that is not associated with a spot suitable for attributes</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRP_RETURNED<a id="a53f576f97e0dfa8314afb16bd74a76d0a440e55ee67b08379ca74b24eb623789b"></a></td>
<td class="doxyEnumItemDescription">An attribute for the function return value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRP_CALL_SITE_RETURNED<a id="a53f576f97e0dfa8314afb16bd74a76d0a8bd94921b59d24f031ef7e64525e14f8"></a></td>
<td class="doxyEnumItemDescription">An attribute for a call site return value</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRP_FUNCTION<a id="a53f576f97e0dfa8314afb16bd74a76d0aa823f70d88660d88196943a3f09301da"></a></td>
<td class="doxyEnumItemDescription">An attribute for a function (scope)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRP_CALL_SITE<a id="a53f576f97e0dfa8314afb16bd74a76d0a4b033e6b489e8f06fe2819955eb8011b"></a></td>
<td class="doxyEnumItemDescription">An attribute for a call site (function scope)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRP_ARGUMENT<a id="a53f576f97e0dfa8314afb16bd74a76d0a212200718d90163dbf9fc504df5ff62f"></a></td>
<td class="doxyEnumItemDescription">An attribute for a function argument</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IRP_CALL_SITE_ARGUMENT<a id="a53f576f97e0dfa8314afb16bd74a76d0af5dba641c6a961375aee403f7cde7b31"></a></td>
<td class="doxyEnumItemDescription">An attribute for a call site argument</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IRPosition() {#af247a28fd83cea9873d310162110439f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRPosition::IRPosition ()</td>
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

<p>Default constructor available to create invalid positions implicitly.</p>


<p>All other positions need to be created explicitly through the appropriate static member function.</p>


<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a593cc2f204f7b2edc16ee222c37c3196">verify</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributes/#af7ed9c51a4767475d4395de37d802231">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributes::AAAMDAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdmaxnumworkgroups/#abaea187a24e570ce0c47523c8232b439">anonymous{AMDGPUAttributor.cpp}::AAAMDMaxNumWorkgroups::AAAMDMaxNumWorkgroups</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdsizerangeattribute/#ab69f1b8bb7c5246d9ec243fdcc7bf41e">anonymous{AMDGPUAttributor.cpp}::AAAMDSizeRangeAttribute::AAAMDSizeRangeAttribute</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aafoldruntimecall/#a788dfcc7e15c55db05b38ac2ff6e2f40">anonymous{OpenMPOpt.cpp}::AAFoldRuntimeCall::AAFoldRuntimeCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptoshared/#ad635617b57bbdc04bad39a5485ec0b5b">anonymous{OpenMPOpt.cpp}::AAHeapToShared::AAHeapToShared</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtracker/#adaa5e0f5d7f55275cd46ba5917a25481">anonymous{OpenMPOpt.cpp}::AAICVTracker::AAICVTracker</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfo/#a194b28808ce8385c21c2889c2b19e5ab">anonymous{OpenMPOpt.cpp}::AAKernelInfo::AAKernelInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aauniformworkgroupsize/#acfcbc26b81836cf24c50965bc0d7f98f">anonymous{AMDGPUAttributor.cpp}::AAUniformWorkGroupSize::AAUniformWorkGroupSize</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#acff34214cf426db8b010a1d977bd2899">llvm::AbstractAttribute::AbstractAttribute</a>, <a href="#a67ee5b213c199841ee5f2d0a338e466e">argument</a>, <a href="#a882f8f4551f4267174aa36b7e3b68a97">callsite_argument</a>, <a href="#a4c17a71e75898bbc42578a1c0b94c6b6">callsite_argument</a>, <a href="#aeef35bb007616add7418161b0313b56b">callsite_function</a>, <a href="#a22b55f73ab4057a8c3da9f32bd582f4b">callsite_returned</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributes/#a42bb2cd6393cce07af23cfc468a8e4a3">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributes::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdmaxnumworkgroups/#aad4cff313563f8b6bb6de08669d2051d">anonymous{AMDGPUAttributor.cpp}::AAAMDMaxNumWorkgroups::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aauniformworkgroupsize/#a96036029850b3ab1f23cfce88962d88a">anonymous{AMDGPUAttributor.cpp}::AAUniformWorkGroupSize::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aafoldruntimecall/#a976ae83bc84b2d91c2859dd2196ba1dc">anonymous{OpenMPOpt.cpp}::AAFoldRuntimeCall::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptoshared/#a77867478c7f5c6ae9168ca7211c97f1d">anonymous{OpenMPOpt.cpp}::AAHeapToShared::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtracker/#ab7d0fb185c728add8067642433e5640d">anonymous{OpenMPOpt.cpp}::AAICVTracker::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfo/#a01e0d5d490f9eabb3ba09c95c4f5e695">anonymous{OpenMPOpt.cpp}::AAKernelInfo::createForPosition</a>, <a href="#a8936a7eb7c9151c46513b192053afb2e">function</a>, <a href="#ad441c7387fd01e3cf86c9d16d9305495">function_scope</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a5f2500e712b42f1383181348ca06aefd">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="#a4a67bf6ab49ae2630d14e3159ef51cf4">inst</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a0b23d1cedd8202d1b786e1ab43313084">llvm::AbstractAttribute::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a651e22db115dbbeacdd4c9ded06f9af3">llvm::AbstractAttribute::isValidIRPositionForUpdate</a>, <a href="#a3348a66521dda8655c4e19128bddb12a">operator!=</a>, <a href="#a800fdefc42edd314b247d662316b5cb1">operator==</a>, <a href="#a2422bd05c002b7bb1686feaa13f08acd">returned</a>, <a href="#ae11c0e8ba89a3f9a29a09466e9aaaf10">stripCallBaseContext</a> and <a href="#a3bee165465962ee97307066da4f0fb13">value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### IRPosition() {#a0bdb1c175975c7b217961699ccc77341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRPosition::IRPosition (void * Ptr, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3c0bf0d84bda6e0ec2d44d83850a328a">CallBaseContext</a> * CBContext=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Private constructor for special values only!</p>

<p>Definition at line 949 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### IRPosition() {#ae38bce8519927031b00cf74edf7604dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRPosition::IRPosition (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; AnchorVal, <a href="#a53f576f97e0dfa8314afb16bd74a76d0">Kind</a> PK, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3c0bf0d84bda6e0ec2d44d83850a328a">CallBaseContext</a> * CBContext=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> anchored at <span class="doxyComputerOutput">AnchorVal</span> with kind/argument numbet <span class="doxyComputerOutput">PK</span>.</p>

<p>Definition at line 955 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### IRPosition() {#ac02b38a827832b09e3a9d3ea8e004213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRPosition::IRPosition (<a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp; U, <a href="#a53f576f97e0dfa8314afb16bd74a76d0">Kind</a> PK)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> for the use <span class="doxyComputerOutput">U</span>.</p>


<p>The position kind <span class="doxyComputerOutput">PK</span> needs to be IRP_CALL_SITE_ARGUMENT, the anchor value is the user, the associated value the used value.</p>


<p>Definition at line 1010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator void \*() {#a5a38c565f80b4b9de4b17af8b043382d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRPosition::operator void * ()</td>
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


<p>Conversion into a void * to allow reuse of pointer hashing.</p>


<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### operator!=() {#a3348a66521dda8655c4e19128bddb12a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRPosition::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; RHS)</td>
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



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a800fdefc42edd314b247d662316b5cb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRPosition::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; RHS)</td>
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



<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnchorScope() {#afa339f4513a2704e8e2dadb6a92faab3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::IRPosition::getAnchorScope ()</td>
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

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> surrounding the anchor value.</p>

<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a9f40f87a556db81bd2403007b83acce7">getAnchorValue</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aainterfnreachability/#a8d69513ffd7a2b6d5ecea50eaf8b7673">llvm::AAInterFnReachability::canReach</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ae4b9f7a4322b4668f7fd018deef3e839">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::changeToSPMDMode</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#abbea65eed8b9b7cd07f0b8eef53df6f5">llvm::Attributor::checkForAllUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a9e78a16876b18d86097c67afa39bc090">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::checkUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoundefimpl/#acbaeee5dbc1a9493254186f8908f0c9f">anonymous{AttributorAttributes.cpp}::AANoUndefImpl::followUseInMBEC</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ae86be98f39008a27ba987e282fc8dc2c">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::genericValueTraversal</a>, <a href="#a054de50dbf11b87063f6a32f3bccee80">getAssociatedFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a86b1638912d3f2fbeaf9edffdaa00c10">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::getAsStr</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#ae92d755a80dec605503e2ba653765360">llvm::Attributor::getAssumedSimplifiedValues</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#aa5a45de2ff151caaae105b2aa429f35b">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getConstantRangeFromLVI</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#aa917f47e75cf32ee8a1abf71f2ebde01">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getConstantRangeFromSCEV</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ad06b99b6c5abffb1da312f75775f2f08">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getKnownStateFromValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a0b1acdea3aaa8e166e24b51e22def764">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getSCEV</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#aeda99db80deee5e043ee85bd09835da9">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::getSize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#ae957d55f18d016455143fa3b219c5203">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::giveUpOnIntraprocedural</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#ad567ae138977391ddcc0d292749aecc8">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::handleCallees</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a4366c809736e919b276b5cda925d17ac">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleLoadInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ad0fe28a9dccc66e85a05b9447f4141ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handlePHINode</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a49114a789143912efbf912250aea8397">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleSelectInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaassumptioninfocallsite/#a9ff13f2caa99f818de5c88147552bab2">anonymous{AttributorAttributes.cpp}::AAAssumptionInfoCallSite::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadenormalfpmathfunction/#ab9ac902089ba2b707e62211f6e6fb297">anonymous{AttributorAttributes.cpp}::AADenormalFPMathFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a424871cbef50e8414bb8bbed3a4068db">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a5522acc0a362d7bea43440e227660448">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocapturecallsitereturned/#abf28dca4e7e8f438ff9600a463057881">anonymous{AttributorAttributes.cpp}::AANoCaptureCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoundeffloating/#a10d30d8aa39878aaa802fa9036093945">anonymous{AttributorAttributes.cpp}::AANoUndefFloating::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a92d1a2aa02b302934a11d953531de329">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aawillreturnfunction/#aa650c2ac2aadb7358a01e9f85de431f4">anonymous{AttributorAttributes.cpp}::AAWillReturnFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a434c328cc87725efcfb56d78ca310e56">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#ac3b3ae3662af2dcad3cab15f9ba148d4">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackercallsite/#acd39051ae7085c6e8a7cc9bc23454500">anonymous{OpenMPOpt.cpp}::AAICVTrackerCallSite::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ac5c4384a376959ec882f7650e427dbb5">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#af471b1ff6b59d2257a9e1e301d173015">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#aaa8ee7d6ed01d35fd4b92fa9acc0eb1d">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a3ab97c855b4dcf01f5b3de1c50c98018">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a28ca3a54ea9ef7dd53412258dc067de3">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a532d694575abb82423e79aedce3437cc">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#aeb97ea777b4c90532ce50e3f1bedcac6">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::isAssumedDeadInternalFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a5749980418be3808e831c1189b77f829">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::isEdgeDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a0fdc6cad0c749330f186d0415048e2cd">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::isExecutedByInitialThreadOnly</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a6d53d8df2e0ea40eee8a7349563a9df7">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::isExecutedInAlignedRegion</a>, <a href="/web-llvm/docs/api/structs/llvm/aanoalias/#a0a95494aa0152eb057e6e9ca25572f87">llvm::AANoAlias::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aanonnull/#ad13f5148dfe5bbfa20ec5cdabfcb8547">llvm::AANonNull::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#a0a41d500fe5dcf2f575b99316d25ec30">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::isKnownNoAliasDueToNoAliasPreservation</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#aa706a9b987f484bb0ac2c16422522dbc">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a665e880cc41e9fd97416741590e2e0d0">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a2c8f5eab9499a8b7a3238177f2ecf52c">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#af60845674c792fb83289ea7695d3807e">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::mayAliasWithArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a8d09e795aeee61f61bd7d8ec5383a067">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::recurseForValue</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#ae2b97aec15d3a340e6d2eab0f467aa0a">llvm::Attributor::shouldInitialize</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#afc379e94b702009982a10bb57c4a9e7a">llvm::Attributor::shouldUpdateAA</a>, <a href="/web-llvm/docs/api/classes/llvm/subsumingpositioniterator/#a88c3ecf0e220e6dcd1afee9f86c8d806">llvm::SubsumingPositionIterator::SubsumingPositionIterator</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaassumptioninfocallsite/#af16220fe3fc119680f375c4538494003">anonymous{AttributorAttributes.cpp}::AAAssumptionInfoCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#abe94b0d36f169e52ede6a35d6ac41859">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a6aaeb440ac0f45225f89b6b83444db1a">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamustprogresscallsite/#a03cbaff1b92ba39f9f8b6e672c2c9d1e">anonymous{AttributorAttributes.cpp}::AAMustProgressCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a2b832055235bac7e33fee8273b9c0211">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanorecursefunction/#a70d0199665a55282a85300405acf7419">anonymous{AttributorAttributes.cpp}::AANoRecurseFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesargument/#a2cc688aac3b055fb8d0cca7033823473">anonymous{AttributorAttributes.cpp}::AAPotentialValuesArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsitereturned/#a326827ab35aa09c37cb1a4ee329f67ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a8f6027dabb6a1e32d6d01e904d6372a0">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaundefinedbehaviorimpl/#ae455d1ecbeb7d95762d758c9aae70512">anonymous{AttributorAttributes.cpp}::AAUndefinedBehaviorImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a8178893fef2816f4172536f259aa6450">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackercallsite/#a02ca92064e58264c2b89a838efeb545a">anonymous{OpenMPOpt.cpp}::AAICVTrackerCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackerfunction/#a8e6bda36d87255e722de98932c92fb60">anonymous{OpenMPOpt.cpp}::AAICVTrackerFunction::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackerfunctionreturned/#aeb5f8b50b9a352fa5ba67cc4fb084b63">anonymous{OpenMPOpt.cpp}::AAICVTrackerFunctionReturned::updateImpl</a>.</p>

</div>
</div>

### getAnchorValue() {#a9f40f87a556db81bd2403007b83acce7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value &amp; llvm::IRPosition::getAnchorValue ()</td>
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

<p>Return the value this abstract attribute is anchored with.</p>


<p>The anchor value might not be the associated value if the latter is not sufficient to determine where arguments will be manifested. This is, so far, only the case for call site arguments as the value is not sufficient to pinpoint them. Instead, we can use the call site as an anchor.</p>


<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaglobalvalueinfofloating/#ab7660504ac6ac15f209047da7f39755a">anonymous{AttributorAttributes.cpp}::AAGlobalValueInfoFloating::checkUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#aaffd2ef85a5bde3351bbc659c18c1ebe">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::forceSingleThreadPerWorkgroupHelper</a>, <a href="#ad441c7387fd01e3cf86c9d16d9305495">function_scope</a>, <a href="#afa339f4513a2704e8e2dadb6a92faab3">getAnchorScope</a>, <a href="#a9854202d54cc31542b08f1822ceee85d">getArg</a>, <a href="#a265735d2c2edc0a1a03611e7aadd24cd">getAssociatedArgument</a>, <a href="#a054de50dbf11b87063f6a32f3bccee80">getAssociatedFunction</a>, <a href="#a96130007e2acc25ee2ed2dd8f08f3e18">getAssociatedValue</a>, <a href="#a4081fd08df96363717c46a40ea774794">getAttrList</a>, <a href="#ab7a3b4198c15b98d1689f769b8f07126">getAttrListAnchor</a>, <a href="#a5cdc54db452dfdce67b7f0713f822f71">getCtxI</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#ad10f589dc1ab8e883ac7ee7d8957e965">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::getKnownStateFromValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ad06b99b6c5abffb1da312f75775f2f08">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getKnownStateFromValue</a>, <a href="#ae7547d953171225ca4aea8c69ccabb7c">getNumArgs</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#abc575c6c80287df1f51f698ec74e315e">llvm::Attributor::hasAttr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyfloating/#a327e58d77c06661b6d29951f0c441eba">anonymous{AttributorAttributes.cpp}::AAValueSimplifyFloating::initialize</a>, <a href="/web-llvm/docs/api/structs/llvm/aawillreturn/#ad363b24d67098ccf362ea38277ce9c61">llvm::AAWillReturn::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#a0a41d500fe5dcf2f575b99316d25ec30">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::isKnownNoAliasDueToNoAliasPreservation</a>, <a href="/web-llvm/docs/api/structs/llvm/aaglobalvalueinfo/#ac897780087e527a2deab188ff691610c">llvm::AAGlobalValueInfo::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aaisdead/#a4b6322e8503550536c5b31634875755a">llvm::AAIsDead::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaassumptioninfoimpl/#afd7017a3f3a492552121875308910210">anonymous{AttributorAttributes.cpp}::AAAssumptionInfoImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsiteargument/#a5d6050f7be56f61036d2d194ac7f66f8">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a0451826f9ecd21f9d963cc51401b1b4d">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#ae444282c6d6bc8d5e9905620c936d39e">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#a9a1b2954b9c4eb6f178a0c7e66581822">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a9971c8a3647ef1b5439ed7cd18aee749">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsiteargument/#a8779a21bd698d1abfabf4fc3f7fd64b9">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#abc4265ad1d2a8b43fcf0e44d4b4f6274">llvm::Attributor::manifestAttrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf6e500a902879012046ea1f8008d7e6">llvm::operator&lt;&lt;</a>, <a href="#a167c9f2ddb243187bdd2313de8586458">setAttrList</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#afc379e94b702009982a10bb57c4a9e7a">llvm::Attributor::shouldUpdateAA</a>, <a href="/web-llvm/docs/api/classes/llvm/subsumingpositioniterator/#a88c3ecf0e220e6dcd1afee9f86c8d806">llvm::SubsumingPositionIterator::SubsumingPositionIterator</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalleetocallsite/#a13627a051dc8e791e2f3f1699575605b">anonymous{AttributorAttributes.cpp}::AACalleeToCallSite&lt; AADereferenceable, AADereferenceableImpl &gt;::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaglobalvalueinfofloating/#ad2836a92e1e5443f5318dc46446a9197">anonymous{AttributorAttributes.cpp}::AAGlobalValueInfoFloating::updateImpl</a>.</p>

</div>
</div>

### getArg() {#a9854202d54cc31542b08f1822ceee85d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::IRPosition::getArg (unsigned ArgNo)</td>
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

<p>Return theargument <span class="doxyComputerOutput">ArgNo</span> associated with this function or call site scope.</p>

<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a9f40f87a556db81bd2403007b83acce7">getAnchorValue</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aecf2b6d6f052a378dd8f69fd1bb700b1">llvm::Function::getArg</a>, <a href="#a054de50dbf11b87063f6a32f3bccee80">getAssociatedFunction</a>, <a href="#aea16db681aa18f4eded0015e284fdfe5">getPositionKind</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a4b033e6b489e8f06fe2819955eb8011b">IRP_CALL_SITE</a> and <a href="#a53f576f97e0dfa8314afb16bd74a76d0aa823f70d88660d88196943a3f09301da">IRP_FUNCTION</a>.</p>

</div>
</div>

### getAssociatedArgument() {#a265735d2c2edc0a1a03611e7aadd24cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Argument * IRPosition::getAssociatedArgument ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the associated argument, if any.</p>

<p>Declaration at line 731 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 995 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#ac6baa801e4aea800984e760d5460662f">llvm::Function::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="#a9f40f87a556db81bd2403007b83acce7">getAnchorValue</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aecf2b6d6f052a378dd8f69fd1bb700b1">llvm::Function::getArg</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#a7e8ae04873ef7a72fbad37852333d290">llvm::AbstractCallSite::getCallArgOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#a401e244b78386047c64edc64f80ba9c0">llvm::AbstractCallSite::getCallbackUses</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#abe5141e594e4351ab2b1f5e73c736733">llvm::AbstractCallSite::getCalledFunction</a>, <a href="#ac74aa0fe9252fce4caabf80617085afa">getCallSiteArgNo</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#ab8b5e4f9ae59fedfc0f0be8395992ea3">llvm::AbstractCallSite::getNumArgOperands</a>, <a href="#aea16db681aa18f4eded0015e284fdfe5">getPositionKind</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a212200718d90163dbf9fc504df5ff62f">IRP_ARGUMENT</a> and <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#a2300cb53451591b87c7c5621c31643a2">llvm::AbstractCallSite::isCallbackCall</a>.</p>


<p>Referenced by <a href="#a054de50dbf11b87063f6a32f3bccee80">getAssociatedFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsiteargument/#a12170d0ad51240b43cda989d850ab479">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSiteArgument::initialize</a>, <a href="/web-llvm/docs/api/structs/llvm/aanocapture/#adb7886272a3ab071ecd4a576d865dc21">llvm::AANoCapture::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignargument/#a7d8cd3f39aea155598c6f6035c08e1b5">anonymous{AttributorAttributes.cpp}::AAAlignArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaaligncallsiteargument/#a92d005e0d6f5aecbf06dcb3eddf5a63f">anonymous{AttributorAttributes.cpp}::AAAlignCallSiteArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadargument/#a26e9414eff6220d3277d7f7095a03617">anonymous{AttributorAttributes.cpp}::AAIsDeadArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ae965a8b6001eaf1612d36d070594c706">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::manifest</a>, <a href="/web-llvm/docs/api/classes/llvm/subsumingpositioniterator/#a88c3ecf0e220e6dcd1afee9f86c8d806">llvm::SubsumingPositionIterator::SubsumingPositionIterator</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaaligncallsiteargument/#a90d18de54863d37fc84ed61f7f87455e">anonymous{AttributorAttributes.cpp}::AAAlignCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainstanceinfocallsiteargument/#a2cf1a30aab8cfc08c8d3d0b52005607a">anonymous{AttributorAttributes.cpp}::AAInstanceInfoCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsiteargument/#a5fb77be1b52b827ae66c6664e8e72420">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsiteargument/#a1866f24992e827ce8c69e245522b591f">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a31f2a80a770f0aa93c1fab42e9d41407">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocapturecallsiteargument/#af8af50bbe36f25d0fd0d35c5d6e973fa">anonymous{AttributorAttributes.cpp}::AANoCaptureCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a2b832055235bac7e33fee8273b9c0211">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreecallsiteargument/#a057aad39e2f87b33e18b53e28adbf90b">anonymous{AttributorAttributes.cpp}::AANoFreeCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>.</p>

</div>
</div>

### getAssociatedFunction() {#a054de50dbf11b87063f6a32f3bccee80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::IRPosition::getAssociatedFunction ()</td>
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

<p>Return the associated function, if any.</p>

<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3377eac88526e806d9d887c4a0ba2a73">llvm::dyn_cast_if_present</a>, <a href="#afa339f4513a2704e8e2dadb6a92faab3">getAnchorScope</a>, <a href="#a9f40f87a556db81bd2403007b83acce7">getAnchorValue</a> and <a href="#a265735d2c2edc0a1a03611e7aadd24cd">getAssociatedArgument</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaassumptioninfofunction/#a6f755c66c89370306331ff6ae5733abc">anonymous{AttributorAttributes.cpp}::AAAssumptionInfoFunction::AAAssumptionInfoFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaintrafnreachabilityfunction/#a03e718c0f5caa7631dc8a42d5f76caae">anonymous{AttributorAttributes.cpp}::AAIntraFnReachabilityFunction::AAIntraFnReachabilityFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a6982073fb3620dd727922e78e140af8f">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizePtrValue</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#afe7689e6835845cf28f72769c620e36c">llvm::Attributor::checkForAllCallSites</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a20e98490072ce547a896b89b31e110ed">llvm::Attributor::checkForAllInstructions</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a6a9714645534051ae76feba39ffbfb13">llvm::Attributor::checkForAllReadWriteInstructions</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a789d552f9e7bede3444f4350d05025af">llvm::Attributor::checkForAllReturnedValues</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdsizerangeattribute/#a67ae1ad562dccec0023641ab0e8fc48e">anonymous{AMDGPUAttributor.cpp}::AAAMDSizeRangeAttribute::emitAttributeIfNotDefaultAfterClamp</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#aaffd2ef85a5bde3351bbc659c18c1ebe">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::forceSingleThreadPerWorkgroupHelper</a>, <a href="#ad441c7387fd01e3cf86c9d16d9305495">function_scope</a>, <a href="#a9854202d54cc31542b08f1822ceee85d">getArg</a>, <a href="#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">getAssociatedType</a>, <a href="#a4081fd08df96363717c46a40ea774794">getAttrList</a>, <a href="#ab7a3b4198c15b98d1689f769b8f07126">getAttrListAnchor</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-8e3d49d8257628f3fde0f02587f68f13/#ad84c5f2b4d317dc0213d926f5bb71e1e">llvm::DOTGraphTraits&lt; AttributorCallGraph * &gt;::getNodeLabel</a>, <a href="#ae7547d953171225ca4aea8c69ccabb7c">getNumArgs</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#a45491e6a28947b2fc05de4cf7cc2b60f">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdflatworkgroupsize/#aef14a169486d41becf73e9ef0c945760">anonymous{AMDGPUAttributor.cpp}::AAAMDFlatWorkGroupSize::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdgpunoagpr/#a24f0bfcf3ec8d137adc269d4d3d3b86e">anonymous{AMDGPUAttributor.cpp}::AAAMDGPUNoAGPR::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdmaxnumworkgroups/#a323a4c1032fc5346fac2a3a3f00b7ade">anonymous{AMDGPUAttributor.cpp}::AAAMDMaxNumWorkgroups::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a798b523ae8591cd1d289cde6b234c1a6">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aauniformworkgroupsizefunction/#a648218e5a35c790866556b17f83ebcf0">anonymous{AMDGPUAttributor.cpp}::AAUniformWorkGroupSizeFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsiteargument/#a12170d0ad51240b43cda989d850ab479">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSiteArgument::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesreturned/#a71d3a2348721abffb57415ad91f74908">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a30f92140edfc60c710d849308c039161">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangereturned/#aed13ba291673dddaaa77b0ad21c4182d">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsitereturned/#a249035cbf55468e38187c74bfcd1204b">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aafoldruntimecallcallsitereturned/#a4ef5420ebe7c75b26c668ce810ddf6fb">anonymous{OpenMPOpt.cpp}::AAFoldRuntimeCallCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackercallsite/#acd39051ae7085c6e8a7cc9bc23454500">anonymous{OpenMPOpt.cpp}::AAICVTrackerCallSite::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#ab0859b33717bfc3149f2b4051949b5cb">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::initialize</a>, <a href="/web-llvm/docs/api/structs/llvm/aanocapture/#adb7886272a3ab071ecd4a576d865dc21">llvm::AANoCapture::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aanonnull/#ad13f5148dfe5bbfa20ec5cdabfcb8547">llvm::AANonNull::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aanosync/#a490ad1c48c230e1b6d37e946faee435a">llvm::AANoSync::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aaisdead/#a197b6c04a007a3c42624364e59f277f0">llvm::AAIsDead::isLiveInstSet</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a651e22db115dbbeacdd4c9ded06f9af3">llvm::AbstractAttribute::isValidIRPositionForUpdate</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#a508aceda7d46a30692b5bb3531e16dba">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdflatworkgroupsize/#a12dbc89def6756ecdc8e342cdf435dbc">anonymous{AMDGPUAttributor.cpp}::AAAMDFlatWorkGroupSize::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdgpunoagpr/#af41e92c622f732d73b21ab36030fa90b">anonymous{AMDGPUAttributor.cpp}::AAAMDGPUNoAGPR::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdmaxnumworkgroups/#a858b2d1d8e8f50fb043e650fb6197d91">anonymous{AMDGPUAttributor.cpp}::AAAMDMaxNumWorkgroups::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a35f541d4719ade66c4f0b78b04381af3">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aauniformworkgroupsizefunction/#a7e545ca98465fdb21ed037cb8cd05f06">anonymous{AMDGPUAttributor.cpp}::AAUniformWorkGroupSizeFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadenormalfpmathfunction/#a3930112816f97f9c7a92b22d4e332107">anonymous{AttributorAttributes.cpp}::AADenormalFPMathFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadreturned/#a5fbd0b238ec5abc8ab5dbc065b002c7a">anonymous{AttributorAttributes.cpp}::AAIsDeadReturned::manifest</a>, <a href="#a167c9f2ddb243187bdd2313de8586458">setAttrList</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#afc379e94b702009982a10bb57c4a9e7a">llvm::Attributor::shouldUpdateAA</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#a1757cce9d6fc5259895ec599716aa7fc">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdmaxnumworkgroups/#a78b300aeab76328894717218a55b32d1">anonymous{AMDGPUAttributor.cpp}::AAAMDMaxNumWorkgroups::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a6e7ec06ac86c48e6d651e37817ed7359">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aauniformworkgroupsizefunction/#a8aba32ec039ca723fa00f67c6f462cfa">anonymous{AMDGPUAttributor.cpp}::AAUniformWorkGroupSizeFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadenormalfpmathfunction/#a40c2cb36cf0ed7535884f2e86de3aa55">anonymous{AttributorAttributes.cpp}::AADenormalFPMathFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationcallsite/#a36ef96efb68b331087c86a5c9920173c">anonymous{AttributorAttributes.cpp}::AAMemoryLocationCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a2b832055235bac7e33fee8273b9c0211">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesargument/#a2cc688aac3b055fb8d0cca7033823473">anonymous{AttributorAttributes.cpp}::AAPotentialValuesArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsitereturned/#a326827ab35aa09c37cb1a4ee329f67ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackercallsitereturned/#a816b7da08e9b4f98b437bded6580302a">anonymous{OpenMPOpt.cpp}::AAICVTrackerCallSiteReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#aa952da5010350f12b8d601516719d22b">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdsizerangeattribute/#a29bd4b6b1ce02623406f833daf4668cc">anonymous{AMDGPUAttributor.cpp}::AAAMDSizeRangeAttribute::updateImplImpl</a>.</p>

</div>
</div>

### getAssociatedType() {#a6a0e4ff765ad5ab3c9a53c917f3cf1cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::IRPosition::getAssociatedType ()</td>
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

<p>Return the type this abstract attribute is associated with.</p>

<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a054de50dbf11b87063f6a32f3bccee80">getAssociatedFunction</a>, <a href="#a96130007e2acc25ee2ed2dd8f08f3e18">getAssociatedValue</a>, <a href="#aea16db681aa18f4eded0015e284fdfe5">getPositionKind</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#acdd05db170cbfee8a0fcbc047b8504e5">llvm::Function::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="#a53f576f97e0dfa8314afb16bd74a76d0a440e55ee67b08379ca74b24eb623789b">IRP_RETURNED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliasimpl/#a245291f1391c73bdd3abfa54d4fc2179">anonymous{AttributorAttributes.cpp}::AANoAliasImpl::AANoAliasImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#a7e85dae54d01cf0410db2477b07152d9">llvm::AAValueConstantRange::AAValueConstantRange</a>, <a href="/web-llvm/docs/api/structs/llvm/aavaluesimplify/#ae7bf9ba7de768737791369b8a4f2144d">llvm::AAValueSimplify::AAValueSimplify</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a135bd9f6645b2fba9c7652cbd7b8a157">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::addValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesimpl/#a5701c4158af221ec50dcd7fcd971b67e">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesImpl::fillSetWithConstantValues</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialvalues/#afbaf43cc6d56847d8f8202623b7f61e7">llvm::AAPotentialValues::getSingleValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaaddressspaceimpl/#ababfc1ae6bfe4af0f71dec574016e677">anonymous{AttributorAttributes.cpp}::AAAddressSpaceImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/llvm/aanonnull/#ad13f5148dfe5bbfa20ec5cdabfcb8547">llvm::AANonNull::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aaaddressspace/#a63d0bb6e63c83c8a5c8c641c4c6aa630">llvm::AAAddressSpace::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aaalign/#a46d88fcef3d7d691eb17d3eb537dedfe">llvm::AAAlign::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aaallocationinfo/#a4640ec7a4d5d3d7b9cd3b0204f986077">llvm::AAAllocationInfo::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aadereferenceable/#abc9713fe6e5299f52649a0213cf7f3d6">llvm::AADereferenceable::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a1d7efda60b9905c2287555f2e3e97e32">llvm::AAMemoryBehavior::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ae548fb21c1de2eb3ad47389ae31488f3">llvm::AAMemoryLocation::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aanoalias/#acae0109819a6600fc6ddd106a82e2f45">llvm::AANoAlias::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aanocapture/#a0639b327e46a46c804bc64ef0c12a7e1">llvm::AANoCapture::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aanofpclass/#a43a3482d080ee5a0dbc8d9668baa1fbd">llvm::AANoFPClass::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aanofree/#a580b45bc8d796ba9773b3e1d0529072f">llvm::AANoFree::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aanonnull/#a4b39699a3bc4c4e6435157c180985c54">llvm::AANonNull::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aanosync/#a0f6906a85729db7eed4b3e39c310fa90">llvm::AANoSync::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aapointerinfo/#a07bee2e824c483aa3d14d1d3aeacd7f3">llvm::AAPointerInfo::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialconstantvalues/#af5da78fb4956605377823b84dc51cc8a">llvm::AAPotentialConstantValues::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aaprivatizableptr/#a1394737f4696b9d788c1f05ab1290034">llvm::AAPrivatizablePtr::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aaunderlyingobjects/#a0ab6c751c4d0f19523dbcf38565b4a3d">llvm::AAUnderlyingObjects::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#a0db738999f015d26cefccb2a66eada25">llvm::AAValueConstantRange::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaaddressspaceimpl/#a53cdd0197a337c06817844761012a6e0">anonymous{AttributorAttributes.cpp}::AAAddressSpaceImpl::manifest</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a469217e1991252d89a236638f25c5293">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::manifestReplacementValue</a>.</p>

</div>
</div>

### getAssociatedValue() {#a96130007e2acc25ee2ed2dd8f08f3e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value &amp; llvm::IRPosition::getAssociatedValue ()</td>
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

<p>Return the value this abstract attribute is associated with.</p>

<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a9f40f87a556db81bd2403007b83acce7">getAnchorValue</a>, <a href="#ac74aa0fe9252fce4caabf80617085afa">getCallSiteArgNo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#a032ee1ab74cd70ec3ff4801ec8a49f0f">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::addAccessedBytesForUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a98e912ad4f52dcd78856d78ad4c06338">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::askOtherAA</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ac74c71265c51cb1cd82cebadc0cfa913">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::askSimplifiedValueFor</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a23c3ad9b1a74163fc898fc3f8fa398dc">llvm::Attributor::changeAfterManifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a9359926dcece9d9c26725b86829b4103">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::checkAndUpdate</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignimpl/#a22f7409291622b8972b279f9bb4239f0">anonymous{AttributorAttributes.cpp}::AAAlignImpl::followUseInMBEC</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#acaea35e256aaaac40d3dcc889776d741">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::followUseInMBEC</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanonnullimpl/#a949cfd9dba9632dde317810cc3a33a99">anonymous{AttributorAttributes.cpp}::AANonNullImpl::followUseInMBEC</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a7dcc7e60c55b76d16688ee3b04f804e4">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::forallInterferingAccesses</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaunderlyingobjectsimpl/#ab7d7a47641c9fe9bccdfc0265528f8b6">anonymous{AttributorAttributes.cpp}::AAUnderlyingObjectsImpl::forallUnderlyingObjects</a>, <a href="#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">getAssociatedType</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#adf4f579a309437c24aed6e78e5c566c2">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::getAsStr</a>, <a href="/web-llvm/docs/api/structs/llvm/aapotentialconstantvalues/#ac6c45f02f71621808dd33da72d73cb00">llvm::AAPotentialConstantValues::getAssumedConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#a1e99011cd6c37ad4ab5be287c94735bf">llvm::AAValueConstantRange::getAssumedConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a853ba647ef2e86e05cd988dae8ed8897">llvm::Attributor::getAssumedConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a529439af5980ea04e96200187061c86d">llvm::Attributor::getAssumedSimplified</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#ae92d755a80dec605503e2ba653765360">llvm::Attributor::getAssumedSimplifiedValues</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#aff3d225ae8841fccee34cd8a722f14b2">llvm::Attributor::getAttrsFromAssumes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#aa5a45de2ff151caaae105b2aa429f35b">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getConstantRangeFromLVI</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a0b1acdea3aaa8e166e24b51e22def764">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getSCEV</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#ae957d55f18d016455143fa3b219c5203">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::giveUpOnIntraprocedural</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ad0fe28a9dccc66e85a05b9447f4141ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handlePHINode</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a49114a789143912efbf912250aea8397">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleSelectInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrfloating/#a37c45fca70e23e6ba77beb4f17ea4cae">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrFloating::identifyPrivatizableType</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a93339349de364716175a03098d94d44f">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#ad4ad93c1d7d4ebde3579c37dcd403982">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ad277bd35b295f10501e8ead87d705599">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignimpl/#a5fda3f49dbfb55b94b59d3a415bb40b8">anonymous{AttributorAttributes.cpp}::AAAlignImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#a35445c95fd89ba05e25a51bc417d24ff">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainstanceinfoimpl/#a7daaff79526608a42072ac2e7544c30c">anonymous{AttributorAttributes.cpp}::AAInstanceInfoImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsiteargument/#ac861cd301641588b3545b331f151cf9b">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteArgument::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsitereturned/#a26e4580a4b5734beab116527fedd9cf0">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a6bb99a515b0f1ece7560275f4c47033c">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofpclassimpl/#a15b5bdf6941d33266e2377777aebb9d8">anonymous{AttributorAttributes.cpp}::AANoFPClassImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanonnullimpl/#a0fd406aa58dfe4f8dc6c60a64f5a7f2b">anonymous{AttributorAttributes.cpp}::AANonNullImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoundefimpl/#a2ef97828cee96a92e8b3aee5e2426fb4">anonymous{AttributorAttributes.cpp}::AANoUndefImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluescallsiteargument/#ae1809da391ffa31e9c942e627f41463a">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesCallSiteArgument::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#a0c8ffe0c88515a42bacdd5565e55f5b1">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesargument/#a9820ec9c7c0f863ac4ee6269af81cf3e">anonymous{AttributorAttributes.cpp}::AAPotentialValuesArgument::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a92d1a2aa02b302934a11d953531de329">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangecallsitereturned/#adea35464b5cc6628399f3a058c28bb0b">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a2b827c74bf3fdb8d906b3eeb0e1e5f8f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a5aaf0b4e889521266e9e87ec9a0511ce">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aafoldruntimecallcallsitereturned/#a4ef5420ebe7c75b26c668ce810ddf6fb">anonymous{OpenMPOpt.cpp}::AAFoldRuntimeCallCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#ab0859b33717bfc3149f2b4051949b5cb">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::initialize</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0214244f107a21a911d07efd0c8e899b">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/llvm/aanoalias/#a0a95494aa0152eb057e6e9ca25572f87">llvm::AANoAlias::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aanocapture/#adb7886272a3ab071ecd4a576d865dc21">llvm::AANoCapture::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aanonnull/#ad13f5148dfe5bbfa20ec5cdabfcb8547">llvm::AANonNull::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aanoundef/#ad91f1de0705a6d8cfb9d1269ae996737">llvm::AANoUndef::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/irattribute/#ac283e789a1c5ae7c595bdd1fde85cbaa">llvm::IRAttribute&lt; AK, BaseType, AAType &gt;::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#a0a41d500fe5dcf2f575b99316d25ec30">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::isKnownNoAliasDueToNoAliasPreservation</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#ad1373816b599022e1b5f8d5c1497f3a8">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::isRemovableStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#ade252ec650f1f043ccf664b66c038d38">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::isValidCtxInstructionForOutsideAnalysis</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaaddressspaceimpl/#a53cdd0197a337c06817844761012a6e0">anonymous{AttributorAttributes.cpp}::AAAddressSpaceImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaaligncallsiteargument/#a92d005e0d6f5aecbf06dcb3eddf5a63f">anonymous{AttributorAttributes.cpp}::AAAlignCallSiteArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignimpl/#a386b43737ff3f36caaf7369350e678b1">anonymous{AttributorAttributes.cpp}::AAAlignImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a4c0d39301fbda30cede0fcbb4d649c75">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorargument/#a40a41eccaeafb327b27a589542a5f106">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#aaf6f1a343b2a0c4e03abaff3569e5269">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a12fa48f6f87955f0d3b9a0912669ef38">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsiteargument/#a8779a21bd698d1abfabf4fc3f7fd64b9">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a7e4935f6285534875f64d5399fd6836c">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a469217e1991252d89a236638f25c5293">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::manifestReplacementValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#af60845674c792fb83289ea7695d3807e">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::mayAliasWithArgument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf6e500a902879012046ea1f8008d7e6">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/subsumingpositioniterator/#a88c3ecf0e220e6dcd1afee9f86c8d806">llvm::SubsumingPositionIterator::SubsumingPositionIterator</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignfloating/#a0206ea336f22470d5fe01f65dae9eb85">anonymous{AttributorAttributes.cpp}::AAAlignFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceablefloating/#a41c5ffc9c348c806bd197076e245aa1a">anonymous{AttributorAttributes.cpp}::AADereferenceableFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainstanceinfoimpl/#a42d1b636e669eab226d5c36c5569c4d6">anonymous{AttributorAttributes.cpp}::AAInstanceInfoImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsitereturned/#a7919aaff0b333257cd367569bae6f56d">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a416fe9863798afdfa2854866604d1bc4">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a31f2a80a770f0aa93c1fab42e9d41407">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#ae7864a73feb64332db5d9304ee4a7ace">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a2b832055235bac7e33fee8273b9c0211">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofpclassfloating/#a9c2d1fb920f390ee52852043fb2a2741">anonymous{AttributorAttributes.cpp}::AANoFPClassFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanonnullfloating/#a4b1fa4ad98c736b05369d73702328439">anonymous{AttributorAttributes.cpp}::AANonNullFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoundeffloating/#a6b86977408d6fd3bc77f900143401adb">anonymous{AttributorAttributes.cpp}::AANoUndefFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluescallsiteargument/#aac76be7819743fabe47e340fdfe9cdc5">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#a4061dbec7eefa7f2e5d2570e32eae1f7">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#adba089cecb7b89737a7fa570790f6b68">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaunderlyingobjectsimpl/#a5853fd1282daf0510e9eb037ffe23f8a">anonymous{AttributorAttributes.cpp}::AAUnderlyingObjectsImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a326d4c3fb95ebe6cbdca9c9e312da4a8">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#aa952da5010350f12b8d601516719d22b">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::updateImpl</a>.</p>

</div>
</div>

### getAttrIdx() {#a1a40b5fffb32c10d26633893df3b21ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IRPosition::getAttrIdx ()</td>
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

<p>Return the index in the attribute list for this position.</p>

<p>Definition at line 818 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">llvm::AttributeList::FirstArgIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">llvm::AttributeList::FunctionIndex</a>, <a href="#a4930f70e8a125f3d0a45a777adc3b305">getCalleeArgNo</a>, <a href="#ac74aa0fe9252fce4caabf80617085afa">getCallSiteArgNo</a>, <a href="#aea16db681aa18f4eded0015e284fdfe5">getPositionKind</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a212200718d90163dbf9fc504df5ff62f">IRP_ARGUMENT</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a4b033e6b489e8f06fe2819955eb8011b">IRP_CALL_SITE</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0af5dba641c6a961375aee403f7cde7b31">IRP_CALL_SITE_ARGUMENT</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a8bd94921b59d24f031ef7e64525e14f8">IRP_CALL_SITE_RETURNED</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0ae11f9a858d0a751bf2f9ea534be9457e">IRP_FLOAT</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0aa823f70d88660d88196943a3f09301da">IRP_FUNCTION</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0afd1465681c30be50be67dcf938d73f5f">IRP_INVALID</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a440e55ee67b08379ca74b24eb623789b">IRP_RETURNED</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af5dcb6d3da4b30a7d21c9fb39bbf1a68a167699508089d6cf7e6afe448d82e6df">llvm::AttributeList::ReturnIndex</a>.</p>

</div>
</div>

### getAttrList() {#a4081fd08df96363717c46a40ea774794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::IRPosition::getAttrList ()</td>
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

<p>Return the attributes associated with this function or call site scope.</p>

<p>Definition at line 846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a9f40f87a556db81bd2403007b83acce7">getAnchorValue</a>, <a href="#a054de50dbf11b87063f6a32f3bccee80">getAssociatedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ac8d6f220fcf8f327c6c739813df8c4c9">llvm::AttributeList::getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#a7477aafbbe989ad35b96fac186d8e9fd">llvm::Function::getAttributes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>.</p>

</div>
</div>

### getAttrListAnchor() {#ab7a3b4198c15b98d1689f769b8f07126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::IRPosition::getAttrListAnchor ()</td>
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

<p>Return the value attributes are attached to.</p>

<p>Definition at line 839 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a9f40f87a556db81bd2403007b83acce7">getAnchorValue</a> and <a href="#a054de50dbf11b87063f6a32f3bccee80">getAssociatedFunction</a>.</p>

</div>
</div>

### getCallBaseContext() {#a8e5f6784c446af664c5c0f6ab3c9fa26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallBaseContext * llvm::IRPosition::getCallBaseContext ()</td>
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

<p>Get the call base context from the position.</p>

<p>Definition at line 932 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a20affbb8e81211322b21dd9c967dbafa">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateBinaryOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a9fe92d5d425b0ddab77a3bd58e734a74">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCastInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a28797a7ad88ceb957e31f0bc5802395f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCmpInst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a193d427e5f23228ebb54da668ab02360">anonymous{AttributorAttributes.cpp}::getArgumentStateFromCallBaseContext</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-9f64d73143315c4916785a7d42181db8/#aee1836009a97cfc6536ac14329d1a733">llvm::DenseMapInfo&lt; IRPosition &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a3de59e829dffdff466e6c22944ac47a8">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleGenericInst</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a532d694575abb82423e79aedce3437cc">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf6e500a902879012046ea1f8008d7e6">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aareturnedfromreturnedvalues/#aa68de19d331847e762e5806f1210aad7">anonymous{AttributorAttributes.cpp}::AAReturnedFromReturnedValues&lt; AADereferenceable, AADereferenceableImpl &gt;::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a326d4c3fb95ebe6cbdca9c9e312da4a8">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyreturned/#ac9ae54449e677f539c50426011907713">anonymous{AttributorAttributes.cpp}::AAValueSimplifyReturned::updateImpl</a>.</p>

</div>
</div>

### getCalleeArgNo() {#a4930f70e8a125f3d0a45a777adc3b305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::IRPosition::getCalleeArgNo ()</td>
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

<p>Return the callee argument number of the associated value if it is an argument or call site argument, otherwise a negative value.</p>


<p>In contrast to <span class="doxyComputerOutput">getCallSiteArgNo</span> this method will always return the "argument number" from the perspective of the callee. This may not the same as the call site if this is a callback call.</p>


<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aanocapture/#af9efb4b2e9c757aaa9d2fada609eaee8">llvm::AANoCapture::determineFunctionCaptureCapabilities</a>, <a href="#a1a40b5fffb32c10d26633893df3b21ea">getAttrIdx</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#af60845674c792fb83289ea7695d3807e">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::mayAliasWithArgument</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesargument/#a2cc688aac3b055fb8d0cca7033823473">anonymous{AttributorAttributes.cpp}::AAPotentialValuesArgument::updateImpl</a>.</p>

</div>
</div>

### getCallSiteArgNo() {#ac74aa0fe9252fce4caabf80617085afa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::IRPosition::getCallSiteArgNo ()</td>
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

<p>Return the call site argument number of the associated value if it is an argument or call site argument, otherwise a negative value.</p>


<p>In contrast to <span class="doxyComputerOutput">getCalleArgNo</span> this method will always return the "operand number" from the perspective of the call site. This may not the same as the callee perspective if this is a callback call.</p>


<p>Definition at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a23c3ad9b1a74163fc898fc3f8fa398dc">llvm::Attributor::changeAfterManifest</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a193d427e5f23228ebb54da668ab02360">anonymous{AttributorAttributes.cpp}::getArgumentStateFromCallBaseContext</a>, <a href="#a265735d2c2edc0a1a03611e7aadd24cd">getAssociatedArgument</a>, <a href="#a96130007e2acc25ee2ed2dd8f08f3e18">getAssociatedValue</a>, <a href="#a1a40b5fffb32c10d26633893df3b21ea">getAttrIdx</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsiteargument/#a5d6050f7be56f61036d2d194ac7f66f8">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsiteargument/#a8779a21bd698d1abfabf4fc3f7fd64b9">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteArgument::manifest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf6e500a902879012046ea1f8008d7e6">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>.</p>

</div>
</div>

### getCtxI() {#a5cdc54db452dfdce67b7f0713f822f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::IRPosition::getCtxI ()</td>
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

<p>Return the context instruction, if any.</p>

<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a9f40f87a556db81bd2403007b83acce7">getAnchorValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a23c3ad9b1a74163fc898fc3f8fa398dc">llvm::Attributor::changeAfterManifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ae86be98f39008a27ba987e282fc8dc2c">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::genericValueTraversal</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#ae92d755a80dec605503e2ba653765360">llvm::Attributor::getAssumedSimplifiedValues</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#aff3d225ae8841fccee34cd8a722f14b2">llvm::Attributor::getAttrsFromAssumes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#ae957d55f18d016455143fa3b219c5203">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::giveUpOnIntraprocedural</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#ad4ad93c1d7d4ebde3579c37dcd403982">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignimpl/#a5fda3f49dbfb55b94b59d3a415bb40b8">anonymous{AttributorAttributes.cpp}::AAAlignImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceableimpl/#a35445c95fd89ba05e25a51bc417d24ff">anonymous{AttributorAttributes.cpp}::AADereferenceableImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#a30d8d29c9510e2f8b7f6244979fc9376">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsitereturned/#a26e4580a4b5734beab116527fedd9cf0">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofpclassimpl/#a15b5bdf6941d33266e2377777aebb9d8">anonymous{AttributorAttributes.cpp}::AANoFPClassImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanonnullimpl/#a0fd406aa58dfe4f8dc6c60a64f5a7f2b">anonymous{AttributorAttributes.cpp}::AANonNullImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoundeffloating/#a10d30d8aa39878aaa802fa9036093945">anonymous{AttributorAttributes.cpp}::AANoUndefFloating::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a92d1a2aa02b302934a11d953531de329">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a98a9160e61aee9e51514937e1cd8b2f0">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsitereturned/#a249035cbf55468e38187c74bfcd1204b">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadvalueimpl/#a3674ac8a00013298f5ac325bc4511a1a">anonymous{AttributorAttributes.cpp}::AAIsDeadValueImpl::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0214244f107a21a911d07efd0c8e899b">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/llvm/aanonnull/#ad13f5148dfe5bbfa20ec5cdabfcb8547">llvm::AANonNull::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#a0a41d500fe5dcf2f575b99316d25ec30">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::isKnownNoAliasDueToNoAliasPreservation</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#ade252ec650f1f043ccf664b66c038d38">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::isValidCtxInstructionForOutsideAnalysis</a>, <a href="/web-llvm/docs/api/structs/llvm/aaindirectcallinfo/#ade925b52067587c1d8f4327e1f45ab3f">llvm::AAIndirectCallInfo::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#aaf6f1a343b2a0c4e03abaff3569e5269">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#a12fa48f6f87955f0d3b9a0912669ef38">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsiteargument/#a8779a21bd698d1abfabf4fc3f7fd64b9">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aafoldruntimecallcallsitereturned/#af1bd9d5096d40a231c52e763ca91647f">anonymous{OpenMPOpt.cpp}::AAFoldRuntimeCallCallSiteReturned::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackercallsite/#a39ea6c7721d9ef18e3e61b9b206939fe">anonymous{OpenMPOpt.cpp}::AAICVTrackerCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#adca255bafe3002c3988f715a5179c2c1">llvm::AbstractAttribute::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignfloating/#a0206ea336f22470d5fe01f65dae9eb85">anonymous{AttributorAttributes.cpp}::AAAlignFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaallocationinfoimpl/#ae66a50449dec20c1a137f704e5e2c949">anonymous{AttributorAttributes.cpp}::AAAllocationInfoImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgescallsite/#a827970be0131200af76c14c9e1a24b15">anonymous{AttributorAttributes.cpp}::AACallEdgesCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceablefloating/#a41c5ffc9c348c806bd197076e245aa1a">anonymous{AttributorAttributes.cpp}::AADereferenceableFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#a554ade21fa5bda8daa3af645c00364b1">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsitereturned/#a7919aaff0b333257cd367569bae6f56d">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofpclassfloating/#a9c2d1fb920f390ee52852043fb2a2741">anonymous{AttributorAttributes.cpp}::AANoFPClassFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsitereturned/#a326827ab35aa09c37cb1a4ee329f67ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a326d4c3fb95ebe6cbdca9c9e312da4a8">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackercallsite/#a02ca92064e58264c2b89a838efeb545a">anonymous{OpenMPOpt.cpp}::AAICVTrackerCallSite::updateImpl</a>.</p>

</div>
</div>

### getNumArgs() {#ae7547d953171225ca4aea8c69ccabb7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::IRPosition::getNumArgs ()</td>
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

<p>Return the number of arguments associated with this function or call site scope.</p>

<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#ac6baa801e4aea800984e760d5460662f">llvm::Function::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a9f40f87a556db81bd2403007b83acce7">getAnchorValue</a>, <a href="#a054de50dbf11b87063f6a32f3bccee80">getAssociatedFunction</a>, <a href="#aea16db681aa18f4eded0015e284fdfe5">getPositionKind</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a4b033e6b489e8f06fe2819955eb8011b">IRP_CALL_SITE</a> and <a href="#a53f576f97e0dfa8314afb16bd74a76d0aa823f70d88660d88196943a3f09301da">IRP_FUNCTION</a>.</p>

</div>
</div>

### getPositionKind() {#aea16db681aa18f4eded0015e284fdfe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind llvm::IRPosition::getPositionKind ()</td>
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

<p>Return the associated position kind.</p>

<p>Definition at line 882 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a53f576f97e0dfa8314afb16bd74a76d0a212200718d90163dbf9fc504df5ff62f">IRP_ARGUMENT</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a4b033e6b489e8f06fe2819955eb8011b">IRP_CALL_SITE</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0af5dba641c6a961375aee403f7cde7b31">IRP_CALL_SITE_ARGUMENT</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a8bd94921b59d24f031ef7e64525e14f8">IRP_CALL_SITE_RETURNED</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0ae11f9a858d0a751bf2f9ea534be9457e">IRP_FLOAT</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0aa823f70d88660d88196943a3f09301da">IRP_FUNCTION</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0afd1465681c30be50be67dcf938d73f5f">IRP_INVALID</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a440e55ee67b08379ca74b24eb623789b">IRP_RETURNED</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a23c3ad9b1a74163fc898fc3f8fa398dc">llvm::Attributor::changeAfterManifest</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a1bdef12f6088e0d320946736b48fb137">anonymous{AttributorAttributes.cpp}::clampCallSiteArgumentStates</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributes/#a42bb2cd6393cce07af23cfc468a8e4a3">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributes::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdflatworkgroupsize/#ae5d4e65bf36d20e911e0c3b66a3ed106">anonymous{AMDGPUAttributor.cpp}::AAAMDFlatWorkGroupSize::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdgpunoagpr/#a06f25e6f9fa71b983c1f52b35274fe0b">anonymous{AMDGPUAttributor.cpp}::AAAMDGPUNoAGPR::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdmaxnumworkgroups/#aad4cff313563f8b6bb6de08669d2051d">anonymous{AMDGPUAttributor.cpp}::AAAMDMaxNumWorkgroups::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a4fe353d1c5d7b1d7ffc32524bcdb1bac">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aauniformworkgroupsize/#a96036029850b3ab1f23cfce88962d88a">anonymous{AMDGPUAttributor.cpp}::AAUniformWorkGroupSize::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aafoldruntimecall/#a976ae83bc84b2d91c2859dd2196ba1dc">anonymous{OpenMPOpt.cpp}::AAFoldRuntimeCall::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptoshared/#a77867478c7f5c6ae9168ca7211c97f1d">anonymous{OpenMPOpt.cpp}::AAHeapToShared::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtracker/#ab7d0fb185c728add8067642433e5640d">anonymous{OpenMPOpt.cpp}::AAICVTracker::createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfo/#a01e0d5d490f9eabb3ba09c95c4f5e695">anonymous{OpenMPOpt.cpp}::AAKernelInfo::createForPosition</a>, <a href="/web-llvm/docs/api/structs/llvm/aaexecutiondomain/#a49479d09ce9ca5942db280559eab93c4">llvm::AAExecutionDomain::createForPosition</a>, <a href="#a9854202d54cc31542b08f1822ceee85d">getArg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a193d427e5f23228ebb54da668ab02360">anonymous{AttributorAttributes.cpp}::getArgumentStateFromCallBaseContext</a>, <a href="#a265735d2c2edc0a1a03611e7aadd24cd">getAssociatedArgument</a>, <a href="#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">getAssociatedType</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a529439af5980ea04e96200187061c86d">llvm::Attributor::getAssumedSimplified</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#ae92d755a80dec605503e2ba653765360">llvm::Attributor::getAssumedSimplifiedValues</a>, <a href="#a1a40b5fffb32c10d26633893df3b21ea">getAttrIdx</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#aff3d225ae8841fccee34cd8a722f14b2">llvm::Attributor::getAttrsFromAssumes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a8df2e20241276fa840a50aaf747a059e">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getDeducedAttributes</a>, <a href="#ae7547d953171225ca4aea8c69ccabb7c">getNumArgs</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ad49bf673f21e06478f2be1990749ee37">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::identifyPrivatizableType</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofpclassimpl/#a15b5bdf6941d33266e2377777aebb9d8">anonymous{AttributorAttributes.cpp}::AANoFPClassImpl::initialize</a>, <a href="#a2fa1cd6176ec069f35692b6748d057c7">isAnyCallSitePosition</a>, <a href="#aec15d884ee42b3559536c100446d54a7">isArgumentPosition</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0214244f107a21a911d07efd0c8e899b">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#ac4e3c1743f6f71b7424a580571065530">isAssumedReadOnlyOrReadNone</a>, <a href="#ac8dd312c8d0f11d5519b3d5e264ac5f9">isFnInterfaceKind</a>, <a href="#a79c71e9c03aff7ec01197395cab4e521">isFunctionScope</a>, <a href="/web-llvm/docs/api/structs/llvm/aanoalias/#a0a95494aa0152eb057e6e9ca25572f87">llvm::AANoAlias::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aanocapture/#adb7886272a3ab071ecd4a576d865dc21">llvm::AANoCapture::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aanonnull/#ad13f5148dfe5bbfa20ec5cdabfcb8547">llvm::AANonNull::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aanoundef/#ad91f1de0705a6d8cfb9d1269ae996737">llvm::AANoUndef::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/llvm/aaglobalvalueinfo/#ac897780087e527a2deab188ff691610c">llvm::AAGlobalValueInfo::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aaindirectcallinfo/#ade925b52067587c1d8f4327e1f45ab3f">llvm::AAIndirectCallInfo::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aaisdead/#a4b6322e8503550536c5b31634875755a">llvm::AAIsDead::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf6e500a902879012046ea1f8008d7e6">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#afc379e94b702009982a10bb57c4a9e7a">llvm::Attributor::shouldUpdateAA</a>, <a href="/web-llvm/docs/api/classes/llvm/subsumingpositioniterator/#a88c3ecf0e220e6dcd1afee9f86c8d806">llvm::SubsumingPositionIterator::SubsumingPositionIterator</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>.</p>

</div>
</div>

### hasCallBaseContext() {#a1e87ff0b4410e061ceac8ca9fc7e46b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRPosition::hasCallBaseContext ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the position has any call base context.</p>

<p>Definition at line 935 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abf6e500a902879012046ea1f8008d7e6">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>.</p>

</div>
</div>

### isAnyCallSitePosition() {#a2fa1cd6176ec069f35692b6748d057c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRPosition::isAnyCallSitePosition ()</td>
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



<p>Definition at line 902 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#aea16db681aa18f4eded0015e284fdfe5">getPositionKind</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a4b033e6b489e8f06fe2819955eb8011b">IRP_CALL_SITE</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0af5dba641c6a961375aee403f7cde7b31">IRP_CALL_SITE_ARGUMENT</a> and <a href="#a53f576f97e0dfa8314afb16bd74a76d0a8bd94921b59d24f031ef7e64525e14f8">IRP_CALL_SITE_RETURNED</a>.</p>


<p>Referenced by <a href="#ad441c7387fd01e3cf86c9d16d9305495">function_scope</a> and <a href="/web-llvm/docs/api/structs/llvm/attributor/#afc379e94b702009982a10bb57c4a9e7a">llvm::Attributor::shouldUpdateAA</a>.</p>

</div>
</div>

### isArgumentPosition() {#aec15d884ee42b3559536c100446d54a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRPosition::isArgumentPosition ()</td>
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

<p>Return true if the position is an argument or call site argument.</p>

<p>Definition at line 914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#aea16db681aa18f4eded0015e284fdfe5">getPositionKind</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a212200718d90163dbf9fc504df5ff62f">IRP_ARGUMENT</a> and <a href="#a53f576f97e0dfa8314afb16bd74a76d0af5dba641c6a961375aee403f7cde7b31">IRP_CALL_SITE_ARGUMENT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a051fd4ce3d6dd22954dc588c14b9ced1">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::getDeducedAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/aanocapture/#adb7886272a3ab071ecd4a576d865dc21">llvm::AANoCapture::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a2b832055235bac7e33fee8273b9c0211">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreefloating/#a81f7ea399468b1020d91546408433b54">anonymous{AttributorAttributes.cpp}::AANoFreeFloating::updateImpl</a>.</p>

</div>
</div>

### isFnInterfaceKind() {#ac8dd312c8d0f11d5519b3d5e264ac5f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRPosition::isFnInterfaceKind ()</td>
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

<p>Return true if the position refers to a function interface, that is the function scope, the function return, or an argument.</p>

<p>Definition at line 735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#aea16db681aa18f4eded0015e284fdfe5">getPositionKind</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a212200718d90163dbf9fc504df5ff62f">IRP_ARGUMENT</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0aa823f70d88660d88196943a3f09301da">IRP_FUNCTION</a> and <a href="#a53f576f97e0dfa8314afb16bd74a76d0a440e55ee67b08379ca74b24eb623789b">IRP_RETURNED</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a651e22db115dbbeacdd4c9ded06f9af3">llvm::AbstractAttribute::isValidIRPositionForUpdate</a>.</p>

</div>
</div>

### isFunctionScope() {#a79c71e9c03aff7ec01197395cab4e521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRPosition::isFunctionScope ()</td>
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

<p>Return true if this is a function or call site position.</p>

<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#aea16db681aa18f4eded0015e284fdfe5">getPositionKind</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a4b033e6b489e8f06fe2819955eb8011b">IRP_CALL_SITE</a> and <a href="#a53f576f97e0dfa8314afb16bd74a76d0aa823f70d88660d88196943a3f09301da">IRP_FUNCTION</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a1d7efda60b9905c2287555f2e3e97e32">llvm::AAMemoryBehavior::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ae548fb21c1de2eb3ad47389ae31488f3">llvm::AAMemoryLocation::isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/llvm/aanofree/#a580b45bc8d796ba9773b3e1d0529072f">llvm::AANoFree::isValidIRPositionForInit</a> and <a href="/web-llvm/docs/api/structs/llvm/aanosync/#a0f6906a85729db7eed4b3e39c310fa90">llvm::AANoSync::isValidIRPositionForInit</a>.</p>

</div>
</div>

### setAttrList() {#a167c9f2ddb243187bdd2313de8586458}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::IRPosition::setAttrList (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> &amp; AttrList)</td>
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

<p>Update the attributes associated with this function or call site scope.</p>

<p>Definition at line 853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a9f40f87a556db81bd2403007b83acce7">getAnchorValue</a>, <a href="#a054de50dbf11b87063f6a32f3bccee80">getAssociatedFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/function/#a9e4c6c67f4b2528b5648299db4a86926">llvm::Function::setAttributes</a>.</p>

</div>
</div>

### stripCallBaseContext() {#ae11c0e8ba89a3f9a29a09466e9aaaf10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRPosition llvm::IRPosition::stripCallBaseContext ()</td>
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

<p>Return the same position without the call base context.</p>

<p>Definition at line 925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a5d9b598f1c0dd1ef47f78469582de44d">llvm::Attributor::getOrCreateAAFor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getArgNo() {#a018464cb036d2011ae48b568d0451df4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::IRPosition::getArgNo (bool CallbackCalleeArgIfApplicable)</td>
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

<p>Return the callee argument number of the associated value if it is an argument or call site argument.</p>


<p>See also <span class="doxyComputerOutput">getCalleeArgNo</span> and <span class="doxyComputerOutput">getCallSiteArgNo</span>.</p>


<p>Definition at line 991 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### getAsUsePtr() {#adc11ff1c9d0746ed2a3b9950a669bf66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use * llvm::IRPosition::getAsUsePtr ()</td>
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

<p>Return the underlying pointer as <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *, valid only for IRP_CALL_SITE_ARGUMENT positions.</p>

<p>Definition at line 1030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### getAsValuePtr() {#aca0130086cc6ea1961e712c469542ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::IRPosition::getAsValuePtr ()</td>
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

<p>Return the underlying pointer as <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, valid for all positions but IRP_CALL_SITE_ARGUMENT.</p>

<p>Definition at line 1022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### getEncodingBits() {#a8fb5f4ad8a22f0fd74a9b59b3d510270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::IRPosition::getEncodingBits ()</td>
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

<p>Return the encoding bits.</p>

<p>Definition at line 1073 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### isReturnPosition() {#a4c77fe669c7a0558225ef0aabc45dd35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRPosition::isReturnPosition ()</td>
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

<p>Return true if the encoding bits describe a returned or call site returned position.</p>

<p>Definition at line 1044 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### verify() {#adcc36b7035d1e165c8738c36823a815e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRPosition::verify ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify internal invariants.</p>

<p>Declaration at line 1018 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 1327 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CBContext {#a71eeb7bb75e2694ec61deee92c2f5a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallBaseContext* llvm::IRPosition::CBContext = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>


<p>Call base context. Used for callsite specific analysis.</p>


<p>Definition at line 1070 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### Enc {#ad1deaa31948458d3cf5ee3a4a3b16772}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerIntPair&lt;void *, NumEncodingBits, char&gt; llvm::IRPosition::Enc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The pointer with the encoding bits.</p>

<p>Definition at line 1066 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### argument() {#a67ee5b213c199841ee5f2d0a338e466e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRPosition llvm::IRPosition::argument (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> &amp; Arg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3c0bf0d84bda6e0ec2d44d83850a328a">CallBaseContext</a> * CBContext=nullptr)</td>
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

<p>Create a position describing the argument <span class="doxyComputerOutput">Arg</span>.</p>


<p><span class="doxyComputerOutput">CBContext</span> is used for call base specific analysis.</p>


<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a53f576f97e0dfa8314afb16bd74a76d0a212200718d90163dbf9fc504df5ff62f">IRP_ARGUMENT</a> and <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrfloating/#a37c45fca70e23e6ba77beb4f17ea4cae">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrFloating::identifyPrivatizableType</a>, <a href="/web-llvm/docs/api/structs/llvm/aanocapture/#adb7886272a3ab071ecd4a576d865dc21">llvm::AANoCapture::isImpliedByIR</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#ae444282c6d6bc8d5e9905620c936d39e">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a1cfca839ff13dd1c214a5dae9c737bda">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::manifest</a>, <a href="/web-llvm/docs/api/classes/llvm/subsumingpositioniterator/#a88c3ecf0e220e6dcd1afee9f86c8d806">llvm::SubsumingPositionIterator::SubsumingPositionIterator</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaaligncallsiteargument/#a90d18de54863d37fc84ed61f7f87455e">anonymous{AttributorAttributes.cpp}::AAAlignCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#a554ade21fa5bda8daa3af645c00364b1">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainstanceinfocallsiteargument/#a2cf1a30aab8cfc08c8d3d0b52005607a">anonymous{AttributorAttributes.cpp}::AAInstanceInfoCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsiteargument/#a5fb77be1b52b827ae66c6664e8e72420">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsiteargument/#a1866f24992e827ce8c69e245522b591f">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocapturecallsiteargument/#af8af50bbe36f25d0fd0d35c5d6e973fa">anonymous{AttributorAttributes.cpp}::AANoCaptureCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreecallsiteargument/#a057aad39e2f87b33e18b53e28adbf90b">anonymous{AttributorAttributes.cpp}::AANoFreeCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfocallsiteargument/#afd64f56df116f9c6c4763b55bf74897a">anonymous{AttributorAttributes.cpp}::AAPointerInfoCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a> and <a href="#a3bee165465962ee97307066da4f0fb13">value</a>.</p>

</div>
</div>

### callsite\_argument() {#a4c17a71e75898bbc42578a1c0b94c6b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRPosition llvm::IRPosition::callsite_argument (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, unsigned ArgNo)</td>
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

<p>Create a position describing the argument of <span class="doxyComputerOutput">CB</span> at position <span class="doxyComputerOutput">ArgNo</span>.</p>

<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#aa1c6e6fdb0e2812d7f3b97ae16caeb44">llvm::CallBase::getArgOperandUse</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0af5dba641c6a961375aee403f7cde7b31">IRP_CALL_SITE_ARGUMENT</a> and <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a135bd9f6645b2fba9c7652cbd7b8a157">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::addValue</a>, <a href="#a882f8f4551f4267174aa36b7e3b68a97">callsite_argument</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a58d962e3d29a81e1cdd18243bf6c71d3">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizeArgumentPointerLocations</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a9e78a16876b18d86097c67afa39bc090">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::checkUse</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a1bdef12f6088e0d320946736b48fb137">anonymous{AttributorAttributes.cpp}::clampCallSiteArgumentStates</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofpclassimpl/#a4fe45f17e366eb34bdb1632fff1c53f7">anonymous{AttributorAttributes.cpp}::AANoFPClassImpl::followUseInMBEC</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a193d427e5f23228ebb54da668ab02360">anonymous{AttributorAttributes.cpp}::getArgumentStateFromCallBaseContext</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a5d4d9464721afd6bb6956c909c852bde">anonymous{AttributorAttributes.cpp}::getKnownAlignForUse</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a7159508155406ad5c350cc429980e09d">anonymous{AttributorAttributes.cpp}::getKnownNonNullAndDerefBytesForUse</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ad49bf673f21e06478f2be1990749ee37">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::identifyPrivatizableType</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsitereturned/#a249035cbf55468e38187c74bfcd1204b">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a78cf0931abfbc70e124e7c225584b686">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#a0a41d500fe5dcf2f575b99316d25ec30">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::isKnownNoAliasDueToNoAliasPreservation</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a0451826f9ecd21f9d963cc51401b1b4d">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#af60845674c792fb83289ea7695d3807e">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::mayAliasWithArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/subsumingpositioniterator/#a88c3ecf0e220e6dcd1afee9f86c8d806">llvm::SubsumingPositionIterator::SubsumingPositionIterator</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a975eb04de3ce355131f2bdc9328def27">llvm::Attributor::translateArgumentToCallSiteContent</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#abe94b0d36f169e52ede6a35d6ac41859">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainstanceinfoimpl/#a42d1b636e669eab226d5c36c5569c4d6">anonymous{AttributorAttributes.cpp}::AAInstanceInfoImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreefloating/#a81f7ea399468b1020d91546408433b54">anonymous{AttributorAttributes.cpp}::AANoFreeFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesargument/#a2cc688aac3b055fb8d0cca7033823473">anonymous{AttributorAttributes.cpp}::AAPotentialValuesArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaundefinedbehaviorimpl/#ae455d1ecbeb7d95762d758c9aae70512">anonymous{AttributorAttributes.cpp}::AAUndefinedBehaviorImpl::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyargument/#a04db9be64fd2281358f89ee3bebca79e">anonymous{AttributorAttributes.cpp}::AAValueSimplifyArgument::updateImpl</a>.</p>

</div>
</div>

### callsite\_argument() {#a882f8f4551f4267174aa36b7e3b68a97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRPosition llvm::IRPosition::callsite_argument (<a href="/web-llvm/docs/api/classes/llvm/abstractcallsite">AbstractCallSite</a> ACS, unsigned ArgNo)</td>
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

<p>Create a position describing the argument of <span class="doxyComputerOutput">ACS</span> at position <span class="doxyComputerOutput">ArgNo</span>.</p>

<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a4c17a71e75898bbc42578a1c0b94c6b6">callsite_argument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#a7e8ae04873ef7a72fbad37852333d290">llvm::AbstractCallSite::getCallArgOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#a1d97fd714e72a72bd6d96a8b1ebf62ea">llvm::AbstractCallSite::getInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/abstractcallsite/#ab8b5e4f9ae59fedfc0f0be8395992ea3">llvm::AbstractCallSite::getNumArgOperands</a> and <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a>.</p>

</div>
</div>

### callsite\_function() {#aeef35bb007616add7418161b0313b56b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRPosition llvm::IRPosition::callsite_function (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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

<p>Create a position describing the function scope of <span class="doxyComputerOutput">CB</span>.</p>

<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a53f576f97e0dfa8314afb16bd74a76d0a4b033e6b489e8f06fe2819955eb8011b">IRP_CALL_SITE</a> and <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ae2c6df05bd2236b9d36680de5e09b78a">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizeAccessedLocations</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a130fa46387c197f8e770059b89d2a4b4">llvm::Attributor::checkForAllCallees</a>, <a href="#ad441c7387fd01e3cf86c9d16d9305495">function_scope</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a0cb597b1f0cffe907fa834e9a95fe719">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a753ca373c3a99cb66666a497408ed72f">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#ab0859b33717bfc3149f2b4051949b5cb">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadvalueimpl/#a2758a929f5cb19b83ebb78e91b10ccb2">anonymous{AttributorAttributes.cpp}::AAIsDeadValueImpl::isAssumedSideEffectFree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#add4df090e923f2fe0dceeb0c60e5f74b">llvm::AA::isNoSyncInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainterfnreachabilityfunction/#a6c50862efd6adb69da166ddce9dc912c">anonymous{AttributorAttributes.cpp}::AAInterFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#aa706a9b987f484bb0ac2c16422522dbc">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a370b5637d8494d95fb8867b813fa71d8">anonymous{OpenMPOpt.cpp}::OpenMPOpt::registerAAsForFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/subsumingpositioniterator/#a88c3ecf0e220e6dcd1afee9f86c8d806">llvm::SubsumingPositionIterator::SubsumingPositionIterator</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaassumptioninfofunction/#a38534da78e53a11f3966c8b245512865">anonymous{AttributorAttributes.cpp}::AAAssumptionInfoFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgesfunction/#a43bed485775922bde4815519e5f19d12">anonymous{AttributorAttributes.cpp}::AACallEdgesFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#a7cbfbbbb3a4ab59262caf3c1a7c6bd04">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamustprogressfunction/#a84b5ff4a5e48342e4d1dc19ffdb26105">anonymous{AttributorAttributes.cpp}::AAMustProgressFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreeimpl/#a642335d91f91ad57c209550723da37c2">anonymous{AttributorAttributes.cpp}::AANoFreeImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanosyncimpl/#a671a7ae35e26ce8b5b12340ec2c712a6">anonymous{AttributorAttributes.cpp}::AANoSyncImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanounwindimpl/#ae8a0b1fdd249b94eeb8f937104a6c90d">anonymous{AttributorAttributes.cpp}::AANoUnwindImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aawillreturnimpl/#a716d51da277d8ec4901a5f425dc274d1">anonymous{AttributorAttributes.cpp}::AAWillReturnImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ab05c198311b34d95f57423b9f9c1d1e6">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::updateImpl</a>.</p>

</div>
</div>

### callsite\_returned() {#a22b55f73ab4057a8c3da9f32bd582f4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRPosition llvm::IRPosition::callsite_returned (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
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

<p>Create a position describing the returned value of <span class="doxyComputerOutput">CB</span>.</p>

<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a53f576f97e0dfa8314afb16bd74a76d0a8bd94921b59d24f031ef7e64525e14f8">IRP_CALL_SITE_RETURNED</a> and <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a6982073fb3620dd727922e78e140af8f">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizePtrValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackerfunction/#ab0a8c344bd57a953ec6b9327a443b2b0">anonymous{OpenMPOpt.cpp}::AAICVTrackerFunction::getValueForCall</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a424871cbef50e8414bb8bbed3a4068db">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aafoldruntimecallcallsitereturned/#a4ef5420ebe7c75b26c668ce810ddf6fb">anonymous{OpenMPOpt.cpp}::AAFoldRuntimeCallCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#ac3b3ae3662af2dcad3cab15f9ba148d4">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0214244f107a21a911d07efd0c8e899b">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a2c8f5eab9499a8b7a3238177f2ecf52c">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a> and <a href="#a3bee165465962ee97307066da4f0fb13">value</a>.</p>

</div>
</div>

### function() {#a8936a7eb7c9151c46513b192053afb2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRPosition llvm::IRPosition::function (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3c0bf0d84bda6e0ec2d44d83850a328a">CallBaseContext</a> * CBContext=nullptr)</td>
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

<p>Create a position describing the function scope of <span class="doxyComputerOutput">F</span>.</p>


<p><span class="doxyComputerOutput">CBContext</span> is used for call base specific analysis.</p>


<p>Definition at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0aa823f70d88660d88196943a3f09301da">IRP_FUNCTION</a> and <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a440c7b43772713f767d18f81c9caadf2">llvm::Attributor::checkForAllInstructions</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a6a9714645534051ae76feba39ffbfb13">llvm::Attributor::checkForAllReadWriteInstructions</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#abbea65eed8b9b7cd07f0b8eef53df6f5">llvm::Attributor::checkForAllUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a7dcc7e60c55b76d16688ee3b04f804e4">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::forallInterferingAccesses</a>, <a href="#ad441c7387fd01e3cf86c9d16d9305495">function_scope</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#ad567ae138977391ddcc0d292749aecc8">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::handleCallees</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#a1217110bea3dc6c47ed8fab732d092b9">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::handleParallel51</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ad0fe28a9dccc66e85a05b9447f4141ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handlePHINode</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaassumptioninfocallsite/#a9ff13f2caa99f818de5c88147552bab2">anonymous{AttributorAttributes.cpp}::AAAssumptionInfoCallSite::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a28ca3a54ea9ef7dd53412258dc067de3">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a532d694575abb82423e79aedce3437cc">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a64ffcd16d1457fc57339e15655b68627">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::isDeadFence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a365173e63bd73b3ee58033678429636e">isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainterfnreachabilityfunction/#a6c50862efd6adb69da166ddce9dc912c">anonymous{AttributorAttributes.cpp}::AAInterFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a2c8f5eab9499a8b7a3238177f2ecf52c">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::manifest</a>, <a href="/web-llvm/docs/api/classes/llvm/aacalledgeiterator/#ad1f9364c189c5b5a4dedc0af84eaa577">llvm::AACallEdgeIterator::operator*</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a370b5637d8494d95fb8867b813fa71d8">anonymous{OpenMPOpt.cpp}::OpenMPOpt::registerAAsForFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuattributor-cpp-/#a54acd54cc3db43b11d42ebf210d08cf7">anonymous{AMDGPUAttributor.cpp}::runImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/subsumingpositioniterator/#a88c3ecf0e220e6dcd1afee9f86c8d806">llvm::SubsumingPositionIterator::SubsumingPositionIterator</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdattributesfunction/#a1757cce9d6fc5259895ec599716aa7fc">anonymous{AMDGPUAttributor.cpp}::AAAMDAttributesFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdgpunoagpr/#ab53804e7e3d51ed854878696adab7821">anonymous{AMDGPUAttributor.cpp}::AAAMDGPUNoAGPR::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdmaxnumworkgroups/#a78b300aeab76328894717218a55b32d1">anonymous{AMDGPUAttributor.cpp}::AAAMDMaxNumWorkgroups::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdwavespereu/#a6e7ec06ac86c48e6d651e37817ed7359">anonymous{AMDGPUAttributor.cpp}::AAAMDWavesPerEU::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aauniformworkgroupsizefunction/#a8aba32ec039ca723fa00f67c6f462cfa">anonymous{AMDGPUAttributor.cpp}::AAUniformWorkGroupSizeFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaassumptioninfocallsite/#af16220fe3fc119680f375c4538494003">anonymous{AttributorAttributes.cpp}::AAAssumptionInfoCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalleetocallsite/#a13627a051dc8e791e2f3f1699575605b">anonymous{AttributorAttributes.cpp}::AACalleeToCallSite&lt; AADereferenceable, AADereferenceableImpl &gt;::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadenormalfpmathfunction/#a40c2cb36cf0ed7535884f2e86de3aa55">anonymous{AttributorAttributes.cpp}::AADenormalFPMathFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#abe94b0d36f169e52ede6a35d6ac41859">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainstanceinfoimpl/#a42d1b636e669eab226d5c36c5569c4d6">anonymous{AttributorAttributes.cpp}::AAInstanceInfoImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationcallsite/#a36ef96efb68b331087c86a5c9920173c">anonymous{AttributorAttributes.cpp}::AAMemoryLocationCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamustprogresscallsite/#a03cbaff1b92ba39f9f8b6e672c2c9d1e">anonymous{AttributorAttributes.cpp}::AAMustProgressCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a2b832055235bac7e33fee8273b9c0211">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanonconvergentfunction/#a7e5c9d15b3fcbb936077ce73cfb12692">anonymous{AttributorAttributes.cpp}::AANonConvergentFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanorecursefunction/#a70d0199665a55282a85300405acf7419">anonymous{AttributorAttributes.cpp}::AANoRecurseFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a8178893fef2816f4172536f259aa6450">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackercallsite/#a02ca92064e58264c2b89a838efeb545a">anonymous{OpenMPOpt.cpp}::AAICVTrackerCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackerfunctionreturned/#aeb5f8b50b9a352fa5ba67cc4fb084b63">anonymous{OpenMPOpt.cpp}::AAICVTrackerFunctionReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#aa952da5010350f12b8d601516719d22b">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ab05c198311b34d95f57423b9f9c1d1e6">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/aaamdsizerangeattribute/#a29bd4b6b1ce02623406f833daf4668cc">anonymous{AMDGPUAttributor.cpp}::AAAMDSizeRangeAttribute::updateImplImpl</a>.</p>

</div>
</div>

### function\_scope() {#ad441c7387fd01e3cf86c9d16d9305495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRPosition llvm::IRPosition::function_scope (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3c0bf0d84bda6e0ec2d44d83850a328a">CallBaseContext</a> * CBContext=nullptr)</td>
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

<p>Create a position with function scope matching the "context" of <span class="doxyComputerOutput">IRP</span>.</p>


<p>If <span class="doxyComputerOutput">IRP</span> is a call site (see <a href="#a2fa1cd6176ec069f35692b6748d057c7">isAnyCallSitePosition()</a>) then the result will be a call site position, otherwise the function position of the associated function.</p>


<p>Definition at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aeef35bb007616add7418161b0313b56b">callsite_function</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a8936a7eb7c9151c46513b192053afb2e">function</a>, <a href="#a9f40f87a556db81bd2403007b83acce7">getAnchorValue</a>, <a href="#a054de50dbf11b87063f6a32f3bccee80">getAssociatedFunction</a>, <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a> and <a href="#a2fa1cd6176ec069f35692b6748d057c7">isAnyCallSitePosition</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a31f2a80a770f0aa93c1fab42e9d41407">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliasargument/#abfc802ab387bc38bb8602eb1732737bd">anonymous{AttributorAttributes.cpp}::AANoAliasArgument::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreefloating/#a81f7ea399468b1020d91546408433b54">anonymous{AttributorAttributes.cpp}::AANoFreeFloating::updateImpl</a>.</p>

</div>
</div>

### inst() {#a4a67bf6ab49ae2630d14e3159ef51cf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRPosition llvm::IRPosition::inst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3c0bf0d84bda6e0ec2d44d83850a328a">CallBaseContext</a> * CBContext=nullptr)</td>
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

<p>Create a position describing the instruction <span class="doxyComputerOutput">I</span>.</p>


<p>This is different from the value version because call sites are treated as intrusctions rather than their return value in this function.</p>


<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0ae11f9a858d0a751bf2f9ea534be9457e">IRP_FLOAT</a> and <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#ab44571c39a32f937c4340ae3b578a58e">checkForAllInstructionsImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a6a9714645534051ae76feba39ffbfb13">llvm::Attributor::checkForAllReadWriteInstructions</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a957f22748fdfd31dfbe31f71feb5329b">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::getAssumedSimplifiedValues</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ad0fe28a9dccc66e85a05b9447f4141ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handlePHINode</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a49114a789143912efbf912250aea8397">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleSelectInst</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a532d694575abb82423e79aedce3437cc">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a78cf0931abfbc70e124e7c225584b686">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaallocationinfoimpl/#ac388d17329447d2fd72ceabf79fefeba">anonymous{AttributorAttributes.cpp}::AAAllocationInfoImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aafoldruntimecallcallsitereturned/#af1bd9d5096d40a231c52e763ca91647f">anonymous{OpenMPOpt.cpp}::AAFoldRuntimeCallCallSiteReturned::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackercallsite/#a39ea6c7721d9ef18e3e61b9b206939fe">anonymous{OpenMPOpt.cpp}::AAICVTrackerCallSite::manifest</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsitereturned/#a326827ab35aa09c37cb1a4ee329f67ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteReturned::updateImpl</a>.</p>

</div>
</div>

### returned() {#a2422bd05c002b7bb1686feaa13f08acd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRPosition llvm::IRPosition::returned (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3c0bf0d84bda6e0ec2d44d83850a328a">CallBaseContext</a> * CBContext=nullptr)</td>
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

<p>Create a position describing the returned value of <span class="doxyComputerOutput">F</span>.</p>


<p><span class="doxyComputerOutput">CBContext</span> is used for call base specific analysis.</p>


<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0a440e55ee67b08379ca74b24eb623789b">IRP_RETURNED</a> and <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a789d552f9e7bede3444f4350d05025af">llvm::Attributor::checkForAllReturnedValues</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a78cf0931abfbc70e124e7c225584b686">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a1cfca839ff13dd1c214a5dae9c737bda">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::manifest</a>, <a href="/web-llvm/docs/api/classes/llvm/subsumingpositioniterator/#a88c3ecf0e220e6dcd1afee9f86c8d806">llvm::SubsumingPositionIterator::SubsumingPositionIterator</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalleetocallsite/#a13627a051dc8e791e2f3f1699575605b">anonymous{AttributorAttributes.cpp}::AACalleeToCallSite&lt; AADereferenceable, AADereferenceableImpl &gt;::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a2b832055235bac7e33fee8273b9c0211">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsitereturned/#a326827ab35aa09c37cb1a4ee329f67ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaundefinedbehaviorimpl/#ae455d1ecbeb7d95762d758c9aae70512">anonymous{AttributorAttributes.cpp}::AAUndefinedBehaviorImpl::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackercallsitereturned/#a816b7da08e9b4f98b437bded6580302a">anonymous{OpenMPOpt.cpp}::AAICVTrackerCallSiteReturned::updateImpl</a>.</p>

</div>
</div>

### value() {#a3bee165465962ee97307066da4f0fb13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRPosition llvm::IRPosition::value (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3c0bf0d84bda6e0ec2d44d83850a328a">CallBaseContext</a> * CBContext=nullptr)</td>
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

<p>Create a position describing the value of <span class="doxyComputerOutput">V</span>.</p>

<p>Definition at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a67ee5b213c199841ee5f2d0a338e466e">argument</a>, <a href="#a22b55f73ab4057a8c3da9f32bd582f4b">callsite_returned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a53f576f97e0dfa8314afb16bd74a76d0ae11f9a858d0a751bf2f9ea534be9457e">IRP_FLOAT</a> and <a href="#af247a28fd83cea9873d310162110439f">IRPosition</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesimpl/#a135bd9f6645b2fba9c7652cbd7b8a157">anonymous{AttributorAttributes.cpp}::AAPotentialValuesImpl::addValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a20affbb8e81211322b21dd9c967dbafa">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateBinaryOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a9fe92d5d425b0ddab77a3bd58e734a74">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCastInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a28797a7ad88ceb957e31f0bc5802395f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::calculateCmpInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a6982073fb3620dd727922e78e140af8f">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizePtrValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a3c38e0e568db780d1a47a0b2ce3991f7">clampReturnedValueStates</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a1e5d35d93b0a1cd5f85018b1a98a883f">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::collectConstantsForGEP</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ae86be98f39008a27ba987e282fc8dc2c">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::genericValueTraversal</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignimpl/#a7f62f5a5ebedf7a57d3ae233194f0436">anonymous{AttributorAttributes.cpp}::AAAlignImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a713758a5b4aeee53e9d6bea99a501d45">llvm::Attributor::getAssumedConstant</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#af916e9c6236ca0251f6b7ce190543435">llvm::Attributor::getAssumedSimplified</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#ae92d755a80dec605503e2ba653765360">llvm::Attributor::getAssumedSimplifiedValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a605fed3c698bbafcf2d81aa2a1b191af">getPotentialCopiesOfMemoryValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a3de59e829dffdff466e6c22944ac47a8">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleGenericInst</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a3b776824b1ee93e75dcf982fec706900">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#adab9b2e1a33cfbe6f0fa6443046dcaf8">llvm::Attributor::identifyDefaultAbstractAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a78cf0931abfbc70e124e7c225584b686">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a1f2a3f39b7febd40285065a7ed05b71d">llvm::AA::isAssumedThreadLocalObject</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a2a4744a0553a69a758f119c04c303ae5">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::isDeadStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a559168f78e20f2d3d0e1763ee6e751ef">llvm::AA::isDynamicallyUnique</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#a0a41d500fe5dcf2f575b99316d25ec30">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::isKnownNoAliasDueToNoAliasPreservation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a2517066083f5a59ca08c9724f8e727db">llvm::AA::isPotentiallyAffectedByBarrier</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ae965a8b6001eaf1612d36d070594c706">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifycallsiteargument/#a8779a21bd698d1abfabf4fc3f7fd64b9">anonymous{AttributorAttributes.cpp}::AAValueSimplifyCallSiteArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a370b5637d8494d95fb8867b813fa71d8">anonymous{OpenMPOpt.cpp}::OpenMPOpt::registerAAsForFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuattributor-cpp-/#a54acd54cc3db43b11d42ebf210d08cf7">anonymous{AMDGPUAttributor.cpp}::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a8f460c92906b40c343854b69d48db50a">stripAndAccumulateOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/subsumingpositioniterator/#a88c3ecf0e220e6dcd1afee9f86c8d806">llvm::SubsumingPositionIterator::SubsumingPositionIterator</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaalignfloating/#a0206ea336f22470d5fe01f65dae9eb85">anonymous{AttributorAttributes.cpp}::AAAlignFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgescallsite/#a827970be0131200af76c14c9e1a24b15">anonymous{AttributorAttributes.cpp}::AACallEdgesCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aadereferenceablefloating/#a41c5ffc9c348c806bd197076e245aa1a">anonymous{AttributorAttributes.cpp}::AADereferenceableFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#a554ade21fa5bda8daa3af645c00364b1">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#ae7864a73feb64332db5d9304ee4a7ace">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliasreturned/#a58add1c5be55c8da55788e7cc412a877">anonymous{AttributorAttributes.cpp}::AANoAliasReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a2b832055235bac7e33fee8273b9c0211">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofpclassfloating/#a9c2d1fb920f390ee52852043fb2a2741">anonymous{AttributorAttributes.cpp}::AANoFPClassFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanonnullfloating/#a4b1fa4ad98c736b05369d73702328439">anonymous{AttributorAttributes.cpp}::AANonNullFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoundeffloating/#a6b86977408d6fd3bc77f900143401adb">anonymous{AttributorAttributes.cpp}::AANoUndefFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluescallsiteargument/#aac76be7819743fabe47e340fdfe9cdc5">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluescallsitereturned/#a326827ab35aa09c37cb1a4ee329f67ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesCallSiteReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesreturned/#a8f6027dabb6a1e32d6d01e904d6372a0">anonymous{AttributorAttributes.cpp}::AAPotentialValuesReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaundefinedbehaviorimpl/#ae455d1ecbeb7d95762d758c9aae70512">anonymous{AttributorAttributes.cpp}::AAUndefinedBehaviorImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaunderlyingobjectsimpl/#a5853fd1282daf0510e9eb037ffe23f8a">anonymous{AttributorAttributes.cpp}::AAUnderlyingObjectsImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a326d4c3fb95ebe6cbdca9c9e312da4a8">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyreturned/#ac9ae54449e677f539c50426011907713">anonymous{AttributorAttributes.cpp}::AAValueSimplifyReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ab05c198311b34d95f57423b9f9c1d1e6">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#ab6ccb880feb2a2e1b75a7e15f3a7db51">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::updateWithBinaryOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#af8fd85d6783b4f0fbb5f4a8d6bf40bdc">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::updateWithCastInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#a6903727302b4d2ede04403999ffd2827">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::updateWithICmpInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#ad945212604a8516c398d616618f30329">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::updateWithInstruction</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialconstantvaluesfloating/#af9ec5fb7fffc6b74b241d8ecc20e346b">anonymous{AttributorAttributes.cpp}::AAPotentialConstantValuesFloating::updateWithSelectInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### isReturnPosition() {#a808f522f0e55d169bdbde1bcd6be6810}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IRPosition::isReturnPosition (char EncodingBits)</td>
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

<p>Return true if <span class="doxyComputerOutput">EncodingBits</span> describe a returned or call site returned position.</p>

<p>Definition at line 1038 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### EmptyKey {#a75747cfadac3aa9128cb081adf37190a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRPosition IRPosition::EmptyKey</td>
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

<p>Special <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> key values.</p>


<p>{</p>


<p>Definition at line 940 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-9f64d73143315c4916785a7d42181db8/#a570c51559229d60f5c0ab352953fb31c">llvm::DenseMapInfo&lt; IRPosition &gt;::getEmptyKey</a>.</p>

</div>
</div>

### TombstoneKey {#a515f72643916067816c01b28240e49d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IRPosition IRPosition::TombstoneKey</td>
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



<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-9f64d73143315c4916785a7d42181db8/#a70e06cbe6835e8e49bb6fb749dad021f">llvm::DenseMapInfo&lt; IRPosition &gt;::getTombstoneKey</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### NumEncodingBits {#a593d823cf50de540a86b8c87a391d932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::IRPosition::NumEncodingBits</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="/web-llvm/docs/api/structs/llvm/pointerliketypetraits">PointerLikeTypeTraits</a>&lt;void *&gt;::NumLowBitsAvailable
</div>
</dd>
</dl>

<p>Definition at line 1061 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp">Attributor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
