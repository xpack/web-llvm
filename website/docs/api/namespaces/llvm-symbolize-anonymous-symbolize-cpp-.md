---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/symbolize/anonymous-symbolize-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{Symbolize.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::symbolize::anonymous{Symbolize.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09ab439d0ecd05e649734000a3e35478">getDarwinDWARFResourceForPath</a> (const std::string &amp;Path, const std::string &amp;Basename)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade75bef9f219b31ef89e452d482e59a7">checkFileCRC</a> (StringRef Path, uint32_t CRCHash)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca915d08912b7239d76d1044c7a8a073">getGNUDebuglinkContents</a> (const ObjectFile *Obj, std::string &amp;DebugName, uint32_t &amp;CRCHash)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a992787f0142954b821c221ff5a2c921f">darwinDsymMatchesBinary</a> (const MachOObjectFile *DbgObj, const MachOObjectFile *Obj)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae263aed138fcb0a6ceea9c9f29fcfb8d">demanglePE32ExternCFunc</a> (StringRef SymbolName)</td>
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


<div class="doxySectionDef">

## Functions

### checkFileCRC() {#ade75bef9f219b31ef89e452d482e59a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::symbolize::anonymous{Symbolize.cpp}::checkFileCRC (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, uint32_t CRCHash)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1b144823e66f38f789fb4909c29b8bec">llvm::arrayRefFromStringRef</a>, <a href="#ade75bef9f219b31ef89e452d482e59a7">checkFileCRC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b39f29a121496d294af31158c65740b">llvm::crc32</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a9c54e2428ad0163441789c281ca42ee4">llvm::MemoryBuffer::getFileOrSTDIN</a>.</p>


<p>Referenced by <a href="#ade75bef9f219b31ef89e452d482e59a7">checkFileCRC</a>.</p>

</div>
</div>

### darwinDsymMatchesBinary() {#a992787f0142954b821c221ff5a2c921f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::symbolize::anonymous{Symbolize.cpp}::darwinDsymMatchesBinary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * DbgObj, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">MachOObjectFile</a> * Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>


<p>References <a href="#a992787f0142954b821c221ff5a2c921f">darwinDsymMatchesBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#adb9cab4abca6bf2855c882dcf79fb1cb">llvm::ArrayRef&lt; T &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile/#a99d3e689123b378a1d01ac234f9a6d3c">llvm::object::MachOObjectFile::getUuid</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/mergeicmps-cpp/#affd23ab4a2fbb796128b383986b7286f">memcmp</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a992787f0142954b821c221ff5a2c921f">darwinDsymMatchesBinary</a>.</p>

</div>
</div>

### demanglePE32ExternCFunc() {#ae263aed138fcb0a6ceea9c9f29fcfb8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::symbolize::anonymous{Symbolize.cpp}::demanglePE32ExternCFunc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymbolName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="#ae263aed138fcb0a6ceea9c9f29fcfb8d">demanglePE32ExternCFunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82c27bc751f7669f9c2a79de96e2d0fd">llvm::isDigit</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>.</p>


<p>Referenced by <a href="#ae263aed138fcb0a6ceea9c9f29fcfb8d">demanglePE32ExternCFunc</a>.</p>

</div>
</div>

### getDarwinDWARFResourceForPath() {#a09ab439d0ecd05e649734000a3e35478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::symbolize::anonymous{Symbolize.cpp}::getDarwinDWARFResourceForPath (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Path, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Basename)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ad1056825d31bf187d0be430c51aac281">llvm::sys::path::extension</a> and <a href="#a09ab439d0ecd05e649734000a3e35478">getDarwinDWARFResourceForPath</a>.</p>


<p>Referenced by <a href="#a09ab439d0ecd05e649734000a3e35478">getDarwinDWARFResourceForPath</a>.</p>

</div>
</div>

### getGNUDebuglinkContents() {#aca915d08912b7239d76d1044c7a8a073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::symbolize::anonymous{Symbolize.cpp}::getGNUDebuglinkContents (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> * Obj, std::string &amp; DebugName, uint32_t &amp; CRCHash)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a17638a9e9146a6f6feef1adb50c53d2b">llvm::DataExtractor::getCStr</a>, <a href="#aca915d08912b7239d76d1044c7a8a073">getGNUDebuglinkContents</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a0eb55ea3f585f9c8a2619fe7250e56f4">llvm::DataExtractor::getU32</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#a638ca5d7bf4e2a09998c8e7fe8563ad8">llvm::object::Binary::isLittleEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad7e3a2f9134fa59a38cc0a86acaaf351">llvm::DataExtractor::isValidOffsetForDataOfSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a7f73649118e365a230be4870d824e7cf">llvm::object::ObjectFile::sections</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#aca915d08912b7239d76d1044c7a8a073">getGNUDebuglinkContents</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/symbolize/symbolize-cpp">Symbolize.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
