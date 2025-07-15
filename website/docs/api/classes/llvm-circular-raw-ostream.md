---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/circular-raw-ostream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `circular_raw_ostream` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream">circular_raw_ostream</a> - A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> which <em>can</em> save its data to a circular buffer, or can pass it through directly to an underlying stream if specified with a buffer of zero. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::circular_raw_ostream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">llvm/Support/circular_raw_ostream.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class implements an extremely fast bulk output stream that can <em>only</em> output to a stream. <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42664fb7b2765468ff290e0b46cbb079">circular_raw_ostream</a> (raw_ostream &amp;Stream, const char *Header, size_t BuffSize=0, bool Owns=REFERENCE_ONLY)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream">circular_raw_ostream</a> - Construct an optionally circular-buffered stream, handing it an underlying stream to do the "real" output. <a href="#a42664fb7b2765468ff290e0b46cbb079">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d4db71785e433a2a0aa7a37fbcacf5f">~circular_raw_ostream</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b76de8502785e9e581e759d51078b9">is_displayed</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if this stream is connected to a "tty" or "console" window. <a href="#a35b76de8502785e9e581e759d51078b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc8b7debcef19eb1c6c0dd39cec3f7f6">setStream</a> (raw_ostream &amp;Stream, bool Owns=REFERENCE_ONLY)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setStream - Tell the <a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream">circular_raw_ostream</a> to output a different stream. <a href="#abc8b7debcef19eb1c6c0dd39cec3f7f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d35e899d253649e0248ab661f741fa7">flushBufferWithBanner</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>flushBufferWithBanner - Force output of the buffer along with a small header. <a href="#a1d35e899d253649e0248ab661f741fa7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a246cd5cd0b20cea045bf611aa7d0417e">flushBuffer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>flushBuffer - Dump the contents of the buffer to Stream. <a href="#a246cd5cd0b20cea045bf611aa7d0417e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ee50576858d121ba88b01d7b507207f">write_impl</a> (const char *Ptr, size_t Size) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The is the piece of the class that is implemented by subclasses. <a href="#a2ee50576858d121ba88b01d7b507207f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac115d6e2cbc835e085a8a8567e3d8b67">current_pos</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>current_pos - Return the current position within the stream, not counting the bytes currently in the buffer. <a href="#ac115d6e2cbc835e085a8a8567e3d8b67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c7ec4459d82b49fde2d6037092cf7b1">releaseStream</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>releaseStream - Delete the held stream if needed. <a href="#a7c7ec4459d82b49fde2d6037092cf7b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a25d48be913c9d3e972288123c15a4">TheStream</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TheStream - The real stream we output to. <a href="#ac2a25d48be913c9d3e972288123c15a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35a14b4ed85ca288ddf14612f9181e33">OwnsStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>OwnsStream - Are we responsible for managing the underlying stream? <a href="#a35a14b4ed85ca288ddf14612f9181e33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a638b19f5e84b1872d2d0df22abe38a20">BufferSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BufferSize - The size of the buffer in bytes. <a href="#a638b19f5e84b1872d2d0df22abe38a20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8386877b34aa317aa6a782e296bcfe94">BufferArray</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>BufferArray - The actual buffer storage. <a href="#a8386877b34aa317aa6a782e296bcfe94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a147b7003dadb5ec30f860c069b17cca2">Cur</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cur - Pointer to the current output point in BufferArray. <a href="#a147b7003dadb5ec30f860c069b17cca2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa46745d9d1221ae2b39fc0472d96d22a">Filled</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Filled - Indicate whether the buffer has been completely filled. <a href="#aa46745d9d1221ae2b39fc0472d96d22a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac75243188b5111c39abbea1da5cf6968">Banner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Banner - A pointer to a banner to print before dumping the log. <a href="#ac75243188b5111c39abbea1da5cf6968">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bfd041e7afcbe159ca2f8aa2a0bb23a">TAKE_OWNERSHIP</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TAKE_OWNERSHIP - Tell this stream that it owns the underlying stream and is responsible for cleanup, memory management issues, etc. <a href="#a2bfd041e7afcbe159ca2f8aa2a0bb23a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70524ecd20bbff380a56e850d7ad0f2d">REFERENCE_ONLY</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>REFERENCE_ONLY - Tell this stream it should not manage the held stream. <a href="#a70524ecd20bbff380a56e850d7ad0f2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream">circular_raw_ostream</a> - A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> which <em>can</em> save its data to a circular buffer, or can pass it through directly to an underlying stream if specified with a buffer of zero.</p>

<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### circular\_raw\_ostream() {#a42664fb7b2765468ff290e0b46cbb079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::circular_raw_ostream::circular_raw_ostream (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Stream, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Header, size_t BuffSize=0, bool Owns=<a href="#a70524ecd20bbff380a56e850d7ad0f2d">REFERENCE_ONLY</a>)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream">circular_raw_ostream</a> - Construct an optionally circular-buffered stream, handing it an underlying stream to do the "real" output.</p>


<p>As a side effect, if BuffSize is nonzero, the given Stream is set to be Unbuffered. This is because <a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream">circular_raw_ostream</a> does its own buffering, so it doesn't want another layer of buffering to be happening underneath it.</p>


<p>"Owns" tells the <a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream">circular_raw_ostream</a> whether it is responsible for managing the held stream, doing memory management of it, etc.</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f4b64a0f7aec0a02e7f2ff5a6552723">llvm::raw_ostream::raw_ostream</a>, <a href="#a70524ecd20bbff380a56e850d7ad0f2d">REFERENCE_ONLY</a>, <a href="#abc8b7debcef19eb1c6c0dd39cec3f7f6">setStream</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~circular\_raw\_ostream() {#a0d4db71785e433a2a0aa7a37fbcacf5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::circular_raw_ostream::~circular_raw_ostream ()</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a> and <a href="#a1d35e899d253649e0248ab661f741fa7">flushBufferWithBanner</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### flushBufferWithBanner() {#a1d35e899d253649e0248ab661f741fa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void circular_raw_ostream::flushBufferWithBanner ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>flushBufferWithBanner - Force output of the buffer along with a small header.</p>

<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>, definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/support/circular-raw-ostream-cpp">circular_raw_ostream.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/debug-cpp/#a4113346ad7a761b7f9df8ae45f8c580c">debug_user_sig_handler</a> and <a href="#a0d4db71785e433a2a0aa7a37fbcacf5f">~circular_raw_ostream</a>.</p>

</div>
</div>

### is\_displayed() {#a35b76de8502785e9e581e759d51078b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::circular_raw_ostream::is_displayed ()</td>
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

<p>This function determines if this stream is connected to a "tty" or "console" window.</p>


<p>That is, the output would be displayed to the user rather than being put on a pipe or stored in a file.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>

</div>
</div>

### setStream() {#abc8b7debcef19eb1c6c0dd39cec3f7f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::circular_raw_ostream::setStream (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Stream, bool Owns=<a href="#a70524ecd20bbff380a56e850d7ad0f2d">REFERENCE_ONLY</a>)</td>
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

<p>setStream - Tell the <a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream">circular_raw_ostream</a> to output a different stream.</p>


<p>"Owns" tells <a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream">circular_raw_ostream</a> whether it should take responsibility for managing the underlying stream.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f4b64a0f7aec0a02e7f2ff5a6552723">llvm::raw_ostream::raw_ostream</a> and <a href="#a70524ecd20bbff380a56e850d7ad0f2d">REFERENCE_ONLY</a>.</p>


<p>Referenced by <a href="#a42664fb7b2765468ff290e0b46cbb079">circular_raw_ostream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### current\_pos() {#ac115d6e2cbc835e085a8a8567e3d8b67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::circular_raw_ostream::current_pos ()</td>
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

<p>current_pos - Return the current position within the stream, not counting the bytes currently in the buffer.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>

</div>
</div>

### flushBuffer() {#a246cd5cd0b20cea045bf611aa7d0417e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::circular_raw_ostream::flushBuffer ()</td>
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

<p>flushBuffer - Dump the contents of the buffer to Stream.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>

</div>
</div>

### releaseStream() {#a7c7ec4459d82b49fde2d6037092cf7b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::circular_raw_ostream::releaseStream ()</td>
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

<p>releaseStream - Delete the held stream if needed.</p>


<p>Otherwise, transfer the buffer settings from this <a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream">circular_raw_ostream</a> back to the underlying stream.</p>


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>

</div>
</div>

### write\_impl() {#a2ee50576858d121ba88b01d7b507207f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void circular_raw_ostream::write_impl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size)</td>
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

<p>The is the piece of the class that is implemented by subclasses.</p>


<p>This writes the <span class="doxyComputerOutput">Size</span> bytes starting at <span class="doxyComputerOutput">Ptr</span> to the underlying stream.</p>


<p>This function is guaranteed to only be called at a point at which it is safe for the subclass to install a new buffer via SetBuffer.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ptr</td>
<td class="doxyParamItemDescription"><p>The start of the data to be written. For buffered streams this is guaranteed to be the start of the buffer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>The number of bytes to be written.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Invariant</dt>
<dd><p>{ Size &gt; 0 }</p></dd>
</dl>


<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/support/circular-raw-ostream-cpp">circular_raw_ostream.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Banner {#ac75243188b5111c39abbea1da5cf6968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::circular_raw_ostream::Banner</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Banner - A pointer to a banner to print before dumping the log.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>

</div>
</div>

### BufferArray {#a8386877b34aa317aa6a782e296bcfe94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char* llvm::circular_raw_ostream::BufferArray = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BufferArray - The actual buffer storage.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>

</div>
</div>

### BufferSize {#a638b19f5e84b1872d2d0df22abe38a20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::circular_raw_ostream::BufferSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>BufferSize - The size of the buffer in bytes.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>

</div>
</div>

### Cur {#a147b7003dadb5ec30f860c069b17cca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char* llvm::circular_raw_ostream::Cur</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cur - Pointer to the current output point in BufferArray.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>

</div>
</div>

### Filled {#aa46745d9d1221ae2b39fc0472d96d22a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::circular_raw_ostream::Filled = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Filled - Indicate whether the buffer has been completely filled.</p>


<p>This helps avoid garbage output.</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>

</div>
</div>

### OwnsStream {#a35a14b4ed85ca288ddf14612f9181e33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::circular_raw_ostream::OwnsStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>OwnsStream - Are we responsible for managing the underlying stream?</p>

<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>

</div>
</div>

### TheStream {#ac2a25d48be913c9d3e972288123c15a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream* llvm::circular_raw_ostream::TheStream = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TheStream - The real stream we output to.</p>


<p>We set it to be unbuffered, since we're already doing our own buffering.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### REFERENCE\_ONLY {#a70524ecd20bbff380a56e850d7ad0f2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::circular_raw_ostream::REFERENCE_ONLY = false</td>
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

<p>REFERENCE_ONLY - Tell this stream it should not manage the held stream.</p>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>


<p>Referenced by <a href="#a42664fb7b2765468ff290e0b46cbb079">circular_raw_ostream</a> and <a href="#abc8b7debcef19eb1c6c0dd39cec3f7f6">setStream</a>.</p>

</div>
</div>

### TAKE\_OWNERSHIP {#a2bfd041e7afcbe159ca2f8aa2a0bb23a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::circular_raw_ostream::TAKE_OWNERSHIP = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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

<p>TAKE_OWNERSHIP - Tell this stream that it owns the underlying stream and is responsible for cleanup, memory management issues, etc.</p>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/circular-raw-ostream-h">circular_raw_ostream.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/circular-raw-ostream-cpp">circular_raw_ostream.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
