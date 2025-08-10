---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/aamemorylocation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AAMemoryLocation` Struct

<p>An abstract interface for all memory location attributes (readnone/argmemonly/inaccessiblememonly/inaccessibleorargmemonly). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AAMemoryLocation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irattribute">IRAttribute&lt;AK, BaseType, AAType&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class that provides common functionality to manifest IR attributes. <a href="/web-llvm/docs/api/structs/llvm/irattribute/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl">AAMemoryLocationImpl</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acffe374fb52ac7da0511285fdf18db3f">MemoryLocationsKind</a> = StateType::base_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a85955f71af20254ae831687849a1a737">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encoding of different locations that could be accessed by a memory access. <a href="#a85955f71af20254ae831687849a1a737">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AccessKind { <a href="#ace2d4d5ab8dffea597c39bc129d90f7f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple enum to distinguish read/write/read-write accesses. <a href="#ace2d4d5ab8dffea597c39bc129d90f7f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a660dfbde897cf25a66779982ac229d5f">AAMemoryLocation</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6886f1cf25f5fb9b9271fc963eb44bb0">isKnownReadNone</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know that the associated functions has no observable accesses. <a href="#a6886f1cf25f5fb9b9271fc963eb44bb0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae336b602cf0a89b2fa9551663c6f3295">isAssumedReadNone</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we assume that the associated functions has no observable accesses. <a href="#ae336b602cf0a89b2fa9551663c6f3295">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f5e7b52ec272644d623f90e9bdf2a6">isKnowStackOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know that the associated functions has at most local/stack accesses. <a href="#ab0f5e7b52ec272644d623f90e9bdf2a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a670ad7c64202fcadc4b495d202ca94">isAssumedStackOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we assume that the associated functions has at most local/stack accesses. <a href="#a1a670ad7c64202fcadc4b495d202ca94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cc1dadfdb53fcbf5569c0c981aa5712">isKnownInaccessibleMemOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know that the underlying value will only access inaccesible memory only (see Attribute::InaccessibleMemOnly). <a href="#a8cc1dadfdb53fcbf5569c0c981aa5712">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a876121bc7d9e565f5627b2350d643c64">isAssumedInaccessibleMemOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we assume that the underlying value will only access inaccesible memory only (see Attribute::InaccessibleMemOnly). <a href="#a876121bc7d9e565f5627b2350d643c64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4378e42ae258a4054ff58e63f9b01ee0">isKnownArgMemOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know that the underlying value will only access argument pointees (see Attribute::ArgMemOnly). <a href="#a4378e42ae258a4054ff58e63f9b01ee0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e57f7a255f09243d9c303563c08ceb">isAssumedArgMemOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we assume that the underlying value will only access argument pointees (see Attribute::ArgMemOnly). <a href="#af6e57f7a255f09243d9c303563c08ceb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a563e350e9c47314a067dc36597f6fd6e">isKnownInaccessibleOrArgMemOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know that the underlying value will only access inaccesible memory or argument pointees (see Attribute::InaccessibleOrArgMemOnly). <a href="#a563e350e9c47314a067dc36597f6fd6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6830f20bec5f8746595c497d5c3c4ed">isAssumedInaccessibleOrArgMemOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we assume that the underlying value will only access inaccesible memory or argument pointees (see Attribute::InaccessibleOrArgMemOnly). <a href="#aa6830f20bec5f8746595c497d5c3c4ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af50764d16f0637e29df3c7966b6cf502">mayAccessArgMem</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the underlying value may access memory through arguement pointers of the associated function, if any. <a href="#af50764d16f0637e29df3c7966b6cf502">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79910be6a27195b251b67ff40f7698c5">isAssumedSpecifiedMemOnly</a> (MemoryLocationsKind MLK) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if only the memory locations specififed by <span class="doxyComputerOutput">MLK</span> are assumed to be accessed by the associated function. <a href="#a79910be6a27195b251b67ff40f7698c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acffe374fb52ac7da0511285fdf18db3f">MemoryLocationsKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7370cc538424a0e12fd632cb076c14c">getAssumedNotAccessedLocation</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the locations that are assumed to be not accessed by the associated function, if any. <a href="#ad7370cc538424a0e12fd632cb076c14c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec4f1c7abc767de9538c126136a46bf4">checkForAllAccessesToMemoryKind</a> (function_ref&lt; bool(const Instruction *, const Value *, AccessKind, MemoryLocationsKind)&gt; Pred, MemoryLocationsKind MLK) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> <span class="doxyComputerOutput">Pred</span> on all accesses to the memory kinds specified by <span class="doxyComputerOutput">MLK</span>. <a href="#aec4f1c7abc767de9538c126136a46bf4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef3103113c35eb930555239792ef2dca">getAsStr</a> (Attributor *A) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractState::getAsStr(Attributor). <a href="#aef3103113c35eb930555239792ef2dca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f480f9a790c3338388cb4d173cb669">getName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a7d84d85c6cb8cc16db41d83859096256">AbstractAttribute::getName()</a> <a href="#a68f480f9a790c3338388cb4d173cb669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16c79ab103872bfbfd17fca7ec5b4213">getIdAddr</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afb1ae982372c7bd88717c53d8f8e5470">AbstractAttribute::getIdAddr()</a> <a href="#a16c79ab103872bfbfd17fca7ec5b4213">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9faf87acb45cf235040ff743d7c8210">requiresCalleeForCallBase</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a42f6982d76a1141138c99c4e1b989ba0">AbstractAttribute::requiresCalleeForCallBase</a>. <a href="#ab9faf87acb45cf235040ff743d7c8210">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1fc577eaf160d9948ec93967020fa6c">hasTrivialInitializer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afdcbf0c6bc57e95a2975054b96839b85">AbstractAttribute::hasTrivialInitializer</a>. <a href="#ae1fc577eaf160d9948ec93967020fa6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae548fb21c1de2eb3ad47389ae31488f3">isValidIRPositionForInit</a> (Attributor &amp;A, const IRPosition &amp;IRP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a0b23d1cedd8202d1b786e1ab43313084">AbstractAttribute::isValidIRPositionForInit</a>. <a href="#ae548fb21c1de2eb3ad47389ae31488f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#acffe374fb52ac7da0511285fdf18db3f">MemoryLocationsKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0831ad69241e3cde373281a1024848">inverseLocation</a> (MemoryLocationsKind Loc, bool AndLocalMem, bool AndConstMem)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the inverse of location <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>, thus for NO_XXX the return describes ONLY_XXX. <a href="#afc0831ad69241e3cde373281a1024848">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37f5c90d6e9853a204b4ca1da2317c66">getMemoryLocationsAsStr</a> (MemoryLocationsKind MLK)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the locations encoded by <span class="doxyComputerOutput">MLK</span> as a readable string. <a href="#a37f5c90d6e9853a204b4ca1da2317c66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation">AAMemoryLocation</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352ad646ccf23e5cf4ad1420330357e3">createForPosition</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an abstract attribute view for the position <span class="doxyComputerOutput">IRP</span>. <a href="#a352ad646ccf23e5cf4ad1420330357e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7a2ec4e2d42563fd0e6ba6ed2fd4ea4">classof</a> (const AbstractAttribute *AA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function should return true if the type of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> is <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation">AAMemoryLocation</a>. <a href="#ad7a2ec4e2d42563fd0e6ba6ed2fd4ea4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57002bf60277fbf32d88bd544be41e0f">ID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique ID (due to the unique address) <a href="#a57002bf60277fbf32d88bd544be41e0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An abstract interface for all memory location attributes (readnone/argmemonly/inaccessiblememonly/inaccessibleorargmemonly).</p>

<p>Definition at line 4709 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MemoryLocationsKind {#acffe374fb52ac7da0511285fdf18db3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AAMemoryLocation::MemoryLocationsKind =  StateType::base_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a85955f71af20254ae831687849a1a737}

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

<p>Encoding of different locations that could be accessed by a memory access.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ALL_LOCATIONS<a id="a85955f71af20254ae831687849a1a737a0e7b3ae5911d61bd79225d9bda18f625"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_LOCAL_MEM<a id="a85955f71af20254ae831687849a1a737a3cd674c8b8c557b19cea3e0a6c4eb9a4"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_CONST_MEM<a id="a85955f71af20254ae831687849a1a737ab78c83bfe8ae55b0ce8b10773f244443"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_GLOBAL_INTERNAL_MEM<a id="a85955f71af20254ae831687849a1a737a5bc229053d97809b7320418384ae49b2"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_GLOBAL_EXTERNAL_MEM<a id="a85955f71af20254ae831687849a1a737af3f5a89da741bc5d46d9c5c13ae4bd52"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_GLOBAL_MEM<a id="a85955f71af20254ae831687849a1a737a8bd4fe34d8c924ec42c22a5156f9221d"></a></td>
<td class="doxyEnumItemDescription"> (= NO_GLOBAL_INTERNAL_MEM | NO_GLOBAL_EXTERNAL_MEM)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_ARGUMENT_MEM<a id="a85955f71af20254ae831687849a1a737ae2f2e5630a82d0153e2369b9e8290b6b"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_INACCESSIBLE_MEM<a id="a85955f71af20254ae831687849a1a737a8540c0ac516fe3b3e9ac52d378537f41"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_MALLOCED_MEM<a id="a85955f71af20254ae831687849a1a737a5702b1d175e7a1236d500fc64a1207bf"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_UNKOWN_MEM<a id="a85955f71af20254ae831687849a1a737afd32faf24ee03f6bc85e632020569048"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_LOCATIONS<a id="a85955f71af20254ae831687849a1a737ad3983885c932078fb829f29d2b7fed01"></a></td>
<td class="doxyEnumItemDescription">
 (= NO_LOCAL_MEM | NO_CONST_MEM | NO_GLOBAL_INTERNAL_MEM |
                   NO_GLOBAL_EXTERNAL_MEM | NO_ARGUMENT_MEM |
                   NO_INACCESSIBLE_MEM | NO_MALLOCED_MEM | NO_UNKOWN_MEM)
</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VALID_STATE<a id="a85955f71af20254ae831687849a1a737a9cac5c2e512a4b66789775333f4b5d53"></a></td>
<td class="doxyEnumItemDescription"> (= NO_LOCATIONS + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BEST_STATE<a id="a85955f71af20254ae831687849a1a737a4dd21df945eb0ef4d3eaa8137eb7a98a"></a></td>
<td class="doxyEnumItemDescription"> (= NO_LOCATIONS | VALID_STATE)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 4734 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### AccessKind {#ace2d4d5ab8dffea597c39bc129d90f7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AAMemoryLocation::AccessKind </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Simple enum to distinguish read/write/read-write accesses.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NONE<a id="ace2d4d5ab8dffea597c39bc129d90f7faed185f46b5cbd4dad3125978f8e69e6b"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">READ<a id="ace2d4d5ab8dffea597c39bc129d90f7faf8d236460bf15db958f25e6c7a258897"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WRITE<a id="ace2d4d5ab8dffea597c39bc129d90f7fa5f6f5c92d79526533958cfb066ec63bc"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">READ_WRITE<a id="ace2d4d5ab8dffea597c39bc129d90f7fa02060fba95d9f2779f0d05683b601c24"></a></td>
<td class="doxyEnumItemDescription"> (= READ | WRITE)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 4849 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AAMemoryLocation() {#a660dfbde897cf25a66779982ac229d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AAMemoryLocation::AAMemoryLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 4716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/structs/llvm/irattribute/#ac3333cdcba76a6af382bcb7acd0d8419">llvm::IRAttribute&lt; Attribute::None, StateWrapper&lt; BitIntegerState&lt; uint32_t, 511 &gt;, AbstractAttribute &gt;, AAMemoryLocation &gt;::IRAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a14fd1a0c7ba79d015f0d48a648e1c74e">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::AAMemoryLocationImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ae2c6df05bd2236b9d36680de5e09b78a">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizeAccessedLocations</a>, <a href="#a352ad646ccf23e5cf4ad1420330357e3">createForPosition</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationcallsite/#a36ef96efb68b331087c86a5c9920173c">anonymous{AttributorAttributes.cpp}::AAMemoryLocationCallSite::updateImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### checkForAllAccessesToMemoryKind() {#aec4f1c7abc767de9538c126136a46bf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAMemoryLocation::checkForAllAccessesToMemoryKind (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="#ace2d4d5ab8dffea597c39bc129d90f7f">AccessKind</a>, <a href="#acffe374fb52ac7da0511285fdf18db3f">MemoryLocationsKind</a>)&gt; Pred, <a href="#acffe374fb52ac7da0511285fdf18db3f">MemoryLocationsKind</a> MLK)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> <span class="doxyComputerOutput">Pred</span> on all accesses to the memory kinds specified by <span class="doxyComputerOutput">MLK</span>.</p>


<p>This method will evaluate <span class="doxyComputerOutput">Pred</span> on all accesses (access instruction + underlying accessed memory pointer) and it will return true if <span class="doxyComputerOutput">Pred</span> holds every time.</p>


<p>Definition at line 4861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### getAsStr() {#aef3103113c35eb930555239792ef2dca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::AAMemoryLocation::getAsStr (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> * A)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See AbstractState::getAsStr(Attributor).</p>

<p>Definition at line 4872 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#ad7370cc538424a0e12fd632cb076c14c">getAssumedNotAccessedLocation</a> and <a href="#a37f5c90d6e9853a204b4ca1da2317c66">getMemoryLocationsAsStr</a>.</p>

</div>
</div>

### getAssumedNotAccessedLocation() {#ad7370cc538424a0e12fd632cb076c14c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocationsKind llvm::AAMemoryLocation::getAssumedNotAccessedLocation ()</td>
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

<p>Return the locations that are assumed to be not accessed by the associated function, if any.</p>

<p>Definition at line 4830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#a8791f3eb0abe69328cbf726f8d0716ce">llvm::IntegerStateBase&lt; uint32_t, BestState, 0 &gt;::getAssumed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#adc7a4a81ba257d29a226a6f27a29a654">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::checkForAllAccessesToMemoryKind</a>, <a href="#aef3103113c35eb930555239792ef2dca">getAsStr</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction/#a4de16ddc7d968804ec058444ee4145fd">anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::updateImpl</a>.</p>

</div>
</div>

### getIdAddr() {#a16c79ab103872bfbfd17fca7ec5b4213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AAMemoryLocation::getIdAddr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afb1ae982372c7bd88717c53d8f8e5470">AbstractAttribute::getIdAddr()</a></p>

<p>Definition at line 4880 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a57002bf60277fbf32d88bd544be41e0f">ID</a>.</p>

</div>
</div>

### getName() {#a68f480f9a790c3338388cb4d173cb669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::AAMemoryLocation::getName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a7d84d85c6cb8cc16db41d83859096256">AbstractAttribute::getName()</a></p>

<p>Definition at line 4877 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### isAssumedArgMemOnly() {#af6e57f7a255f09243d9c303563c08ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::isAssumedArgMemOnly ()</td>
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

<p>Return true if we assume that the underlying value will only access argument pointees (see Attribute::ArgMemOnly).</p>

<p>Definition at line 4798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#afc0831ad69241e3cde373281a1024848">inverseLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a38acb9f66b8669c71052db94e468b3a9">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::isAssumed</a> and <a href="#a85955f71af20254ae831687849a1a737ae2f2e5630a82d0153e2369b9e8290b6b">NO_ARGUMENT_MEM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a8df2e20241276fa840a50aaf747a059e">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getDeducedAttributes</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction/#a8b0634676415b9b78a340cc026357ce8">anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::trackStatistics</a>.</p>

</div>
</div>

### isAssumedInaccessibleMemOnly() {#a876121bc7d9e565f5627b2350d643c64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::isAssumedInaccessibleMemOnly ()</td>
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

<p>Return true if we assume that the underlying value will only access inaccesible memory only (see Attribute::InaccessibleMemOnly).</p>

<p>Definition at line 4786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#afc0831ad69241e3cde373281a1024848">inverseLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a38acb9f66b8669c71052db94e468b3a9">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::isAssumed</a> and <a href="#a85955f71af20254ae831687849a1a737a8540c0ac516fe3b3e9ac52d378537f41">NO_INACCESSIBLE_MEM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a8df2e20241276fa840a50aaf747a059e">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getDeducedAttributes</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction/#a8b0634676415b9b78a340cc026357ce8">anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::trackStatistics</a>.</p>

</div>
</div>

### isAssumedInaccessibleOrArgMemOnly() {#aa6830f20bec5f8746595c497d5c3c4ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::isAssumedInaccessibleOrArgMemOnly ()</td>
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

<p>Return true if we assume that the underlying value will only access inaccesible memory or argument pointees (see Attribute::InaccessibleOrArgMemOnly).</p>

<p>Definition at line 4813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#afc0831ad69241e3cde373281a1024848">inverseLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a38acb9f66b8669c71052db94e468b3a9">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::isAssumed</a>, <a href="#a85955f71af20254ae831687849a1a737ae2f2e5630a82d0153e2369b9e8290b6b">NO_ARGUMENT_MEM</a> and <a href="#a85955f71af20254ae831687849a1a737a8540c0ac516fe3b3e9ac52d378537f41">NO_INACCESSIBLE_MEM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a8df2e20241276fa840a50aaf747a059e">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getDeducedAttributes</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction/#a8b0634676415b9b78a340cc026357ce8">anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::trackStatistics</a>.</p>

</div>
</div>

### isAssumedReadNone() {#ae336b602cf0a89b2fa9551663c6f3295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::isAssumedReadNone ()</td>
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

<p>Return true if we assume that the associated functions has no observable accesses.</p>

<p>Definition at line 4762 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a38acb9f66b8669c71052db94e468b3a9">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::isAssumed</a>, <a href="#a1a670ad7c64202fcadc4b495d202ca94">isAssumedStackOnly</a> and <a href="#a85955f71af20254ae831687849a1a737ad3983885c932078fb829f29d2b7fed01">NO_LOCATIONS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a8df2e20241276fa840a50aaf747a059e">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getDeducedAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationcallsite/#a9ff3eac1297ecb11ef708d2586789719">anonymous{AttributorAttributes.cpp}::AAMemoryLocationCallSite::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction/#a8b0634676415b9b78a340cc026357ce8">anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::trackStatistics</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction/#a4de16ddc7d968804ec058444ee4145fd">anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::updateImpl</a>.</p>

</div>
</div>

### isAssumedSpecifiedMemOnly() {#a79910be6a27195b251b67ff40f7698c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::isAssumedSpecifiedMemOnly (<a href="#acffe374fb52ac7da0511285fdf18db3f">MemoryLocationsKind</a> MLK)</td>
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

<p>Return true if only the memory locations specififed by <span class="doxyComputerOutput">MLK</span> are assumed to be accessed by the associated function.</p>

<p>Definition at line 4824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a38acb9f66b8669c71052db94e468b3a9">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::isAssumed</a>.</p>

</div>
</div>

### isAssumedStackOnly() {#a1a670ad7c64202fcadc4b495d202ca94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::isAssumedStackOnly ()</td>
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

<p>Return true if we assume that the associated functions has at most local/stack accesses.</p>

<p>Definition at line 4774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#afc0831ad69241e3cde373281a1024848">inverseLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a38acb9f66b8669c71052db94e468b3a9">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::isAssumed</a> and <a href="#a85955f71af20254ae831687849a1a737a3cd674c8b8c557b19cea3e0a6c4eb9a4">NO_LOCAL_MEM</a>.</p>


<p>Referenced by <a href="#ae336b602cf0a89b2fa9551663c6f3295">isAssumedReadNone</a>.</p>

</div>
</div>

### isKnownArgMemOnly() {#a4378e42ae258a4054ff58e63f9b01ee0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::isKnownArgMemOnly ()</td>
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

<p>Return true if we know that the underlying value will only access argument pointees (see Attribute::ArgMemOnly).</p>

<p>Definition at line 4792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#afc0831ad69241e3cde373281a1024848">inverseLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#af53ef7825e1ab608c8b6cc2ab94e5ddf">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::isKnown</a> and <a href="#a85955f71af20254ae831687849a1a737ae2f2e5630a82d0153e2369b9e8290b6b">NO_ARGUMENT_MEM</a>.</p>

</div>
</div>

### isKnownInaccessibleMemOnly() {#a8cc1dadfdb53fcbf5569c0c981aa5712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::isKnownInaccessibleMemOnly ()</td>
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

<p>Return true if we know that the underlying value will only access inaccesible memory only (see Attribute::InaccessibleMemOnly).</p>

<p>Definition at line 4780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#afc0831ad69241e3cde373281a1024848">inverseLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#af53ef7825e1ab608c8b6cc2ab94e5ddf">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::isKnown</a> and <a href="#a85955f71af20254ae831687849a1a737a8540c0ac516fe3b3e9ac52d378537f41">NO_INACCESSIBLE_MEM</a>.</p>

</div>
</div>

### isKnownInaccessibleOrArgMemOnly() {#a563e350e9c47314a067dc36597f6fd6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::isKnownInaccessibleOrArgMemOnly ()</td>
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

<p>Return true if we know that the underlying value will only access inaccesible memory or argument pointees (see Attribute::InaccessibleOrArgMemOnly).</p>

<p>Definition at line 4805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#afc0831ad69241e3cde373281a1024848">inverseLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#af53ef7825e1ab608c8b6cc2ab94e5ddf">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::isKnown</a>, <a href="#a85955f71af20254ae831687849a1a737ae2f2e5630a82d0153e2369b9e8290b6b">NO_ARGUMENT_MEM</a> and <a href="#a85955f71af20254ae831687849a1a737a8540c0ac516fe3b3e9ac52d378537f41">NO_INACCESSIBLE_MEM</a>.</p>

</div>
</div>

### isKnownReadNone() {#a6886f1cf25f5fb9b9271fc963eb44bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::isKnownReadNone ()</td>
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

<p>Return true if we know that the associated functions has no observable accesses.</p>

<p>Definition at line 4758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#af53ef7825e1ab608c8b6cc2ab94e5ddf">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::isKnown</a> and <a href="#a85955f71af20254ae831687849a1a737ad3983885c932078fb829f29d2b7fed01">NO_LOCATIONS</a>.</p>

</div>
</div>

### isKnowStackOnly() {#ab0f5e7b52ec272644d623f90e9bdf2a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::isKnowStackOnly ()</td>
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

<p>Return true if we know that the associated functions has at most local/stack accesses.</p>

<p>Definition at line 4768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#afc0831ad69241e3cde373281a1024848">inverseLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#af53ef7825e1ab608c8b6cc2ab94e5ddf">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::isKnown</a> and <a href="#a85955f71af20254ae831687849a1a737a3cd674c8b8c557b19cea3e0a6c4eb9a4">NO_LOCAL_MEM</a>.</p>

</div>
</div>

### mayAccessArgMem() {#af50764d16f0637e29df3c7966b6cf502}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::mayAccessArgMem ()</td>
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

<p>Return true if the underlying value may access memory through arguement pointers of the associated function, if any.</p>

<p>Definition at line 4820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a38acb9f66b8669c71052db94e468b3a9">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::isAssumed</a> and <a href="#a85955f71af20254ae831687849a1a737ae2f2e5630a82d0153e2369b9e8290b6b">NO_ARGUMENT_MEM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ad7a2ec4e2d42563fd0e6ba6ed2fd4ea4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> * AA)</td>
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

<p>This function should return true if the type of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> is <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation">AAMemoryLocation</a>.</p>

<p>Definition at line 4884 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a57002bf60277fbf32d88bd544be41e0f">ID</a>.</p>

</div>
</div>

### createForPosition() {#a352ad646ccf23e5cf4ad1420330357e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMemoryLocation &amp; llvm::AAMemoryLocation::createForPosition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>Create an abstract attribute view for the position <span class="doxyComputerOutput">IRP</span>.</p>

<p>Definition at line 4868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a660dfbde897cf25a66779982ac229d5f">AAMemoryLocation</a>.</p>

</div>
</div>

### getMemoryLocationsAsStr() {#a37f5c90d6e9853a204b4ca1da2317c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string AAMemoryLocation::getMemoryLocationsAsStr (<a href="#acffe374fb52ac7da0511285fdf18db3f">MemoryLocationsKind</a> MLK)</td>
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

<p>Return the locations encoded by <span class="doxyComputerOutput">MLK</span> as a readable string.</p>


<p>-----------------— <a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> Locations Attributes ------------------------— Includes read-none, argmemonly, inaccessiblememonly,</p>



### inaccessiblememorargmemonly {#autotoc_md122}


<p>Declaration at line 4846 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>, definition at line 8325 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="#a85955f71af20254ae831687849a1a737ae2f2e5630a82d0153e2369b9e8290b6b">NO_ARGUMENT_MEM</a>, <a href="#a85955f71af20254ae831687849a1a737ab78c83bfe8ae55b0ce8b10773f244443">NO_CONST_MEM</a>, <a href="#a85955f71af20254ae831687849a1a737af3f5a89da741bc5d46d9c5c13ae4bd52">NO_GLOBAL_EXTERNAL_MEM</a>, <a href="#a85955f71af20254ae831687849a1a737a5bc229053d97809b7320418384ae49b2">NO_GLOBAL_INTERNAL_MEM</a>, <a href="#a85955f71af20254ae831687849a1a737a8540c0ac516fe3b3e9ac52d378537f41">NO_INACCESSIBLE_MEM</a>, <a href="#a85955f71af20254ae831687849a1a737a3cd674c8b8c557b19cea3e0a6c4eb9a4">NO_LOCAL_MEM</a>, <a href="#a85955f71af20254ae831687849a1a737ad3983885c932078fb829f29d2b7fed01">NO_LOCATIONS</a>, <a href="#a85955f71af20254ae831687849a1a737a5702b1d175e7a1236d500fc64a1207bf">NO_MALLOCED_MEM</a> and <a href="#a85955f71af20254ae831687849a1a737afd32faf24ee03f6bc85e632020569048">NO_UNKOWN_MEM</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ae2c6df05bd2236b9d36680de5e09b78a">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizeAccessedLocations</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a6982073fb3620dd727922e78e140af8f">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizePtrValue</a>, <a href="#aef3103113c35eb930555239792ef2dca">getAsStr</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction/#a4de16ddc7d968804ec058444ee4145fd">anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::updateImpl</a>.</p>

</div>
</div>

### hasTrivialInitializer() {#ae1fc577eaf160d9948ec93967020fa6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::hasTrivialInitializer ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afdcbf0c6bc57e95a2975054b96839b85">AbstractAttribute::hasTrivialInitializer</a>.</p>

<p>Definition at line 4722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### inverseLocation() {#afc0831ad69241e3cde373281a1024848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryLocationsKind llvm::AAMemoryLocation::inverseLocation (<a href="#acffe374fb52ac7da0511285fdf18db3f">MemoryLocationsKind</a> Loc, bool AndLocalMem, bool AndConstMem)</td>
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

<p>Return the inverse of location <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/loc">Loc</a></span>, thus for NO_XXX the return describes ONLY_XXX.</p>


<p>The flags <span class="doxyComputerOutput">AndLocalMem</span> and <span class="doxyComputerOutput">AndConstMem</span> determine if local (=stack) and constant memory are allowed as well. Most of the time we do want them to be included, e.g., argmemonly allows accesses via argument pointers or local or constant memory accesses.</p>


<p>Definition at line 4840 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="#a85955f71af20254ae831687849a1a737ab78c83bfe8ae55b0ce8b10773f244443">NO_CONST_MEM</a>, <a href="#a85955f71af20254ae831687849a1a737a3cd674c8b8c557b19cea3e0a6c4eb9a4">NO_LOCAL_MEM</a> and <a href="#a85955f71af20254ae831687849a1a737ad3983885c932078fb829f29d2b7fed01">NO_LOCATIONS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ae2c6df05bd2236b9d36680de5e09b78a">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizeAccessedLocations</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ad06b99b6c5abffb1da312f75775f2f08">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::getKnownStateFromValue</a>, <a href="#af6e57f7a255f09243d9c303563c08ceb">isAssumedArgMemOnly</a>, <a href="#a876121bc7d9e565f5627b2350d643c64">isAssumedInaccessibleMemOnly</a>, <a href="#aa6830f20bec5f8746595c497d5c3c4ed">isAssumedInaccessibleOrArgMemOnly</a>, <a href="#a1a670ad7c64202fcadc4b495d202ca94">isAssumedStackOnly</a>, <a href="#a4378e42ae258a4054ff58e63f9b01ee0">isKnownArgMemOnly</a>, <a href="#a8cc1dadfdb53fcbf5569c0c981aa5712">isKnownInaccessibleMemOnly</a>, <a href="#a563e350e9c47314a067dc36597f6fd6e">isKnownInaccessibleOrArgMemOnly</a>, <a href="#ab0f5e7b52ec272644d623f90e9bdf2a6">isKnowStackOnly</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction/#a4de16ddc7d968804ec058444ee4145fd">anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::updateImpl</a>.</p>

</div>
</div>

### isValidIRPositionForInit() {#ae548fb21c1de2eb3ad47389ae31488f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::isValidIRPositionForInit (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a0b23d1cedd8202d1b786e1ab43313084">AbstractAttribute::isValidIRPositionForInit</a>.</p>

<p>Definition at line 4725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">llvm::IRPosition::getAssociatedType</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a79c71e9c03aff7ec01197395cab4e521">llvm::IRPosition::isFunctionScope</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#ab03652069eab17006c51f00c261a6a44">llvm::Type::isPtrOrPtrVectorTy</a>.</p>

</div>
</div>

### requiresCalleeForCallBase() {#ab9faf87acb45cf235040ff743d7c8210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryLocation::requiresCalleeForCallBase ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a42f6982d76a1141138c99c4e1b989ba0">AbstractAttribute::requiresCalleeForCallBase</a>.</p>

<p>Definition at line 4719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a57002bf60277fbf32d88bd544be41e0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char AAMemoryLocation::ID = 0</td>
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

<p>Unique ID (due to the unique address)</p>

<p>Definition at line 4889 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#ad7a2ec4e2d42563fd0e6ba6ed2fd4ea4">classof</a>, <a href="#a16c79ab103872bfbfd17fca7ec5b4213">getIdAddr</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a6c7a8371c75641e29a5259c131fd8408">runAttributorLightOnFunctions</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
