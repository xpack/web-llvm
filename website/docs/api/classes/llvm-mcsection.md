---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcsection
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCSection` Class Reference

<p>Instances of this class represent a uniqued identifier for a section in the current translation unit. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCSection { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">llvm/MC/MCSection.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff">MCSectionCOFF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents a section on Windows. <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectiondxcontainer">MCSectionDXContainer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents a section on linux, lots of unix variants and some bare metal systems. <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectiongoff">MCSectionGOFF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho">MCSectionMachO</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents a section on a Mach-O system (used by Mac OS X). <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionspirv">MCSectionSPIRV</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm">MCSectionWasm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents a section on wasm. <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff">MCSectionXCOFF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">SectionVariant { <a href="#afecf7c84b079ea5c169f71b6c06ece98">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">BundleLockStateType { <a href="#ab9c1a8452d93b2ffca2f794f1affd929">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Express the state of bundle locked groups while emitting code. <a href="#ab9c1a8452d93b2ffca2f794f1affd929">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66050b0d714007a303ba65f52adb1e7f">MCSection</a> (const MCSection &amp;)=delete</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2c130ecb0e15e740bfad7eb61eb061e">MCSection</a> (SectionVariant V, StringRef Name, bool IsText, bool IsVirtual, MCSymbol *Begin)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352cfb70ee9de3e1b38106be8cb05a87">~MCSection</a> ()</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f434b885bed2af923f820f59267f79f">operator=</a> (const MCSection &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac4366cca0c8d3cd472a02a71f4aa34c">getName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90366eeb65f96f6d6d6b721551c260df">isText</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afecf7c84b079ea5c169f71b6c06ece98">SectionVariant</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2337a53a051cfed7b9fc29a4eb1e5f1c">getVariant</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac690da7fe3ddf1862812d82c36a02766">getBeginSymbol</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5999859dd9b8d2535023707a1cd54173">getBeginSymbol</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61ee519481ec9d6b36a55212e44a34e6">setBeginSymbol</a> (MCSymbol *Sym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e761f9cd5b9c1a95d3201f171d40d8c">getEndSymbol</a> (MCContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0bf80f50c3a1ef6cb8351dae8824355">hasEnded</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3908d151fa93bdc906cbf57d96060673">getAlign</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a028a2916c58908b43c9866673f0b651c">setAlignment</a> (Align Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa8088b7ca6c8fccd88370bc5be4afa">ensureMinAlignment</a> (Align MinAlignment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Makes sure that Alignment is at least MinAlignment. <a href="#a0fa8088b7ca6c8fccd88370bc5be4afa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04990a85b6279a802df811663e2852f5">getOrdinal</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87c843b7d5be00f8abfc1311db9522df">setOrdinal</a> (unsigned Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab9c1a8452d93b2ffca2f794f1affd929">BundleLockStateType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80089fafced114cea5d67a81cd0e2b7">getBundleLockState</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4929fc1571e15e805f8090b20714f4ea">setBundleLockState</a> (BundleLockStateType NewState)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99765f738be90b59cfc93272ee1c0884">isBundleLocked</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78d839697cc8a8e497d926abd4116e6d">isBundleGroupBeforeFirstInst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c14d9e4108f2949b24c75949aa1b62">setBundleGroupBeforeFirstInst</a> (bool IsFirst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac89ade652e2f41e90d9d3fd963c442">hasInstructions</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60578598b0e71b3e4f6cf19d23e5d797">setHasInstructions</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a210d8f949ccd98375e076ccd141e5b8b">hasLayout</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2bbb8680cf10b86f2d70a4f02f0334e">setHasLayout</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5db3ab7dc50b1dd4b70bf8a9ee4ed00c">isRegistered</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8b62fefed4c00fef144db6c85ab83da">setIsRegistered</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdummyfragment">MCDummyFragment</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a048361d11b0e8b35fe125565f9aa6178">getDummyFragment</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdummyfragment">MCDummyFragment</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da22738591c13fef81152850ca33af7">getDummyFragment</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcsection/fraglist">FragList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac28ea8ba1e28d8b3a3ca7234e1bc1083">curFragList</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcsection/iterator">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add652e7ff42f6239bfb6aeef0e86c6f1">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcsection/iterator">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a967d04b22ca5b64a2d2aa5d46909ec93">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a139e160072c0a4f8626e4ffaf4aa2af7">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8aa733571ca6b64337247f8a0456444">printSwitchToSection</a> (const MCAsmInfo &amp;MAI, const Triple &amp;T, raw_ostream &amp;OS, uint32_t Subsection) const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95b765eaaa37732996b35ff6e60651df">useCodeAlign</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if a .align directive should use "optimized nops" to fill instead of 0s. <a href="#a95b765eaaa37732996b35ff6e60651df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a915b90d97a0e500c99adefff0c22fec3">isVirtualSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this section is "virtual", that is has no actual object file contents. <a href="#a915b90d97a0e500c99adefff0c22fec3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d8df62998b2a92dfd09e3f7ae4483ed">getVirtualSectionKind</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7895f1ab24bfbee4130756567795e8d2">MCAssembler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5da0098da9f4084880f8745ea842e8">MCObjectStreamer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93cf15fffef6e58ff9e85810de335dfe">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afecf7c84b079ea5c169f71b6c06ece98">SectionVariant</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a5eab427913897c7e600925a4216ca0">Variant</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcsection/fraglist">FragList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c9105003f5d347365e43533d5827cc">CurFragList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0a1428e6eee436b5ecc6675c5a39b43">Begin</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfe25363f953bc11cb1f2d6082c60918">End</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e37d38d492612b7e87049e9717199bf">Alignment</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The alignment requirement of this section. <a href="#a9e37d38d492612b7e87049e9717199bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fddb0909a2265a676983d989e62042e">Ordinal</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The section index in the assemblers section list. <a href="#a2fddb0909a2265a676983d989e62042e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab9c1a8452d93b2ffca2f794f1affd929">BundleLockStateType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a64e40fed4390fe5aec2d70ac41201a">BundleLockState</a> = <a href="#ab9c1a8452d93b2ffca2f794f1affd929aba1ac3cb604494515c8af6abdfa08f12">NotBundleLocked</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeping track of bundle-locked state. <a href="#a2a64e40fed4390fe5aec2d70ac41201a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f48e026d8f4096db3613456c1583a93">BundleLockNestingDepth</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current nesting depth of bundle_lock directives. <a href="#a5f48e026d8f4096db3613456c1583a93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf595553ffeb706b9d005415ea2c2fdc">BundleGroupBeforeFirstInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We've seen a bundle_lock directive but not its first instruction yet. <a href="#abf595553ffeb706b9d005415ea2c2fdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a07490768fbe33cdbc16adad59e87f1">HasInstructions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this section has had instructions emitted into it. <a href="#a9a07490768fbe33cdbc16adad59e87f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e6e2f825924e5d99699216b6003be91">HasLayout</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2de6081982184904ccf40ba0f6a0730">IsRegistered</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a522ff7eebc85141e673dc0f6f23ffd28">IsText</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2926445d328ffcf9eac47c12159d4ac">IsVirtual</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdummyfragment">MCDummyFragment</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa75bd3d96fcf7032b29e9869caba8469">DummyFragment</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/structs/llvm/mcsection/fraglist">FragList</a> &gt;, 1 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5b6ba9c43e8e1298174e67367e2579e">Subsections</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57a444303c725373f3a4c2cba82e548c">NonUniqueID</a> = ~0U</td>
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

<p>Instances of this class represent a uniqued identifier for a section in the current translation unit.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> class uniques and creates these.</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### BundleLockStateType {#ab9c1a8452d93b2ffca2f794f1affd929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCSection::BundleLockStateType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Express the state of bundle locked groups while emitting code.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NotBundleLocked<a id="ab9c1a8452d93b2ffca2f794f1affd929aba1ac3cb604494515c8af6abdfa08f12"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BundleLocked<a id="ab9c1a8452d93b2ffca2f794f1affd929a7d78e6ec63c46b48f1abf5a1a6913a80"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BundleLockedAlignToEnd<a id="ab9c1a8452d93b2ffca2f794f1affd929aa7642d8ab47217b582890e161a5bffda"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### SectionVariant {#afecf7c84b079ea5c169f71b6c06ece98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCSection::SectionVariant </td>
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
<td class="doxyEnumItemName">SV_COFF<a id="afecf7c84b079ea5c169f71b6c06ece98abcf1b00b3f8f61318b8837dc27cebb15"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SV_ELF<a id="afecf7c84b079ea5c169f71b6c06ece98a5f6a277923e4b004ff7fed8dd4ad7aee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SV_GOFF<a id="afecf7c84b079ea5c169f71b6c06ece98a3a20c1edca8a41204a274bddc080b1f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SV_MachO<a id="afecf7c84b079ea5c169f71b6c06ece98a55ed9b1dac938f496436528db3576783"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SV_Wasm<a id="afecf7c84b079ea5c169f71b6c06ece98a7c374a7bda5381a1dc719ad365618053"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SV_XCOFF<a id="afecf7c84b079ea5c169f71b6c06ece98a60f91836b77b5497f07e364fb0acbf64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SV_SPIRV<a id="afecf7c84b079ea5c169f71b6c06ece98a99f2c762afd972d01d0b192b5bba690e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SV_DXContainer<a id="afecf7c84b079ea5c169f71b6c06ece98a10d1a462d156ee494cd83a4413c99d30"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCSection() {#a66050b0d714007a303ba65f52adb1e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCSection::MCSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Reference <a href="#ad2c130ecb0e15e740bfad7eb61eb061e">MCSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### MCSection() {#ad2c130ecb0e15e740bfad7eb61eb061e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection::MCSection (<a href="#afecf7c84b079ea5c169f71b6c06ece98">SectionVariant</a> V, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool IsText, bool IsVirtual, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Begin)</td>
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



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsection-cpp">MCSection.cpp</a>.</p>


<p>References <a href="#a93cf15fffef6e58ff9e85810de335dfe">Name</a> and <a href="#a3a5eab427913897c7e600925a4216ca0">Variant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff/#afe6a7467cf74ecf887cfa6960a340dde">llvm::MCSectionCOFF::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a0bd233268f2eabaf43ddf9b80404acc6">llvm::MCSectionELF::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectiongoff/#acf24ff295508c60e81ac7a09c6039211">llvm::MCSectionGOFF::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#ad10116482e7a563e3eed9f06cdafa098">llvm::MCSectionMachO::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm/#a757321a88fef03bfeb03bf365fea6c83">llvm::MCSectionWasm::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff/#a8c48247612d42f94b186a1ace5435430">llvm::MCSectionXCOFF::classof</a>, <a href="#a5999859dd9b8d2535023707a1cd54173">getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a178045e1351d4bc3f42bea0d71e56bce">llvm::MCSectionELF::getLinkedToSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectiongoff/#a0a46562ec719b367ad08c227ce95b3cd">llvm::MCSectionGOFF::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionCOFF::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectiondxcontainer/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionDXContainer::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionELF::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectiongoff/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionGOFF::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionspirv/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionSPIRV::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionWasm::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionXCOFF::MCContext</a>, <a href="#a66050b0d714007a303ba65f52adb1e7f">MCSection</a> and <a href="#a9f434b885bed2af923f820f59267f79f">operator=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~MCSection() {#a352cfb70ee9de3e1b38106be8cb05a87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection::~MCSection ()</td>
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



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>, definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsection-cpp">MCSection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a9f434b885bed2af923f820f59267f79f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSection &amp; llvm::MCSection::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Reference <a href="#ad2c130ecb0e15e740bfad7eb61eb061e">MCSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#add652e7ff42f6239bfb6aeef0e86c6f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MCSection::begin ()</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a6144ace1bbb2a8b3fe310225914ee101">EmitUnwindCode</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#adc76b392eb3df7f2d5456efe795060c3">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::finalizeCGProfile</a> and <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#af452e21aa5eefd6666ed1d0b693f770c">llvm::MachObjectWriter::writeObject</a>.</p>

</div>
</div>

### curFragList() {#ac28ea8ba1e28d8b3a3ca7234e1bc1083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FragList * llvm::MCSection::curFragList ()</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#a8afbb5dfa522ea740721a0b001ba51cb">llvm::MCSectionMachO::allocAtoms</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcmachostreamer-cpp-/mcmachostreamer/#a5b9193e77b26973b0c65a96716330b87">anonymous{MCMachOStreamer.cpp}::MCMachOStreamer::createAddrSigSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a087b12083e027a47db241b0b3fbdce28">llvm::MCAssembler::getSectionAddressSize</a>.</p>

</div>
</div>

### dump() {#a139e160072c0a4f8626e4ffaf4aa2af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void MCSection::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>, definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsection-cpp">MCSection.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="#aac4366cca0c8d3cd472a02a71f4aa34c">getName</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a3a68266def3072d13b2cafb555b9e28c">llvm::MCAssembler::dump</a>.</p>

</div>
</div>

### end() {#a967d04b22ca5b64a2d2aa5d46909ec93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MCSection::end ()</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### ensureMinAlignment() {#a0fa8088b7ca6c8fccd88370bc5be4afa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSection::ensureMinAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> MinAlignment)</td>
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

<p>Makes sure that Alignment is at least MinAlignment.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a296ba2dbfb0e9605f94744804b1612b9">llvm::MCWinCOFFStreamer::emitCOFFSafeSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#ac26c6bea8d31cc52a500469bc470d0b6">llvm::MCWinCOFFStreamer::emitCOFFSymbolIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa07427c984394cc2c4b4cf8b7158def4">llvm::AMDGPUAsmPrinter::emitFunctionBodyEnd</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a8c9b4bc17f742123fb67a743e46e11bc">anonymous{X86AsmBackend.cpp}::X86AsmBackend::emitInstructionEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a21d70037ecf679b5f8d13af07f8f136a">llvm::MCObjectStreamer::emitValueToAlignment</a> and <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a94031e736c9e04044ac7181147a54bf6">llvm::MipsTargetELFStreamer::finish</a>.</p>

</div>
</div>

### getAlign() {#a3908d151fa93bdc906cbf57d96060673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MCSection::getAlign ()</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp/#a9baafe0b9a21c4fea0ca7cc671837a29">addData</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a701e935a2d02fd488218cf26b8eedb67">anonymous{ELFObjectWriter.cpp}::ELFWriter::computeSymbolTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp/#a5d36c914304ad459642fcae234d04021">getAlignment</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-xcoffobjectwriter-cpp-/#a6a17294e96011f1167ca424b5aa247f6">anonymous{XCOFFObjectWriter.cpp}::getEncodedType</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a0536664f5fb6bbdea8b29f944e01c0c7">llvm::MachObjectWriter::getPaddingSize</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#aaf1d0c4d37d55950252509e0b0c84501">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeSectionData</a>.</p>

</div>
</div>

### getBeginSymbol() {#ac690da7fe3ddf1862812d82c36a02766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::MCSection::getBeginSymbol ()</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a3abb9664e1a14148cc2ad7f330009b20">llvm::DwarfCompileUnit::addAddrTableBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab967d1b87b81cc88415cd294bc1d70c4">llvm::DwarfUnit::addRnglistsBase</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a4e4e697039d4692563c2ccc3608864d1">llvm::DwarfCompileUnit::addScopeRangeList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1c1d3ec37aec1008ed52018d257a2608">llvm::DwarfUnit::addStringOffsetsStart</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a780e3087cd40ac6f03e93e1722993cc2">llvm::DwarfCompileUnit::applyStmtList</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a2e5dc7053e3ede207302a8e223953743">llvm::MCContext::createELFRelSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0c77b8d4ff2ea875d1c29128d4ef848">llvm::DwarfUnit::emitCommonHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a6f09a8aebb37ccdb0041ea53a9b6ba88">llvm::MCObjectFileInfo::getBBAddrMapSection</a>, <a href="#a5999859dd9b8d2535023707a1cd54173">getBeginSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a919076c2cfa73586ca99b52ff984ae40">llvm::MCObjectFileInfo::getKCFITrapSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#ab6ce753721421b09ebdefeec3e7e993e">llvm::MCObjectFileInfo::getPCSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a7cec802e187b8b84478ffe1fa783a2dd">llvm::MCObjectFileInfo::getPseudoProbeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a65ff3ae888d49df6baad0fb54f3cb8dc">llvm::MCObjectFileInfo::getStackSizesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#a5bf6adcaa4ad6740a1a7544e827a5231">llvm::DwarfCompileUnit::initStmtList</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr/#a4b8cb2b434353c5d0957495b0582cce6">llvm::MCDwarfLineStr::MCDwarfLineStr</a>, <a href="/web-llvm/docs/api/classes/llvm/elfobjectwriter/#a73aed7794053594cfb9536d55eac30fd">llvm::ELFObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a> and <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a36a4b135a95576724f4b520be6063ef1">llvm::LoongArchAsmBackend::shouldInsertFixupForCodeAlign</a>.</p>

</div>
</div>

### getBeginSymbol() {#a5999859dd9b8d2535023707a1cd54173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol * llvm::MCSection::getBeginSymbol ()</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>References <a href="#ac690da7fe3ddf1862812d82c36a02766">getBeginSymbol</a> and <a href="#ad2c130ecb0e15e740bfad7eb61eb061e">MCSection</a>.</p>

</div>
</div>

### getBundleLockState() {#ac80089fafced114cea5d67a81cd0e2b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BundleLockStateType llvm::MCSection::getBundleLockState ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### getDummyFragment() {#a048361d11b0e8b35fe125565f9aa6178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCDummyFragment &amp; llvm::MCSection::getDummyFragment ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### getDummyFragment() {#a9da22738591c13fef81152850ca33af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDummyFragment &amp; llvm::MCSection::getDummyFragment ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### getEndSymbol() {#a2e761f9cd5b9c1a95d3201f171d40d8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCSection::getEndSymbol (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsection-cpp">MCSection.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa72d5840fe6b92c329861c90b8a7c58c">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLineEndEntry</a>.</p>

</div>
</div>

### getName() {#aac4366cca0c8d3cd472a02a71f4aa34c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSection::getName ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Reference <a href="#a93cf15fffef6e58ff9e85810de335dfe">Name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/wasmobjectwriter-cpp/#a9baafe0b9a21c4fea0ca7cc671837a29">addData</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#ab40656d9663103c44945a8c495157f0c">anonymous{ELFObjectWriter.cpp}::ELFWriter::addToSectionTable</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#af5b3d468d882817a49ac012840023d10">llvm::BTFDebug::beginFunctionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/mctargetdesc/aarch64machobjectwriter-cpp/#a4bdfc7678b89f0959870e072aaf0d036">canUseLocalRelocation</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a01e8d5b5fce0c5c0440880ba3af1e2ca">anonymous{ELFObjectWriter.cpp}::ELFWriter::createRelocationSection</a>, <a href="#a139e160072c0a4f8626e4ffaf4aa2af7">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a92d2d1c2ac97f1151ed8f38d854e8b34">llvm::MCObjectStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#a3ce73ec5824c032df5044c83409259be">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitZerofill</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#aef93e9316e910cbb64002e1cdfad0f01">llvm::MCContext::getAssociativeCOFFSection</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-elfobjectwriter-cpp-/#a740acf4dce2922d79f8d78b15d1387bd">anonymous{ELFObjectWriter.cpp}::isDwoSection</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-wasmobjectwriter-cpp-/#af778cedd323207eed725ac7e6fdf5ce6">anonymous{WasmObjectWriter.cpp}::isDwoSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/wincoffobjectwriter-cpp/#a7ae7754aaf6513bc0ea0bd5f457fe7cc">isDwoSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfodarwin/#ab4ef3ac1427687f11d30de588a790122">llvm::MCAsmInfoDarwin::isSectionAtomizableBySymbols</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff/#a77f123c56608c1beff683d87d40c214f">llvm::MCSectionCOFF::printSwitchToSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a23f075e7a28f48f0f37a416bda54c16a">llvm::MCSectionELF::printSwitchToSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectiongoff/#a43e43dde02f5fd562a4a33fb1fb3ec7f">llvm::MCSectionGOFF::printSwitchToSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#adaebfb20a6b5145fda04f26aa65a47ae">llvm::MCSectionMachO::printSwitchToSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm/#a7dde3ab7501ba49c539fd851003d5e40">llvm::MCSectionWasm::printSwitchToSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff/#ac7bf23262f398f691573404e6d3b6681">llvm::MCSectionXCOFF::printSwitchToSection</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetelfstreamer/#a6b855a9517fc684cfa6a43f414122f59">llvm::XtensaTargetELFStreamer::startLiteralSection</a> and <a href="/web-llvm/docs/api/classes/llvm/wincoffwriter/#a204d14337c246adfd274aac0837c6045">llvm::WinCOFFWriter::writeObject</a>.</p>

</div>
</div>

### getOrdinal() {#a04990a85b6279a802df811663e2852f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSection::getOrdinal ()</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64machobjectwriter-cpp-/aarch64machobjectwriter/#ab0bd2f62658fdbaf0b7206e161932596">anonymous{AArch64MachObjectWriter.cpp}::AArch64MachObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-armmachobjectwriter-cpp-/armmachobjectwriter/#a03347d16edde093da0fc95c0e4a51420">anonymous{ARMMachObjectWriter.cpp}::ARMMachObjectWriter::recordRelocation</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a27e478bd5208561e8eb16ec550509761">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeObject</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#aeaa22f130bcc2796a4d90a2be0e2fe38">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeSectionHeader</a>.</p>

</div>
</div>

### getVariant() {#a2337a53a051cfed7b9fc29a4eb1e5f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionVariant llvm::MCSection::getVariant ()</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Reference <a href="#a3a5eab427913897c7e600925a4216ca0">Variant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff/#afe6a7467cf74ecf887cfa6960a340dde">llvm::MCSectionCOFF::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a0bd233268f2eabaf43ddf9b80404acc6">llvm::MCSectionELF::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectiongoff/#acf24ff295508c60e81ac7a09c6039211">llvm::MCSectionGOFF::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho/#ad10116482e7a563e3eed9f06cdafa098">llvm::MCSectionMachO::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm/#a757321a88fef03bfeb03bf365fea6c83">llvm::MCSectionWasm::classof</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff/#a8c48247612d42f94b186a1ace5435430">llvm::MCSectionXCOFF::classof</a>.</p>

</div>
</div>

### getVirtualSectionKind() {#a0d8df62998b2a92dfd09e3f7ae4483ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef MCSection::getVirtualSectionKind ()</td>
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



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsection-cpp">MCSection.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a92d2d1c2ac97f1151ed8f38d854e8b34">llvm::MCObjectStreamer::emitInstruction</a>.</p>

</div>
</div>

### hasEnded() {#ab0bf80f50c3a1ef6cb8351dae8824355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCSection::hasEnded ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsection-cpp">MCSection.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mcasmstreamer-cpp-/mcasmstreamer/#aa72d5840fe6b92c329861c90b8a7c58c">anonymous{MCAsmStreamer.cpp}::MCAsmStreamer::emitDwarfLineEndEntry</a>.</p>

</div>
</div>

### hasInstructions() {#a5ac89ade652e2f41e90d9d3fd963c442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::hasInstructions ()</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcexpr-cpp/#a3372eaf7daf5cd4032acb451ab70acdc">AttemptToFoldSymbolOffsetDifference</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#acd7f92acd9a62aeb25b9a8b9530f65cb">llvm::MCObjectStreamer::mayHaveInstructions</a>.</p>

</div>
</div>

### hasLayout() {#a210d8f949ccd98375e076ccd141e5b8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::hasLayout ()</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a082b39e969e2a698446f8f8b27ddb411">llvm::MCAssembler::ensureValid</a>.</p>

</div>
</div>

### isBundleGroupBeforeFirstInst() {#a78d839697cc8a8e497d926abd4116e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::isBundleGroupBeforeFirstInst ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a283e6f0c37b443b2002881149730a709">llvm::MCELFStreamer::emitBundleUnlock</a>.</p>

</div>
</div>

### isBundleLocked() {#a99765f738be90b59cfc93272ee1c0884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::isBundleLocked ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Reference <a href="#ab9c1a8452d93b2ffca2f794f1affd929aba1ac3cb604494515c8af6abdfa08f12">NotBundleLocked</a>.</p>

</div>
</div>

### isRegistered() {#a5db3ab7dc50b1dd4b70bf8a9ee4ed00c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::isRegistered ()</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64targetstreamer/#ad8a1ae695b98f49601a5986f612da526">llvm::AArch64TargetStreamer::emitNoteSection</a>.</p>

</div>
</div>

### isText() {#a90366eeb65f96f6d6d6b721551c260df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::isText ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcsectiondxcontainer/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionDXContainer::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectiongoff/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionGOFF::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionWasm::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionXCOFF::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff/#ac7bf23262f398f691573404e6d3b6681">llvm::MCSectionXCOFF::printSwitchToSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff/#ab18d968b4b493d128d2299eff4a6f46e">llvm::MCSectionCOFF::useCodeAlign</a>.</p>

</div>
</div>

### isVirtualSection() {#a915b90d97a0e500c99adefff0c22fec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::isVirtualSection ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether this section is "virtual", that is has no actual object file contents.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a1ea7eb384d0b1f1c6bf101116462320f">llvm::AsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a92d2d1c2ac97f1151ed8f38d854e8b34">llvm::MCObjectStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/machobjectwriter/#a0536664f5fb6bbdea8b29f944e01c0c7">llvm::MachObjectWriter::getPaddingSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ad1f09d354ee1d85dc432472549170b87">llvm::MCAssembler::getSectionFileSize</a> and <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a2a301492f7142fbc3744cc1c5a86f5ec">llvm::MCAssembler::writeSectionData</a>.</p>

</div>
</div>

### printSwitchToSection() {#af8aa733571ca6b64337247f8a0456444}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::MCSection::printSwitchToSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &amp; MAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, uint32_t Subsection)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### setAlignment() {#a028a2916c58908b43c9866673f0b651c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSection::setAlignment (<a href="/web-llvm/docs/api/structs/llvm/align">Align</a> Value)</td>
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



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a701e935a2d02fd488218cf26b8eedb67">anonymous{ELFObjectWriter.cpp}::ELFWriter::computeSymbolTable</a>, <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a01e8d5b5fce0c5c0440880ba3af1e2ca">anonymous{ELFObjectWriter.cpp}::ELFWriter::createRelocationSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a4d9e8e23e14d63569e6f0121aabd33ce">llvm::MipsTargetELFStreamer::emitDirectiveEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#afeed6d8af2306405a117845c04177102">llvm::MipsTargetELFStreamer::emitMipsAbiFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsreginforecord/#aa84b1e01b55d45024625b88ccccd4772">llvm::MipsRegInfoRecord::EmitMipsOptionRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#aeb71b6f90fe6bf50b3ff54cfc7092077">llvm::dwarf_linker::classic::DwarfStreamer::emitSwiftAST</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarfstreamer/#a74e0e8c4a75f7e6b6be6c976a5738a0f">llvm::dwarf_linker::classic::DwarfStreamer::emitSwiftReflectionSection</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af0df6b7695918476493cd9b95a4c1f62">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::SetupMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensatargetelfstreamer/#a6b855a9517fc684cfa6a43f414122f59">llvm::XtensaTargetELFStreamer::startLiteralSection</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a27e478bd5208561e8eb16ec550509761">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeObject</a>.</p>

</div>
</div>

### setBeginSymbol() {#a61ee519481ec9d6b36a55212e44a34e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSection::setBeginSymbol (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>.</p>

</div>
</div>

### setBundleGroupBeforeFirstInst() {#ae0c14d9e4108f2949b24c75949aa1b62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSection::setBundleGroupBeforeFirstInst (bool IsFirst)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a03d5b66fb043f263c71b72ed453af330">llvm::MCELFStreamer::emitBundleLock</a>.</p>

</div>
</div>

### setBundleLockState() {#a4929fc1571e15e805f8090b20714f4ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCSection::setBundleLockState (<a href="#ab9c1a8452d93b2ffca2f794f1affd929">BundleLockStateType</a> NewState)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>, definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsection-cpp">MCSection.cpp</a>.</p>


<p>References <a href="#ab9c1a8452d93b2ffca2f794f1affd929aa7642d8ab47217b582890e161a5bffda">BundleLockedAlignToEnd</a>, <a href="#ab9c1a8452d93b2ffca2f794f1affd929aba1ac3cb604494515c8af6abdfa08f12">NotBundleLocked</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a03d5b66fb043f263c71b72ed453af330">llvm::MCELFStreamer::emitBundleLock</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a283e6f0c37b443b2002881149730a709">llvm::MCELFStreamer::emitBundleUnlock</a>.</p>

</div>
</div>

### setHasInstructions() {#a60578598b0e71b3e4f6cf19d23e5d797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSection::setHasInstructions (bool Value)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### setHasLayout() {#ad2bbb8680cf10b86f2d70a4f02f0334e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSection::setHasLayout (bool Value)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a082b39e969e2a698446f8f8b27ddb411">llvm::MCAssembler::ensureValid</a> and <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a4172c40c16e915c478ab94311e76e1a8">llvm::MCAssembler::layout</a>.</p>

</div>
</div>

### setIsRegistered() {#ae8b62fefed4c00fef144db6c85ab83da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSection::setIsRegistered (bool Value)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### setOrdinal() {#a87c843b7d5be00f8abfc1311db9522df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCSection::setOrdinal (unsigned Value)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a4172c40c16e915c478ab94311e76e1a8">llvm::MCAssembler::layout</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a27e478bd5208561e8eb16ec550509761">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeObject</a>.</p>

</div>
</div>

### useCodeAlign() {#a95b765eaaa37732996b35ff6e60651df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::MCSection::useCodeAlign ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if a .align directive should use "optimized nops" to fill instead of 0s.</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#abc4d6b7d638e45034130bc3ab18e5be6">llvm::MCAssembler::computeFragmentSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MCAssembler {#a7895f1ab24bfbee4130756567795e8d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::MCSection::MCAssembler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### MCObjectStreamer {#a0f5da0098da9f4084880f8745ea842e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::MCSection::MCObjectStreamer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Name {#a93cf15fffef6e58ff9e85810de335dfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCSection::Name</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="#aac4366cca0c8d3cd472a02a71f4aa34c">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff/#a23fd58fa9c15dc65e47a85577318e3d1">llvm::MCSectionCOFF::isImplicitlyDiscardable</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionCOFF::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectiondxcontainer/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionDXContainer::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionELF::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectiongoff/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionGOFF::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionWasm::MCContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff/#a7862d2f746209c16291d7139dab55e00">llvm::MCSectionXCOFF::MCContext</a>, <a href="#ad2c130ecb0e15e740bfad7eb61eb061e">MCSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff/#a430ef91751373b5487c314b46ec144c1">llvm::MCSectionCOFF::shouldOmitSectionDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#a9e5a8a215bc7442846547c057b29842d">llvm::MCSectionELF::shouldOmitSectionDirective</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm/#a762403a6aa5b0c887129edbb4a008807">llvm::MCSectionWasm::shouldOmitSectionDirective</a>.</p>

</div>
</div>

### Variant {#a3a5eab427913897c7e600925a4216ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionVariant llvm::MCSection::Variant</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="#a2337a53a051cfed7b9fc29a4eb1e5f1c">getVariant</a> and <a href="#ad2c130ecb0e15e740bfad7eb61eb061e">MCSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Alignment {#a9e37d38d492612b7e87049e9717199bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::MCSection::Alignment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The alignment requirement of this section.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### Begin {#aa0a1428e6eee436b5ecc6675c5a39b43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MCSection::Begin</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### BundleGroupBeforeFirstInst {#abf595553ffeb706b9d005415ea2c2fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::BundleGroupBeforeFirstInst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We've seen a bundle_lock directive but not its first instruction yet.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### BundleLockNestingDepth {#a5f48e026d8f4096db3613456c1583a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSection::BundleLockNestingDepth = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current nesting depth of bundle_lock directives.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### BundleLockState {#a2a64e40fed4390fe5aec2d70ac41201a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BundleLockStateType llvm::MCSection::BundleLockState = <a href="#ab9c1a8452d93b2ffca2f794f1affd929aba1ac3cb604494515c8af6abdfa08f12">NotBundleLocked</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeping track of bundle-locked state.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### CurFragList {#a55c9105003f5d347365e43533d5827cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FragList* llvm::MCSection::CurFragList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### DummyFragment {#aa75bd3d96fcf7032b29e9869caba8469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDummyFragment llvm::MCSection::DummyFragment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### End {#abfe25363f953bc11cb1f2d6082c60918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MCSection::End = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### HasInstructions {#a9a07490768fbe33cdbc16adad59e87f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::HasInstructions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether this section has had instructions emitted into it.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### HasLayout {#a1e6e2f825924e5d99699216b6003be91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::HasLayout</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### IsRegistered {#aa2de6081982184904ccf40ba0f6a0730}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::IsRegistered</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### IsText {#a522ff7eebc85141e673dc0f6f23ffd28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::IsText</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### IsVirtual {#ad2926445d328ffcf9eac47c12159d4ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCSection::IsVirtual</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### Ordinal {#a2fddb0909a2265a676983d989e62042e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSection::Ordinal = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The section index in the assemblers section list.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

### Subsections {#ac5b6ba9c43e8e1298174e67367e2579e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;unsigned, FragList&gt;, 1&gt; llvm::MCSection::Subsections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### NonUniqueID {#a57a444303c725373f3a4c2cba82e548c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCSection::NonUniqueID = ~0U</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mccontext/#adf2235eabe74d3b9ee0314b91b71ee06">llvm::MCContext::createELFGroupSection</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a757f4848f0df934624e443324559371f">llvm::AsmPrinter::emitPatchableFunctionEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a25e51557ff442df4d50f2ad5d1f55743">llvm::AsmPrinter::emitXRayTable</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a3fb2ccf37b0ca8de3cbecdd5d84918e0">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a84ea0567e15790f68c421dada011ec5f">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a3ee35c67e483d503d4f72dc5e0e4b368">llvm::MCContext::getELFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#ac8b6405ee0ca88cdcd7aea5d129551c4">llvm::TargetLoweringObjectFileELF::getSectionForLSDA</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf/#aaf9d85a7591f8b80f0f5e00470504d5c">llvm::MCSectionELF::isUnique</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcsection-h">MCSection.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcsection-cpp">MCSection.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
