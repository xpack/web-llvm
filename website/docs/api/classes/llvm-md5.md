---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/md5
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MD5` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MD5 { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">llvm/Support/MD5.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">uint32_t <a href="#a91d91a556724086e54c0b7a19d42ac7b">MD5_u32plus</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa6155ec36de415ab2dcf5e54b670d13">MD5</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f41856aade4440631544e50238f75f5">update</a> (ArrayRef&lt; uint8_t &gt; Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates the hash for the byte stream provided. <a href="#a3f41856aade4440631544e50238f75f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a155b676479d4f275c239be608c5314ee">update</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates the hash for the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> provided. <a href="#a155b676479d4f275c239be608c5314ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5138672d89124f45e2217d8484a59a40">final</a> (MD5Result &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finishes off the hash and puts the result in result. <a href="#a5138672d89124f45e2217d8484a59a40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5Result</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6619a5c386e36ca0c518f9369083cd4b">final</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finishes off the hash, and returns the 16-byte hash data. <a href="#a6619a5c386e36ca0c518f9369083cd4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5Result</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c6fdc9e89019b2c169fb700d64f76e4">result</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finishes off the hash, and returns the 16-byte hash data. <a href="#a6c6fdc9e89019b2c169fb700d64f76e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae6f25f1f0dcf310fe06de249806fe8f">body</a> (ArrayRef&lt; uint8_t &gt; Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This processes one or more 64-byte data blocks, but does NOT update the bit counters. <a href="#aae6f25f1f0dcf310fe06de249806fe8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">MD5_u32plus</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bb994103b9ec34f4a1d0d3f503360c9">a</a> = 0x67452301</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MD5_u32plus</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac956eabbc7bd44c6367d96b90cbcf25b">b</a> = 0xefcdab89</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MD5_u32plus</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9ba2d06b075a7a7f93a6d54772502d">c</a> = 0x98badcfe</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MD5_u32plus</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb871ceca413199c264d529a1852fb4e">d</a> = 0x10325476</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MD5_u32plus</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6792823c2bd6480d1ada988206a2ec4a">hi</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MD5_u32plus</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99769495224d689d27c21a35bb093f60">lo</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a814b46e2755a527e14254b86623639">buffer</a>[64]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">MD5_u32plus</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a139cd613a1ffbda23621cca6ef7a5a46">block</a>[16]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8fdc894e9e46e2bdba683177e074832">InternalState</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a450646b00c73312350d0f0f113a860e8">stringifyResult</a> (MD5Result &amp;Result, SmallVectorImpl&lt; char &gt; &amp;Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Translates the bytes in <span class="doxyComputerOutput">Res</span> to a hex string that is deposited into <span class="doxyComputerOutput">Str</span>. <a href="#a450646b00c73312350d0f0f113a860e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5Result</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e8154c81c83bd9f77282d42ee62cddd">hash</a> (ArrayRef&lt; uint8_t &gt; Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Computes the hash for a given bytes. <a href="#a6e8154c81c83bd9f77282d42ee62cddd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### MD5\_u32plus {#a91d91a556724086e54c0b7a19d42ac7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef uint32_t llvm::MD5::MD5_u32plus</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MD5() {#afa6155ec36de415ab2dcf5e54b670d13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MD5::MD5 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="#a6e8154c81c83bd9f77282d42ee62cddd">hash</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### final() {#a5138672d89124f45e2217d8484a59a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MD5::final (<a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5Result</a> &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finishes off the hash and puts the result in result.</p>


<p>Finish the hash and place the resulting hash into <span class="doxyComputerOutput">result</span>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Result</td>
<td class="doxyParamItemDescription"><p>is assumed to be a minimum of 16-bytes in size.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp">MD5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a4f05956d010455624c13f5eb2217bc8b">llvm::support::endian::write32le</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp/#a583d026b8d43fe8bfa1bb824342a521e">computeHashString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eeb42cfad58d947c605b1e21376e0b7">llvm::emitAMDGPUPrintfCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-nameanonglobals-cpp-/modulehasher/#a1df471b751b0e5d0812dd5cebc1dfe98">anonymous{NameAnonGlobals.cpp}::ModuleHasher::get</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#a3895fb1bb3ce7eb70a9582110ad0ad55">anonymous{NVPTXCtorDtorLowering.cpp}::getHash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3185cb2a23629ee9ed7ad67f719b60c">llvm::getUniqueInternalLinkagePostfix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b8599f07b1b0181899c650b7b385b26">llvm::getUniqueModuleId</a>, <a href="#a6e8154c81c83bd9f77282d42ee62cddd">hash</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#affd65b6c842827550ed102e2d82b90fa">llvm::DwarfDebug::makeTypeSignature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ade579376a1cb799b25765b38039915b9">llvm::sys::fs::md5_contents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcc6aac115764c36b17d83e4bd4cc36e">llvm::MD5Hash</a> and <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae44a97a569de65d01e1f80ae5261121b">llvm::MCContext::setGenDwarfRootFile</a>.</p>

</div>
</div>

### final() {#a6619a5c386e36ca0c518f9369083cd4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MD5::MD5Result MD5::final ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finishes off the hash, and returns the 16-byte hash data.</p>

<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>, definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp">MD5.cpp</a>.</p>

</div>
</div>

### result() {#a6c6fdc9e89019b2c169fb700d64f76e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MD5::MD5Result MD5::result ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finishes off the hash, and returns the 16-byte hash data.</p>


<p>This is suitable for getting the <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> at any time without invalidating the internal state, so that more calls can be made into <span class="doxyComputerOutput">update</span>.</p>


<p>Declaration at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp">MD5.cpp</a>.</p>

</div>
</div>

### update() {#a3f41856aade4440631544e50238f75f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MD5::update (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates the hash for the byte stream provided.</p>


<p>Incrementally add the bytes in <span class="doxyComputerOutput">Data</span> to the hash.</p>


<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>, definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp">MD5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp/#a583d026b8d43fe8bfa1bb824342a521e">computeHashString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eeb42cfad58d947c605b1e21376e0b7">llvm::emitAMDGPUPrintfCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-nameanonglobals-cpp-/modulehasher/#a1df471b751b0e5d0812dd5cebc1dfe98">anonymous{NameAnonGlobals.cpp}::ModuleHasher::get</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#a3895fb1bb3ce7eb70a9582110ad0ad55">anonymous{NVPTXCtorDtorLowering.cpp}::getHash</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3185cb2a23629ee9ed7ad67f719b60c">llvm::getUniqueInternalLinkagePostfix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b8599f07b1b0181899c650b7b385b26">llvm::getUniqueModuleId</a>, <a href="#a6e8154c81c83bd9f77282d42ee62cddd">hash</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebug/#affd65b6c842827550ed102e2d82b90fa">llvm::DwarfDebug::makeTypeSignature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ade579376a1cb799b25765b38039915b9">llvm::sys::fs::md5_contents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcc6aac115764c36b17d83e4bd4cc36e">llvm::MD5Hash</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae44a97a569de65d01e1f80ae5261121b">llvm::MCContext::setGenDwarfRootFile</a> and <a href="#a155b676479d4f275c239be608c5314ee">update</a>.</p>

</div>
</div>

### update() {#a155b676479d4f275c239be608c5314ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MD5::update (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates the hash for the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> provided.</p>


<p>Add the bytes in the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <span class="doxyComputerOutput">Str</span> to the hash.</p>


<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>, definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp">MD5.cpp</a>.</p>


<p>Reference <a href="#a3f41856aade4440631544e50238f75f5">update</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### body() {#aae6f25f1f0dcf310fe06de249806fe8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t * MD5::body (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This processes one or more 64-byte data blocks, but does NOT update the bit counters.</p>


<p>There are no alignment requirements.</p>


<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp">MD5.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### a {#a2bb994103b9ec34f4a1d0d3f503360c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MD5_u32plus llvm::MD5::a = 0x67452301</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>.</p>

</div>
</div>

### b {#ac956eabbc7bd44c6367d96b90cbcf25b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MD5_u32plus llvm::MD5::b = 0xefcdab89</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>.</p>

</div>
</div>

### block {#a139cd613a1ffbda23621cca6ef7a5a46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MD5_u32plus llvm::MD5::block[16]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>.</p>

</div>
</div>

### buffer {#a8a814b46e2755a527e14254b86623639}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::MD5::buffer[64]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>.</p>

</div>
</div>

### c {#aec9ba2d06b075a7a7f93a6d54772502d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MD5_u32plus llvm::MD5::c = 0x98badcfe</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>.</p>

</div>
</div>

### d {#adb871ceca413199c264d529a1852fb4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MD5_u32plus llvm::MD5::d = 0x10325476</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>.</p>

</div>
</div>

### hi {#a6792823c2bd6480d1ada988206a2ec4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MD5_u32plus llvm::MD5::hi = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>.</p>

</div>
</div>

### lo {#a99769495224d689d27c21a35bb093f60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MD5_u32plus llvm::MD5::lo = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InternalState {#ae8fdc894e9e46e2bdba683177e074832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm::MD5 llvm::MD5::InternalState</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### hash() {#a6e8154c81c83bd9f77282d42ee62cddd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MD5::MD5Result MD5::hash (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
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

<p>Computes the hash for a given bytes.</p>

<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>, definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp">MD5.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a5138672d89124f45e2217d8484a59a40">final</a>, <a href="#afa6155ec36de415ab2dcf5e54b670d13">MD5</a> and <a href="#a3f41856aade4440631544e50238f75f5">update</a>.</p>

</div>
</div>

### stringifyResult() {#a450646b00c73312350d0f0f113a860e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MD5::stringifyResult (<a href="/web-llvm/docs/api/structs/llvm/md5/md5result">MD5Result</a> &amp; Result, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Str)</td>
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

<p>Translates the bytes in <span class="doxyComputerOutput">Res</span> to a hex string that is deposited into <span class="doxyComputerOutput">Str</span>.</p>


<p>The result will be of length 32.</p>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp">MD5.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abec19670f96ed423c2e4d4f10a4c6975">llvm::toHex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typerecordmapping-cpp/#a583d026b8d43fe8bfa1bb824342a521e">computeHashString</a>, <a href="/web-llvm/docs/api/classes/anonymous-nameanonglobals-cpp-/modulehasher/#a1df471b751b0e5d0812dd5cebc1dfe98">anonymous{NameAnonGlobals.cpp}::ModuleHasher::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3185cb2a23629ee9ed7ad67f719b60c">llvm::getUniqueInternalLinkagePostfix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6b8599f07b1b0181899c650b7b385b26">llvm::getUniqueModuleId</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">MD5.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp">MD5.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
