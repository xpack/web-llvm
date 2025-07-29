---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/memprof/rawmemprofreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `RawMemProfReader` Class



## Declaration

<div class="doxyDeclaration">
class llvm::memprof::RawMemProfReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">llvm/ProfileData/MemProfReader.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader">MemProfReader</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f729ba6865d20934390bcc34bcd21ce">RawMemProfReader</a> (const RawMemProfReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8752e79c1ff428a443a4bd1e5d57bf9">RawMemProfReader</a> (std::unique_ptr&lt; llvm::symbolize::SymbolizableModule &gt; Sym, llvm::SmallVectorImpl&lt; SegmentEntry &gt; &amp;Seg, llvm::MapVector&lt; uint64_t, MemInfoBlock &gt; &amp;Prof, CallStackMap &amp;SM, bool KeepName=false)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77762001f0acdef36f9b48fbd15b0905">RawMemProfReader</a> (object::OwningBinary&lt; object::Binary &gt; &amp;&amp;Bin, bool KeepName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa3aedfb1ee64ce5ef518842c822ef9e">~RawMemProfReader</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader">RawMemProfReader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30fc6abde4540cab3fa22516a3487631">operator=</a> (const RawMemProfReader &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2265dbec910f82a9711acc0619cfc1cb">printYAML</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa35ea12116aa94322f977239282e6e1e">readNextRecord</a> (GuidMemProfRecordPair &amp;GuidRecord, std::function&lt; const Frame(const FrameId)&gt; Callback) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a513c0d12d72a7e66293d5f0b1ad60fcc">initialize</a> (std::unique_ptr&lt; MemoryBuffer &gt; DataBuffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765dd80c8d320f69f17d6fb69e0c68af">readRawProfile</a> (std::unique_ptr&lt; MemoryBuffer &gt; DataBuffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7ac26ac4d1b37cb95f27b87dbb42917">setupForSymbolization</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1f5c269c6de33c82167a0fc53eb7615">symbolizeAndFilterStackFrames</a> (std::unique_ptr&lt; llvm::symbolize::SymbolizableModule &gt; Symbolizer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada458df321dcac80cd0aa5ae83bca356">mapRawProfileToRecords</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf30b383e25b26d11e35171ffe0fddcf">getModuleOffset</a> (uint64_t VirtualAddress)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; std::pair&lt; uint64_t, MemInfoBlock &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeffcb0d0f411ed9ef0feabc1884041e8">readMemInfoBlocks</a> (const char *Ptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/binary">object::Binary</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8972c3a821d0e03991119da96e40a4">Binary</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea20f53fc45866926ca4bb61e7fd947">MemprofRawVersion</a> = MEMPROF_RAW_VERSION</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa5e60383444ca810ce163774dd5b5d">PreferredTextSegmentAddress</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7494542615a9e0c24e4d914adade156">ProfiledTextSegmentStart</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11cfb152cbcd79b1c2881ff08fcfa87a">ProfiledTextSegmentEnd</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; SegmentEntry, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05247f97086b8650ad96ad23b0f2bf23">SegmentInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; uint64_t, MemInfoBlock &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a093e960586ba4d6705d258d26adeeffb">CallstackProfileData</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ad95623ea8056308a1e5b6955572db5e0">CallStackMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac2a1e230ab55576d3f0d29c0a58f154">StackMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">llvm::DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">FrameId</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e00e726be52518cf8c65ad95139888f">SymbolizedFrame</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56c693bffa655adcb4c16765567f6919">KeepSymbolName</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">llvm::DenseMap</a>&lt; uint64_t, std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc0bd49c46f23557b2f006e5d8eeb75e">GuidToSymbolName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6239b296c0498d12a965b70fba539d7">hasFormat</a> (const MemoryBuffer &amp;DataBuffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afaa5bd7225c533cda8178eb88b6b25fc">hasFormat</a> (const StringRef Path)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader">RawMemProfReader</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a529ab1228d3ec2e3eb5e89d8871751ba">create</a> (const Twine &amp;Path, StringRef ProfiledBinary, bool KeepName=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader">RawMemProfReader</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e40bbc853b758d181123ba30308e326">create</a> (std::unique_ptr&lt; MemoryBuffer &gt; Buffer, StringRef ProfiledBinary, bool KeepName=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91e332bfcd4030aa1b14feb8792ff8f3">peekBuildIds</a> (MemoryBuffer *DataBuffer)</td>
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


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RawMemProfReader() {#a4f729ba6865d20934390bcc34bcd21ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::RawMemProfReader::RawMemProfReader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader">RawMemProfReader</a> &amp;)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<p>Reference <a href="#a4f729ba6865d20934390bcc34bcd21ce">RawMemProfReader</a>.</p>


<p>Referenced by <a href="#a0e40bbc853b758d181123ba30308e326">create</a>, <a href="#a30fc6abde4540cab3fa22516a3487631">operator=</a> and <a href="#a4f729ba6865d20934390bcc34bcd21ce">RawMemProfReader</a>.</p>

</div>
</div>

### RawMemProfReader() {#aa8752e79c1ff428a443a4bd1e5d57bf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::RawMemProfReader::RawMemProfReader (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">llvm::symbolize::SymbolizableModule</a> &gt; Sym, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">llvm::SmallVectorImpl</a>&lt; SegmentEntry &gt; &amp; Seg, <a href="/web-llvm/docs/api/classes/llvm/mapvector">llvm::MapVector</a>&lt; uint64_t, MemInfoBlock &gt; &amp; Prof, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ad95623ea8056308a1e5b6955572db5e0">CallStackMap</a> &amp; SM, bool KeepName=false)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader/#a5c92c06cdddcf09a7c945e48832f82a1">llvm::memprof::MemProfReader::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader/#a0a572fd22db0d70baab5143a2d69c7da">llvm::memprof::MemProfReader::end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### RawMemProfReader() {#a77762001f0acdef36f9b48fbd15b0905}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::RawMemProfReader::RawMemProfReader (<a href="/web-llvm/docs/api/classes/llvm/object/owningbinary">object::OwningBinary</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/binary">object::Binary</a> &gt; &amp;&amp; Bin, bool KeepName)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~RawMemProfReader() {#afa3aedfb1ee64ce5ef518842c822ef9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::memprof::RawMemProfReader::~RawMemProfReader ()</td>
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



<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a30fc6abde4540cab3fa22516a3487631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RawMemProfReader &amp; llvm::memprof::RawMemProfReader::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memprof/rawmemprofreader">RawMemProfReader</a> &amp;)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>


<p>Reference <a href="#a4f729ba6865d20934390bcc34bcd21ce">RawMemProfReader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### printYAML() {#a2265dbec910f82a9711acc0619cfc1cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::memprof::RawMemProfReader::printYAML (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader/#a5433f28dd23b726c305096acb90b3f23">llvm::memprof::MemProfReader::MemProfData</a>.</p>

</div>
</div>

### readNextRecord() {#aa35ea12116aa94322f977239282e6e1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::memprof::RawMemProfReader::readNextRecord (<a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader/#ae57b87972d9c822df3642f18cae4e8bb">GuidMemProfRecordPair</a> &amp; GuidRecord, std::function&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/memprof/frame">Frame</a>(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ae2c822b1c6260b47be435d3eda363ccc">FrameId</a>)&gt; Callback)</td>
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



<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader/#a24cde697b280becd4df6c0e2eace1700">llvm::memprof::MemProfReader::idToFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader/#aa9e99c4516b416d029a11cf49b01e8c8">llvm::memprof::MemProfReader::Iter</a> and <a href="/web-llvm/docs/api/classes/llvm/memprof/memprofreader/#a7ebfa82e2e3b9ec55997fbad3f2a8e0c">llvm::memprof::MemProfReader::readNextRecord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getModuleOffset() {#aaf30b383e25b26d11e35171ffe0fddcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">object::SectionedAddress llvm::memprof::RawMemProfReader::getModuleOffset (uint64_t VirtualAddress)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>

</div>
</div>

### initialize() {#a513c0d12d72a7e66293d5f0b1ad60fcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::memprof::RawMemProfReader::initialize (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; DataBuffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>

</div>
</div>

### mapRawProfileToRecords() {#ada458df321dcac80cd0aa5ae83bca356}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::memprof::RawMemProfReader::mapRawProfileToRecords ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>

</div>
</div>

### readMemInfoBlocks() {#aeffcb0d0f411ed9ef0feabc1884041e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt; std::pair&lt; uint64_t, MemInfoBlock &gt; &gt; llvm::memprof::RawMemProfReader::readMemInfoBlocks (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>

</div>
</div>

### readRawProfile() {#a765dd80c8d320f69f17d6fb69e0c68af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::memprof::RawMemProfReader::readRawProfile (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; DataBuffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>

</div>
</div>

### setupForSymbolization() {#aa7ac26ac4d1b37cb95f27b87dbb42917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::memprof::RawMemProfReader::setupForSymbolization ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>

</div>
</div>

### symbolizeAndFilterStackFrames() {#aa1f5c269c6de33c82167a0fc53eb7615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::memprof::RawMemProfReader::symbolizeAndFilterStackFrames (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizablemodule">llvm::symbolize::SymbolizableModule</a> &gt; Symbolizer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Binary {#a6c8972c3a821d0e03991119da96e40a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">object::OwningBinary&lt;object::Binary&gt; llvm::memprof::RawMemProfReader::Binary</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

### CallstackProfileData {#a093e960586ba4d6705d258d26adeeffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MapVector&lt;uint64_t, MemInfoBlock&gt; llvm::memprof::RawMemProfReader::CallstackProfileData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

### GuidToSymbolName {#acc0bd49c46f23557b2f006e5d8eeb75e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DenseMap&lt;uint64_t, std::string&gt; llvm::memprof::RawMemProfReader::GuidToSymbolName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

### KeepSymbolName {#a56c693bffa655adcb4c16765567f6919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::RawMemProfReader::KeepSymbolName = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

### MemprofRawVersion {#a5ea20f53fc45866926ca4bb61e7fd947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::memprof::RawMemProfReader::MemprofRawVersion = MEMPROF_RAW_VERSION</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

### PreferredTextSegmentAddress {#a7fa5e60383444ca810ce163774dd5b5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::memprof::RawMemProfReader::PreferredTextSegmentAddress = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

### ProfiledTextSegmentEnd {#a11cfb152cbcd79b1c2881ff08fcfa87a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::memprof::RawMemProfReader::ProfiledTextSegmentEnd = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

### ProfiledTextSegmentStart {#ae7494542615a9e0c24e4d914adade156}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::memprof::RawMemProfReader::ProfiledTextSegmentStart = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

### SegmentInfo {#a05247f97086b8650ad96ad23b0f2bf23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt;SegmentEntry, 2&gt; llvm::memprof::RawMemProfReader::SegmentInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

### StackMap {#aac2a1e230ab55576d3f0d29c0a58f154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallStackMap llvm::memprof::RawMemProfReader::StackMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

### SymbolizedFrame {#a3e00e726be52518cf8c65ad95139888f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DenseMap&lt;uint64_t, llvm::SmallVector&lt;FrameId&gt; &gt; llvm::memprof::RawMemProfReader::SymbolizedFrame</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### create() {#a529ab1228d3ec2e3eb5e89d8871751ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; RawMemProfReader &gt; &gt; llvm::memprof::RawMemProfReader::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Path, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ProfiledBinary, bool KeepName=false)</td>
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



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>


<p>References <a href="#a529ab1228d3ec2e3eb5e89d8871751ba">create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a9c54e2428ad0163441789c281ca42ee4">llvm::MemoryBuffer::getFileOrSTDIN</a>.</p>


<p>Referenced by <a href="#a529ab1228d3ec2e3eb5e89d8871751ba">create</a>.</p>

</div>
</div>

### create() {#a0e40bbc853b758d181123ba30308e326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; RawMemProfReader &gt; &gt; llvm::memprof::RawMemProfReader::create (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Buffer, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ProfiledBinary, bool KeepName=false)</td>
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



<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="#a91e332bfcd4030aa1b14feb8792ff8f3">peekBuildIds</a> and <a href="#a4f729ba6865d20934390bcc34bcd21ce">RawMemProfReader</a>.</p>

</div>
</div>

### hasFormat() {#ab6239b296c0498d12a965b70fba539d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::RawMemProfReader::hasFormat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp; DataBuffer)</td>
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



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a2ea075bd68f15b57e95f0771b8ba0bca">llvm::MemoryBuffer::getBufferSize</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#af1972b9a0324e0311ad641eac2de2b7f">llvm::MemoryBuffer::getBufferStart</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/memprof/anonymous-memprofreader-cpp-/#a82b60c8deaa06915cacf9e571cb6f894">llvm::memprof::anonymous{MemProfReader.cpp}::checkBuffer</a> and <a href="#afaa5bd7225c533cda8178eb88b6b25fc">hasFormat</a>.</p>

</div>
</div>

### hasFormat() {#afaa5bd7225c533cda8178eb88b6b25fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::memprof::RawMemProfReader::hasFormat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
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



<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a9c54e2428ad0163441789c281ca42ee4">llvm::MemoryBuffer::getFileOrSTDIN</a> and <a href="#ab6239b296c0498d12a965b70fba539d7">hasFormat</a>.</p>

</div>
</div>

### peekBuildIds() {#a91e332bfcd4030aa1b14feb8792ff8f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::string &gt; llvm::memprof::RawMemProfReader::peekBuildIds (<a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> * DataBuffer)</td>
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



<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a>, definition at line 612 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#af1972b9a0324e0311ad641eac2de2b7f">llvm::MemoryBuffer::getBufferStart</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a> and <a href="/web-llvm/docs/api/classes/llvm/setvector/#a7c36580f905b274ca0a1ade46ba06ae0">llvm::SetVector&lt; T, Vector, Set, N &gt;::takeVector</a>.</p>


<p>Referenced by <a href="#a0e40bbc853b758d181123ba30308e326">create</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofreader-h">MemProfReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/memprofreader-cpp">MemProfReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
