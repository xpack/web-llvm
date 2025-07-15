---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/opt/option
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Option` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> - Abstract representation for a single form of driver argument. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::opt::Option { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">llvm/Option/Option.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OptionClass { <a href="#a60071c133b78fca37ea728e2d1db6fdb">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RenderStyleKind { <a href="#a739567de085c6a58e82c61c620cff335">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b29f4fee068660e847497750070f564">Option</a> (const OptTable::Info *Info, const OptTable *Owner)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99f5ea5ba3bdee23daa085d5610947f2">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6c2cfdd6ffa4c50bc9c35c159134e5b">getID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a60071c133b78fca37ea728e2d1db6fdb">OptionClass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9f02df6ca48ba1f7a3010c445393be">getKind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc97061b780820c39cc4afd878aec21b">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name of this option without any prefix. <a href="#acc97061b780820c39cc4afd878aec21b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26489197ed722748950eeaf82d2732f7">getGroup</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048c8480477c33a0b65c0b5815540c4b">getAlias</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae70494db86ba499b0d16e5f5d0a0af">getAliasArgs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the alias arguments as a \0 separated list. <a href="#a1ae70494db86ba499b0d16e5f5d0a0af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6604b3e1abb2089b8fb2e1880a92daa6">getPrefix</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the default prefix for this option. <a href="#a6604b3e1abb2089b8fb2e1880a92daa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90afd0b4b229eea67299a6310c9a3f7f">getPrefixedName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name of this option with the default prefix. <a href="#a90afd0b4b229eea67299a6310c9a3f7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcd1d96887e825b2f656e101ca3c6e3f">getHelpText</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the help text for this option. <a href="#abcd1d96887e825b2f656e101ca3c6e3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92653bffe5310da6286ad25623c1b891">getMetaVar</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the meta-variable list for this option. <a href="#a92653bffe5310da6286ad25623c1b891">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a123b053ace6cf2ab911b09183e453738">getNumArgs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a99a33090035c4835bad939af394777">hasNoOptAsInput</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a739567de085c6a58e82c61c620cff335">RenderStyleKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fe1d32f521a1a65b0794f992fcfcdbd">getRenderStyle</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5297d732b8f9e9447a4f86e9eda1780e">hasFlag</a> (unsigned Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this option has the flag <em>Val</em>. <a href="#a5297d732b8f9e9447a4f86e9eda1780e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a772f45a13c458f1ca87fe137724017bf">hasVisibilityFlag</a> (unsigned Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this option has the visibility flag <em>Val</em>. <a href="#a772f45a13c458f1ca87fe137724017bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33fbc0000453934c9139005e31036ff6">getUnaliasedOption</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getUnaliasedOption - Return the final option this option aliases (itself, if the option has no alias). <a href="#a33fbc0000453934c9139005e31036ff6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a442eaaa9f9bfd7ba6d3b6d2dfe0b2714">getRenderName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getRenderName - Return the name to use when rendering this option. <a href="#a442eaaa9f9bfd7ba6d3b6d2dfe0b2714">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34443bb51a0b61e6c113e721533d3235">matches</a> (OptSpecifier ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>matches - <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> for whether this option is part of the given option (which may be a group). <a href="#a34443bb51a0b61e6c113e721533d3235">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad51076ec38d35888db2929e6df4c72b8">accept</a> (const ArgList &amp;Args, StringRef CurArg, bool GroupedShortOption, unsigned &amp;Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Potentially accept the current argument, returning a new <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> instance, or 0 if the option does not accept this argument (or the argument is missing values). <a href="#ad51076ec38d35888db2929e6df4c72b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a> (raw_ostream &amp;O, bool AddNewLine=true) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07df67e096ac6736534eeb740165d530">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5163baa61c57343dae94d6a4b9a3fc1b">acceptInternal</a> (const ArgList &amp;Args, StringRef CurArg, unsigned &amp;Index) const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info">OptTable::Info</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26840bd5357df22b8465782d8c50504a">Owner</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> - Abstract representation for a single form of driver argument.</p>


<p>An <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> class represents a form of option that the driver takes, for example how many arguments the option has and how they can be provided. Individual option instances store additional information about what group the option is a member of (if any), if the option is an alias, and a number of flags. At runtime the driver parses the command line into concrete <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> instances, each of which corresponds to a particular <a href="/web-llvm/docs/api/classes/llvm/opt/option">Option</a> instance.</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### OptionClass {#a60071c133b78fca37ea728e2d1db6fdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::opt::Option::OptionClass </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GroupClass<a id="a60071c133b78fca37ea728e2d1db6fdba0f16fdf1d979a9ba138dc95d6717ceef"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InputClass<a id="a60071c133b78fca37ea728e2d1db6fdba7024d387cb59117469f0c569582aa5f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UnknownClass<a id="a60071c133b78fca37ea728e2d1db6fdba71db01a325850d1a7b626f06e71a6504"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FlagClass<a id="a60071c133b78fca37ea728e2d1db6fdba27b06b20590e7663bda7eaecf0c37a9c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">JoinedClass<a id="a60071c133b78fca37ea728e2d1db6fdba00b88f85db9274d8b0b201f43ee119aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ValuesClass<a id="a60071c133b78fca37ea728e2d1db6fdbaf6b275b7fac73f5fe312a2792767a14e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SeparateClass<a id="a60071c133b78fca37ea728e2d1db6fdba8cc1cc3ad33454d90a35df26268b75e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RemainingArgsClass<a id="a60071c133b78fca37ea728e2d1db6fdba67c06d35b9ba366cd9bd137a72ea8a24"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RemainingArgsJoinedClass<a id="a60071c133b78fca37ea728e2d1db6fdbaf04ccf92614d9d8e8cb585d71d1e31b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CommaJoinedClass<a id="a60071c133b78fca37ea728e2d1db6fdba12db4284256b50d5b531680ae77ab8e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MultiArgClass<a id="a60071c133b78fca37ea728e2d1db6fdba6fcf25ba21f30298b3d3a78bd31a44ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">JoinedOrSeparateClass<a id="a60071c133b78fca37ea728e2d1db6fdba659e5c55e0d0fe0918c9a7f9a6baa337"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">JoinedAndSeparateClass<a id="a60071c133b78fca37ea728e2d1db6fdbaa237a218eacb9074f730d871a7fa7489"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>

</div>
</div>

### RenderStyleKind {#a739567de085c6a58e82c61c620cff335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::opt::Option::RenderStyleKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RenderCommaJoinedStyle<a id="a739567de085c6a58e82c61c620cff335a5c95bf60f491f70f205ec32efbc0782b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RenderJoinedStyle<a id="a739567de085c6a58e82c61c620cff335acc1219b60acb3b04c128b71b3902f7b9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RenderSeparateStyle<a id="a739567de085c6a58e82c61c620cff335a2dd324dea833643936661a8ceccc2134"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RenderValuesStyle<a id="a739567de085c6a58e82c61c620cff335ab9ce42236f52b039069d85487491099d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Option() {#a3b29f4fee068660e847497750070f564}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Option::Option (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/opt/opttable/info">OptTable::Info</a> * Info, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/opttable">OptTable</a> * Owner)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp">Option.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba27b06b20590e7663bda7eaecf0c37a9c">FlagClass</a>, <a href="#a048c8480477c33a0b65c0b5815540c4b">getAlias</a>, <a href="#a1ae70494db86ba499b0d16e5f5d0a0af">getAliasArgs</a>, <a href="#ade9f02df6ca48ba1f7a3010c445393be">getKind</a>, <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#ad7f64bcc544dcefb2e068282af1c549d">info</a>, <a href="#a99f5ea5ba3bdee23daa085d5610947f2">isValid</a> and <a href="#a26840bd5357df22b8465782d8c50504a">Owner</a>.</p>


<p>Referenced by <a href="#ad51076ec38d35888db2929e6df4c72b8">accept</a>, <a href="#a048c8480477c33a0b65c0b5815540c4b">getAlias</a>, <a href="#a26489197ed722748950eeaf82d2732f7">getGroup</a>, <a href="#a33fbc0000453934c9139005e31036ff6">getUnaliasedOption</a>, <a href="#a34443bb51a0b61e6c113e721533d3235">matches</a> and <a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### accept() {#ad51076ec38d35888db2929e6df4c72b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Arg &gt; Option::accept (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> &amp; Args, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CurArg, bool GroupedShortOption, unsigned &amp; Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Potentially accept the current argument, returning a new <a href="/web-llvm/docs/api/classes/llvm/opt/arg">Arg</a> instance, or 0 if the option does not accept this argument (or the argument is missing values).</p>


<p>If the option accepts the current argument, <a href="#ad51076ec38d35888db2929e6df4c72b8">accept()</a> sets Index to the position where argument parsing should resume (even if the argument is missing values).</p>


<p><span class="doxyComputerOutput">CurArg</span> The argument to be matched. It may be shorter than the underlying storage to represent a Joined argument. <span class="doxyComputerOutput">GroupedShortOption</span> If true, we are handling the fallback case of parsing a prefix of the current argument as a short option.</p>


<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>, definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp">Option.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba27b06b20590e7663bda7eaecf0c37a9c">FlagClass</a>, <a href="#a1ae70494db86ba499b0d16e5f5d0a0af">getAliasArgs</a>, <a href="#aa6c2cfdd6ffa4c50bc9c35c159134e5b">getID</a>, <a href="#ade9f02df6ca48ba1f7a3010c445393be">getKind</a>, <a href="#acc97061b780820c39cc4afd878aec21b">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a29d52b9fb127c8147a41bda94dbe004c">llvm::opt::Arg::getOwnsValues</a>, <a href="#a6604b3e1abb2089b8fb2e1880a92daa6">getPrefix</a>, <a href="#a33fbc0000453934c9139005e31036ff6">getUnaliasedOption</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a5fae2e9403c3f2b91455abe787c41add">llvm::opt::Arg::getValues</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba00b88f85db9274d8b0b201f43ee119aa">JoinedClass</a>, <a href="#a3b29f4fee068660e847497750070f564">Option</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/arg/#a7ff387bacccd19c72cfd221be08db836">llvm::opt::Arg::setOwnsValues</a>.</p>

</div>
</div>

### dump() {#a07df67e096ac6736534eeb740165d530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Option::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>, definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp">Option.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#a25c39b3831711b590024c338280aca72">llvm::opt::OptTable::OptTable</a>.</p>

</div>
</div>

### getAlias() {#a048c8480477c33a0b65c0b5815540c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Option llvm::opt::Option::getAlias ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>, <a href="#a3b29f4fee068660e847497750070f564">Option</a> and <a href="#a26840bd5357df22b8465782d8c50504a">Owner</a>.</p>


<p>Referenced by <a href="#a33fbc0000453934c9139005e31036ff6">getUnaliasedOption</a>, <a href="#a34443bb51a0b61e6c113e721533d3235">matches</a>, <a href="#a3b29f4fee068660e847497750070f564">Option</a> and <a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a>.</p>

</div>
</div>

### getAliasArgs() {#a1ae70494db86ba499b0d16e5f5d0a0af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::opt::Option::getAliasArgs ()</td>
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

<p>Get the alias arguments as a \0 separated list.</p>


<p>E.g. ["foo", "bar"] would be returned as "foo\0bar\0".</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>.</p>


<p>Referenced by <a href="#ad51076ec38d35888db2929e6df4c72b8">accept</a> and <a href="#a3b29f4fee068660e847497750070f564">Option</a>.</p>

</div>
</div>

### getGroup() {#a26489197ed722748950eeaf82d2732f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Option llvm::opt::Option::getGroup ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>, <a href="#a3b29f4fee068660e847497750070f564">Option</a> and <a href="#a26840bd5357df22b8465782d8c50504a">Owner</a>.</p>


<p>Referenced by <a href="#a34443bb51a0b61e6c113e721533d3235">matches</a> and <a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a>.</p>

</div>
</div>

### getHelpText() {#abcd1d96887e825b2f656e101ca3c6e3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::opt::Option::getHelpText ()</td>
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

<p>Get the help text for this option.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>.</p>

</div>
</div>

### getID() {#aa6c2cfdd6ffa4c50bc9c35c159134e5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::Option::getID ()</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>.</p>


<p>Referenced by <a href="#ad51076ec38d35888db2929e6df4c72b8">accept</a> and <a href="#a34443bb51a0b61e6c113e721533d3235">matches</a>.</p>

</div>
</div>

### getKind() {#ade9f02df6ca48ba1f7a3010c445393be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptionClass llvm::opt::Option::getKind ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>.</p>


<p>Referenced by <a href="#ad51076ec38d35888db2929e6df4c72b8">accept</a>, <a href="#a1fe1d32f521a1a65b0794f992fcfcdbd">getRenderStyle</a>, <a href="#a3b29f4fee068660e847497750070f564">Option</a> and <a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a>.</p>

</div>
</div>

### getMetaVar() {#a92653bffe5310da6286ad25623c1b891}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::opt::Option::getMetaVar ()</td>
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

<p>Get the meta-variable list for this option.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>.</p>

</div>
</div>

### getName() {#acc97061b780820c39cc4afd878aec21b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::opt::Option::getName ()</td>
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

<p>Get the name of this option without any prefix.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a> and <a href="#a26840bd5357df22b8465782d8c50504a">Owner</a>.</p>


<p>Referenced by <a href="#ad51076ec38d35888db2929e6df4c72b8">accept</a>, <a href="#a442eaaa9f9bfd7ba6d3b6d2dfe0b2714">getRenderName</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#aca9495741a522bfdc26c89f88b16ff69">llvm::opt::DerivedArgList::MakeFlagArg</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#a5893f33295c921df5928e5ab9feb90cc">llvm::opt::DerivedArgList::MakeJoinedArg</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#a909c2fa4bf18ec1dbe50a77adf3f48a3">llvm::opt::DerivedArgList::MakePositionalArg</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#a2afff7edd330e44f3f1814a6e364c081">llvm::opt::DerivedArgList::MakeSeparateArg</a> and <a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a>.</p>

</div>
</div>

### getNumArgs() {#a123b053ace6cf2ab911b09183e453738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::opt::Option::getNumArgs ()</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>Reference <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>.</p>


<p>Referenced by <a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a>.</p>

</div>
</div>

### getPrefix() {#a6604b3e1abb2089b8fb2e1880a92daa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::opt::Option::getPrefix ()</td>
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

<p>Get the default prefix for this option.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a> and <a href="#a26840bd5357df22b8465782d8c50504a">Owner</a>.</p>


<p>Referenced by <a href="#ad51076ec38d35888db2929e6df4c72b8">accept</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#aca9495741a522bfdc26c89f88b16ff69">llvm::opt::DerivedArgList::MakeFlagArg</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#a5893f33295c921df5928e5ab9feb90cc">llvm::opt::DerivedArgList::MakeJoinedArg</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#a909c2fa4bf18ec1dbe50a77adf3f48a3">llvm::opt::DerivedArgList::MakePositionalArg</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/derivedarglist/#a2afff7edd330e44f3f1814a6e364c081">llvm::opt::DerivedArgList::MakeSeparateArg</a>.</p>

</div>
</div>

### getPrefixedName() {#a90afd0b4b229eea67299a6310c9a3f7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::opt::Option::getPrefixedName ()</td>
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

<p>Get the name of this option with the default prefix.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a> and <a href="#a26840bd5357df22b8465782d8c50504a">Owner</a>.</p>

</div>
</div>

### getRenderName() {#a442eaaa9f9bfd7ba6d3b6d2dfe0b2714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::opt::Option::getRenderName ()</td>
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

<p>getRenderName - Return the name to use when rendering this option.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="#acc97061b780820c39cc4afd878aec21b">getName</a> and <a href="#a33fbc0000453934c9139005e31036ff6">getUnaliasedOption</a>.</p>

</div>
</div>

### getRenderStyle() {#a1fe1d32f521a1a65b0794f992fcfcdbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RenderStyleKind llvm::opt::Option::getRenderStyle ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="#a60071c133b78fca37ea728e2d1db6fdba12db4284256b50d5b531680ae77ab8e6">CommaJoinedClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba27b06b20590e7663bda7eaecf0c37a9c">FlagClass</a>, <a href="#ade9f02df6ca48ba1f7a3010c445393be">getKind</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba0f16fdf1d979a9ba138dc95d6717ceef">GroupClass</a>, <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba7024d387cb59117469f0c569582aa5f5">InputClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdbaa237a218eacb9074f730d871a7fa7489">JoinedAndSeparateClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba00b88f85db9274d8b0b201f43ee119aa">JoinedClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba659e5c55e0d0fe0918c9a7f9a6baa337">JoinedOrSeparateClass</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba6fcf25ba21f30298b3d3a78bd31a44ac">MultiArgClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba67c06d35b9ba366cd9bd137a72ea8a24">RemainingArgsClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdbaf04ccf92614d9d8e8cb585d71d1e31b4">RemainingArgsJoinedClass</a>, <a href="#a739567de085c6a58e82c61c620cff335a5c95bf60f491f70f205ec32efbc0782b">RenderCommaJoinedStyle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/opt/#a834f7f7c0030af7d8ca758ed0468c8dcab11a4c028e5d5cef4434a124831d1790">llvm::opt::RenderJoined</a>, <a href="#a739567de085c6a58e82c61c620cff335acc1219b60acb3b04c128b71b3902f7b9">RenderJoinedStyle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/opt/#a834f7f7c0030af7d8ca758ed0468c8dca18e71836d111ff8565e7697f9ae61af7">llvm::opt::RenderSeparate</a>, <a href="#a739567de085c6a58e82c61c620cff335a2dd324dea833643936661a8ceccc2134">RenderSeparateStyle</a>, <a href="#a739567de085c6a58e82c61c620cff335ab9ce42236f52b039069d85487491099d">RenderValuesStyle</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba8cc1cc3ad33454d90a35df26268b75e4">SeparateClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba71db01a325850d1a7b626f06e71a6504">UnknownClass</a> and <a href="#a60071c133b78fca37ea728e2d1db6fdbaf6b275b7fac73f5fe312a2792767a14e">ValuesClass</a>.</p>

</div>
</div>

### getUnaliasedOption() {#a33fbc0000453934c9139005e31036ff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Option llvm::opt::Option::getUnaliasedOption ()</td>
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

<p>getUnaliasedOption - Return the final option this option aliases (itself, if the option has no alias).</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="#a048c8480477c33a0b65c0b5815540c4b">getAlias</a>, <a href="#a33fbc0000453934c9139005e31036ff6">getUnaliasedOption</a>, <a href="#a99f5ea5ba3bdee23daa085d5610947f2">isValid</a> and <a href="#a3b29f4fee068660e847497750070f564">Option</a>.</p>


<p>Referenced by <a href="#ad51076ec38d35888db2929e6df4c72b8">accept</a>, <a href="#a442eaaa9f9bfd7ba6d3b6d2dfe0b2714">getRenderName</a> and <a href="#a33fbc0000453934c9139005e31036ff6">getUnaliasedOption</a>.</p>

</div>
</div>

### hasFlag() {#a5297d732b8f9e9447a4f86e9eda1780e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::Option::hasFlag (unsigned Val)</td>
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

<p>Test if this option has the flag <em>Val</em>.</p>

<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>Reference <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#ac095b04e69b50cc16e488b2cebd8ecc6">llvm::opt::OptTable::ParseArgs</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#a534b852fce32e3f367c7d79668439fe0">llvm::opt::OptTable::ParseOneArg</a>.</p>

</div>
</div>

### hasNoOptAsInput() {#a5a99a33090035c4835bad939af394777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::Option::hasNoOptAsInput ()</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>References <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a> and <a href="/web-llvm/docs/api/namespaces/llvm/opt/#a834f7f7c0030af7d8ca758ed0468c8dcade44c6628f8b8f63d51faa333af05b5b">llvm::opt::RenderAsInput</a>.</p>

</div>
</div>

### hasVisibilityFlag() {#a772f45a13c458f1ca87fe137724017bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::Option::hasVisibilityFlag (unsigned Val)</td>
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

<p>Test if this option has the visibility flag <em>Val</em>.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>Reference <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#aae1e1c17454fb6433f039b5fb02c5c4d">llvm::opt::OptTable::ParseArgs</a> and <a href="/web-llvm/docs/api/classes/llvm/opt/opttable/#a209267a94d47fc715aedcb7c0b836d36">llvm::opt::OptTable::ParseOneArg</a>.</p>

</div>
</div>

### isValid() {#a99f5ea5ba3bdee23daa085d5610947f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::opt::Option::isValid ()</td>
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



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>Reference <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>.</p>


<p>Referenced by <a href="#a33fbc0000453934c9139005e31036ff6">getUnaliasedOption</a>, <a href="#a34443bb51a0b61e6c113e721533d3235">matches</a>, <a href="#a3b29f4fee068660e847497750070f564">Option</a> and <a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a>.</p>

</div>
</div>

### matches() {#a34443bb51a0b61e6c113e721533d3235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Option::matches (<a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier">OptSpecifier</a> ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>matches - <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> for whether this option is part of the given option (which may be a group).</p>


<p>Note that matches against options which are an alias should never be done – aliases do not participate in matching and so such a query will always be false.</p>


<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp">Option.cpp</a>.</p>


<p>References <a href="#a048c8480477c33a0b65c0b5815540c4b">getAlias</a>, <a href="#a26489197ed722748950eeaf82d2732f7">getGroup</a>, <a href="#aa6c2cfdd6ffa4c50bc9c35c159134e5b">getID</a>, <a href="/web-llvm/docs/api/classes/llvm/opt/optspecifier/#af3dfa747aaff5143476f4840de4df433">llvm::opt::OptSpecifier::getID</a>, <a href="#a99f5ea5ba3bdee23daa085d5610947f2">isValid</a>, <a href="#a34443bb51a0b61e6c113e721533d3235">matches</a> and <a href="#a3b29f4fee068660e847497750070f564">Option</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/opt/arglist/#ab7ef568579e2fc175c4d3d68921a1a9b">llvm::opt::ArgList::AddAllArgsExcept</a> and <a href="#a34443bb51a0b61e6c113e721533d3235">matches</a>.</p>

</div>
</div>

### print() {#afd58fdbc2f1005c2c368a24fd8af0c7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Option::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, bool AddNewLine=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp">Option.cpp</a>.</p>


<p>References <a href="#a60071c133b78fca37ea728e2d1db6fdba12db4284256b50d5b531680ae77ab8e6">CommaJoinedClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba27b06b20590e7663bda7eaecf0c37a9c">FlagClass</a>, <a href="#a048c8480477c33a0b65c0b5815540c4b">getAlias</a>, <a href="#a26489197ed722748950eeaf82d2732f7">getGroup</a>, <a href="#ade9f02df6ca48ba1f7a3010c445393be">getKind</a>, <a href="#acc97061b780820c39cc4afd878aec21b">getName</a>, <a href="#a123b053ace6cf2ab911b09183e453738">getNumArgs</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba0f16fdf1d979a9ba138dc95d6717ceef">GroupClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a85ba404acf949ab8564ec8c27f965b4c">Info</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba7024d387cb59117469f0c569582aa5f5">InputClass</a>, <a href="#a99f5ea5ba3bdee23daa085d5610947f2">isValid</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdbaa237a218eacb9074f730d871a7fa7489">JoinedAndSeparateClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba00b88f85db9274d8b0b201f43ee119aa">JoinedClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba659e5c55e0d0fe0918c9a7f9a6baa337">JoinedOrSeparateClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba6fcf25ba21f30298b3d3a78bd31a44ac">MultiArgClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a3b29f4fee068660e847497750070f564">Option</a>, <a href="#a26840bd5357df22b8465782d8c50504a">Owner</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba67c06d35b9ba366cd9bd137a72ea8a24">RemainingArgsClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdbaf04ccf92614d9d8e8cb585d71d1e31b4">RemainingArgsJoinedClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba8cc1cc3ad33454d90a35df26268b75e4">SeparateClass</a>, <a href="#a60071c133b78fca37ea728e2d1db6fdba71db01a325850d1a7b626f06e71a6504">UnknownClass</a> and <a href="#a60071c133b78fca37ea728e2d1db6fdbaf6b275b7fac73f5fe312a2792767a14e">ValuesClass</a>.</p>


<p>Referenced by <a href="#a07df67e096ac6736534eeb740165d530">dump</a> and <a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### acceptInternal() {#a5163baa61c57343dae94d6a4b9a3fc1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; Arg &gt; Option::acceptInternal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/opt/arglist">ArgList</a> &amp; Args, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CurArg, unsigned &amp; Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp">Option.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Info {#a85ba404acf949ab8564ec8c27f965b4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OptTable::Info* llvm::opt::Option::Info</td>
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



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>Referenced by <a href="#a048c8480477c33a0b65c0b5815540c4b">getAlias</a>, <a href="#a1ae70494db86ba499b0d16e5f5d0a0af">getAliasArgs</a>, <a href="#a26489197ed722748950eeaf82d2732f7">getGroup</a>, <a href="#abcd1d96887e825b2f656e101ca3c6e3f">getHelpText</a>, <a href="#aa6c2cfdd6ffa4c50bc9c35c159134e5b">getID</a>, <a href="#ade9f02df6ca48ba1f7a3010c445393be">getKind</a>, <a href="#a92653bffe5310da6286ad25623c1b891">getMetaVar</a>, <a href="#acc97061b780820c39cc4afd878aec21b">getName</a>, <a href="#a123b053ace6cf2ab911b09183e453738">getNumArgs</a>, <a href="#a6604b3e1abb2089b8fb2e1880a92daa6">getPrefix</a>, <a href="#a90afd0b4b229eea67299a6310c9a3f7f">getPrefixedName</a>, <a href="#a1fe1d32f521a1a65b0794f992fcfcdbd">getRenderStyle</a>, <a href="#a5297d732b8f9e9447a4f86e9eda1780e">hasFlag</a>, <a href="#a5a99a33090035c4835bad939af394777">hasNoOptAsInput</a>, <a href="#a772f45a13c458f1ca87fe137724017bf">hasVisibilityFlag</a>, <a href="#a99f5ea5ba3bdee23daa085d5610947f2">isValid</a>, <a href="#a3b29f4fee068660e847497750070f564">Option</a> and <a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a>.</p>

</div>
</div>

### Owner {#a26840bd5357df22b8465782d8c50504a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OptTable* llvm::opt::Option::Owner</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a>.</p>


<p>Referenced by <a href="#a048c8480477c33a0b65c0b5815540c4b">getAlias</a>, <a href="#a26489197ed722748950eeaf82d2732f7">getGroup</a>, <a href="#acc97061b780820c39cc4afd878aec21b">getName</a>, <a href="#a6604b3e1abb2089b8fb2e1880a92daa6">getPrefix</a>, <a href="#a90afd0b4b229eea67299a6310c9a3f7f">getPrefixedName</a>, <a href="#a3b29f4fee068660e847497750070f564">Option</a> and <a href="#afd58fdbc2f1005c2c368a24fd8af0c7a">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/option/option-h">Option.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp">Option.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
