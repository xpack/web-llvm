---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mccontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCContext` Class Reference

<p>Context object for machine code objects. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">llvm/MC/MCContext.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa446787f1602d571ba5543a5295fe7c1">SymbolTable</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcsymboltablevalue">MCSymbolTableValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e9f52b1aa04f522af6653ff65b1d888">DiagHandlerTy</a> = std::function&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp;, bool, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp;, std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Environment { <a href="#af13dae4c64d48ea988d060a767605890">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c75c94fa169456ebdef2337504928e6">MCContext</a> (const Triple &amp;TheTriple, const MCAsmInfo *MAI, const MCRegisterInfo *MRI, const MCSubtargetInfo *MSTI, const SourceMgr *Mgr=nullptr, MCTargetOptions const *TargetOpts=nullptr, bool DoAutoReset=true, StringRef Swift5ReflSegmentName={})</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29706a277659ceb9d10a7891eaa49c86">MCContext</a> (const MCContext &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75b7ed17686752b3420b0ad6ffb6c726">~MCContext</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd9326a55f25cd9effc0b0f350ef59b5">operator=</a> (const MCContext &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af13dae4c64d48ea988d060a767605890">Environment</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1357b82842249c1488257e19ee78f2b2">getObjectFileType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a546be23da489afe72406d18d974f15f4">getSwift5ReflectionSegmentName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afff5b8282b36f6a0ed50aeafe462250d">getTargetTriple</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0238c5455430b5bef943138b198e522">getSourceManager</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f78358076dadb56305f7a236c5e3d8">initInlineSourceManager</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1abe656f2fed82507750b6173c36952">getInlineSourceManager</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af868e37f8586a148a5f224743078a5ee">getLocInfos</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68fb1a489deef96ac4b0d93d629e2ce1">setDiagnosticHandler</a> (DiagHandlerTy DiagHandler)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a139a14c94184b5c989786a1666037955">setObjectFileInfo</a> (const MCObjectFileInfo *Mofi)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3beac794c4afb5b1fb6d06cb7786587">getAsmInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eff7fcbe27aa063e7dced4042ca3416">getRegisterInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01d6d82d18a5da901c50a546932c4264">getObjectFileInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbcf25f6a20ef3f5197a782bf7e55d55">getSubtargetInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad270e6f1bba829cef8708bba5faeeb8a">getTargetOptions</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeviewcontext">CodeViewContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bdf9164b69f96821c0c0269dde3ebf7">getCVContext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf651d1717dcdbe43fe8ce45a32b8eac">setUseNamesOnTempLabels</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee07502ffb216b231a76356816de4f26">getSecureLogFile</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c3b692c1ce37d522ad721fc60f44ac">getSecureLog</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa872583a92136483ec5699b862e6974e">setSecureLog</a> (std::unique_ptr&lt; raw_fd_ostream &gt; Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a636712256c661bec6ad7b981476a2f7d">getSecureLogUsed</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f67b8685a1404b9ba5898447ee8fe6c">setSecureLogUsed</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d676337d17f32eb1e8ff4ab2b4e7f93">allocate</a> (unsigned Size, unsigned Align=8)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10a32ed0247891267c067a42fb9cff87">deallocate</a> (void *Ptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a598983d169adb6ccd6307753bf2021b7">allocateString</a> (StringRef s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocates a copy of the given string on the allocator managed by this context and returns the result. <a href="#a598983d169adb6ccd6307753bf2021b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16be3cf71194a82a5cf1d124ebbdc433">hadError</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a498f34a9cf9f29168a1ac92143e3cd96">diagnose</a> (const SMDiagnostic &amp;SMD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3107671801e6bb16ef896f382759cd">reportError</a> (SMLoc L, const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99057f5cbc5ee5f973d463d4c30abe7d">reportWarning</a> (SMLoc L, const Twine &amp;Msg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e05d443eeaa7af08eacb9179ae573f9">lookupMacro</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fb29f3e5885dbb7ea6c53b8be5e7179">defineMacro</a> (StringRef Name, MCAsmMacro Macro)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a783a17d8f062723eacbb184f536898ae">undefineMacro</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobetable">MCPseudoProbeTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01cf35ff8a291a79d6970f1e1e35a272">getMCPseudoProbeTable</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6384dbaf99c5ce5bb0983222acb1750e">NextInstance</a> (unsigned LocalLabelVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NextInstance() creates the next instance of the directional local label for the LocalLabelVal and adds it to the map if needed. <a href="#a6384dbaf99c5ce5bb0983222acb1750e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ceef29d40d663002f912b4ab0ec7c5">GetInstance</a> (unsigned LocalLabelVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetInstance() gets the current instance of the directional local label for the LocalLabelVal and adds it to the map if needed. <a href="#a53ceef29d40d663002f912b4ab0ec7c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ca741597356333a68f752e675d713f7">reportCommon</a> (SMLoc Loc, std::function&lt; void(SMDiagnostic &amp;, const SourceMgr *)&gt;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdatafragment">MCDataFragment</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4319fd8f91cf933aa6c289054887f7b7">allocInitialFragment</a> (MCSection &amp;Sec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36c4d873ae691b877ffb6a5893ba0c4b">getSymbolTableEntry</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebd8789f27ba19f128cfec03f102c2ab">createSymbolImpl</a> (const MCSymbolTableEntry *Name, bool IsTemporary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a523aa0f26cb925aeca838c48705c1013">createRenamableSymbol</a> (const Twine &amp;Name, bool AlwaysAddSuffix, bool IsTemporary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c61935b3730e67c3ddcc30be70adba">getOrCreateDirectionalLocalSymbol</a> (unsigned LocalLabelVal, unsigned Instance)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Symbol&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">Symbol *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a165f584cb1a4409c46783117c44b9dec">getOrCreateSectionSymbol</a> (StringRef Section)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad494942b9bf8df80430d48231bf9d70e">createELFSectionImpl</a> (StringRef Section, unsigned Type, unsigned Flags, unsigned EntrySize, const MCSymbolELF *Group, bool IsComdat, unsigned UniqueID, const MCSymbolELF *LinkedToSym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff">MCSymbolXCOFF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af807cd9fcd2a4713760e9b303f1502ae">createXCOFFSymbolImpl</a> (const MCSymbolTableEntry *Name, bool IsTemporary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af13dae4c64d48ea988d060a767605890">Environment</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cee20f137e51d70889330f78bef593f">Env</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c464ed6da56954cc0fe67758841ee56">Swift5ReflectionSegmentName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The name of the Segment where Swift5 Reflection Section data will be outputted. <a href="#a6c464ed6da56954cc0fe67758841ee56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab593b067786e5d4b65500e0b1b2c23ae">TT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The triple for this object. <a href="#ab593b067786e5d4b65500e0b1b2c23ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a686f12dafe63bd82ac22966b5ee84f0c">SrcMgr</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> for this object, if any. <a href="#a686f12dafe63bd82ac22966b5ee84f0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb8072a8b87089c7676d64cc9882aed">InlineSrcMgr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> for inline assembly, if any. <a href="#a2cb8072a8b87089c7676d64cc9882aed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1586249aafa5a65e9a2ed0c0e6475b0">LocInfos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9e9f52b1aa04f522af6653ff65b1d888">DiagHandlerTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8eef406063289c55a9133be39e008ed8">DiagHandler</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7d5f0cd4a3f3b0d69e4d5fd69d02b51">MAI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> for this target. <a href="#ae7d5f0cd4a3f3b0d69e4d5fd69d02b51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47962f3c52b02d1d5863a41e16511fc7">MRI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> for this target. <a href="#a47962f3c52b02d1d5863a41e16511fc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca01892cfc3ef7303890c6bad2d5f81">MOFI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> for this target. <a href="#a4ca01892cfc3ef7303890c6bad2d5f81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57f7a9f5d61d1bde9a49ac168fef57bd">MSTI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> for this target. <a href="#a57f7a9f5d61d1bde9a49ac168fef57bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext">CodeViewContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a117ed7fd50dfbb32869c638838f4164e">CVContext</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef65cccaef6ec02c16ae00719258b7c">Allocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocator object used for creating machine code objects. <a href="#a4ef65cccaef6ec02c16ae00719258b7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5549d6874c9b72daceb959241a886dd5">FragmentAllocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> instances. <a href="#a5549d6874c9b72daceb959241a886dd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff">MCSectionCOFF</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0fb37eb03f31746ccf00a287acf4a94">COFFAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectiondxcontainer">MCSectionDXContainer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c85df6270ae48be94df3dd081727ddb">DXCAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bd64eb2f8f3207bf5c93b6500729bc0">ELFAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho">MCSectionMachO</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a09e4af5f9ad2ae849e026c8e4741a1">MachOAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectiongoff">MCSectionGOFF</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64bfce45bbe2aa79edd9e99803816ec6">GOFFAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectionspirv">MCSectionSPIRV</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1583bcc9441392c28eba4dd53685442">SPIRVAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm">MCSectionWasm</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c03efeca91236bbf231040635140285">WasmAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff">MCSectionXCOFF</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ad4abda75e1683b2d3adaeba3a9892">XCOFFAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfcbd3a1813581fc143f4c444387021d">MCInstAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature">wasm::WasmSignature</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae51525ab840d0eef02cb81e0539dcb5a">WasmSignatureAllocator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa446787f1602d571ba5543a5295fe7c1">SymbolTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea769589411147fd0d5c755d21b9dbc1">Symbols</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bindings of names to symbol table values. <a href="#aea769589411147fd0d5c755d21b9dbc1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; unsigned, unsigned &gt;, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cfabfb41bb4bdda311adec5afeecf9e">LocalSymbols</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mapping from a local label number and an instance count to a symbol. <a href="#a9cfabfb41bb4bdda311adec5afeecf9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc50af4d182f7ee401ade09beab82c35">InlineAsmUsedLabelNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps track of labels that are used in inline assembly. <a href="#acc50af4d182f7ee401ade09beab82c35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/mclabel">MCLabel</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a01a4116846290a5a44d64ca65b628">Instances</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Instances of directional local labels. <a href="#a75a01a4116846290a5a44d64ca65b628">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a560a0a1efc0c244b9d2473d52b4dc253">BBAddrMapVersion</a> = 2</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM_BB_ADDR_MAP version to emit. <a href="#a560a0a1efc0c244b9d2473d52b4dc253">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf885909270b643032f372e1d2291f99">SecureLogFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The file name of the log file from the environment variable AS_SECURE_LOG_FILE. <a href="#aaf885909270b643032f372e1d2291f99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39380cb9306a7c54dadd2476f762e15c">SecureLog</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The stream that gets written to for the .secure_log_unique directive. <a href="#a39380cb9306a7c54dadd2476f762e15c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeff0ee85b13469673dfa70aa060ce364">SecureLogUsed</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/#a965a7b0afb2678973d155a103b9f55b5">Boolean</a> toggled when .secure_log_unique / .secure_log_reset is seen to catch errors if .secure_log_unique appears twice without .secure_log_reset appearing between them. <a href="#aeff0ee85b13469673dfa70aa060ce364">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23a2a6d7eb1d1c849688e410ac627882">CompilationDir</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The compilation directory to use for DW_AT_comp_dir. <a href="#a23a2a6d7eb1d1c849688e410ac627882">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; std::string, std::string &gt;, 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2a82cbf1a5f2824cb2405bf8bef76c3">DebugPrefixMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prefix replacement map for source file information. <a href="#ad2a82cbf1a5f2824cb2405bf8bef76c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46376eb91a04b67b80b79ed65dd9dc98">MainFileName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The main file name if passed in explicitly. <a href="#a46376eb91a04b67b80b79ed65dd9dc98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable">MCDwarfLineTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c20ea7c44a6fdd34d846f6897bd4d7">MCDwarfLineTablesCUMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The dwarf file and directory tables from the dwarf .file directive. <a href="#ad6c20ea7c44a6fdd34d846f6897bd4d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdwarfloc">MCDwarfLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaebf7ae1605b8810e5d419ff1dd18adb">CurrentDwarfLoc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current dwarf line information from the last dwarf .loc directive. <a href="#aaebf7ae1605b8810e5d419ff1dd18adb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e2f676fa96eff9173c66f3a9898f662">DwarfLocSeen</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae433b3d9a6c16e9df5a6ea5489c4be65">GenDwarfForAssembly</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generate dwarf debugging info for assembly source files. <a href="#ae433b3d9a6c16e9df5a6ea5489c4be65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54689688ad673a3d3c19d37cae98c915">GenDwarfFileNumber</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current dwarf file number when generate dwarf debugging info for assembly source files. <a href="#a54689688ad673a3d3c19d37cae98c915">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b155d59ed55163f930e86eadf876131">SectionsForRanges</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sections for generating the .debug_ranges and .debug_aranges sections. <a href="#a5b155d59ed55163f930e86eadf876131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mcgendwarflabelentry">MCGenDwarfLabelEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fdfe1eeda5abd27a9efbcac5a08901e">MCGenDwarfLabelEntries</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The information gathered from labels that will have dwarf label entries when generating dwarf assembly source files. <a href="#a0fdfe1eeda5abd27a9efbcac5a08901e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0465275c8758800f96202a40f462d9bd">DwarfDebugFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The string to embed in the debug information for the compile unit, if non-empty. <a href="#a0465275c8758800f96202a40f462d9bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d20ec35cfc18469ed0a042a0dbba1eb">DwarfDebugProducer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The string to embed in as the dwarf AT_producer for the compile unit, if non-empty. <a href="#a0d20ec35cfc18469ed0a042a0dbba1eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7244269bc98ace167d81badd70dca26f">DwarfVersion</a> = 4</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum version of dwarf that we should emit. <a href="#a7244269bc98ace167d81badd70dca26f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d1d3b1cdfdeac42edccc834f35f956">DwarfFormat</a> = <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">dwarf::DWARF32</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The format of dwarf that we emit. <a href="#af1d1d3b1cdfdeac42edccc834f35f956">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ccab89113e7e09eaf482c6637ea1af5">SaveTempLabels</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Honor temporary labels, this is useful for debugging semantic differences between temporary and non-temporary labels (primarily on Darwin). <a href="#a8ccab89113e7e09eaf482c6637ea1af5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae06e3bee1e9d3d454216aa39da258a76">UseNamesOnTempLabels</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49c62e473eb674a6a70085249fae3928">DwarfCompileUnitID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Compile Unit <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> that we are currently processing. <a href="#a49c62e473eb674a6a70085249fae3928">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobetable">MCPseudoProbeTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25735ebc2cbcdb606d00fc8a5c8a59af">PseudoProbeTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A collection of <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe">MCPseudoProbe</a> in the current module. <a href="#a25735ebc2cbcdb606d00fc8a5c8a59af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho">MCSectionMachO</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26f8c2c6affcb5a9e05b7e321ea58bca">MachOUniquingMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; COFFSectionKey, <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff">MCSectionCOFF</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f1f0c7646924e17e953e65dca7e31b8">COFFUniquingMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a172c3981c9df7ca767e44a8770142968">ELFUniquingMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, <a href="/web-llvm/docs/api/classes/llvm/mcsectiongoff">MCSectionGOFF</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d733811b2652c0290afb513f752230">GOFFUniquingMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; WasmSectionKey, <a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm">MCSectionWasm</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a283bebbc7deb168dec8e30f433c79d29">WasmUniquingMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; XCOFFSectionKey, <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff">MCSectionXCOFF</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf50f5dc48a48c4e84061f6d6f8f25e">XCOFFUniquingMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsectiondxcontainer">MCSectionDXContainer</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e836806d61db7bbcdaf0458946fdfbb">DXCUniquingMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba4274a071653f74e69cceb94bf31fb0">RelSecNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a295558fbb50b7592b675f48576cbc30e">MCSubtargetAllocator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab4dedc56885378ec2bd6bc4a0d03f92">AutoReset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Do automatic reset in destructor. <a href="#aab4dedc56885378ec2bd6bc4a0d03f92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3ffde0bd3e3d104ce2cd905a5dd3906">TargetOptions</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31e899ef271c0672c2ac9e81f36cdb9d">HadError</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae19dd8e06b15983218d42c7fc8fcf62">MacroMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map of currently defined macros. <a href="#aae19dd8e06b15983218d42c7fc8fcf62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::tuple&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, unsigned, unsigned &gt;, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3940e59d85d351ae6ecfe6006de38188">ELFEntrySizeMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d3282b6edc7deb84282d32232b39364">ELFSeenGenericMergeableSections</a></td>
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

## Section Management Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#aa96980c44bc03ccd7b7b1fde53bc1f7d">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho">MCSectionMachO</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0842bdee75832f17fb2b6a6199d1cc4d">getMachOSection</a> (StringRef Segment, StringRef Section, unsigned TypeAndAttributes, unsigned Reserved2, SectionKind K, const char *BeginSymName=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> for the specified mach-o section. <a href="#a0842bdee75832f17fb2b6a6199d1cc4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionmacho">MCSectionMachO</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af04e69d878824d996d620bcce1363a39">getMachOSection</a> (StringRef Segment, StringRef Section, unsigned TypeAndAttributes, SectionKind K, const char *BeginSymName=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fddc32fd70ea36b8482c9055eb68c40">getELFSection</a> (const Twine &amp;Section, unsigned Type, unsigned Flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fb2ccf37b0ca8de3cbecdd5d84918e0">getELFSection</a> (const Twine &amp;Section, unsigned Type, unsigned Flags, unsigned EntrySize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ee35c67e483d503d4f72dc5e0e4b368">getELFSection</a> (const Twine &amp;Section, unsigned Type, unsigned Flags, unsigned EntrySize, const Twine &amp;Group, bool IsComdat)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfbfa4b8157b753fa4ea370e8ffc8177">getELFSection</a> (const Twine &amp;Section, unsigned Type, unsigned Flags, unsigned EntrySize, const Twine &amp;Group, bool IsComdat, unsigned UniqueID, const MCSymbolELF *LinkedToSym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84ea0567e15790f68c421dada011ec5f">getELFSection</a> (const Twine &amp;Section, unsigned Type, unsigned Flags, unsigned EntrySize, const MCSymbolELF *Group, bool IsComdat, unsigned UniqueID, const MCSymbolELF *LinkedToSym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dafd75134861ffaa0f5f26e6ae5945a">getELFNamedSection</a> (const Twine &amp;Prefix, const Twine &amp;Suffix, unsigned Type, unsigned Flags, unsigned EntrySize=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a section with the provided group identifier. <a href="#a3dafd75134861ffaa0f5f26e6ae5945a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e5dc7053e3ede207302a8e223953743">createELFRelSection</a> (const Twine &amp;Name, unsigned Type, unsigned Flags, unsigned EntrySize, const MCSymbolELF *Group, const MCSectionELF *RelInfoSection)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf2235eabe74d3b9ee0314b91b71ee06">createELFGroupSection</a> (const MCSymbolELF *Group, bool IsComdat)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35965f6177893c536dcf4e924b387613">recordELFMergeableSectionInfo</a> (StringRef SectionName, unsigned Flags, unsigned UniqueID, unsigned EntrySize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9c510b9c8ab206680f3fe62f346046a">isELFImplicitMergeableSectionNamePrefix</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85e0ab8f47856461c14ee5f263e79999">isELFGenericMergeableSection</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a976e91f3dbcff07e94ea94fe83d0c926">getELFUniqueIDForEntsize</a> (StringRef SectionName, unsigned Flags, unsigned EntrySize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the section with the given name, flags and entry size, if it exists. <a href="#a976e91f3dbcff07e94ea94fe83d0c926">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectiongoff">MCSectionGOFF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82203778666af1baa04dec0f8791f26f">getGOFFSection</a> (StringRef Section, SectionKind Kind, MCSection *Parent, uint32_t Subsection=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff">MCSectionCOFF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64fec16b33fa7f23710afb8904948f30">getCOFFSection</a> (StringRef Section, unsigned Characteristics, StringRef COMDATSymName, int Selection, unsigned UniqueID=GenericSectionID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff">MCSectionCOFF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca28d2a04b948a01f9401075b0db725d">getCOFFSection</a> (StringRef Section, unsigned Characteristics)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff">MCSectionCOFF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef93e9316e910cbb64002e1cdfad0f01">getAssociativeCOFFSection</a> (MCSectionCOFF *Sec, const MCSymbol *KeySym, unsigned UniqueID=GenericSectionID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets or creates a section equivalent to Sec that is associated with the section containing KeySym. <a href="#aef93e9316e910cbb64002e1cdfad0f01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionspirv">MCSectionSPIRV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acffc1b92965b5c7cddb78486106ba384">getSPIRVSection</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm">MCSectionWasm</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354ee5b1baec10051b0d9da350bfe027">getWasmSection</a> (const Twine &amp;Section, SectionKind K, unsigned Flags=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm">MCSectionWasm</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec55174841f8aa80f2d1c3f56c4165af">getWasmSection</a> (const Twine &amp;Section, SectionKind K, unsigned Flags, const Twine &amp;Group, unsigned UniqueID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionwasm">MCSectionWasm</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad715fadab36063fc73cd1c87d0fcc636">getWasmSection</a> (const Twine &amp;Section, SectionKind K, unsigned Flags, const MCSymbolWasm *Group, unsigned UniqueID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectiondxcontainer">MCSectionDXContainer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbd17835611b883adf6f7dcc6d2eca0f">getDXContainerSection</a> (StringRef Section, SectionKind K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the section for the provided Section name. <a href="#abbd17835611b883adf6f7dcc6d2eca0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdef71fa8592899f0266affccef0e45e">hasXCOFFSection</a> (StringRef Section, XCOFF::CsectProperties CsectProp) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff">MCSectionXCOFF</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a435597fd04ebfd9b5fb5708a4309febb">getXCOFFSection</a> (StringRef Section, SectionKind K, std::optional&lt; XCOFF::CsectProperties &gt; CsectProp=std::nullopt, bool MultiSymbolsAllowed=false, std::optional&lt; XCOFF::DwarfSectionSubtypeFlags &gt; DwarfSubtypeFlags=std::nullopt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05939d944f98272791751dca10bb9f70">getSubtargetCopy</a> (const MCSubtargetInfo &amp;STI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4967f1d9be0ff3a0b2beec4532c0de98">getBBAddrMapVersion</a> () const</td>
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

## Module Lifetime Management Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8197434a9fa5a233ebc553cda3101ebd">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>reset - return object to right after construction state to prepare to process a new module <a href="#a8197434a9fa5a233ebc553cda3101ebd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## McInst Management Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b751cce960c243db7372dc393d67883">createMCInst</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create and return a new MC instruction. <a href="#a2b751cce960c243db7372dc393d67883">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename F, typename... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aed79db19d00f742ef88eafad5b074be0">allocFragment</a> (Args &amp;&amp;...args)</td>
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

## Symbol Management Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a331b0cec2bd2881f3383a47f4e0deec0">createLinkerPrivateTempSymbol</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new linker temporary symbol with the specified prefix (Name) or "tmp". <a href="#a331b0cec2bd2881f3383a47f4e0deec0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac24bf3fc8a5d5546cdda06886e305c95">createLinkerPrivateSymbol</a> (const Twine &amp;Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299bf2f0329389424760f4a7c8af75ac">createTempSymbol</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a temporary symbol with a unique name. <a href="#a299bf2f0329389424760f4a7c8af75ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab004175805bb32f89cdd49bca178e25">createTempSymbol</a> (const Twine &amp;Name, bool AlwaysAddSuffix=true)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff468f9432c24e89b881976f5e1f9cf8">createNamedTempSymbol</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a temporary symbol with a unique name whose name cannot be omitted in the symbol table. <a href="#aff468f9432c24e89b881976f5e1f9cf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58961f1ac4c43b9709824a686262b0b4">createNamedTempSymbol</a> (const Twine &amp;Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03742cf8aa97edf5612a800e4f159876">createBlockSymbol</a> (const Twine &amp;Name, bool AlwaysEmit=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get or create a symbol for a basic block. <a href="#a03742cf8aa97edf5612a800e4f159876">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57c17c36da95d81b14dc348d3f6102ad">createLocalSymbol</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a local, non-temporary symbol like an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> mapping symbol. <a href="#a57c17c36da95d81b14dc348d3f6102ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97cbccbfd2f64e098e0005ee9fdd943c">createDirectionalLocalSymbol</a> (unsigned LocalLabelVal)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the definition of a directional local symbol for numbered label (used for "1:" definitions). <a href="#a97cbccbfd2f64e098e0005ee9fdd943c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8a5e63fad89ccba5fee1f314d644b5">getDirectionalLocalSymbol</a> (unsigned LocalLabelVal, bool Before)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create and return a directional local symbol for numbered label (used for "1b" or 1f" references). <a href="#afb8a5e63fad89ccba5fee1f314d644b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac11eef690074972378846024abbe8722">getOrCreateSymbol</a> (const Twine &amp;Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup the symbol inside with the specified <span class="doxyComputerOutput">Name</span>. <a href="#ac11eef690074972378846024abbe8722">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d5af327caeae379919145f09cd51341">getOrCreateFrameAllocSymbol</a> (const Twine &amp;FuncName, unsigned Idx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets a symbol that will be defined to the final stack offset of a local variable after codegen. <a href="#a2d5af327caeae379919145f09cd51341">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e31ab123dec096ae41bbd8cbb73e036">getOrCreateParentFrameOffsetSymbol</a> (const Twine &amp;FuncName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9961367ad9649b3df25a31117bba067">getOrCreateLSDASymbol</a> (const Twine &amp;FuncName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7099c67764b3ea472791762cb6bd9e2f">lookupSymbol</a> (const Twine &amp;Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the symbol for <span class="doxyComputerOutput">Name</span>, or null. <a href="#a7099c67764b3ea472791762cb6bd9e2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21aceafe085b9a14a9864954b9fdb14b">setSymbolValue</a> (MCStreamer &amp;Streamer, const Twine &amp;Sym, uint64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set value for a symbol. <a href="#a21aceafe085b9a14a9864954b9fdb14b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aa446787f1602d571ba5543a5295fe7c1">SymbolTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3a724ff67c13baf6feab0902b175204">getSymbols</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSymbols - Get a reference for the symbol table for clients that want to, for example, iterate over all symbols. <a href="#aa3a724ff67c13baf6feab0902b175204">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a392412e22be62f31478cfca07d562055">getInlineAsmLabel</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isInlineAsmLabel - Return true if the name is a label referenced in inline assembly. <a href="#a392412e22be62f31478cfca07d562055">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a575d0689ae105eb694d6bdc9cc873935">registerInlineAsmLabel</a> (MCSymbol *Sym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>registerInlineAsmLabel - Records that the name is a label referenced in inline assembly. <a href="#a575d0689ae105eb694d6bdc9cc873935">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/wasm/wasmsignature">wasm::WasmSignature</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d3a0ff7d64b165758e5fb15be26279a">createWasmSignature</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allocates and returns a new <span class="doxyComputerOutput">WasmSignature</span> instance (with empty parameter and return type lists). <a href="#a3d3a0ff7d64b165758e5fb15be26279a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Dwarf Management Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a19163118e2b27686c1010ab26556a3">getCompilationDir</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the compilation directory for DW_AT_comp_dir The compilation directory should be set with <span class="doxyComputerOutput">setCompilationDir</span> before calling this function. <a href="#a2a19163118e2b27686c1010ab26556a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83fc1b3aaadeeadd3b56de78e1415abb">setCompilationDir</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the compilation directory for DW_AT_comp_dir. <a href="#a83fc1b3aaadeeadd3b56de78e1415abb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a292e9b2444ced8a458c20aaf3b816626">addDebugPrefixMapEntry</a> (const std::string &amp;From, const std::string &amp;To)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an entry to the debug prefix map. <a href="#a292e9b2444ced8a458c20aaf3b816626">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01ecf33b3bb3331985f61bca570827d7">remapDebugPath</a> (SmallVectorImpl&lt; char &gt; &amp;Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remap one path in-place as per the debug prefix map. <a href="#a01ecf33b3bb3331985f61bca570827d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b6fa558341bb0ce850c615f39b429f5">RemapDebugPaths</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2465bb2474b7bacc584546860c1c234b">getMainFileName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the main file name for use in error messages and debug info. <a href="#a2465bb2474b7bacc584546860c1c234b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfd2641cfadb2bf0ad06a93ad6753abd">setMainFileName</a> (StringRef S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the main file name and override the default. <a href="#abfd2641cfadb2bf0ad06a93ad6753abd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ad186547248b6c5236a8795cce3f477">getDwarfFile</a> (StringRef Directory, StringRef FileName, unsigned FileNumber, std::optional&lt; MD5::MD5Result &gt; Checksum, std::optional&lt; StringRef &gt; Source, unsigned CUID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an entry in the dwarf file and directory tables. <a href="#a3ad186547248b6c5236a8795cce3f477">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50a6c8425d664907bb4a20247bdee178">isValidDwarfFileNumber</a> (unsigned FileNumber, unsigned CUID=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isValidDwarfFileNumber - takes a dwarf file number and returns true if it currently is assigned and false otherwise. <a href="#a50a6c8425d664907bb4a20247bdee178">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::map&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable">MCDwarfLineTable</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a844102db6a944e0b900e1dcb331cd8ba">getMCDwarfLineTables</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable">MCDwarfLineTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f7e21c9dac9e7acb4fdd713e712d20">getMCDwarfLineTable</a> (unsigned CUID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable">MCDwarfLineTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7098313285ab3aa2553db1f6fe8c53d">getMCDwarfLineTable</a> (unsigned CUID) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/mcdwarffile">MCDwarfFile</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81530c44115124e6e977b6e14b8ec4a1">getMCDwarfFiles</a> (unsigned CUID=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::string &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11e4d2892230408be583cbf6ee7c28c0">getMCDwarfDirs</a> (unsigned CUID=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aabd162418263d017e3559978931451">getDwarfCompileUnitID</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad619a8d1435a4b5a4b75cce8878486fe">setDwarfCompileUnitID</a> (unsigned CUIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa7b9baa221c1a5ea68940b0cf6b5a26">setMCLineTableRootFile</a> (unsigned CUID, StringRef CompilationDir, StringRef Filename, std::optional&lt; MD5::MD5Result &gt; Checksum, std::optional&lt; StringRef &gt; Source)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specifies the "root" file and directory of the compilation unit. <a href="#afa7b9baa221c1a5ea68940b0cf6b5a26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137ae51c4db9a5f30ed3148a9aad81ce">isDwarfMD5UsageConsistent</a> (unsigned CUID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reports whether <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> checksum usage is consistent (all-or-none). <a href="#a137ae51c4db9a5f30ed3148a9aad81ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bef0ea056c194d113570558f2c07132">setCurrentDwarfLoc</a> (unsigned FileNum, unsigned Line, unsigned Column, unsigned Flags, unsigned Isa, unsigned Discriminator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Saves the information from the currently parsed dwarf .loc directive and sets DwarfLocSeen. <a href="#a8bef0ea056c194d113570558f2c07132">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a533301811e7317a14fd07d84073590ee">clearDwarfLocSeen</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a285982216c5eb361f38a33f46ed2f124">getDwarfLocSeen</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdwarfloc">MCDwarfLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2fe3b101fb1f6389502b5d4f99c0640">getCurrentDwarfLoc</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b487b9dffd6d0f849e9131ebabc998f">getGenDwarfForAssembly</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48d092c1445b69a1587b8f24d43d12ec">setGenDwarfForAssembly</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8628c8e12fcc26b3fbb4edf01a01fa82">getGenDwarfFileNumber</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a86a87fba6a15227ff4f33edd538e6d0f">EmitDwarfUnwindType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88c3f925ea4397b617e665c3d9be424">emitDwarfUnwindInfo</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7374fa80c820bab9544f60931b8ca408">emitCompactUnwindNonCanonical</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfed6f3916764b6062de06e25e4a6603">setGenDwarfFileNumber</a> (unsigned FileNumber)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae44a97a569de65d01e1f80ae5261121b">setGenDwarfRootFile</a> (StringRef FileName, StringRef Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specifies information about the "root file" for assembler clients (e.g., llvm-mc). <a href="#ae44a97a569de65d01e1f80ae5261121b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ffd38472bf725df4e4c3cac8c0ad771">getGenDwarfSectionSyms</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a589edc5876425761e8515d0d03ba9576">addGenDwarfSection</a> (MCSection *Sec)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa565526e57992a6482d7062b03933b99">finalizeDwarfSections</a> (MCStreamer &amp;MCOS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove empty sections from SectionsForRanges, to avoid generating useless debug info for them. <a href="#aa565526e57992a6482d7062b03933b99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/mcgendwarflabelentry">MCGenDwarfLabelEntry</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed43a765c7bd89683590bab0196c87b3">getMCGenDwarfLabelEntries</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab699e113c8ef43f15b51d32819a96c44">addMCGenDwarfLabelEntry</a> (const MCGenDwarfLabelEntry &amp;E)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8869af36f9069b8e91c06a99d37eb630">setDwarfDebugFlags</a> (StringRef S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2757e59e5aa1e5a66e2b11352caa61bd">getDwarfDebugFlags</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9573f499fce315377b867ee2f1a52216">setDwarfDebugProducer</a> (StringRef S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fa812f878a36093c56d691c50a23a3e">getDwarfDebugProducer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8262581122296e7b4247a5043fe30fa1">setDwarfFormat</a> (dwarf::DwarfFormat f)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae871de84d03670534d73ae7448b6b6d9">getDwarfFormat</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ed247246b5256063c6c357b46a134b">setDwarfVersion</a> (uint16_t v)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99c58fcbed2434b9535b866015cd0259">getDwarfVersion</a> () const</td>
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

<p>Context object for machine code objects.</p>


<p>This class owns all of the sections that it creates.</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### DiagHandlerTy {#a9e9f52b1aa04f522af6653ff65b1d888}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MCContext::DiagHandlerTy = 
      std::function&lt;void(const SMDiagnostic &amp;, bool, const SourceMgr &amp;,
                         std::vector&lt;const MDNode *&gt; &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### SymbolTable {#aa446787f1602d571ba5543a5295fe7c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MCContext::SymbolTable =  StringMap&lt;MCSymbolTableValue, BumpPtrAllocator &amp;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### Environment {#af13dae4c64d48ea988d060a767605890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MCContext::Environment </td>
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
<td class="doxyEnumItemName">IsMachO<a id="af13dae4c64d48ea988d060a767605890a1d8067015bb1e7a65f9ebbe516f79bca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsELF<a id="af13dae4c64d48ea988d060a767605890ac8172f032ec16640838e35d9e8c78b50"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsGOFF<a id="af13dae4c64d48ea988d060a767605890aa096d16f497f52e13268f3071a82ca31"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsCOFF<a id="af13dae4c64d48ea988d060a767605890a730e6df3f810384d6d4f7970f1853df6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsSPIRV<a id="af13dae4c64d48ea988d060a767605890a1d78ddf6bf9eb21bee5ac825e378b224"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsWasm<a id="af13dae4c64d48ea988d060a767605890a4a69ee4b595474eec127121caddd21c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsXCOFF<a id="af13dae4c64d48ea988d060a767605890a92573e214aa83c1df78138a2320e9e6f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IsDXContainer<a id="af13dae4c64d48ea988d060a767605890ae21b6548859f1d9bb8f608af6b9be307"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MCContext() {#a8c75c94fa169456ebdef2337504928e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext::MCContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TheTriple, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> * MAI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> * MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> * MSTI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> * Mgr=nullptr, <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * TargetOpts=nullptr, bool DoAutoReset=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Swift5ReflSegmentName={})</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp/#a4c4cc7fd1400fb03f06f4254fc03db53">defaultDiagHandler</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#a377ba69923635f8154cad5784be89ff6">DWARF2_FLAG_IS_STMT</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a2e265a0d332c3e2db0acf0c7afd4175d">llvm::Triple::getObjectFormat</a>.</p>


<p>Referenced by <a href="#a29706a277659ceb9d10a7891eaa49c86">MCContext</a> and <a href="#abd9326a55f25cd9effc0b0f350ef59b5">operator=</a>.</p>

</div>
</div>

### MCContext() {#a29706a277659ceb9d10a7891eaa49c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MCContext::MCContext (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;)</td>
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



<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="#a8c75c94fa169456ebdef2337504928e6">MCContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MCContext() {#a75b7ed17686752b3420b0ad6ffb6c726}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext::~MCContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="#a8197434a9fa5a233ebc553cda3101ebd">reset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#abd9326a55f25cd9effc0b0f350ef59b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCContext &amp; llvm::MCContext::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp;)</td>
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



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="#a8c75c94fa169456ebdef2337504928e6">MCContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allocate() {#a0d676337d17f32eb1e8ff4ab2b4e7f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::MCContext::allocate (unsigned Size, unsigned Align=8)</td>
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



<p>Definition at line 816 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### allocateString() {#a598983d169adb6ccd6307753bf2021b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCContext::allocateString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> s)</td>
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

<p>Allocates a copy of the given string on the allocator managed by this context and returns the result.</p>

<p>Definition at line 824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringsaver/#ada08f15f76fa550da28d92b038b6644b">llvm::StringSaver::save</a>.</p>

</div>
</div>

### deallocate() {#a10a32ed0247891267c067a42fb9cff87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::deallocate (void * Ptr)</td>
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



<p>Definition at line 820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### defineMacro() {#a2fb29f3e5885dbb7ea6c53b8be5e7179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::defineMacro (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/structs/llvm/mcasmmacro">MCAsmMacro</a> Macro)</td>
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



<p>Definition at line 838 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a4374cf34c5d58482ffae982196bd2114">llvm::Macro</a>.</p>

</div>
</div>

### diagnose() {#a498f34a9cf9f29168a1ac92143e3cd96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::diagnose (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; SMD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 1027 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getAsmInfo() {#aa3beac794c4afb5b1fb6d06cb7786587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmInfo * llvm::MCContext::getAsmInfo ()</td>
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



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcfiexception/#af2d29f19a7e1b49d4ecf82154691a33d">llvm::DwarfCFIException::beginFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgputargetasmstreamer/#abf468fdf1fecb6e06d29a8cbfaa808bb">llvm::AMDGPUTargetAsmStreamer::EmitAmdhsaKernelDescriptor</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a07c0db5089a287c91b8197cad7f2eeda">emitFDESymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a3076428f827ac1e84c8ffef025bd7d88">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitInst</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetstreamer/#a35fb67d88bdb317b8d0ed132e9403414">llvm::ARMTargetStreamer::emitInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#adf60d16739e1ceabb1cee9e9dede7ba5">llvm::MCDwarfLineTable::emitOne</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#aa5b673bb0b1684ee529dc9fcafd6167b">EmitPersonality</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ab521cbeeba5f775524447eec5b221d56">getDataAlignmentFactor</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae482cc4ee4cf4d5b4bfe6e1dde4f1ed8">getSizeForEncoding</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#ab6fb66900168f71c259a40c4213258ee">llvm::MCResourceInfo::getSymbol</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>.</p>

</div>
</div>

### getCVContext() {#a7bdf9164b69f96821c0c0269dde3ebf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeViewContext &amp; MCContext::getCVContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 1017 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a79e4fddfcfc0d5ed30a1b811fcd17a6e">llvm::MCStreamer::checkCVLocSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a7f014c82821d76aff471c10829f336c6">llvm::MCObjectStreamer::emitCVDefRangeDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#adf42e6aacb6951ef0ed334e1526d7678">llvm::MCObjectStreamer::emitCVFileChecksumOffsetDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#af3ddec166c838e59362d5b7a85f50384">llvm::MCObjectStreamer::emitCVFileChecksumsDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a33c2e7b8c7463f2698a3132452cc4d12">llvm::MCStreamer::emitCVFileDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a13ac5fe9bbe382dd5e366288ba91fa43">llvm::MCStreamer::emitCVFuncIdDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3590fc09ce2f93b9c19c488fb5cc3645">llvm::MCObjectStreamer::emitCVInlineLinetableDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aea7cedf9c3df1534425168ee9969871c">llvm::MCStreamer::emitCVInlineSiteIdDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#af86cdbc272816dffaa30c62bdd8ec4b1">llvm::MCObjectStreamer::emitCVLinetableDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a61b27602b6cd429e5c1e226117c6da67">llvm::MCObjectStreamer::emitCVLocDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3b37cee5f8e850d8bbe6e9086a4e3733">llvm::MCObjectStreamer::emitCVStringTableDirective</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#ac60cbf99d76cbbbbc3c094a7d78fb834">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::emitFrameDataRecord</a> and <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a7f964c60245b61612ddd6509cba7eb74">llvm::MCWinCOFFStreamer::finishImpl</a>.</p>

</div>
</div>

### getInlineSourceManager() {#ac1abe656f2fed82507750b6173c36952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourceMgr * llvm::MCContext::getInlineSourceManager ()</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### getLocInfos() {#af868e37f8586a148a5f224743078a5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; const MDNode * &gt; &amp; llvm::MCContext::getLocInfos ()</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### getMCPseudoProbeTable() {#a01cf35ff8a291a79d6970f1e1e35a272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCPseudoProbeTable &amp; llvm::MCContext::getMCPseudoProbeTable ()</td>
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



<p>Definition at line 844 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobetable/#af165f606b60b68425ab228437d209753">llvm::MCPseudoProbeTable::emit</a>.</p>

</div>
</div>

### getObjectFileInfo() {#a01d6d82d18a5da901c50a546932c4264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCObjectFileInfo * llvm::MCContext::getObjectFileInfo ()</td>
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



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetstreamer/#ab7ccb3b4d754b7e2ab62aca1113ab56d">llvm::NVPTXTargetStreamer::changeSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a89cdc6ed6476f39c32e5a49327bb692e">llvm::MCDwarfLineTable::emit</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a296ba2dbfb0e9605f94744804b1612b9">llvm::MCWinCOFFStreamer::emitCOFFSafeSEH</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a46ca451d0ba24a1a138f28bd71a72271">llvm::MCWinCOFFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuasmprinter/#aa07427c984394cc2c4b4cf8b7158def4">llvm::AMDGPUAsmPrinter::emitFunctionBodyEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a98ffe083ab6ade934683a26a65204179">llvm::MCWinCOFFStreamer::emitLocalCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr/#a1578026c1ceb637e4b37023412f971ac">llvm::MCDwarfLineStr::emitSection</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a7e24606b8fe6124decedb17e5ffa405e">llvm::X86FrameLowering::enableShrinkWrapping</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a94031e736c9e04044ac7181147a54bf6">llvm::MipsTargetELFStreamer::finish</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a17d3b4679a104b0852f1679b817d2070">llvm::MipsTargetELFStreamer::MipsTargetELFStreamer</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvasmparser-cpp-/riscvasmparser/#af34b3385ad6d2dc040f431e84cd822eb">anonymous{RISCVAsmParser.cpp}::RISCVAsmParser::RISCVAsmParser</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilegoff/#a8c58f11a5aa16a65fa81203993787033">llvm::TargetLoweringObjectFileGOFF::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/faultmaps/#a393b0f5b51aef71d44cc36b4e7b048a7">llvm::FaultMaps::serializeToFaultMapSection</a>, <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#a64f17d34c6ec33d574438b69fa43c2e2">llvm::StackMaps::serializeToStackMapSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7363e46d4dd6c78affffabaea0de482b">llvm::write</a>.</p>

</div>
</div>

### getObjectFileType() {#a1357b82842249c1488257e19ee78f2b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Environment llvm::MCContext::getObjectFileType ()</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### getRegisterInfo() {#a7eff7fcbe27aa063e7dced4042ca3416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo * llvm::MCContext::getRegisterInfo ()</td>
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



<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzframelowering-cpp/#a28391c59e5f478e4513f021226549734">buildDefCFAReg</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430framelowering/#a66fceb6b28377362e963e250c5c865c1">llvm::MSP430FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a6c1f3151b66ea2dfd6a8b9cef815d51c">llvm::X86FrameLowering::emitCalleeSavedFrameMoves</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#acbd4fee4d18fa2066d758dff7168ef36">llvm::X86FrameLowering::emitCalleeSavedFrameMovesFullCFA</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86wincofftargetstreamer-cpp-/fpostatemachine/#ac60cbf99d76cbbbbc3c094a7d78fb834">anonymous{X86WinCOFFTargetStreamer.cpp}::FPOStateMachine::emitFrameDataRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a83709b9d2961247a986101cd796eeca7">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitMovSP</a>, <a href="/web-llvm/docs/api/classes/llvm/mips16framelowering/#affe78904b64f71286945c438ebf31bc7">llvm::Mips16FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#ae528e90e0e85a0d0597982913065596c">llvm::MipsSEFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#aa670bf850cd6767f78408604873036f7">llvm::PPCFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1framelowering/#a28025294ad7a2c17e26f3aacac9a7467">llvm::Thumb1FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoreframelowering/#afc48ca3b84128ca1b9ab1701d4f30b8c">llvm::XCoreFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensaframelowering/#a52e2cb94c2423daf62dc0ab22b688ee1">llvm::XtensaFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#af7b885257ab544caad5ce47c9939079d">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitRegSave</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudisassembler/#a16d28a91d7aca8ef06fa3e2533047f0b">llvm::AMDGPUDisassembler::getRegClassName</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcframelowering/#af0a5a3bd252aaac7b161ad8c01cf0951">llvm::PPCFrameLowering::inlineStackProbe</a>.</p>

</div>
</div>

### getSecureLog() {#a63c3b692c1ce37d522ad721fc60f44ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_ostream * llvm::MCContext::getSecureLog ()</td>
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



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### getSecureLogFile() {#aee07502ffb216b231a76356816de4f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCContext::getSecureLogFile ()</td>
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



<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### getSecureLogUsed() {#a636712256c661bec6ad7b981476a2f7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::getSecureLogUsed ()</td>
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



<p>Definition at line 813 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### getSourceManager() {#aa0238c5455430b5bef943138b198e522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SourceMgr * llvm::MCContext::getSourceManager ()</td>
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



<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aa660e7b419602632507f83ec8a1520aa">llvm::MCObjectStreamer::emitFill</a>.</p>

</div>
</div>

### getSubtargetInfo() {#afbcf25f6a20ef3f5197a782bf7e55d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo * llvm::MCContext::getSubtargetInfo ()</td>
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



<p>Definition at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cskyconstantpool/#a504a7be63300c2c61d79be758524a433">llvm::CSKYConstantPool::emitAll</a>.</p>

</div>
</div>

### getSwift5ReflectionSegmentName() {#a546be23da489afe72406d18d974f15f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const StringRef &amp; llvm::MCContext::getSwift5ReflectionSegmentName ()</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### getTargetOptions() {#ad270e6f1bba829cef8708bba5faeeb8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCTargetOptions * llvm::MCContext::getTargetOptions ()</td>
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



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64elfstreamer-cpp-/aarch64elfstreamer/#ab3c1d7ab672f0bd15bc00752eb7f8c4d">anonymous{AArch64ELFStreamer.cpp}::AArch64ELFStreamer::AArch64ELFStreamer</a>.</p>

</div>
</div>

### getTargetTriple() {#afff5b8282b36f6a0ed50aeafe462250d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::MCContext::getTargetTriple ()</td>
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



<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcwincoffstreamer/#a46ca451d0ba24a1a138f28bd71a72271">llvm::MCWinCOFFStreamer::emitCommonSymbol</a>.</p>

</div>
</div>

### hadError() {#a16be3cf71194a82a5cf1d124ebbdc433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::hadError ()</td>
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



<p>Definition at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>.</p>

</div>
</div>

### initInlineSourceManager() {#a64f78358076dadb56305f7a236c5e3d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::initInlineSourceManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### lookupMacro() {#a5e05d443eeaa7af08eacb9179ae573f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCAsmMacro * llvm::MCContext::lookupMacro (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### reportError() {#aac3107671801e6bb16ef896f382759cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::reportError (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 1072 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a> and <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acdf08ebc749ce91001ea768a16da0605">llvm::SourceMgr::GetMessage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a6574f704d2fbd168f81e7552695170a8">ARM64EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#aa32035802671dce51123a77b96594506">checkARM64Instructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a1a64f841fb788b307e31f8a70e6c022a">checkARMInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a79e4fddfcfc0d5ed30a1b811fcd17a6e">llvm::MCStreamer::checkCVLocSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#abc4d6b7d638e45034130bc3ab18e5be6">llvm::MCAssembler::computeFragmentSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a11eed8ef0a19a4cd80fc06a8488061fd">llvm::MCStreamer::emitCFIStartProc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aea7cedf9c3df1534425168ee9969871c">llvm::MCStreamer::emitCVInlineSiteIdDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a92d2d1c2ac97f1151ed8f38d854e8b34">llvm::MCObjectStreamer::emitInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a822ae1a4f19b7b00a297a100749f9b8a">llvm::MCStreamer::emitLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#acfe4f94dca14855495d5743fc3e60998">llvm::MCELFStreamer::emitSymbolAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#afd1e58493361c4e4fee6d7faca43a225">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a9ef24f653b777a160537ee3e1d824663">llvm::MCObjectStreamer::emitValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ad9bb2bc90c804c28497604ae91e27bd7">llvm::MCStreamer::emitWinCFIAllocStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9b6d232a4258f0dd9f16ee5b4f558633">llvm::MCStreamer::emitWinCFIEndChained</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9d158c6b4a4302d51fd73aac4075086d">llvm::MCStreamer::emitWinCFIEndProc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aac38128831e5c5377b98fd32d4f53fc9">llvm::MCStreamer::emitWinCFIFuncletOrFuncEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a4c579bc3d70f8f348c3ddf8224a31220">llvm::MCStreamer::emitWinCFIPushFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9a30cc0783819b780c3e357162b90aec">llvm::MCStreamer::emitWinCFISaveReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a5755faab671780e6c1abcaa95f05fe0b">llvm::MCStreamer::emitWinCFISaveXMM</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acd1f092159870d525f916e3296341d92">llvm::MCStreamer::emitWinCFISetFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7787897c604e14c9e152c890e019e3bf">llvm::MCStreamer::emitWinCFIStartProc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a26b51b14a3b7ce5cd6abe0c45872dd60">llvm::MCStreamer::emitWinEHHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a4e42517f705e57c03ce078fcac4e8f19">llvm::MCStreamer::emitWinEHHandlerData</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac6673eacba606285dd63d8d1669054bd">llvm::MCStreamer::EnsureValidWinFrameInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afa4bd753124bc1895e37282afa974972">llvm::MCStreamer::finish</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#ac06af0994b284d9e18c3b90c7c500a03">llvm::MCAssembler::getBaseSymbol</a>, <a href="#a64fec16b33fa7f23710afb8904948f30">getCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a339d32ea1f7597a13e849615446a7d26">llvm::X86RegisterInfo::getReservedRegs</a>, <a href="#a99057f5cbc5ee5f973d463d4c30abe7d">reportWarning</a>, <a href="/web-llvm/docs/api/classes/llvm/avrtargetobjectfile/#a2ac5016664f09fbfd8b97a954fccd664">llvm::AVRTargetObjectFile::SelectSectionForGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a179d49e133edc4f825fe798450d24458">llvm::MCStreamer::switchSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a2a301492f7142fbc3744cc1c5a86f5ec">llvm::MCAssembler::writeSectionData</a>.</p>

</div>
</div>

### reportWarning() {#a99057f5cbc5ee5f973d463d4c30abe7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::reportWarning (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777a6bcc8ac9374461ed0599334db63365d0">llvm::SourceMgr::DK_Warning</a>, <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#acdf08ebc749ce91001ea768a16da0605">llvm::SourceMgr::GetMessage</a> and <a href="#aac3107671801e6bb16ef896f382759cd">reportError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#acfe4f94dca14855495d5743fc3e60998">llvm::MCELFStreamer::emitSymbolAttribute</a>.</p>

</div>
</div>

### setDiagnosticHandler() {#a68fb1a489deef96ac4b0d93d629e2ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setDiagnosticHandler (<a href="#a9e9f52b1aa04f522af6653ff65b1d888">DiagHandlerTy</a> DiagHandler)</td>
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



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/modulesymboltable-cpp/#af63cc4141d5da9ef88eb0ec4b2b3c959">initializeRecordStreamer</a>.</p>

</div>
</div>

### setObjectFileInfo() {#a139a14c94184b5c989786a1666037955}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setObjectFileInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> * Mofi)</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/modulesymboltable-cpp/#af63cc4141d5da9ef88eb0ec4b2b3c959">initializeRecordStreamer</a>.</p>

</div>
</div>

### setSecureLog() {#aa872583a92136483ec5699b862e6974e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setSecureLog (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> &gt; Value)</td>
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



<p>Definition at line 809 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### setSecureLogUsed() {#a2f67b8685a1404b9ba5898447ee8fe6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setSecureLogUsed (bool Value)</td>
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



<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### setUseNamesOnTempLabels() {#adf651d1717dcdbe43fe8ce45a32b8eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setUseNamesOnTempLabels (bool Value)</td>
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



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### undefineMacro() {#a783a17d8f062723eacbb184f536898ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::undefineMacro (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### allocInitialFragment() {#a4319fd8f91cf933aa6c289054887f7b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDataFragment * MCContext::allocInitialFragment (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### createELFSectionImpl() {#ad494942b9bf8df80430d48231bf9d70e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionELF * MCContext::createELFSectionImpl (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, unsigned Type, unsigned Flags, unsigned EntrySize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> * Group, bool IsComdat, unsigned UniqueID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> * LinkedToSym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### createRenamableSymbol() {#a523aa0f26cb925aeca838c48705c1013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::createRenamableSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, bool AlwaysAddSuffix, bool IsTemporary)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### createSymbolImpl() {#aebd8789f27ba19f128cfec03f102c2ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::createSymbolImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> * Name, bool IsTemporary)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### createXCOFFSymbolImpl() {#af807cd9fcd2a4713760e9b303f1502ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolXCOFF * MCContext::createXCOFFSymbolImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a9f4cf9e4567dcf87070176a271b63e38">MCSymbolTableEntry</a> * Name, bool IsTemporary)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### GetInstance() {#a53ceef29d40d663002f912b4ab0ec7c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MCContext::GetInstance (unsigned LocalLabelVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetInstance() gets the current instance of the directional local label for the LocalLabelVal and adds it to the map if needed.</p>

<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### getOrCreateDirectionalLocalSymbol() {#a63c61935b3730e67c3ddcc30be70adba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::getOrCreateDirectionalLocalSymbol (unsigned LocalLabelVal, unsigned Instance)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### getOrCreateSectionSymbol() {#a165f584cb1a4409c46783117c44b9dec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Symbol&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol * MCContext::getOrCreateSectionSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### getSymbolTableEntry() {#a36c4d873ae691b877ffb6a5893ba0c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbolTableEntry &amp; MCContext::getSymbolTableEntry (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### NextInstance() {#a6384dbaf99c5ce5bb0983222acb1750e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MCContext::NextInstance (unsigned LocalLabelVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>NextInstance() creates the next instance of the directional local label for the LocalLabelVal and adds it to the map if needed.</p>

<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### reportCommon() {#a7ca741597356333a68f752e675d713f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::reportCommon (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> *)&gt; GetMessage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 1041 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Allocator {#a4ef65cccaef6ec02c16ae00719258b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::MCContext::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocator object used for creating machine code objects.</p>


<p>We use a bump pointer allocator to avoid the need to track all allocated objects.</p>


<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### AutoReset {#aab4dedc56885378ec2bd6bc4a0d03f92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::AutoReset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Do automatic reset in destructor.</p>

<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### BBAddrMapVersion {#a560a0a1efc0c244b9d2473d52b4dc253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MCContext::BBAddrMapVersion = 2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>LLVM_BB_ADDR_MAP version to emit.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### COFFAllocator {#ad0fb37eb03f31746ccf00a287acf4a94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;MCSectionCOFF&gt; llvm::MCContext::COFFAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### COFFUniquingMap {#a3f1f0c7646924e17e953e65dca7e31b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;COFFSectionKey, MCSectionCOFF *&gt; llvm::MCContext::COFFUniquingMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### CompilationDir {#a23a2a6d7eb1d1c849688e410ac627882}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;128&gt; llvm::MCContext::CompilationDir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The compilation directory to use for DW_AT_comp_dir.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### CurrentDwarfLoc {#aaebf7ae1605b8810e5d419ff1dd18adb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDwarfLoc llvm::MCContext::CurrentDwarfLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current dwarf line information from the last dwarf .loc directive.</p>

<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### CVContext {#a117ed7fd50dfbb32869c638838f4164e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;CodeViewContext&gt; llvm::MCContext::CVContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### DebugPrefixMap {#ad2a82cbf1a5f2824cb2405bf8bef76c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;std::string, std::string&gt;, 0&gt; llvm::MCContext::DebugPrefixMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Prefix replacement map for source file information.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### DiagHandler {#a8eef406063289c55a9133be39e008ed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagHandlerTy llvm::MCContext::DiagHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### DwarfCompileUnitID {#a49c62e473eb674a6a70085249fae3928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCContext::DwarfCompileUnitID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Compile Unit <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> that we are currently processing.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### DwarfDebugFlags {#a0465275c8758800f96202a40f462d9bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCContext::DwarfDebugFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The string to embed in the debug information for the compile unit, if non-empty.</p>

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### DwarfDebugProducer {#a0d20ec35cfc18469ed0a042a0dbba1eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCContext::DwarfDebugProducer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The string to embed in as the dwarf AT_producer for the compile unit, if non-empty.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### DwarfFormat {#af1d1d3b1cdfdeac42edccc834f35f956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::DwarfFormat llvm::MCContext::DwarfFormat = <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">dwarf::DWARF32</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The format of dwarf that we emit.</p>

<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### DwarfLocSeen {#a1e2f676fa96eff9173c66f3a9898f662}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::DwarfLocSeen = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### DwarfVersion {#a7244269bc98ace167d81badd70dca26f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCContext::DwarfVersion = 4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum version of dwarf that we should emit.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### DXCAllocator {#a8c85df6270ae48be94df3dd081727ddb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;MCSectionDXContainer&gt; llvm::MCContext::DXCAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### DXCUniquingMap {#a6e836806d61db7bbcdaf0458946fdfbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;MCSectionDXContainer *&gt; llvm::MCContext::DXCUniquingMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### ELFAllocator {#a1bd64eb2f8f3207bf5c93b6500729bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;MCSectionELF&gt; llvm::MCContext::ELFAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### ELFEntrySizeMap {#a3940e59d85d351ae6ecfe6006de38188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::tuple&lt;StringRef, unsigned, unsigned&gt;, unsigned&gt; llvm::MCContext::ELFEntrySizeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### ELFSeenGenericMergeableSections {#a1d3282b6edc7deb84282d32232b39364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;StringRef&gt; llvm::MCContext::ELFSeenGenericMergeableSections</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### ELFUniquingMap {#a172c3981c9df7ca767e44a8770142968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;MCSectionELF *&gt; llvm::MCContext::ELFUniquingMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### Env {#a1cee20f137e51d70889330f78bef593f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Environment llvm::MCContext::Env</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### FragmentAllocator {#a5549d6874c9b72daceb959241a886dd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::MCContext::FragmentAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For <a href="/web-llvm/docs/api/classes/llvm/mcfragment">MCFragment</a> instances.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### GenDwarfFileNumber {#a54689688ad673a3d3c19d37cae98c915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCContext::GenDwarfFileNumber = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The current dwarf file number when generate dwarf debugging info for assembly source files.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### GenDwarfForAssembly {#ae433b3d9a6c16e9df5a6ea5489c4be65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::GenDwarfForAssembly = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Generate dwarf debugging info for assembly source files.</p>

<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### GOFFAllocator {#a64bfce45bbe2aa79edd9e99803816ec6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;MCSectionGOFF&gt; llvm::MCContext::GOFFAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### GOFFUniquingMap {#ae0d733811b2652c0290afb513f752230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string, MCSectionGOFF *&gt; llvm::MCContext::GOFFUniquingMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### HadError {#a31e899ef271c0672c2ac9e81f36cdb9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::HadError = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### InlineAsmUsedLabelNames {#acc50af4d182f7ee401ade09beab82c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;MCSymbol *, BumpPtrAllocator &amp;&gt; llvm::MCContext::InlineAsmUsedLabelNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps track of labels that are used in inline assembly.</p>

<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### InlineSrcMgr {#a2cb8072a8b87089c7676d64cc9882aed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SourceMgr&gt; llvm::MCContext::InlineSrcMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> for inline assembly, if any.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### Instances {#a75a01a4116846290a5a44d64ca65b628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, MCLabel *&gt; llvm::MCContext::Instances</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Instances of directional local labels.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### LocalSymbols {#a9cfabfb41bb4bdda311adec5afeecf9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;unsigned, unsigned&gt;, MCSymbol *&gt; llvm::MCContext::LocalSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A mapping from a local label number and an instance count to a symbol.</p>


<p>For example, in the assembly 1: 2: 1: We have three labels represented by the pairs (1, 0), (2, 0) and (1, 1)</p>


<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### LocInfos {#aa1586249aafa5a65e9a2ed0c0e6475b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;const MDNode *&gt; llvm::MCContext::LocInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### MachOAllocator {#a6a09e4af5f9ad2ae849e026c8e4741a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;MCSectionMachO&gt; llvm::MCContext::MachOAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### MachOUniquingMap {#a26f8c2c6affcb5a9e05b7e321ea58bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;MCSectionMachO *&gt; llvm::MCContext::MachOUniquingMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### MacroMap {#aae19dd8e06b15983218d42c7fc8fcf62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;MCAsmMacro&gt; llvm::MCContext::MacroMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map of currently defined macros.</p>

<p>Definition at line 367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### MAI {#ae7d5f0cd4a3f3b0d69e4d5fd69d02b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmInfo* llvm::MCContext::MAI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> for this target.</p>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### MainFileName {#a46376eb91a04b67b80b79ed65dd9dc98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCContext::MainFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The main file name if passed in explicitly.</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### MCDwarfLineTablesCUMap {#ad6c20ea7c44a6fdd34d846f6897bd4d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;unsigned, MCDwarfLineTable&gt; llvm::MCContext::MCDwarfLineTablesCUMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The dwarf file and directory tables from the dwarf .file directive.</p>


<p>We now emit a line table for each compile unit. To reduce the prologue size of each line table, the files and directories used by each compile unit are separated.</p>


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### MCGenDwarfLabelEntries {#a0fdfe1eeda5abd27a9efbcac5a08901e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MCGenDwarfLabelEntry&gt; llvm::MCContext::MCGenDwarfLabelEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The information gathered from labels that will have dwarf label entries when generating dwarf assembly source files.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### MCInstAllocator {#acfcbd3a1813581fc143f4c444387021d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;MCInst&gt; llvm::MCContext::MCInstAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### MCSubtargetAllocator {#a295558fbb50b7592b675f48576cbc30e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;MCSubtargetInfo&gt; llvm::MCContext::MCSubtargetAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### MOFI {#a4ca01892cfc3ef7303890c6bad2d5f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCObjectFileInfo* llvm::MCContext::MOFI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo">MCObjectFileInfo</a> for this target.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### MRI {#a47962f3c52b02d1d5863a41e16511fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo* llvm::MCContext::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> for this target.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### MSTI {#a57f7a9f5d61d1bde9a49ac168fef57bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo* llvm::MCContext::MSTI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> for this target.</p>

<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### PseudoProbeTable {#a25735ebc2cbcdb606d00fc8a5c8a59af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCPseudoProbeTable llvm::MCContext::PseudoProbeTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A collection of <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe">MCPseudoProbe</a> in the current module.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### RelSecNames {#aba4274a071653f74e69cceb94bf31fb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;bool&gt; llvm::MCContext::RelSecNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### SaveTempLabels {#a8ccab89113e7e09eaf482c6637ea1af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::SaveTempLabels = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Honor temporary labels, this is useful for debugging semantic differences between temporary and non-temporary labels (primarily on Darwin).</p>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### SectionsForRanges {#a5b155d59ed55163f930e86eadf876131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SetVector&lt;MCSection *&gt; llvm::MCContext::SectionsForRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sections for generating the .debug_ranges and .debug_aranges sections.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### SecureLog {#a39380cb9306a7c54dadd2476f762e15c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;raw_fd_ostream&gt; llvm::MCContext::SecureLog</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The stream that gets written to for the .secure_log_unique directive.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### SecureLogFile {#aaf885909270b643032f372e1d2291f99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::MCContext::SecureLogFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The file name of the log file from the environment variable AS_SECURE_LOG_FILE.</p>


<p>Which must be set before the .secure_log_unique directive is used or it is an error.</p>


<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### SecureLogUsed {#aeff0ee85b13469673dfa70aa060ce364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::SecureLogUsed = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/#a965a7b0afb2678973d155a103b9f55b5">Boolean</a> toggled when .secure_log_unique / .secure_log_reset is seen to catch errors if .secure_log_unique appears twice without .secure_log_reset appearing between them.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### SPIRVAllocator {#ab1583bcc9441392c28eba4dd53685442}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;MCSectionSPIRV&gt; llvm::MCContext::SPIRVAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### SrcMgr {#a686f12dafe63bd82ac22966b5ee84f0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SourceMgr* llvm::MCContext::SrcMgr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> for this object, if any.</p>

<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### Swift5ReflectionSegmentName {#a6c464ed6da56954cc0fe67758841ee56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCContext::Swift5ReflectionSegmentName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The name of the Segment where Swift5 Reflection Section data will be outputted.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### Symbols {#aea769589411147fd0d5c755d21b9dbc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolTable llvm::MCContext::Symbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bindings of names to symbol table values.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### TargetOptions {#ad3ffde0bd3e3d104ce2cd905a5dd3906}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCTargetOptions const* llvm::MCContext::TargetOptions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### TT {#ab593b067786e5d4b65500e0b1b2c23ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::MCContext::TT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The triple for this object.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### UseNamesOnTempLabels {#ae06e3bee1e9d3d454216aa39da258a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::UseNamesOnTempLabels = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### WasmAllocator {#a7c03efeca91236bbf231040635140285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;MCSectionWasm&gt; llvm::MCContext::WasmAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### WasmSignatureAllocator {#ae51525ab840d0eef02cb81e0539dcb5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;wasm::WasmSignature&gt; llvm::MCContext::WasmSignatureAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### WasmUniquingMap {#a283bebbc7deb168dec8e30f433c79d29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;WasmSectionKey, MCSectionWasm *&gt; llvm::MCContext::WasmUniquingMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### XCOFFAllocator {#a41ad4abda75e1683b2d3adaeba3a9892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;MCSectionXCOFF&gt; llvm::MCContext::XCOFFAllocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### XCOFFUniquingMap {#a1cf50f5dc48a48c4e84061f6d6f8f25e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;XCOFFSectionKey, MCSectionXCOFF *&gt; llvm::MCContext::XCOFFUniquingMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Section Management

### anonymous enum  {#aa96980c44bc03ccd7b7b1fde53bc1f7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
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
<td class="doxyEnumItemName">GenericSectionID<a id="aa96980c44bc03ccd7b7b1fde53bc1f7da62fb23a196d73b6c068b55048cc02008"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> this value as the <a href="/web-llvm/docs/api/classes/uniqueid">UniqueID</a> during section creation to get the generic section with the given name and characteristics (= ~0U)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### createELFGroupSection {#adf2235eabe74d3b9ee0314b91b71ee06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionELF * MCContext::createELFGroupSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> * Group, bool IsComdat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a57a444303c725373f3a4c2cba82e548c">llvm::MCSection::NonUniqueID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ab23570002b1ab10a685e8f349da3ddbca1771b2365460420ea3aee1fa4c324c99">llvm::ELF::SHT_GROUP</a>.</p>

</div>
</div>

### createELFRelSection {#a2e5dc7053e3ede207302a8e223953743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionELF * MCContext::createELFRelSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, unsigned Type, unsigned Flags, unsigned EntrySize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> * Group, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsectionelf">MCSectionELF</a> * RelInfoSection)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getAssociativeCOFFSection {#aef93e9316e910cbb64002e1cdfad0f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionCOFF * MCContext::getAssociativeCOFFSection (<a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff">MCSectionCOFF</a> * Sec, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * KeySym, unsigned UniqueID=<a href="#aa96980c44bc03ccd7b7b1fde53bc1f7da62fb23a196d73b6c068b55048cc02008">GenericSectionID</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets or creates a section equivalent to Sec that is associated with the section containing KeySym.</p>


<p>For example, to create a debug info section associated with an inline function, pass the normal debug info section as Sec and the function symbol as KeySym.</p>


<p>Declaration at line 623 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="#aa96980c44bc03ccd7b7b1fde53bc1f7da62fb23a196d73b6c068b55048cc02008">GenericSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectioncoff/#a95a2d54946c994b25c9b83d63cbd588b">llvm::MCSectionCOFF::getCharacteristics</a>, <a href="#a64fec16b33fa7f23710afb8904948f30">getCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#aac4366cca0c8d3cd472a02a71f4aa34c">llvm::MCSection::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#abb2a5b3cc2301597c2ffed2e4b04f45ea85161daa9965cdbe86d035f42c2c65ed">llvm::COFF::IMAGE_COMDAT_SELECT_ASSOCIATIVE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a45c610228e069b0b3efbcbc1d5577f5aa86b861e119d7e8b4bf5d9664671667ca">llvm::COFF::IMAGE_SCN_LNK_COMDAT</a>.</p>

</div>
</div>

### getBBAddrMapVersion {#a4967f1d9be0ff3a0b2beec4532c0de98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MCContext::getBBAddrMapVersion ()</td>
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



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### getCOFFSection {#a64fec16b33fa7f23710afb8904948f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionCOFF * MCContext::getCOFFSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, unsigned Characteristics, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> COMDATSymName, int Selection, unsigned UniqueID=<a href="#aa96980c44bc03ccd7b7b1fde53bc1f7da62fb23a196d73b6c068b55048cc02008">GenericSectionID</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="#ac11eef690074972378846024abbe8722">getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#ab7d669d1338ce8b4ddf910da10c51607">llvm::MCSymbol::getSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#abb2a5b3cc2301597c2ffed2e4b04f45ea85161daa9965cdbe86d035f42c2c65ed">llvm::COFF::IMAGE_COMDAT_SELECT_ASSOCIATIVE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a2899e74730516967f04d81966bb4f881">llvm::MCSymbol::isDefined</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a3214f95c05e3d2af5e3e56667dc54239">llvm::MCSymbol::isInSection</a>, <a href="#aac3107671801e6bb16ef896f382759cd">reportError</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuiseldagtodag-cpp/#a8953acfc4842c48f4032935d47dbf4a1">Selection</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a59bf6e97f0f02573b74d322186c91327">llvm::MCSymbol::setFragment</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#aef93e9316e910cbb64002e1cdfad0f01">getAssociativeCOFFSection</a>, <a href="#aca28d2a04b948a01f9401075b0db725d">getCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a1d07788150d8bd44cbba78db405f1574">llvm::TargetLoweringObjectFileCOFF::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a300546d54aa331d7615052bd9ba5883d">llvm::TargetLoweringObjectFileCOFF::getSectionForConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#ad75e2aa4d67c101594e1f7448588c8d3">llvm::TargetLoweringObjectFileCOFF::getSectionForJumpTable</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a5835f5de3b78527c3348c7346c197b69">llvm::TargetLoweringObjectFileCOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getCOFFSection {#aca28d2a04b948a01f9401075b0db725d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionCOFF * MCContext::getCOFFSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, unsigned Characteristics)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 728 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="#aa96980c44bc03ccd7b7b1fde53bc1f7da62fb23a196d73b6c068b55048cc02008">GenericSectionID</a> and <a href="#a64fec16b33fa7f23710afb8904948f30">getCOFFSection</a>.</p>

</div>
</div>

### getDXContainerSection {#abbd17835611b883adf6f7dcc6d2eca0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionDXContainer * MCContext::getDXContainerSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the section for the provided Section name.</p>

<p>Declaration at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 872 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/dxiltargetobjectfile/#ae6c346fad803c016b4709a8a6e9deeda">DXILTargetObjectFile::getExplicitSectionGlobal</a>.</p>

</div>
</div>

### getELFNamedSection {#a3dafd75134861ffaa0f5f26e6ae5945a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionELF * MCContext::getELFNamedSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Prefix, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Suffix, unsigned Type, unsigned Flags, unsigned EntrySize=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a section with the provided group identifier.</p>


<p>This section is named by concatenating <span class="doxyComputerOutput">Prefix</span> with '.' then <span class="doxyComputerOutput">Suffix</span>. The <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></span> describes the type of the section and <span class="doxyComputerOutput">Flags</span> are used to further configure this named section.</p>


<p>Declaration at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="#a3fddc32fd70ea36b8482c9055eb68c40">getELFSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a6d60dc7f70a5ab7a44c79f6bba354c0f">llvm::TargetLoweringObjectFileELF::emitPersonalityValue</a>.</p>

</div>
</div>

### getELFSection {#a3fddc32fd70ea36b8482c9055eb68c40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionELF * llvm::MCContext::getELFSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Section, unsigned Type, unsigned Flags)</td>
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



<p>Definition at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="#a3fddc32fd70ea36b8482c9055eb68c40">getELFSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a29a3c5dc6082aabd411724f33011f795">llvm::MCELFStreamer::emitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfstreamer/#a21d50101946fb3648d4d662a0e1d0406">llvm::MCELFStreamer::emitIdent</a>, <a href="/web-llvm/docs/api/classes/anonymous-erlanggcprinter-cpp-/erlanggcprinter/#a574679a34186d5db3a7b14b0ce5c5078">anonymous{ErlangGCPrinter.cpp}::ErlangGCPrinter::finishAssembly</a>, <a href="#a3dafd75134861ffaa0f5f26e6ae5945a">getELFNamedSection</a>, <a href="#a3fddc32fd70ea36b8482c9055eb68c40">getELFSection</a>, <a href="#a3fb2ccf37b0ca8de3cbecdd5d84918e0">getELFSection</a>, <a href="#a3ee35c67e483d503d4f72dc5e0e4b368">getELFSection</a>, <a href="#abfbfa4b8157b753fa4ea370e8ffc8177">getELFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#acf4019263b41c295bc55032dd651b6e4">llvm::HexagonTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/xcoretargetobjectfile/#a820356be1c79740facb142ac6eaa9e39">llvm::XCoreTargetObjectFile::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#ac81b774f768883eac6a9d46cdc8b82a8">llvm::TargetLoweringObjectFileELF::getSectionForCommandLines</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#ac8b6405ee0ca88cdcd7aea5d129551c4">llvm::TargetLoweringObjectFileELF::getSectionForLSDA</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#ae5ed3bb52c2c0b532692d33df8dd705f">llvm::TargetLoweringObjectFileELF::getSectionForMachineBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonmcelfstreamer/#a64f1accd42a5eb6c0d80c800e63123b9">llvm::HexagonMCELFStreamer::HexagonMCEmitCommonSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetobjectfile/#a6cf97a009c47b155189ba67312aa6054">llvm::HexagonTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaitargetobjectfile/#ab6f22139bb2e11e60a30bb572dfcf5a2">llvm::LanaiTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kelftargetobjectfile/#acb04f79feb01601c3da467d19ea03b9f">llvm::M68kELFTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetobjectfile/#ae3a8326eff629fec000d741c44b730bd">llvm::MipsTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#ac2e30a188970123389a986eb645ed6c7">llvm::RISCVELFTargetObjectFile::Initialize</a>, <a href="/web-llvm/docs/api/classes/llvm/msp430targetelfstreamer/#a08e72085c1973f94f76c4444c65e35e5">llvm::MSP430TargetELFStreamer::MSP430TargetELFStreamer</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvelftargetobjectfile/#a56f18a5c4bcd2858f20bb765323fc89a">llvm::RISCVELFTargetObjectFile::SelectSectionForGlobal</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>.</p>

</div>
</div>

### getELFSection {#a3fb2ccf37b0ca8de3cbecdd5d84918e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionELF * llvm::MCContext::getELFSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Section, unsigned Type, unsigned Flags, unsigned EntrySize)</td>
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



<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>References <a href="#a3fddc32fd70ea36b8482c9055eb68c40">getELFSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a57a444303c725373f3a4c2cba82e548c">llvm::MCSection::NonUniqueID</a>.</p>

</div>
</div>

### getELFSection {#a3ee35c67e483d503d4f72dc5e0e4b368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionELF * llvm::MCContext::getELFSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Section, unsigned Type, unsigned Flags, unsigned EntrySize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Group, bool IsComdat)</td>
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



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>References <a href="#a3fddc32fd70ea36b8482c9055eb68c40">getELFSection</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a57a444303c725373f3a4c2cba82e548c">llvm::MCSection::NonUniqueID</a>.</p>

</div>
</div>

### getELFSection {#abfbfa4b8157b753fa4ea370e8ffc8177}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionELF * MCContext::getELFSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Section, unsigned Type, unsigned Flags, unsigned EntrySize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Group, bool IsComdat, unsigned UniqueID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> * LinkedToSym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 559 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a3fddc32fd70ea36b8482c9055eb68c40">getELFSection</a>, <a href="#ac11eef690074972378846024abbe8722">getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a771462b870698fdc4c2484b78ce96f6d">llvm::Twine::isTriviallyEmpty</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a>.</p>

</div>
</div>

### getELFSection {#a84ea0567e15790f68c421dada011ec5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionELF * MCContext::getELFSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Section, unsigned Type, unsigned Flags, unsigned EntrySize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> * Group, bool IsComdat, unsigned UniqueID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolelf">MCSymbolELF</a> * LinkedToSym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 575 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::native</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsection/#a57a444303c725373f3a4c2cba82e548c">llvm::MCSection::NonUniqueID</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a35965f6177893c536dcf4e924b387613">recordELFMergeableSectionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#add1f2d1d972957d22186f4ec92f985f6">llvm::support::endian::write</a>.</p>

</div>
</div>

### getELFUniqueIDForEntsize {#a976e91f3dbcff07e94ea94fe83d0c926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; unsigned &gt; MCContext::getELFUniqueIDForEntsize (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, unsigned Flags, unsigned EntrySize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the unique <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the section with the given name, flags and entry size, if it exists.</p>

<p>Declaration at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getGOFFSection {#a82203778666af1baa04dec0f8791f26f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionGOFF * MCContext::getGOFFSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Parent, uint32_t Subsection=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 674 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilegoff/#a75c01c604ceb3f4e3a45c6ee4df1985f">llvm::TargetLoweringObjectFileGOFF::getSectionForLSDA</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilegoff/#a8c58f11a5aa16a65fa81203993787033">llvm::TargetLoweringObjectFileGOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### getMachOSection {#a0842bdee75832f17fb2b6a6199d1cc4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionMachO * MCContext::getMachOSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Segment, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, unsigned TypeAndAttributes, unsigned Reserved2, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * BeginSymName=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> for the specified mach-o section.</p>


<p>This requires the operands to be valid.</p>


<p>Declaration at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a299bf2f0329389424760f4a7c8af75ac">createTempSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a7bdbc0657e52a4bffa675c290b32840f">llvm::TargetLoweringObjectFileMachO::emitModuleMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86asmprinter-cpp/#acda48e0ba94e27f00cbe44c1585fcfe7">emitNonLazyStubs</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a5e9dfc1cc5890ea9fb55b1dedcc2bd27">llvm::TargetLoweringObjectFileMachO::getExplicitSectionGlobal</a>, <a href="#af04e69d878824d996d620bcce1363a39">getMachOSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a8df1069695195b5c96f1cc2ebf3a3973">llvm::TargetLoweringObjectFileMachO::getSectionForCommandLines</a>.</p>

</div>
</div>

### getMachOSection {#af04e69d878824d996d620bcce1363a39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionMachO * llvm::MCContext::getMachOSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Segment, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, unsigned TypeAndAttributes, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * BeginSymName=nullptr)</td>
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



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="#a0842bdee75832f17fb2b6a6199d1cc4d">getMachOSection</a>.</p>

</div>
</div>

### getSPIRVSection {#acffc1b92965b5c7cddb78486106ba384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionSPIRV * MCContext::getSPIRVSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 865 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### getSubtargetCopy {#a05939d944f98272791751dca10bb9f70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSubtargetInfo &amp; MCContext::getSubtargetCopy (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; STI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 892 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a1f36fcf8463068f9a2d25b02411c08b9">llvm::MCTargetAsmParser::copySTI</a>.</p>

</div>
</div>

### getWasmSection {#a354ee5b1baec10051b0d9da350bfe027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionWasm * llvm::MCContext::getWasmSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Section, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K, unsigned Flags=0)</td>
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



<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="#a354ee5b1baec10051b0d9da350bfe027">getWasmSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#ad7fddd197449964ffb791c5a7e1900ec">llvm::TargetLoweringObjectFileWasm::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#a5b6997ec5b6f4358e270f2e5d9be4657">llvm::TargetLoweringObjectFileWasm::getStaticCtorSection</a>, <a href="#aec55174841f8aa80f2d1c3f56c4165af">getWasmSection</a>, <a href="#a354ee5b1baec10051b0d9da350bfe027">getWasmSection</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilewasm/#a43cbf327e1543318ec8d7a084634995a">llvm::TargetLoweringObjectFileWasm::InitializeWasm</a>.</p>

</div>
</div>

### getWasmSection {#aec55174841f8aa80f2d1c3f56c4165af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionWasm * MCContext::getWasmSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Section, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K, unsigned Flags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Group, unsigned UniqueID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 752 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ac11eef690074972378846024abbe8722">getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#af3dcaf743b04a6ee2c241b2259959b4a">llvm::MCSymbolWasm::getType</a>, <a href="#a354ee5b1baec10051b0d9da350bfe027">getWasmSection</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a771462b870698fdc4c2484b78ce96f6d">llvm::Twine::isTriviallyEmpty</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a1b2eeed02c99b34cc1252ad86bb34b69">llvm::MCSymbolWasm::setComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm/#a817a67945b1632513e9b43ca0da9aacd">llvm::MCSymbolWasm::setType</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#a4c1c1093a7749409c70838678514cc7c">llvm::Twine::str</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ad7d988e101231ece62ebfe7d06884a1f">llvm::wasm::WASM_SYMBOL_TYPE_SECTION</a>.</p>

</div>
</div>

### getWasmSection {#ad715fadab36063fc73cd1c87d0fcc636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionWasm * MCContext::getWasmSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Section, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K, unsigned Flags, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbolwasm">MCSymbolWasm</a> * Group, unsigned UniqueID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 769 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a59bf6e97f0f02573b74d322186c91327">llvm::MCSymbol::setFragment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a6ee7ebc24e11c434031e9653d7f00529ad7d988e101231ece62ebfe7d06884a1f">llvm::wasm::WASM_SYMBOL_TYPE_SECTION</a>.</p>

</div>
</div>

### getXCOFFSection {#a435597fd04ebfd9b5fb5708a4309febb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSectionXCOFF * MCContext::getXCOFFSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, <a href="/web-llvm/docs/api/classes/llvm/sectionkind">SectionKind</a> K, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/xcoff/csectproperties">XCOFF::CsectProperties</a> &gt; CsectProp=std::nullopt, bool MultiSymbolsAllowed=false, std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a0456b0e88222c998e39b69d80338a440">XCOFF::DwarfSectionSubtypeFlags</a> &gt; DwarfSubtypeFlags=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 647 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 805 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a5108aa1d02847a41b154cf255a52348b">llvm::XCOFF::getMappingClassString</a>, <a href="#ac11eef690074972378846024abbe8722">getOrCreateSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolxcoff/#a6a8c201e99f1acf8f6cdc654093c0a61">llvm::MCSymbolXCOFF::getUnqualifiedName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsectionxcoff/#a0ce795092c33264940541697d9e73e61">llvm::MCSectionXCOFF::isMultiSymbolsAllowed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a59bf6e97f0f02573b74d322186c91327">llvm::MCSymbol::setFragment</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502cac7850ad5e926ed392928b68832be764e">llvm::XCOFF::XMC_PR</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a6027e9f6e624a2ac869c29f803baa739">llvm::TargetLoweringObjectFileXCOFF::getExplicitSectionGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a3e40bda8245f90bbe4a72d083b4d8431">llvm::TargetLoweringObjectFileXCOFF::getFunctionEntryPointSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a2ddf5387f9cd603891e1933c2f84cf65">llvm::TargetLoweringObjectFileXCOFF::getSectionForExternalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#adee710107b7fec9dcf8076bd0dc44d2d">llvm::TargetLoweringObjectFileXCOFF::getSectionForFunctionDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a59f70e2f83b2a97372e18a6c6316550d">llvm::TargetLoweringObjectFileXCOFF::getSectionForJumpTable</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#afff1a14d07c4f0d35848b797930090c6">llvm::TargetLoweringObjectFileXCOFF::getSectionForLSDA</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a24e99c9fbb9fedd3a9b504d09ddfa21b">llvm::TargetLoweringObjectFileXCOFF::getSectionForTOCEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#afa6dda813be79bdc7753ef52b9b5ec56">llvm::TargetLoweringObjectFileXCOFF::SelectSectionForGlobal</a>.</p>

</div>
</div>

### hasXCOFFSection {#abdef71fa8592899f0266affccef0e45e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCContext::hasXCOFFSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Section, <a href="/web-llvm/docs/api/structs/llvm/xcoff/csectproperties">XCOFF::CsectProperties</a> CsectProp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/xcoff/csectproperties/#a20c6bfb7b6568e57998b16592f74c756">llvm::XCOFF::CsectProperties::MappingClass</a>.</p>

</div>
</div>

### isELFGenericMergeableSection {#a85e0ab8f47856461c14ee5f263e79999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCContext::isELFGenericMergeableSection (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="#ad9c510b9c8ab206680f3fe62f346046a">isELFImplicitMergeableSectionNamePrefix</a>.</p>


<p>Referenced by <a href="#a35965f6177893c536dcf4e924b387613">recordELFMergeableSectionInfo</a>.</p>

</div>
</div>

### isELFImplicitMergeableSectionNamePrefix {#ad9c510b9c8ab206680f3fe62f346046a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCContext::isELFImplicitMergeableSectionNamePrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Referenced by <a href="#a85e0ab8f47856461c14ee5f263e79999">isELFGenericMergeableSection</a>.</p>

</div>
</div>

### recordELFMergeableSectionInfo {#a35965f6177893c536dcf4e924b387613}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::recordELFMergeableSectionInfo (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SectionName, unsigned Flags, unsigned UniqueID, unsigned EntrySize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="#aa96980c44bc03ccd7b7b1fde53bc1f7da62fb23a196d73b6c068b55048cc02008">GenericSectionID</a>, <a href="#a85e0ab8f47856461c14ee5f263e79999">isELFGenericMergeableSection</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a5def04786ab543821414e3d5f609e015a0e54850eb2f8e74ae549f6dd70926723">llvm::ELF::SHF_MERGE</a>.</p>


<p>Referenced by <a href="#a84ea0567e15790f68c421dada011ec5f">getELFSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Module Lifetime Management

### reset {#a8197434a9fa5a233ebc553cda3101ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>reset - return object to right after construction state to prepare to process a new module</p>

<p>Declaration at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp/#a4c4cc7fd1400fb03f06f4254fc03db53">defaultDiagHandler</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h/#a377ba69923635f8154cad5784be89ff6">DWARF2_FLAG_IS_STMT</a>.</p>


<p>Referenced by <a href="#a75b7ed17686752b3420b0ad6ffb6c726">~MCContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## McInst Management

### allocFragment {#aed79db19d00f742ef88eafad5b074be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename F, typename... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">F * llvm::MCContext::allocFragment (Args &amp;&amp;... args)</td>
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



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a6f19f34683888bee863e73af9a082535">llvm::MCObjectStreamer::changeSectionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe/#a4fbe96db8448f1711fd51c4f4601c063">llvm::MCPseudoProbe::emit</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a38dcf42330d1efcd03d0686ba7bbaf1d">anonymous{X86AsmBackend.cpp}::X86AsmBackend::emitInstructionBegin</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#a8c9b4bc17f742123fb67a743e46e11bc">anonymous{X86AsmBackend.cpp}::X86AsmBackend::emitInstructionEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a970c047f65898d76cc9a251f32a5b70c">llvm::MCObjectStreamer::emitInstToFragment</a> and <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a3558114ca72d34962abb28004d864b19">llvm::MCObjectStreamer::getOrCreateDataFragment</a>.</p>

</div>
</div>

### createMCInst {#a2b751cce960c243db7372dc393d67883}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInst * MCContext::createMCInst ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create and return a new MC instruction.</p>

<p>Declaration at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a77ac85fa1d774b4d1f5a064e1b8ee8c3">llvm::HexagonLowerToMC</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Symbol Management

### createBlockSymbol {#a03742cf8aa97edf5612a800e4f159876}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::createBlockSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, bool AlwaysEmit=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get or create a symbol for a basic block.</p>


<p>For non-always-emit symbols, this behaves like createTempSymbol, except that it uses the PrivateLabelPrefix instead of the PrivateGlobalPrefix. When AlwaysEmit is true, behaves like getOrCreateSymbol, prefixed with PrivateLabelPrefix.</p>


<p>Declaration at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="#ac11eef690074972378846024abbe8722">getOrCreateSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a78b12ba4209266f4d26fa513c576ee18">llvm::MachineBasicBlock::getEndSymbol</a>.</p>

</div>
</div>

### createDirectionalLocalSymbol {#a97cbccbfd2f64e098e0005ee9fdd943c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::createDirectionalLocalSymbol (unsigned LocalLabelVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create the definition of a directional local symbol for numbered label (used for "1:" definitions).</p>

<p>Declaration at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### createLinkerPrivateSymbol {#ac24bf3fc8a5d5546cdda06886e305c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::createLinkerPrivateSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Referenced by <a href="#a331b0cec2bd2881f3383a47f4e0deec0">createLinkerPrivateTempSymbol</a>.</p>

</div>
</div>

### createLinkerPrivateTempSymbol {#a331b0cec2bd2881f3383a47f4e0deec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::createLinkerPrivateTempSymbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new linker temporary symbol with the specified prefix (Name) or "tmp".</p>


<p>This creates a "l"-prefixed symbol for Mach-O and is identical to createNamedTempSymbol for other object file formats.</p>


<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 335 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="#ac24bf3fc8a5d5546cdda06886e305c95">createLinkerPrivateSymbol</a>.</p>

</div>
</div>

### createLocalSymbol {#a57c17c36da95d81b14dc348d3f6102ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::createLocalSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a local, non-temporary symbol like an <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> mapping symbol.</p>


<p>Calling the function with the same name will generate new, unique instances.</p>


<p>Declaration at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### createNamedTempSymbol {#aff468f9432c24e89b881976f5e1f9cf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::createNamedTempSymbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a temporary symbol with a unique name whose name cannot be omitted in the symbol table.</p>


<p>This is rarely used.</p>


<p>Declaration at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 347 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="#aff468f9432c24e89b881976f5e1f9cf8">createNamedTempSymbol</a>.</p>


<p>Referenced by <a href="#aff468f9432c24e89b881976f5e1f9cf8">createNamedTempSymbol</a>.</p>

</div>
</div>

### createNamedTempSymbol {#a58961f1ac4c43b9709824a686262b0b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::createNamedTempSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 319 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### createTempSymbol {#a299bf2f0329389424760f4a7c8af75ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::createTempSymbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a temporary symbol with a unique name.</p>


<p>The name will be omitted in the symbol table if UseNamesOnTempLabels is false (default except MCAsmStreamer). The overload without Name uses an unspecified name.</p>


<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="#a299bf2f0329389424760f4a7c8af75ac">createTempSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeviewcontext/#a63aca47ba5a5a2895c8ffd1e262ced59">llvm::CodeViewContext::addFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a0bd3fbe76161d42d7470f0dd7dd634de">ARM64EmitUnwindInfoForSegment</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#ab831cd4cdeb2330513a8ca4d3ad3f610">ARMEmitUnwindInfo</a>, <a href="#a299bf2f0329389424760f4a7c8af75ac">createTempSymbol</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a7a47959229fe5c4aadbc877fc12e4ba6">llvm::MipsELFStreamer::emitCFIEndProcImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a94cdaca7695af6f6b02f54297384088d">llvm::MipsELFStreamer::emitCFILabel</a>, <a href="/web-llvm/docs/api/classes/llvm/mipselfstreamer/#a4048731284da0f5852f82e4032569370">llvm::MipsELFStreamer::emitCFIStartProcImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a61b27602b6cd429e5c1e226117c6da67">llvm::MCObjectStreamer::emitCVLocDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsasmprinter-cpp/#a487192753b68b0e4380e9d999a5b1549">emitDirectiveRelocJalr</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>, <a href="/web-llvm/docs/api/classes/anonymous-armelfstreamer-cpp-/armelfstreamer/#a79dfbf2591108f9b5c846187ec905eef">anonymous{ARMELFStreamer.cpp}::ARMELFStreamer::emitFnStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a03e59500b09326087aab0f3aa60a1491">llvm::MCStreamer::emitLineTableLabel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzasmprinter-cpp/#ada3b3b8c611fe7959f11bf477afd0b6e">EmitNop</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcwin64eh-cpp/#a5d75ea3f9831315ebdb816d70c58c30b">EmitUnwindInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#aab2cc2813c5a774bb4f83b6f9ae5a98b">llvm::AArch64_MachoTargetObjectFile::getIndirectSymViaGOTPCRel</a>, <a href="#a0842bdee75832f17fb2b6a6199d1cc4d">getMachOSection</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64-machotargetobjectfile/#abda04e72e43a3aaef8a55e4ecf91d127">llvm::AArch64_MachoTargetObjectFile::getTTypeGlobalReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#ac1cd29692079a1f57202b9947c5f5521">llvm::TargetLoweringObjectFile::getTTypeReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarflabelentry/#a741d0c6e829f284182bd9bbef0362e2d">llvm::MCGenDwarfLabelEntry::Make</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineentry/#a7e7c37719e68c7bf9e494110a30cad90">llvm::MCDwarfLineEntry::make</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86indirectthunks-cpp-/retpolinethunkinserter/#aceed22e00e1b77a1a8cab4ac045d6a21">anonymous{X86IndirectThunks.cpp}::RetpolineThunkInserter::populateThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>.</p>

</div>
</div>

### createTempSymbol {#aab004175805bb32f89cdd49bca178e25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::createTempSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name, bool AlwaysAddSuffix=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### createWasmSignature {#a3d3a0ff7d64b165758e5fb15be26279a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">wasm::WasmSignature * MCContext::createWasmSignature ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allocates and returns a new <span class="doxyComputerOutput">WasmSignature</span> instance (with empty parameter and return type lists).</p>

<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### getDirectionalLocalSymbol {#afb8a5e63fad89ccba5fee1f314d644b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::getDirectionalLocalSymbol (unsigned LocalLabelVal, bool Before)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create and return a directional local symbol for numbered label (used for "1b" or 1f" references).</p>

<p>Declaration at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>.</p>

</div>
</div>

### getInlineAsmLabel {#a392412e22be62f31478cfca07d562055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * llvm::MCContext::getInlineAsmLabel (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>isInlineAsmLabel - Return true if the name is a label referenced in inline assembly.</p>

<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>.</p>

</div>
</div>

### getOrCreateFrameAllocSymbol {#a2d5af327caeae379919145f09cd51341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::getOrCreateFrameAllocSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; FuncName, unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets a symbol that will be defined to the final stack offset of a local variable after codegen.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Idx</td>
<td class="doxyParamItemDescription"><p>- The index of a local variable passed to @llvm.localescape.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="#ac11eef690074972378846024abbe8722">getOrCreateSymbol</a>.</p>

</div>
</div>

### getOrCreateLSDASymbol {#ab9961367ad9649b3df25a31117bba067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::getOrCreateLSDASymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; FuncName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="#ac11eef690074972378846024abbe8722">getOrCreateSymbol</a>.</p>

</div>
</div>

### getOrCreateParentFrameOffsetSymbol {#a6e31ab123dec096ae41bbd8cbb73e036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::getOrCreateParentFrameOffsetSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; FuncName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="#ac11eef690074972378846024abbe8722">getOrCreateSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adfeaf9db4445cbd2d43f260218036006">recoverFramePointer</a>.</p>

</div>
</div>

### getOrCreateSymbol {#ac11eef690074972378846024abbe8722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::getOrCreateSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lookup the symbol inside with the specified <span class="doxyComputerOutput">Name</span>.</p>


<p>If it exists, return it. If not, create a forward reference and return it.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>- The symbol name, which must be unique across all symbols.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mipstargetlowering/#a8c0a6f5ad327c20349f2a2e0a5845b3e">llvm::MipsTargetLowering::AdjustInstrPostInstrSelection</a>, <a href="#a03742cf8aa97edf5612a800e4f159876">createBlockSymbol</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/ocamlgcprinter-cpp/#aa776a466c28ef5250df0206206360b8c">EmitCamlGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a886df281f466da825e86d3db00309322">llvm::MCStreamer::emitCFILabelDirective</a>, <a href="/web-llvm/docs/api/classes/llvm/mipstargetelfstreamer/#a1760c43fadfe8ae62e75e7debd68fad5">llvm::MipsTargetELFStreamer::emitDirectiveCpLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a36948c65344166574c860990801dc0a2">llvm::MCDwarfLineTable::endCurrentSeqAndEmitLineStreamLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#ae36c2a9293b9a50a2870d02f93d7d202">llvm::RecordStreamer::flushSymverDirectives</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfileelf/#a4969e899dcb64a6d45ddc42b5bf4f236">llvm::TargetLoweringObjectFileELF::getCFIPersonalitySymbol</a>, <a href="#a64fec16b33fa7f23710afb8904948f30">getCOFFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a210ccb5b83a717a8dce63cd7602a58b6">llvm::MachineBasicBlock::getEHCatchretSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a5d1987fcd07a91cbecea1c8ea8f174d3">llvm::TargetLoweringObjectFileXCOFF::getEHInfoTableSymbol</a>, <a href="#abfbfa4b8157b753fa4ea370e8ffc8177">getELFSection</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilexcoff/#a3e40bda8245f90bbe4a72d083b4d8431">llvm::TargetLoweringObjectFileXCOFF::getFunctionEntryPointSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a2455497c6e33bcd6363fbecc2fe00f0a">llvm::PPCFunctionInfo::getGlobalEPSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a265951c79bd6867cd86f173112f3cc55">llvm::PPCFunctionInfo::getLocalEPSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a5e13c8211ac78de4ed02bd7facb5c18f">llvm::MCResourceInfo::getMaxAGPRSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#a43e26b05f46ee6277cdb509e6e264304">llvm::MCResourceInfo::getMaxSGPRSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#acdfa9217c601394fde2e02fbbfb5aff4">llvm::MCResourceInfo::getMaxVGPRSymbol</a>, <a href="#a2d5af327caeae379919145f09cd51341">getOrCreateFrameAllocSymbol</a>, <a href="#ab9961367ad9649b3df25a31117bba067">getOrCreateLSDASymbol</a>, <a href="#a6e31ab123dec096ae41bbd8cbb73e036">getOrCreateParentFrameOffsetSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a123bd4a5c86831ea657817f781102eaf">llvm::PPCFunctionInfo::getPICOffsetSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/mcresourceinfo/#ab6fb66900168f71c259a40c4213258ee">llvm::MCResourceInfo::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#acc39c2b4b06165d766b52ac292ef2aff">llvm::TargetMachine::getSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfile/#a866133bf888d0b8bbce2275845511edb">llvm::TargetLoweringObjectFile::getSymbolWithGlobalValueBase</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#a95a4a415a083d19b0a8f92cabb81c720">llvm::PPCFunctionInfo::getTOCOffsetSymbol</a>, <a href="#aec55174841f8aa80f2d1c3f56c4165af">getWasmSection</a>, <a href="#a435597fd04ebfd9b5fb5708a4309febb">getXCOFFSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#acb5fd683cbbfb19a2e0d78ee46bb283c">llvm::MCAsmParserExtension::parseDirectiveCGProfile</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a02bbdeea1375089f06a52747e919b4dc">anonymous{AsmParser.cpp}::AsmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a48e574342f9028f1077132c27267952b">anonymous{MasmParser.cpp}::MasmParser::parsePrimaryExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a034b546ea133319ab2244f9bfa28ecae">anonymous{AsmParser.cpp}::AsmParser::parseStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguardlongjmp-cpp-/cfguardlongjmp/#a17b3d486f52582c92dec4b050aedb70a">anonymous{CFGuardLongjmp.cpp}::CFGuardLongjmp::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/faultmaps/#a393b0f5b51aef71d44cc36b4e7b048a7">llvm::FaultMaps::serializeToFaultMapSection</a>, <a href="/web-llvm/docs/api/classes/llvm/stackmaps/#a64f17d34c6ec33d574438b69fa43c2e2">llvm::StackMaps::serializeToStackMapSection</a>, <a href="#a21aceafe085b9a14a9864954b9fdb14b">setSymbolValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonasmprinter-cpp/#a462520f520e196eb7d97d2077f86a8e2">smallData</a>.</p>

</div>
</div>

### getSymbols {#aa3a724ff67c13baf6feab0902b175204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SymbolTable &amp; llvm::MCContext::getSymbols ()</td>
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

<p>getSymbols - Get a reference for the symbol table for clients that want to, for example, iterate over all symbols.</p>


<p>'const' because we still want any modifications to the table itself to use the <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> APIs.</p>


<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### lookupSymbol {#a7099c67764b3ea472791762cb6bd9e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol * MCContext::lookupSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the symbol for <span class="doxyComputerOutput">Name</span>, or null.</p>

<p>Declaration at line 500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/mcparserutils/#a71d0c2aeb5e324a4a962bcfa85617f2c">llvm::MCParserUtils::parseAssignmentExpression</a>.</p>

</div>
</div>

### registerInlineAsmLabel {#a575d0689ae105eb694d6bdc9cc873935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::registerInlineAsmLabel (<a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>registerInlineAsmLabel - Records that the name is a label referenced in inline assembly.</p>

<p>Declaration at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinterinlineasm-cpp/#a362579106cd14231f459ca8c00af60ca">EmitInlineAsmStr</a>.</p>

</div>
</div>

### setSymbolValue {#a21aceafe085b9a14a9864954b9fdb14b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::setSymbolValue (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Streamer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Sym, uint64_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set value for a symbol.</p>

<p>Declaration at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 418 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a04736ef5753e5ecda3c29ce902094e68">llvm::MCStreamer::emitAssignment</a> and <a href="#ac11eef690074972378846024abbe8722">getOrCreateSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Dwarf Management

### addDebugPrefixMapEntry {#a292e9b2444ced8a458c20aaf3b816626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::addDebugPrefixMapEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an entry to the debug prefix map.</p>

<p>Declaration at line 673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 896 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>

</div>
</div>

### addGenDwarfSection {#a589edc5876425761e8515d0d03ba9576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::addGenDwarfSection (<a href="/web-llvm/docs/api/classes/llvm/mcsection">MCSection</a> * Sec)</td>
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



<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>.</p>

</div>
</div>

### addMCGenDwarfLabelEntry {#ab699e113c8ef43f15b51d32819a96c44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::addMCGenDwarfLabelEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcgendwarflabelentry">MCGenDwarfLabelEntry</a> &amp; E)</td>
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



<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcgendwarflabelentry/#a741d0c6e829f284182bd9bbef0362e2d">llvm::MCGenDwarfLabelEntry::Make</a>.</p>

</div>
</div>

### clearDwarfLocSeen {#a533301811e7317a14fd07d84073590ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::clearDwarfLocSeen ()</td>
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



<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#a6f19f34683888bee863e73af9a082535">llvm::MCObjectStreamer::changeSectionImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineentry/#a7e7c37719e68c7bf9e494110a30cad90">llvm::MCDwarfLineEntry::make</a>.</p>

</div>
</div>

### emitCompactUnwindNonCanonical {#a7374fa80c820bab9544f60931b8ca408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCContext::emitCompactUnwindNonCanonical ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 942 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/darwinaarch64asmbackend/#a26e5b6731c22761e5c4e7abe1dc13a21">anonymous{AArch64AsmBackend.cpp}::DarwinAArch64AsmBackend::generateCompactUnwindEncoding</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/darwinx86asmbackend/#a0423592792c76af41a0db8233e30bf45">anonymous{X86AsmBackend.cpp}::DarwinX86AsmBackend::generateCompactUnwindEncoding</a> and <a href="/web-llvm/docs/api/classes/llvm/armasmbackenddarwin/#a0734a023f800982945eec5cff4e9fb22">llvm::ARMAsmBackendDarwin::generateCompactUnwindEncoding</a>.</p>

</div>
</div>

### emitDwarfUnwindInfo {#ad88c3f925ea4397b617e665c3d9be424}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EmitDwarfUnwindType MCContext::emitDwarfUnwindInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 936 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a86a87fba6a15227ff4f33edd538e6d0fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>.</p>

</div>
</div>

### finalizeDwarfSections {#aa565526e57992a6482d7062b03933b99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::finalizeDwarfSections (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; MCOS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove empty sections from SectionsForRanges, to avoid generating useless debug info for them.</p>

<p>Declaration at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 1012 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a9453735a9b47b98c973c5bfa4b6a9203">llvm::MCStreamer::mayHaveInstructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>.</p>

</div>
</div>

### getCompilationDir {#a2a19163118e2b27686c1010ab26556a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCContext::getCompilationDir ()</td>
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

<p>Get the compilation directory for DW_AT_comp_dir The compilation directory should be set with <span class="doxyComputerOutput">setCompilationDir</span> before calling this function.</p>


<p>If it is unset, an empty string will be returned.</p>


<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a> and <a href="#ae44a97a569de65d01e1f80ae5261121b">setGenDwarfRootFile</a>.</p>

</div>
</div>

### getCurrentDwarfLoc {#ae2fe3b101fb1f6389502b5d4f99c0640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCDwarfLoc &amp; llvm::MCContext::getCurrentDwarfLoc ()</td>
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



<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a03e59500b09326087aab0f3aa60a1491">llvm::MCStreamer::emitLineTableLabel</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineentry/#a7e7c37719e68c7bf9e494110a30cad90">llvm::MCDwarfLineEntry::make</a>.</p>

</div>
</div>

### getDwarfCompileUnitID {#a6aabd162418263d017e3559978931451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCContext::getDwarfCompileUnitID ()</td>
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



<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineentry/#a7e7c37719e68c7bf9e494110a30cad90">llvm::MCDwarfLineEntry::make</a>.</p>

</div>
</div>

### getDwarfDebugFlags {#a2757e59e5aa1e5a66e2b11352caa61bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCContext::getDwarfDebugFlags ()</td>
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



<p>Definition at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a> and <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>.</p>

</div>
</div>

### getDwarfDebugProducer {#a1fa812f878a36093c56d691c50a23a3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MCContext::getDwarfDebugProducer ()</td>
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



<p>Definition at line 796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>.</p>

</div>
</div>

### getDwarfFile {#a3ad186547248b6c5236a8795cce3f477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; MCContext::getDwarfFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directory, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, unsigned FileNumber, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5::MD5Result</a> &gt; Checksum, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Source, unsigned CUID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates an entry in the dwarf file and directory tables.</p>


<p>getDwarfFile - takes a file name and number to place in the dwarf file and directory tables.</p>


<p>If the file number has already been allocated it is an error and zero is returned and the client reports the error, else the allocated file number is returned. The file numbers may be in any order.</p>


<p>Declaration at line 690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 989 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#ae399e752589e5b62546a63325cedb528">llvm::MCDwarfLineTable::tryGetFile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a64d1f7d21e406e2796a9bb5afc3aa31e">llvm::MCStreamer::tryEmitDwarfFileDirective</a>.</p>

</div>
</div>

### getDwarfFormat {#ae871de84d03670534d73ae7448b6b6d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::DwarfFormat llvm::MCContext::getDwarfFormat ()</td>
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



<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a3d9503972de494ac87e3025a25bbbbb6">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitFDE</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinestr/#ad325ab6e610eb8bd1f59534515561fdc">llvm::MCDwarfLineStr::emitRef</a>.</p>

</div>
</div>

### getDwarfLocSeen {#a285982216c5eb361f38a33f46ed2f124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::getDwarfLocSeen ()</td>
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



<p>Definition at line 757 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineentry/#a7e7c37719e68c7bf9e494110a30cad90">llvm::MCDwarfLineEntry::make</a>.</p>

</div>
</div>

### getDwarfVersion {#a99c58fcbed2434b9535b866015cd0259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::MCContext::getDwarfVersion ()</td>
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



<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mcdwarflinetableheader/#a1b87cc4b647fd0f14ea7c46227ae2d58">llvm::MCDwarfLineTableHeader::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a89cdc6ed6476f39c32e5a49327bb692e">llvm::MCDwarfLineTable::emit</a>, <a href="/web-llvm/docs/api/classes/anonymous-mcdwarf-cpp-/frameemitterimpl/#a06884c9e11f3d8bb503abfb8dc03586b">anonymous{MCDwarf.cpp}::FrameEmitterImpl::EmitCIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mcdwarf/#ad32db1a85072666827c900bee74761b1">llvm::mcdwarf::emitListsTableHeaderStart</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#adf60d16739e1ceabb1cee9e9dede7ba5">llvm::MCDwarfLineTable::emitOne</a>, <a href="#a50a6c8425d664907bb4a20247bdee178">isValidDwarfFileNumber</a> and <a href="#ae44a97a569de65d01e1f80ae5261121b">setGenDwarfRootFile</a>.</p>

</div>
</div>

### getGenDwarfFileNumber {#a8628c8e12fcc26b3fbb4edf01a01fa82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::MCContext::getGenDwarfFileNumber ()</td>
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



<p>Definition at line 762 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcgendwarflabelentry/#a741d0c6e829f284182bd9bbef0362e2d">llvm::MCGenDwarfLabelEntry::Make</a>.</p>

</div>
</div>

### getGenDwarfForAssembly {#a2b487b9dffd6d0f849e9131ebabc998f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::getGenDwarfForAssembly ()</td>
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



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### getGenDwarfSectionSyms {#a0ffd38472bf725df4e4c3cac8c0ad771}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SetVector&lt; MCSection * &gt; &amp; llvm::MCContext::getGenDwarfSectionSyms ()</td>
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



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcgendwarfinfo/#af945d198ed58841b8d57f45a11e2987e">llvm::MCGenDwarfInfo::Emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ae3810dff97d2b1f712f053e18a98f383">EmitGenDwarfAbbrev</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a1b98f9e375747640ed4f1f019b0558aa">EmitGenDwarfAranges</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#acd1c7609888ea3462f400dcfbca2e486">emitGenDwarfRanges</a> and <a href="/web-llvm/docs/api/classes/llvm/mcgendwarflabelentry/#a741d0c6e829f284182bd9bbef0362e2d">llvm::MCGenDwarfLabelEntry::Make</a>.</p>

</div>
</div>

### getMainFileName {#a2465bb2474b7bacc584546860c1c234b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::MCContext::getMainFileName ()</td>
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

<p>Get the main file name for use in error messages and debug info.</p>


<p>This can be set to ensure we've got the correct file name after preprocessing or for -save-temps.</p>


<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="#ae44a97a569de65d01e1f80ae5261121b">setGenDwarfRootFile</a>.</p>

</div>
</div>

### getMCDwarfDirs {#a11e4d2892230408be583cbf6ee7c28c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; std::string &gt; &amp; llvm::MCContext::getMCDwarfDirs (unsigned CUID=0)</td>
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



<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a2fe3c80bd9d87408e767c1ffd4fceafb">llvm::MCDwarfLineTable::getMCDwarfDirs</a> and <a href="#a62f7e21c9dac9e7acb4fdd713e712d20">getMCDwarfLineTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>.</p>

</div>
</div>

### getMCDwarfFiles {#a81530c44115124e6e977b6e14b8ec4a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; MCDwarfFile &gt; &amp; llvm::MCContext::getMCDwarfFiles (unsigned CUID=0)</td>
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



<p>Definition at line 712 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#af3dabb2d8280080e29d147b7629da1ac">llvm::MCDwarfLineTable::getMCDwarfFiles</a> and <a href="#a62f7e21c9dac9e7acb4fdd713e712d20">getMCDwarfLineTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>.</p>

</div>
</div>

### getMCDwarfLineTable {#a62f7e21c9dac9e7acb4fdd713e712d20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDwarfLineTable &amp; llvm::MCContext::getMCDwarfLineTable (unsigned CUID)</td>
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



<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a29df2eab11142e7ff1e8ee74b0cb6322">llvm::MCStreamer::emitDwarfLocLabelDirective</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a03e59500b09326087aab0f3aa60a1491">llvm::MCStreamer::emitLineTableLabel</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#abfdbd82da864ad373a4e42c0ed3b2230">anonymous{AsmParser.cpp}::AsmParser::enabledGenDwarfForAssembly</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#aa51d3a6818627c9f45797eeef1f1b91c">llvm::MCStreamer::getDwarfLineTableSymbol</a>, <a href="#a11e4d2892230408be583cbf6ee7c28c0">getMCDwarfDirs</a>, <a href="#a81530c44115124e6e977b6e14b8ec4a1">getMCDwarfFiles</a>, <a href="#a137ae51c4db9a5f30ed3148a9aad81ce">isDwarfMD5UsageConsistent</a>, <a href="#a50a6c8425d664907bb4a20247bdee178">isValidDwarfFileNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflineentry/#a7e7c37719e68c7bf9e494110a30cad90">llvm::MCDwarfLineEntry::make</a> and <a href="#afa7b9baa221c1a5ea68940b0cf6b5a26">setMCLineTableRootFile</a>.</p>

</div>
</div>

### getMCDwarfLineTable {#ad7098313285ab3aa2553db1f6fe8c53d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCDwarfLineTable &amp; llvm::MCContext::getMCDwarfLineTable (unsigned CUID)</td>
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



<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getMCDwarfLineTables {#a844102db6a944e0b900e1dcb331cd8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::map&lt; unsigned, MCDwarfLineTable &gt; &amp; llvm::MCContext::getMCDwarfLineTables ()</td>
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



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a89cdc6ed6476f39c32e5a49327bb692e">llvm::MCDwarfLineTable::emit</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#a1f9777a39f525bf9f8a85ce9d52cccd9">anonymous{AsmParser.cpp}::AsmParser::Run</a> and <a href="/web-llvm/docs/api/classes/anonymous-masmparser-cpp-/masmparser/#a46449244c1f2d4e4b2022d1126e7c5ab">anonymous{MasmParser.cpp}::MasmParser::Run</a>.</p>

</div>
</div>

### getMCGenDwarfLabelEntries {#aed43a765c7bd89683590bab0196c87b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; MCGenDwarfLabelEntry &gt; &amp; llvm::MCContext::getMCGenDwarfLabelEntries ()</td>
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



<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#a8ecc921219ca991a8cd7607227646ccf">EmitGenDwarfInfo</a>.</p>

</div>
</div>

### isDwarfMD5UsageConsistent {#a137ae51c4db9a5f30ed3148a9aad81ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCContext::isDwarfMD5UsageConsistent (unsigned CUID)</td>
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

<p>Reports whether <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> checksum usage is consistent (all-or-none).</p>

<p>Definition at line 735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>References <a href="#a62f7e21c9dac9e7acb4fdd713e712d20">getMCDwarfLineTable</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a093be87196f38e1d156df2fca3ad3695">llvm::MCDwarfLineTable::isMD5UsageConsistent</a>.</p>

</div>
</div>

### isValidDwarfFileNumber {#a50a6c8425d664907bb4a20247bdee178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MCContext::isValidDwarfFileNumber (unsigned FileNumber, unsigned CUID=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isValidDwarfFileNumber - takes a dwarf file number and returns true if it currently is assigned and false otherwise.</p>

<p>Declaration at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 1000 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="#a99c58fcbed2434b9535b866015cd0259">getDwarfVersion</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#af3dabb2d8280080e29d147b7629da1ac">llvm::MCDwarfLineTable::getMCDwarfFiles</a> and <a href="#a62f7e21c9dac9e7acb4fdd713e712d20">getMCDwarfLineTable</a>.</p>

</div>
</div>

### remapDebugPath {#a01ecf33b3bb3331985f61bca570827d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::remapDebugPath (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remap one path in-place as per the debug prefix map.</p>

<p>Declaration at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb31f2db6f0fe5eaa5b28464141223aa">llvm::sys::path::replace_path_prefix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b0ac1fa4f05de76413c5e0ca6334035">llvm::reverse</a>.</p>


<p>Referenced by <a href="#a2b6fa558341bb0ce850c615f39b429f5">RemapDebugPaths</a>.</p>

</div>
</div>

### RemapDebugPaths {#a2b6fa558341bb0ce850c615f39b429f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::RemapDebugPaths ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 907 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a01ecf33b3bb3331985f61bca570827d7">remapDebugPath</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcobjectstreamer/#aa8d1c93368ccaad9bdc429b25633f943">llvm::MCObjectStreamer::finishImpl</a>.</p>

</div>
</div>

### setCompilationDir {#a83fc1b3aaadeeadd3b56de78e1415abb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setCompilationDir (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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

<p>Set the compilation directory for DW_AT_comp_dir.</p>

<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>.</p>

</div>
</div>

### setCurrentDwarfLoc {#a8bef0ea056c194d113570558f2c07132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setCurrentDwarfLoc (unsigned FileNum, unsigned Line, unsigned Column, unsigned Flags, unsigned Isa, unsigned Discriminator)</td>
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

<p>Saves the information from the currently parsed dwarf .loc directive and sets DwarfLocSeen.</p>


<p>When the next instruction is assembled an entry in the line number table with this information and the address of the instruction will be created.</p>


<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a43c1c961a6b54da9fccacdf1cf5fc38f">llvm::MCStreamer::emitDwarfLocDirective</a>.</p>

</div>
</div>

### setDwarfCompileUnitID {#ad619a8d1435a4b5a4b75cce8878486fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setDwarfCompileUnitID (unsigned CUIndex)</td>
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



<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### setDwarfDebugFlags {#a8869af36f9069b8e91c06a99d37eb630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setDwarfDebugFlags (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 792 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### setDwarfDebugProducer {#a9573f499fce315377b867ee2f1a52216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setDwarfDebugProducer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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



<p>Definition at line 795 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### setDwarfFormat {#a8262581122296e7b4247a5043fe30fa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setDwarfFormat (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a> f)</td>
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



<p>Definition at line 798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### setDwarfVersion {#a52ed247246b5256063c6c357b46a134b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setDwarfVersion (uint16_t v)</td>
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



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### setGenDwarfFileNumber {#acfed6f3916764b6062de06e25e4a6603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setGenDwarfFileNumber (unsigned FileNumber)</td>
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



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#abfdbd82da864ad373a4e42c0ed3b2230">anonymous{AsmParser.cpp}::AsmParser::enabledGenDwarfForAssembly</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmparser-cpp-/asmparser/#afaaaf7da6379fe3994da86bf71024ddc">anonymous{AsmParser.cpp}::AsmParser::parseAndMatchAndEmitTargetInstruction</a>.</p>

</div>
</div>

### setGenDwarfForAssembly {#a48d092c1445b69a1587b8f24d43d12ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setGenDwarfForAssembly (bool Value)</td>
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



<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### setGenDwarfRootFile {#ae44a97a569de65d01e1f80ae5261121b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCContext::setGenDwarfRootFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specifies information about the "root file" for assembler clients (e.g., llvm-mc).</p>


<p>Assumes compilation dir etc. have been set up.</p>


<p>Declaration at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>, definition at line 948 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a8a7fac667f8ae35285b8b53d9f2dd9dc">llvm::StringRef::consume_front</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a3fb2867a1e9fa36e135d9ee4dffb0167">llvm::StringRef::drop_front</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/md5/#a5138672d89124f45e2217d8484a59a40">llvm::MD5::final</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a61364ca3a5ff90fb2aa0d5a371fd43f7">llvm::StringRef::front</a>, <a href="#a2a19163118e2b27686c1010ab26556a3">getCompilationDir</a>, <a href="#a99c58fcbed2434b9535b866015cd0259">getDwarfVersion</a>, <a href="#a2465bb2474b7bacc584546860c1c234b">getMainFileName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aecbfb983627865ec98e96179df881e37">llvm::sys::path::is_separator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a03907c7df68a93c377bf90c5bdd78ca3">llvm::sys::path::remove_filename</a>, <a href="#afa7b9baa221c1a5ea68940b0cf6b5a26">setMCLineTableRootFile</a> and <a href="/web-llvm/docs/api/classes/llvm/md5/#a3f41856aade4440631544e50238f75f5">llvm::MD5::update</a>.</p>

</div>
</div>

### setMainFileName {#abfd2641cfadb2bf0ad06a93ad6753abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setMainFileName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S)</td>
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

<p>Set the main file name and override the default.</p>

<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>

</div>
</div>

### setMCLineTableRootFile {#afa7b9baa221c1a5ea68940b0cf6b5a26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MCContext::setMCLineTableRootFile (unsigned CUID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CompilationDir, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5::MD5Result</a> &gt; Checksum, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Source)</td>
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

<p>Specifies the "root" file and directory of the compilation unit.</p>


<p>These are "file 0" and "directory 0" in DWARF v5.</p>


<p>Definition at line 726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a>.</p>


<p>References <a href="#a62f7e21c9dac9e7acb4fdd713e712d20">getMCDwarfLineTable</a> and <a href="/web-llvm/docs/api/classes/llvm/mcdwarflinetable/#a531ce2a12a8f1383d5e7041be558c665">llvm::MCDwarfLineTable::setRootFile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#afc5440a8bfa25645fa1f58ee11a4394d">llvm::MCStreamer::emitDwarfFile0Directive</a> and <a href="#ae44a97a569de65d01e1f80ae5261121b">setGenDwarfRootFile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mccontext-h">MCContext.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mccontext-cpp">MCContext.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
