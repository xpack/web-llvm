---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armbasetargetmachine
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMBaseTargetMachine` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ARMBaseTargetMachine { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">Target/ARM/ARMTargetMachine.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl">CodeGenTargetMachineImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>implements a set of functionality in the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a></span> class for targets that make use of the independent code generator (CodeGen) library. <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armbetargetmachine">ARMBETargetMachine</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ARM/Thumb big endian target machine. <a href="/web-llvm/docs/api/classes/llvm/armbetargetmachine/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/armletargetmachine">ARMLETargetMachine</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ARM/Thumb little endian target machine. <a href="/web-llvm/docs/api/classes/llvm/armletargetmachine/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ARMABI { <a href="#a35fea9990d0205966c516f00e0f84102">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af24525644c0d188c873f506b53891787">ARMBaseTargetMachine</a> (const Target &amp;T, const Triple &amp;TT, StringRef CPU, StringRef FS, const TargetOptions &amp;Options, std::optional&lt; Reloc::Model &gt; RM, std::optional&lt; CodeModel::Model &gt; CM, CodeGenOptLevel OL, bool isLittle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> architecture model. <a href="#af24525644c0d188c873f506b53891787">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101381058d70663182a44ea9929eb57b">~ARMBaseTargetMachine</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3a94bd62230f4b9f99b54976663dfe8">getSubtargetImpl</a> (const Function &amp;F) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virtual method implemented by subclasses that returns a reference to that target's TargetSubtargetInfo-derived member variable. <a href="#af3a94bd62230f4b9f99b54976663dfe8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2ae57f880aa42e33c359e42d48e9622">getSubtargetImpl</a> () const =delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7435f5d8965d94ec299c39cd7ccd7aa">isLittleEndian</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac59e426043e1d4b7adfae6e64d3001">getTargetTransformInfo</a> (const Function &amp;F) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> for a given function. <a href="#aeac59e426043e1d4b7adfae6e64d3001">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0eaf325fa3eaea93af8e7b7965ea828">createPassConfig</a> (PassManagerBase &amp;PM) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a pass configuration object to be used by addPassToEmitX methods for generating a pipeline of CodeGen passes. <a href="#ad0eaf325fa3eaea93af8e7b7965ea828">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile">TargetLoweringObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a038432b09540b0f3f11b59a79fcc4a28">getObjFileLowering</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30cb863799efd80f6d23e2ac3612cf2b">isTargetHardFloat</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfab7e447bc6f3e58213d9b7bc11bed4">targetSchedulesPostRAScheduling</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if subtarget inserts the final scheduling pass on its own. <a href="#abfab7e447bc6f3e58213d9b7bc11bed4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d4778b4a0caf7a3bc7f0f4954e11128">createMachineFunctionInfo</a> (BumpPtrAllocator &amp;Allocator, const Function &amp;F, const TargetSubtargetInfo *STI) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the target's instance of <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#a8d4778b4a0caf7a3bc7f0f4954e11128">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6b189b335ac856a08639569a80755b9">isNoopAddrSpaceCast</a> (unsigned SrcAS, unsigned DestAS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if a cast between SrcAS and DestAS is a noop. <a href="#ab6b189b335ac856a08639569a80755b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">yaml::MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe346cc884bc794bf4f774dca6f62119">createDefaultFuncInfoYAML</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate and return a default initialized instance of the YAML representation for the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#abe346cc884bc794bf4f774dca6f62119">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">yaml::MachineFunctionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7eeb14b0131462772a0cdba2564b799">convertFuncInfoToYAML</a> (const MachineFunction &amp;MF) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocate and initialize an instance of the YAML representation of the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>. <a href="#af7eeb14b0131462772a0cdba2564b799">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1589249b2983702336aeaa27b46a7bdf">parseMachineFunctionInfo</a> (const yaml::MachineFunctionInfo &amp;, PerFunctionMIParsingState &amp;PFS, SMDiagnostic &amp;Error, SMRange &amp;SourceRange) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse out the target's <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> from the YAML reprsentation. <a href="#a1589249b2983702336aeaa27b46a7bdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc2c3995cb257e3dc20655ff7c779c3">reset</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset internal state. <a href="#a7dc2c3995cb257e3dc20655ff7c779c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#a35fea9990d0205966c516f00e0f84102">llvm::ARMBaseTargetMachine::ARMABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a630c8cc8b38c870a14916c6986bf85eb">TargetABI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile">TargetLoweringObjectFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47b4e073badc19507801a5303ba813fb">TLOF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab17fbe897c73870bf3b87b2bba090b00">isLittle</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/armsubtarget">ARMSubtarget</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad98aea557653e4bb568ca739fbeef724">SubtargetMap</a></td>
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


<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ARMABI {#a35fea9990d0205966c516f00e0f84102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMBaseTargetMachine::ARMABI </td>
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
<td class="doxyEnumItemName">ARM_ABI_UNKNOWN<a id="a35fea9990d0205966c516f00e0f84102a5db5a8ac18cb47ad6f78ed8b3694b462"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARM_ABI_APCS<a id="a35fea9990d0205966c516f00e0f84102a7424602c00cf8320e081c29111bdeef7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARM_ABI_AAPCS<a id="a35fea9990d0205966c516f00e0f84102a686afcd1d06fbc117abe52c54c5a3798"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARM_ABI_AAPCS16<a id="a35fea9990d0205966c516f00e0f84102af871cdc1efbb58999dd6b201aeb9f28a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ARMBaseTargetMachine() {#af24525644c0d188c873f506b53891787}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMBaseTargetMachine::ARMBaseTargetMachine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp; Options, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; RM, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt; CM, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OL, bool isLittle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an <a href="/web-llvm/docs/api/namespaces/llvm/arm">ARM</a> architecture model.</p>

<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a4480a9aa1ec7c3115acc998e187f5ab3">llvm::CodeGenTargetMachineImpl::CodeGenTargetMachineImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#a003a58caf135efbf7273c5ed84e700d7">computeDataLayout</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp/#a725fe8674a09b1579039321d641118e4">computeTargetABI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetmachine-cpp/#af3bdb2a4dc7856d907dd29807c6545e2">createTLOF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada924e855250645672a493841803ff91a7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/floatabi/#aea077c52d84934aabf9445cef9eab2e2ae41bda228a5aa7298dc5ac9cff9414f2">llvm::FloatABI::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6849e9de7afb5b350a241595d9ed1911">llvm::getEffectiveCodeModel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a63737748f52c9cdcd469b63a01cc454a">llvm::getEffectiveRelocModel</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a33fe94054a904130a7c774f78423c8b7">llvm::TargetMachine::getTargetTriple</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>, <a href="/web-llvm/docs/api/classes/llvm/codegentargetmachineimpl/#a85849733e753fbf08f1c487b153c754b">llvm::CodeGenTargetMachineImpl::initAsmInfo</a>, <a href="#ab17fbe897c73870bf3b87b2bba090b00">isLittle</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#ab1fb67187fc37e569cc5171cbebba873">llvm::TargetMachine::Options</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a588867fa922c392886b07e0ad42038b4">llvm::TargetMachine::RM</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a35061955fa2e0fbba033286ae5ac1e56">llvm::TargetMachine::setMachineOutliner</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a044ef65e7e12002d61ddbc98bc7e37ea">llvm::TargetMachine::setSupportsDebugEntryValues</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a6fadf68fc47b2f0e3a8dd55de3ec93c4">llvm::TargetMachine::setSupportsDefaultOutlining</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a630c8cc8b38c870a14916c6986bf85eb">TargetABI</a>, <a href="#a47b4e073badc19507801a5303ba813fb">TLOF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ada924e855250645672a493841803ff91a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armbetargetmachine/#a4cabb24f403986723ab44d67f52f7268">llvm::ARMBETargetMachine::ARMBETargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armletargetmachine/#ae82a61b1e94127c575e157c9a0ee9e6e">llvm::ARMLETargetMachine::ARMLETargetMachine</a> and <a href="#ad0eaf325fa3eaea93af8e7b7965ea828">createPassConfig</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ARMBaseTargetMachine() {#a101381058d70663182a44ea9929eb57b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMBaseTargetMachine::~ARMBaseTargetMachine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### convertFuncInfoToYAML() {#af7eeb14b0131462772a0cdba2564b799}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::MachineFunctionInfo * ARMBaseTargetMachine::convertFuncInfoToYAML (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Allocate and initialize an instance of the YAML representation of the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>.</p>

<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>, definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a>.</p>

</div>
</div>

### createDefaultFuncInfoYAML() {#abe346cc884bc794bf4f774dca6f62119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::MachineFunctionInfo * ARMBaseTargetMachine::createDefaultFuncInfoYAML ()</td>
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

<p>Allocate and return a default initialized instance of the YAML representation for the <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>.</p>

<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>, definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>

</div>
</div>

### createMachineFunctionInfo() {#a8d4778b4a0caf7a3bc7f0f4954e11128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionInfo * ARMBaseTargetMachine::createMachineFunctionInfo (<a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; Allocator, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * STI)</td>
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

<p>Create the target's instance of <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a>.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo/#a06ad8b2e5a8e3c0f81f05c7870fb3b23">llvm::MachineFunctionInfo::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#aaebd1c0e5f028848cc0e548bf015aaf1">llvm::TargetMachine::STI</a>.</p>

</div>
</div>

### createPassConfig() {#ad0eaf325fa3eaea93af8e7b7965ea828}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arm execution domain ARM Execution Domain false TargetPassConfig * ARMBaseTargetMachine::createPassConfig (<a href="/web-llvm/docs/api/classes/llvm/legacy/passmanagerbase">PassManagerBase</a> &amp; PM)</td>
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

<p>Create a pass configuration object to be used by addPassToEmitX methods for generating a pipeline of CodeGen passes.</p>


<p>createPassConfig - Create a pass configuration object to be used by addPassToEmitX methods for generating a pipeline of CodeGen passes.</p>


<p>Targets may override this to extend <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a>.</p>


<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>, definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>References <a href="#af24525644c0d188c873f506b53891787">ARMBaseTargetMachine</a> and <a href="#ad0eaf325fa3eaea93af8e7b7965ea828">createPassConfig</a>.</p>


<p>Referenced by <a href="#ad0eaf325fa3eaea93af8e7b7965ea828">createPassConfig</a>.</p>

</div>
</div>

### getObjFileLowering() {#a038432b09540b0f3f11b59a79fcc4a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetLoweringObjectFile * llvm::ARMBaseTargetMachine::getObjFileLowering ()</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>


<p>Reference <a href="#a47b4e073badc19507801a5303ba813fb">TLOF</a>.</p>

</div>
</div>

### getSubtargetImpl() {#af3a94bd62230f4b9f99b54976663dfe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMSubtarget * ARMBaseTargetMachine::getSubtargetImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)</td>
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

<p>Virtual method implemented by subclasses that returns a reference to that target's TargetSubtargetInfo-derived member variable.</p>

<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="#ab17fbe897c73870bf3b87b2bba090b00">isLittle</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#af0a50afebb9bed07d36be2bac4c6f729">llvm::TargetMachine::resetTargetOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="#ad98aea557653e4bb568ca739fbeef724">SubtargetMap</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a9ca45577ddb8efe4904398939fae28d1">llvm::TargetMachine::TargetCPU</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a795cc09ce82b6ef057e5400a5cee7d68">llvm::TargetMachine::TargetFS</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a05856d96e88224279af8b29edfd1c9ad">llvm::TargetMachine::TargetTriple</a>.</p>

</div>
</div>

### getSubtargetImpl() {#ad2ae57f880aa42e33c359e42d48e9622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ARMSubtarget * llvm::ARMBaseTargetMachine::getSubtargetImpl ()</td>
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



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>

</div>
</div>

### getTargetTransformInfo() {#aeac59e426043e1d4b7adfae6e64d3001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetTransformInfo ARMBaseTargetMachine::getTargetTransformInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Return a <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> for a given function.</p>


<p>The returned <a href="/web-llvm/docs/api/classes/llvm/targettransforminfo">TargetTransformInfo</a> is specialized to the subtarget corresponding to <span class="doxyComputerOutput">F</span>.</p>


<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### isLittleEndian() {#ae7435f5d8965d94ec299c39cd7ccd7aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMBaseTargetMachine::isLittleEndian ()</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>


<p>Reference <a href="#ab17fbe897c73870bf3b87b2bba090b00">isLittle</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armasmprinter/#a6cff8e6e40904c8170d57f5307f73c20">llvm::ARMAsmPrinter::PrintAsmOperand</a>.</p>

</div>
</div>

### isNoopAddrSpaceCast() {#ab6b189b335ac856a08639569a80755b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMBaseTargetMachine::isNoopAddrSpaceCast (unsigned SrcAS, unsigned DestAS)</td>
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

<p>Returns true if a cast between SrcAS and DestAS is a noop.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>

</div>
</div>

### isTargetHardFloat() {#a30cb863799efd80f6d23e2ac3612cf2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMBaseTargetMachine::isTargetHardFloat ()</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>


<p>References <a href="#a35fea9990d0205966c516f00e0f84102af871cdc1efbb58999dd6b201aeb9f28a">ARM_ABI_AAPCS16</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a9ffca842bbaefcf99484f59a83b618d4ab8efff655ba87c9dfdd350b51a3d4345">llvm::Triple::ARMSubArch_v7em</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324af2b02c10c51141fdaa4cb49402e20169">llvm::Triple::EABIHF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a699fcd7db202863a2a82143681dadb85">llvm::Triple::GNUEABIHF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ae5c77cfc976654fac7f3f50ee1352a8e">llvm::Triple::GNUEABIHFT64</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324ab711c5b8f1cd078c75864af125d07fef">llvm::Triple::MuslEABIHF</a>, <a href="#a630c8cc8b38c870a14916c6986bf85eb">TargetABI</a> and <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a05856d96e88224279af8b29edfd1c9ad">llvm::TargetMachine::TargetTriple</a>.</p>

</div>
</div>

### parseMachineFunctionInfo() {#a1589249b2983702336aeaa27b46a7bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ARMBaseTargetMachine::parseMachineFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">yaml::MachineFunctionInfo</a> &amp;, <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate">PerFunctionMIParsingState</a> &amp; PFS, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Error, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> &amp; SourceRange)</td>
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

<p>Parse out the target's <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">MachineFunctionInfo</a> from the YAML reprsentation.</p>

<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>, definition at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ab7feae1932b436c8630e247166ec42b7">llvm::MachineFunction::getInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/perfunctionmiparsingstate/#ae7f8c6f160583712d2adaafb4cca24fe">llvm::PerFunctionMIParsingState::MF</a>.</p>

</div>
</div>

### targetSchedulesPostRAScheduling() {#abfab7e447bc6f3e58213d9b7bc11bed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMBaseTargetMachine::targetSchedulesPostRAScheduling ()</td>
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

<p>True if subtarget inserts the final scheduling pass on its own.</p>


<p>Branch relaxation, which must happen after block placement, can on some targets (e.g. <a href="/web-llvm/docs/api/namespaces/llvm/systemz">SystemZ</a>) expose additional post-RA scheduling opportunities.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### reset() {#a7dc2c3995cb257e3dc20655ff7c779c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMBaseTargetMachine::reset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset internal state.</p>

<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>, definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a>.</p>


<p>Reference <a href="#ad98aea557653e4bb568ca739fbeef724">SubtargetMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### TargetABI {#a630c8cc8b38c870a14916c6986bf85eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::ARMBaseTargetMachine::ARMABI llvm::ARMBaseTargetMachine::TargetABI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>


<p>Referenced by <a href="#af24525644c0d188c873f506b53891787">ARMBaseTargetMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/armelftargetobjectfile/#ad60d0495301b78e11523def2cb8b2b59">llvm::ARMElfTargetObjectFile::Initialize</a> and <a href="#a30cb863799efd80f6d23e2ac3612cf2b">isTargetHardFloat</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### isLittle {#ab17fbe897c73870bf3b87b2bba090b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ARMBaseTargetMachine::isLittle</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>


<p>Referenced by <a href="#af24525644c0d188c873f506b53891787">ARMBaseTargetMachine</a>, <a href="#af3a94bd62230f4b9f99b54976663dfe8">getSubtargetImpl</a> and <a href="#ae7435f5d8965d94ec299c39cd7ccd7aa">isLittleEndian</a>.</p>

</div>
</div>

### SubtargetMap {#ad98aea557653e4bb568ca739fbeef724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;std::unique_ptr&lt;ARMSubtarget&gt; &gt; llvm::ARMBaseTargetMachine::SubtargetMap</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>


<p>Referenced by <a href="#af3a94bd62230f4b9f99b54976663dfe8">getSubtargetImpl</a> and <a href="#a7dc2c3995cb257e3dc20655ff7c779c3">reset</a>.</p>

</div>
</div>

### TLOF {#a47b4e073badc19507801a5303ba813fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TargetLoweringObjectFile&gt; llvm::ARMBaseTargetMachine::TLOF</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a>.</p>


<p>Referenced by <a href="#af24525644c0d188c873f506b53891787">ARMBaseTargetMachine</a> and <a href="#a038432b09540b0f3f11b59a79fcc4a28">getObjFileLowering</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-cpp">ARMTargetMachine.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargetmachine-h">ARMTargetMachine.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
