---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memorybufferref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MemoryBufferRef` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MemoryBufferRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">llvm/Support/MemoryBufferRef.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a755e1624bf05e8ed0a85fd55048ed1f3">operator==</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> pointer identity (not value) of identifier and data. <a href="#a755e1624bf05e8ed0a85fd55048ed1f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f1dea7a9115e1b664ed90af09fab694">operator!=</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9bc03b20125da6237c8514242ce3261">MemoryBufferRef</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada1f93949e90a03e088337dae60b0e4a">MemoryBufferRef</a> (const MemoryBuffer &amp;Buffer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c137dbcd9366938704b191e230cb732">MemoryBufferRef</a> (StringRef Buffer, StringRef Identifier)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7301c8fd89ad0f595f4ce4609c872704">getBuffer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3201ce149cba3920fc965378ceddbcb8">getBufferIdentifier</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b2843b74e5f05930ebf5c63766a668">getBufferStart</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8780f1948b2e4a8880790dc3923ab92c">getBufferEnd</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2036a4973d159e49dcc471488205656f">getBufferSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a403856071544464513899a64bff78b1b">Buffer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01f3bbfa3c080f8e127462ae2b0b297f">Identifier</a></td>
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


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>.</p>


<div class="doxySectionDef">

## Friends

### operator!= {#a7f1dea7a9115e1b664ed90af09fab694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> &amp; RHS</td>
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


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#af9bc03b20125da6237c8514242ce3261">MemoryBufferRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator== {#a755e1624bf05e8ed0a85fd55048ed1f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> &amp; RHS</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> pointer identity (not value) of identifier and data.</p>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="#af9bc03b20125da6237c8514242ce3261">MemoryBufferRef</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MemoryBufferRef() {#af9bc03b20125da6237c8514242ce3261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryBufferRef::MemoryBufferRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>.</p>


<p>Referenced by <a href="#a7f1dea7a9115e1b664ed90af09fab694">operator!=</a> and <a href="#a755e1624bf05e8ed0a85fd55048ed1f3">operator==</a>.</p>

</div>
</div>

### MemoryBufferRef() {#ada1f93949e90a03e088337dae60b0e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryBufferRef::MemoryBufferRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/support/memorybufferref-cpp">MemoryBufferRef.cpp</a>.</p>


<p>References <a href="#a7301c8fd89ad0f595f4ce4609c872704">getBuffer</a> and <a href="#a3201ce149cba3920fc965378ceddbcb8">getBufferIdentifier</a>.</p>

</div>
</div>

### MemoryBufferRef() {#a0c137dbcd9366938704b191e230cb732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MemoryBufferRef::MemoryBufferRef (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Buffer, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Identifier)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getBuffer() {#a7301c8fd89ad0f595f4ce4609c872704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MemoryBufferRef::getBuffer ()</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/textapireader/#a91cc2902b5c82e2313c928a08a54597c">llvm::MachO::TextAPIReader::canRead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a93afe3b7548a63fa4d20b50bedb0a61a">llvm::orc::checkMachORelocatableObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a94706a904f4d80927ee78935decb3667">llvm::orc::checkMachORelocatableObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/binarycoveragereader/#a75f0ba2a248f2f7f77f477bfb8d6dab2">llvm::coverage::BinaryCoverageReader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#ab1f06bb87aef1053996ec05424135d82">llvm::object::OffloadBinary::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a5ef8ed10341ed52e784b5408bac56424">llvm::object::ObjectFile::createELFObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a41a194a45535dac693ad3d1d358cf200">llvm::jitlink::createLinkGraphFromCOFFObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a4fbdc8f1be1bfc357861f63756755f65">llvm::jitlink::createLinkGraphFromELFObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a81840c63a3bae7ccfa9b92ea03c80f00">llvm::jitlink::createLinkGraphFromMachOObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aad60b2c2a2e09a361eac9a21327a8eaf">llvm::jitlink::createLinkGraphFromObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a3bcb896473d4c0e5275a58bf731ee899">llvm::object::ObjectFile::createMachOObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a214181fcdbdcdd2ce1d22fe395716abc">llvm::object::extractOffloadBinaries</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a67bf5d7f987fa670edc3e7948bac2a07">anonymous{OffloadBinary.cpp}::extractOffloadFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/textapireader/#ae720a98705c6ad89165018117560dc47">llvm::MachO::TextAPIReader::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/amdgpu/#a658b1211d163ef9492d062d29de98201">llvm::offloading::amdgpu::getAMDGPUMetaDataFromImage</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a838e4f1a36cc927704247e621bcf0204">getSymbolicFile</a>, <a href="#ada1f93949e90a03e088337dae60b0e4a">MemoryBufferRef</a> and <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>.</p>

</div>
</div>

### getBufferEnd() {#a8780f1948b2e4a8880790dc3923ab92c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::MemoryBufferRef::getBufferEnd ()</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8b04365fc31f28e28e484d2f3cba05f1">llvm::parseIR</a>.</p>

</div>
</div>

### getBufferIdentifier() {#a3201ce149cba3920fc965378ceddbcb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MemoryBufferRef::getBufferIdentifier ()</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a41a194a45535dac693ad3d1d358cf200">llvm::jitlink::createLinkGraphFromCOFFObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a489285433291b13eea20e7849a2aff39">llvm::jitlink::createLinkGraphFromCOFFObject_x86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a4fbdc8f1be1bfc357861f63756755f65">llvm::jitlink::createLinkGraphFromELFObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a85b7da2fbe9dbb9291c2ebeba26baa11">llvm::jitlink::createLinkGraphFromELFObject_aarch32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ac95049051540ea75bfbcab8a7c8e1f69">llvm::jitlink::createLinkGraphFromELFObject_aarch64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a2a0dc55fe67dc6e71c079367865cd57a">llvm::jitlink::createLinkGraphFromELFObject_i386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ac2b9ede3e13dcfd4f770f6ea25c35ba9">llvm::jitlink::createLinkGraphFromELFObject_loongarch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#af23db7aa950c030363b723a4558961f7">llvm::jitlink::createLinkGraphFromELFObject_ppc64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a1f68b000ad84d40757482a867e804ce9">llvm::jitlink::createLinkGraphFromELFObject_riscv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ade7e70a675849d2a83bd269102ab6f55">llvm::jitlink::createLinkGraphFromELFObject_x86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a81840c63a3bae7ccfa9b92ea03c80f00">llvm::jitlink::createLinkGraphFromMachOObject</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadbinary-cpp-/#a67bf5d7f987fa670edc3e7948bac2a07">anonymous{OffloadBinary.cpp}::extractOffloadFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/textapireader/#ae720a98705c6ad89165018117560dc47">llvm::MachO::TextAPIReader::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>, <a href="#ada1f93949e90a03e088337dae60b0e4a">MemoryBufferRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#adaa1cc0b0e4c0aa5ff49433cc3bc2a2d">llvm::orc::objDesc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b04365fc31f28e28e484d2f3cba05f1">llvm::parseIR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/dylibreader/#a1d593efec1083a71925949203aaf6d31">llvm::MachO::DylibReader::readFile</a>.</p>

</div>
</div>

### getBufferSize() {#a2036a4973d159e49dcc471488205656f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::MemoryBufferRef::getBufferSize ()</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>, <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#ab1f06bb87aef1053996ec05424135d82">llvm::object::OffloadBinary::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae744a53dbb2720e5678fb879156761e9">llvm::embedBufferInModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab5a82b3045c92ee732ddca71ea91a65d">initStream</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/writer/#aef4ecef7a05cd113a04ae7504c4ff08b">llvm::msgpack::Writer::write</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/writer/#ac51fde5dfbfcac23216ca22b76b26bf5">llvm::msgpack::Writer::writeExt</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#a9f26efe564d8f7f1afb5f3033156d58d">writeUniversalArchsToStream</a>.</p>

</div>
</div>

### getBufferStart() {#a62b2843b74e5f05930ebf5c63766a668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::MemoryBufferRef::getBufferStart ()</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coverage/binarycoveragereader/#a75f0ba2a248f2f7f77f477bfb8d6dab2">llvm::coverage::BinaryCoverageReader::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#ab1f06bb87aef1053996ec05424135d82">llvm::object::OffloadBinary::create</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a5ef8ed10341ed52e784b5408bac56424">llvm::object::ObjectFile::createELFObjectFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae744a53dbb2720e5678fb879156761e9">llvm::embedBufferInModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ab5a82b3045c92ee732ddca71ea91a65d">initStream</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b04365fc31f28e28e484d2f3cba05f1">llvm::parseIR</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/writer/#aef4ecef7a05cd113a04ae7504c4ff08b">llvm::msgpack::Writer::write</a>, <a href="/web-llvm/docs/api/classes/llvm/msgpack/writer/#ac51fde5dfbfcac23216ca22b76b26bf5">llvm::msgpack::Writer::writeExt</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#a9f26efe564d8f7f1afb5f3033156d58d">writeUniversalArchsToStream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Buffer {#a403856071544464513899a64bff78b1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MemoryBufferRef::Buffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>.</p>

</div>
</div>

### Identifier {#a01f3bbfa3c080f8e127462ae2b0b297f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::MemoryBufferRef::Identifier</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybufferref-h">MemoryBufferRef.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/memorybufferref-cpp">MemoryBufferRef.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
