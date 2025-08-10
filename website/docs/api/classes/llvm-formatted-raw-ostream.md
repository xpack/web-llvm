---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/formatted-raw-ostream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `formatted_raw_ostream` Class

<p><a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> - A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that wraps another one and keeps track of line and column position, allowing padding out to specific column boundaries and querying the number of lines written to the stream. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::formatted_raw_ostream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">llvm/Support/FormattedStream.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb8a7ef601b3598707e6ae9a6c9f6e4d">formatted_raw_ostream</a> (raw_ostream &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> - Open the specified file for writing. <a href="#adb8a7ef601b3598707e6ae9a6c9f6e4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91b597f0ba8945f847b8df2ff00e5880">formatted_raw_ostream</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb361f836554627ef51810e0d3646c6">~formatted_raw_ostream</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fc7f913807a21ba5a42df7cc2d2e748">PadToColumn</a> (unsigned NewCol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PadToColumn - <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> the output to some column number. <a href="#a1fc7f913807a21ba5a42df7cc2d2e748">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65290bab4b83149e403bf48709658bd1">getColumn</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88de341253439019e912f01fcd55c45b">getLine</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a255a1144d50063acc74b8b5143697694">resetColor</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resets the colors to terminal defaults. <a href="#a255a1144d50063acc74b8b5143697694">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55e6fb1fbaadb04b201cba1f302d7b9">reverseColor</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reverses the foreground and background colors. <a href="#af55e6fb1fbaadb04b201cba1f302d7b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28c28221c236cdabcd2e6553854ed278">changeColor</a> (enum Colors Color, bool Bold, bool BG) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Changes the foreground color of text that will be output from this point forward. <a href="#a28c28221c236cdabcd2e6553854ed278">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0af326688c69076ecde5af500a1a7d5f">is_displayed</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if this stream is connected to a "tty" or "console" window. <a href="#a0af326688c69076ecde5af500a1a7d5f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe0dc170ee1ac6595ff41750af4437fc">write_impl</a> (const char *Ptr, size_t Size) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The is the piece of the class that is implemented by subclasses. <a href="#abe0dc170ee1ac6595ff41750af4437fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd79d672c078032c99364eb43bc5c9a8">current_pos</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>current_pos - Return the current position within the stream, not counting the bytes currently in the buffer. <a href="#afd79d672c078032c99364eb43bc5c9a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2497e9ad2f28aab73f9015b9d1d30172">ComputePosition</a> (const char *Ptr, size_t size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ComputePosition - Examine the given output buffer and figure out the new position after output. <a href="#a2497e9ad2f28aab73f9015b9d1d30172">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf580e50faf88ebc55f95743e66d8a5a">UpdatePosition</a> (const char *Ptr, size_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>UpdatePosition - scan the characters in [Ptr, Ptr+Size), and update the line and column numbers. <a href="#aaf580e50faf88ebc55f95743e66d8a5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb3b11a04b2549a7903574535de34ea0">setStream</a> (raw_ostream &amp;Stream)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab89838a7698af16868b562f9914386e5">PreDisableScan</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a9bf000f361c47c7fb4162d7bc46fdf">PostDisableScan</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81acdaa9ede919f1eed45bee715afa6e">releaseStream</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56328b4f76c62594d9aab1a7c150e858">TheStream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TheStream - The real stream we output to. <a href="#a56328b4f76c62594d9aab1a7c150e858">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; unsigned, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d20fff48491cf6e6182fa6a4413dc6e">Position</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Position - The current output column and line of the data that's been flushed and the portion of the buffer that's been scanned. <a href="#a7d20fff48491cf6e6182fa6a4413dc6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f19693bce22f37bae1e485024982d80">Scanned</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Scanned - This points to one past the last character in the buffer we've scanned. <a href="#a2f19693bce22f37bae1e485024982d80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a490061834f20e68204c00bd9bc577e14">PartialUTF8Char</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PartialUTF8Char - Either empty or a prefix of a UTF-8 code unit sequence for a Unicode scalar value which should be prepended to the buffer for the next call to ComputePosition. <a href="#a490061834f20e68204c00bd9bc577e14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22cad4e0c4f043b325ef2aac881871e5">DisableScan</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DisableScan - Temporarily disable scanning of output. <a href="#a22cad4e0c4f043b325ef2aac881871e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> - A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that wraps another one and keeps track of line and column position, allowing padding out to specific column boundaries and querying the number of lines written to the stream.</p>


<p>This assumes that the contents of the stream is valid UTF-8 encoded text. This doesn't attempt to handle everything Unicode can do (combining characters, right-to-left markers, etc), but should cover the cases likely to appear in source code or diagnostic messages.</p>


<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### formatted\_raw\_ostream() {#adb8a7ef601b3598707e6ae9a6c9f6e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::formatted_raw_ostream::formatted_raw_ostream (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Stream)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> - Open the specified file for writing.</p>


<p>If an error occurs, information about the error is put into <a href="/web-llvm/docs/api/classes/llvm/errorinfo">ErrorInfo</a>, and the stream should be immediately destroyed; the string will be empty if no error occurred.</p>


<p>As a side effect, the given Stream is set to be Unbuffered. This is because <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> does its own buffering, so it doesn't want another layer of buffering to be happening underneath it.</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f4b64a0f7aec0a02e7f2ff5a6552723">llvm::raw_ostream::raw_ostream</a>.</p>


<p>Referenced by <a href="#a1fc7f913807a21ba5a42df7cc2d2e748">PadToColumn</a>.</p>

</div>
</div>

### formatted\_raw\_ostream() {#a91b597f0ba8945f847b8df2ff00e5880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::formatted_raw_ostream::formatted_raw_ostream ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~formatted\_raw\_ostream() {#a0eb361f836554627ef51810e0d3646c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::formatted_raw_ostream::~formatted_raw_ostream ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### changeColor() {#a28c28221c236cdabcd2e6553854ed278}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::formatted_raw_ostream::changeColor (enum <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a> Color, bool Bold, bool BG)</td>
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

<p>Changes the foreground color of text that will be output from this point forward.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Color</td>
<td class="doxyParamItemDescription"><p>ANSI color to use, the special SAVEDCOLOR can be used to change only the bold attribute, and keep colors untouched</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bold</td>
<td class="doxyParamItemDescription"><p>bold/brighter text, default false</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BG</td>
<td class="doxyParamItemDescription"><p>if true change the background, default: change foreground</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>itself so it can be used within &lt;&lt; invocations</p></dd>
</dl>


<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a28fa4a2054d6d628fa4eea21c5262212">llvm::raw_ostream::changeColor</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#aff9ac3b7e5094380eca385afd6023cd4">llvm::raw_ostream::colors_enabled</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f4b64a0f7aec0a02e7f2ff5a6552723">llvm::raw_ostream::raw_ostream</a>.</p>

</div>
</div>

### getColumn() {#a65290bab4b83149e403bf48709658bd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::formatted_raw_ostream::getColumn ()</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a980ad6112624b521eb2d831b39b346eb">llvm::raw_ostream::getBufferStart</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad6cd89674692383208613b1e4ee560fe">llvm::raw_ostream::GetNumBytesInBuffer</a>.</p>


<p>Referenced by <a href="#a1fc7f913807a21ba5a42df7cc2d2e748">PadToColumn</a>.</p>

</div>
</div>

### getLine() {#a88de341253439019e912f01fcd55c45b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::formatted_raw_ostream::getLine ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a980ad6112624b521eb2d831b39b346eb">llvm::raw_ostream::getBufferStart</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad6cd89674692383208613b1e4ee560fe">llvm::raw_ostream::GetNumBytesInBuffer</a>.</p>

</div>
</div>

### is\_displayed() {#a0af326688c69076ecde5af500a1a7d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::formatted_raw_ostream::is_displayed ()</td>
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


<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>

</div>
</div>

### PadToColumn() {#a1fc7f913807a21ba5a42df7cc2d2e748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">formatted_raw_ostream &amp; formatted_raw_ostream::PadToColumn (unsigned NewCol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PadToColumn - <a href="/web-llvm/docs/api/structs/llvm/align">Align</a> the output to some column number.</p>


<p>If the current column is already equal to or more than NewCol, PadToColumn inserts one space.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">NewCol</td>
<td class="doxyParamItemDescription"><p>- The column to move to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NewCol</td>
<td class="doxyParamItemDescription"><p>- The column to move to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/support/formattedstream-cpp">FormattedStream.cpp</a>.</p>


<p>References <a href="#adb8a7ef601b3598707e6ae9a6c9f6e4d">formatted_raw_ostream</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a980ad6112624b521eb2d831b39b346eb">llvm::raw_ostream::getBufferStart</a>, <a href="#a65290bab4b83149e403bf48709658bd1">getColumn</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad6cd89674692383208613b1e4ee560fe">llvm::raw_ostream::GetNumBytesInBuffer</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#a0e50dc982f01eab3eeb5eef624e25f03">emitComments</a>.</p>

</div>
</div>

### resetColor() {#a255a1144d50063acc74b8b5143697694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::formatted_raw_ostream::resetColor ()</td>
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

<p>Resets the colors to terminal defaults.</p>


<p>Call this when you are done outputting colored text, or before program exit.</p>


<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#aff9ac3b7e5094380eca385afd6023cd4">llvm::raw_ostream::colors_enabled</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f4b64a0f7aec0a02e7f2ff5a6552723">llvm::raw_ostream::raw_ostream</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a4219e33c3cd0cc8383f615fc40254d21">llvm::raw_ostream::resetColor</a>.</p>

</div>
</div>

### reverseColor() {#af55e6fb1fbaadb04b201cba1f302d7b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::formatted_raw_ostream::reverseColor ()</td>
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

<p>Reverses the foreground and background colors.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#aff9ac3b7e5094380eca385afd6023cd4">llvm::raw_ostream::colors_enabled</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f4b64a0f7aec0a02e7f2ff5a6552723">llvm::raw_ostream::raw_ostream</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6095e2a0ebe961a05e2b3a7b6acbe769">llvm::raw_ostream::reverseColor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### ComputePosition() {#a2497e9ad2f28aab73f9015b9d1d30172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void formatted_raw_ostream::ComputePosition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ComputePosition - Examine the given output buffer and figure out the new position after output.</p>


<p>ComputePosition - Examine the current output and update line and column counts.</p>


<p>This is safe to call multiple times on the same buffer, as it records the most recently scanned character and resumes from there when the buffer has not been flushed.</p>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>, definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/support/formattedstream-cpp">FormattedStream.cpp</a>.</p>

</div>
</div>

### current\_pos() {#afd79d672c078032c99364eb43bc5c9a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::formatted_raw_ostream::current_pos ()</td>
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

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>

</div>
</div>

### PostDisableScan() {#a2a9bf000f361c47c7fb4162d7bc46fdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::formatted_raw_ostream::PostDisableScan ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>

</div>
</div>

### PreDisableScan() {#ab89838a7698af16868b562f9914386e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::formatted_raw_ostream::PreDisableScan ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>

</div>
</div>

### releaseStream() {#a81acdaa9ede919f1eed45bee715afa6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::formatted_raw_ostream::releaseStream ()</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>

</div>
</div>

### setStream() {#abb3b11a04b2549a7903574535de34ea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::formatted_raw_ostream::setStream (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Stream)</td>
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



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>

</div>
</div>

### UpdatePosition() {#aaf580e50faf88ebc55f95743e66d8a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void formatted_raw_ostream::UpdatePosition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>UpdatePosition - scan the characters in [Ptr, Ptr+Size), and update the line and column numbers.</p>


<p>UpdatePosition - Examine the given char sequence and figure out which column we end up in after output, and how many line breaks are contained.</p>


<p>Unlike ComputePosition, this must be called exactly once on each region of the buffer.</p>


<p>This assumes that the input string is well-formed UTF-8, and takes into account Unicode characters which render as multiple columns wide.</p>


<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/support/formattedstream-cpp">FormattedStream.cpp</a>.</p>

</div>
</div>

### write\_impl() {#abe0dc170ee1ac6595ff41750af4437fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void formatted_raw_ostream::write_impl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size)</td>
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


<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/support/formattedstream-cpp">FormattedStream.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DisableScan {#a22cad4e0c4f043b325ef2aac881871e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::formatted_raw_ostream::DisableScan</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DisableScan - Temporarily disable scanning of output.</p>


<p>Used to ignore color codes.</p>


<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>

</div>
</div>

### PartialUTF8Char {#a490061834f20e68204c00bd9bc577e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;4&gt; llvm::formatted_raw_ostream::PartialUTF8Char</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>PartialUTF8Char - Either empty or a prefix of a UTF-8 code unit sequence for a Unicode scalar value which should be prepended to the buffer for the next call to ComputePosition.</p>


<p>This is needed when the buffer is flushed when it ends part-way through the UTF-8 encoding of a Unicode scalar value, so that we can compute the display width of the character once we have the rest of it.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>

</div>
</div>

### Position {#a7d20fff48491cf6e6182fa6a4413dc6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt;unsigned, unsigned&gt; llvm::formatted_raw_ostream::Position</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Position - The current output column and line of the data that's been flushed and the portion of the buffer that's been scanned.</p>


<p>The line and column scheme is zero-based.</p>


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>

</div>
</div>

### Scanned {#a2f19693bce22f37bae1e485024982d80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::formatted_raw_ostream::Scanned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Scanned - This points to one past the last character in the buffer we've scanned.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>

</div>
</div>

### TheStream {#a56328b4f76c62594d9aab1a7c150e858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream* llvm::formatted_raw_ostream::TheStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TheStream - The real stream we output to.</p>


<p>We set it to be unbuffered, since we're already doing our own buffering.</p>


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">FormattedStream.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/formattedstream-cpp">FormattedStream.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
