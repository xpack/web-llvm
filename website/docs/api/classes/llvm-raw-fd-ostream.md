---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/raw-fd-ostream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `raw_fd_ostream` Class Reference

<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that writes to a file descriptor. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::raw_fd_ostream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstract base class for streams implementations that also support a pwrite operation. <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream">raw_fd_stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> of a file for reading/writing/seeking. <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5462bc0fe5a61eccc662708da280e64">raw_fd_ostream</a> (StringRef Filename, std::error_code &amp;EC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Open the specified file for writing. <a href="#af5462bc0fe5a61eccc662708da280e64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f329fc4145f4e70ab4e391ba53c7c85">raw_fd_ostream</a> (StringRef Filename, std::error_code &amp;EC, sys::fs::CreationDisposition Disp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad93786127ef2bc2f4431394c24c9eea6">raw_fd_ostream</a> (StringRef Filename, std::error_code &amp;EC, sys::fs::FileAccess Access)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4038ac55437b8359cd7c95bc3ae0f94">raw_fd_ostream</a> (StringRef Filename, std::error_code &amp;EC, sys::fs::OpenFlags Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65aa4de0a6a0f21de4233170c7b012d5">raw_fd_ostream</a> (StringRef Filename, std::error_code &amp;EC, sys::fs::CreationDisposition Disp, sys::fs::FileAccess Access, sys::fs::OpenFlags Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8006c8875484467031d61b1e671cfede">raw_fd_ostream</a> (int fd, bool shouldClose, bool unbuffered=false, OStreamKind K=OStreamKind::OK_OStream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>FD is the file descriptor that this writes to. <a href="#a8006c8875484467031d61b1e671cfede">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77063e0754fec7f06f3cdfa9e9bb5c1b">~raw_fd_ostream</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a293545f9b5864a8e1b33e57becbc5b3a">close</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Manually flush the stream and close the file. <a href="#a293545f9b5864a8e1b33e57becbc5b3a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a651eedc8418fc6d2ee6bdaaff02cd72d">supportsSeeking</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98031dbf79580cd3975105f7397b9712">isRegularFile</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e2a27de71f137279ac47e6edd4abc47">seek</a> (uint64_t off)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flushes the stream and repositions the underlying file descriptor position to the offset specified from the beginning of the file. <a href="#a9e2a27de71f137279ac47e6edd4abc47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c2a4031566b90f46f0dc8329e670598">is_displayed</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if this stream is connected to a "tty" or "console" window. <a href="#a0c2a4031566b90f46f0dc8329e670598">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e526ce08487bfff0b9befaea2324cce">has_colors</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if this stream is displayed and supports colors. <a href="#a8e526ce08487bfff0b9befaea2324cce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63dfdb79daa6f106196f4acc2748ce43">tie</a> (raw_ostream *TieTo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tie this stream to the specified stream. <a href="#a63dfdb79daa6f106196f4acc2748ce43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215c95ed69aa5b5756dd9c0f1b1de410">error</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d5a564fb5459ab9ce6e56401786542b">has_error</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value of the flag in this <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> indicating whether an output error has been encountered. <a href="#a0d5a564fb5459ab9ce6e56401786542b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b4fefe70f73556669fd513ed9d0fae4">clear_error</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the flag read by <a href="#a0d5a564fb5459ab9ce6e56401786542b">has_error()</a> to false. <a href="#a7b4fefe70f73556669fd513ed9d0fae4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sys/fs/filelocker">sys::fs::FileLocker</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a33d325e887c5cfa94e8abac79145b3">lock</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Locks the underlying file. <a href="#a5a33d325e887c5cfa94e8abac79145b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sys/fs/filelocker">sys::fs::FileLocker</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add43014c83b068e09ccf25789ee0af48">tryLockFor</a> (Duration const &amp;Timeout)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tries to lock the underlying file within the specified period. <a href="#add43014c83b068e09ccf25789ee0af48">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af96ea3efa5212f54e22e5d5d01cf029c">error_detected</a> (std::error_code EC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the flag indicating that an output error has been encountered. <a href="#af96ea3efa5212f54e22e5d5d01cf029c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad429e128376a6912c6074e6c59dab97e">get_fd</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the file descriptor. <a href="#ad429e128376a6912c6074e6c59dab97e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45c7da9b34cb308a76ace46770cf9a82">inc_pos</a> (uint64_t Delta)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a025a0f815909cd5237226da9b60f35c8">write_impl</a> (const char *Ptr, size_t Size) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See raw_ostream::write_impl. <a href="#a025a0f815909cd5237226da9b60f35c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a643366c34481b229731d574e69da72ea">pwrite_impl</a> (const char *Ptr, size_t Size, uint64_t Offset) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac851444a5791310104499d25780008bd">current_pos</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current position within the stream, not counting the bytes currently in the buffer. <a href="#ac851444a5791310104499d25780008bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b758dae40418c832fa1c80a677e0abc">preferred_buffer_size</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine an efficient buffer size. <a href="#a2b758dae40418c832fa1c80a677e0abc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a325ee764a71da98299fdb729a636ea8e">anchor</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ea8ba12eaa2b2941cdba9fc17bc16bf">FD</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a792fdf2a036dc82a12f91543837c0aa5">ShouldClose</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab189b025f38e99a7b41626118866b48f">SupportsSeeking</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f3a19daee0fc03c9fbd4379fc70744">IsRegularFile</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16dbf52352f1bac9834d83f90f5f8d83">HasColors</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5a17ce5f41d702e8ff929d513d4b869">TiedStream</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional stream this stream is tied to. <a href="#af5a17ce5f41d702e8ff929d513d4b869">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a905a7b3427e8c6ea709342615c470d45">EC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ac8e79b69f1b8cfe33ee2403b7849a8">pos</a> = 0</td>
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

<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that writes to a file descriptor.</p>

<p>Definition at line 460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### raw\_fd\_ostream() {#af5462bc0fe5a61eccc662708da280e64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_ostream::raw_fd_ostream (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::error_code &amp; EC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Open the specified file for writing.</p>


<p>If an error occurs, information about the error is put into EC, and the stream should be immediately destroyed; <span class="doxyComputerOutput">Flags</span> allows optional flags to control how the file will be opened.</p>


<p>As a special case, if Filename is "-", then the stream will use STDOUT_FILENO instead of opening a file. This will not close the stdout descriptor.</p>


<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>Reference <a href="#af5462bc0fe5a61eccc662708da280e64">raw_fd_ostream</a>.</p>


<p>Referenced by <a href="#af5462bc0fe5a61eccc662708da280e64">raw_fd_ostream</a>, <a href="#a1f329fc4145f4e70ab4e391ba53c7c85">raw_fd_ostream</a>, <a href="#a65aa4de0a6a0f21de4233170c7b012d5">raw_fd_ostream</a>, <a href="#ad93786127ef2bc2f4431394c24c9eea6">raw_fd_ostream</a>, <a href="#ac4038ac55437b8359cd7c95bc3ae0f94">raw_fd_ostream</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream/#a26f27b402c83b3bd64d4b0c6ba2e798c">llvm::raw_fd_stream::raw_fd_stream</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream/#ac9a76e6fdfee784d51393f12ce7c5256">llvm::raw_fd_stream::raw_fd_stream</a>.</p>

</div>
</div>

### raw\_fd\_ostream() {#a1f329fc4145f4e70ab4e391ba53c7c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_ostream::raw_fd_ostream (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::error_code &amp; EC, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a93918b3a9b70253cd229fc5864884f58">sys::fs::CreationDisposition</a> Disp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>Reference <a href="#af5462bc0fe5a61eccc662708da280e64">raw_fd_ostream</a>.</p>

</div>
</div>

### raw\_fd\_ostream() {#ad93786127ef2bc2f4431394c24c9eea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_ostream::raw_fd_ostream (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::error_code &amp; EC, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5be5c24e530c666de488a0ed47e086ef">sys::fs::FileAccess</a> Access)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#adb4fa2b9065093d32736f78ea43a8c8a">Access</a> and <a href="#af5462bc0fe5a61eccc662708da280e64">raw_fd_ostream</a>.</p>

</div>
</div>

### raw\_fd\_ostream() {#ac4038ac55437b8359cd7c95bc3ae0f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_ostream::raw_fd_ostream (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::error_code &amp; EC, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695">sys::fs::OpenFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>Reference <a href="#af5462bc0fe5a61eccc662708da280e64">raw_fd_ostream</a>.</p>

</div>
</div>

### raw\_fd\_ostream() {#a65aa4de0a6a0f21de4233170c7b012d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_ostream::raw_fd_ostream (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, std::error_code &amp; EC, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a93918b3a9b70253cd229fc5864884f58">sys::fs::CreationDisposition</a> Disp, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a5be5c24e530c666de488a0ed47e086ef">sys::fs::FileAccess</a> Access, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695">sys::fs::OpenFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilresourceaccess-cpp/#adb4fa2b9065093d32736f78ea43a8c8a">Access</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp/#a2ef27606df20d46db5a3b4f58604ccba">getFD</a>, <a href="#af5462bc0fe5a61eccc662708da280e64">raw_fd_ostream</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>

</div>
</div>

### raw\_fd\_ostream() {#a8006c8875484467031d61b1e671cfede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_ostream::raw_fd_ostream (int fd, bool shouldClose, bool unbuffered=false, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad85a9ad7858d658c954afde33bcf3d43">OStreamKind</a> K=<a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ad85a9ad7858d658c954afde33bcf3d43a2bdd687fb19e606203cb02f5c50bf07b">OStreamKind::OK_OStream</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>FD is the file descriptor that this writes to.</p>


<p>If ShouldClose is true, this closes the file when the stream is destroyed. If FD is for stdout or stderr, it will not be closed.</p>


<p>If ShouldClose is true, this closes the file when the stream is destroyed.</p>


<p>Declaration at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#abb9477fc02ae36079df14aa77d8789c3">llvm::raw_ostream::enable_colors</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream/#a6114ce21446653490e1d609d876b42eb">llvm::raw_pwrite_stream::raw_pwrite_stream</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a6c50be965db24d7532b6b4e6b0755f5ca4676601564b208338edf7317182f473e">llvm::sys::fs::regular_file</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~raw\_fd\_ostream() {#a77063e0754fec7f06f3cdfa9e9bb5c1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_fd_ostream::~raw_fd_ostream ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="#a215c95ed69aa5b5756dd9c0f1b1de410">error</a>, <a href="#af96ea3efa5212f54e22e5d5d01cf029c">error_detected</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="#a0d5a564fb5459ab9ce6e56401786542b">has_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a0777b5060c78b24c4765fffbac259f93">llvm::sys::Process::SafelyCloseFileDescriptor</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear\_error() {#a7b4fefe70f73556669fd513ed9d0fae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_fd_ostream::clear_error ()</td>
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

<p>Set the flag read by <a href="#a0d5a564fb5459ab9ce6e56401786542b">has_error()</a> to false.</p>


<p>If the error flag is set at the time when this <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>'s destructor is called, report_fatal_error is called to report the error. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> <a href="#a7b4fefe70f73556669fd513ed9d0fae4">clear_error()</a> after handling the error to avoid this behavior.</p>


<p>"Errors should never pass silently.
   Unless explicitly silenced."</p>


<ul class="doxyList ">
<li>from The Zen of Python, by Tim Peters</li>
</ul>

<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#ae09841830258172ba68866f0376898eb">llvm::LockFileManager::LockFileManager</a> and <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#ae6c084cf21df6bb57da846088680146b">llvm::LTOCodeGenerator::writeMergedModules</a>.</p>

</div>
</div>

### close() {#a293545f9b5864a8e1b33e57becbc5b3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_fd_ostream::close ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Manually flush the stream and close the file.</p>


<p>Note that this does not call fsync.</p>


<p>Declaration at line 535 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 804 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af96ea3efa5212f54e22e5d5d01cf029c">error_detected</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a> and <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a0777b5060c78b24c4765fffbac259f93">llvm::sys::Process::SafelyCloseFileDescriptor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffdisplaygraph/#af15f59a940b7e5ce205f671241664985">anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::generateDotFile</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga4879fe0f5852edd39ea4a1e14d413bb0">LLVMPrintModuleToFile</a>, <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#ae09841830258172ba68866f0376898eb">llvm::LockFileManager::LockFileManager</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loadvalueinjectionloadhardening-cpp-/x86loadvalueinjectionloadhardeningpass/#a54e4ad32ffe88b1a55da7ca8c9d90521">anonymous{X86LoadValueInjectionLoadHardening.cpp}::X86LoadValueInjectionLoadHardeningPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a8eb4d536e570cc08e82d91095b892ed2">writeJSON</a> and <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#ae6c084cf21df6bb57da846088680146b">llvm::LTOCodeGenerator::writeMergedModules</a>.</p>

</div>
</div>

### error() {#a215c95ed69aa5b5756dd9c0f1b1de410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::raw_fd_ostream::error ()</td>
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



<p>Definition at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga4879fe0f5852edd39ea4a1e14d413bb0">LLVMPrintModuleToFile</a>, <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#ae09841830258172ba68866f0376898eb">llvm::LockFileManager::LockFileManager</a>, <a href="/web-llvm/docs/api/classes/llvm/unittest/tempfile/#a2277a37b366e2d68164f1ab32bb26dca">llvm::unittest::TempFile::TempFile</a>, <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#ae6c084cf21df6bb57da846088680146b">llvm::LTOCodeGenerator::writeMergedModules</a> and <a href="#a77063e0754fec7f06f3cdfa9e9bb5c1b">~raw_fd_ostream</a>.</p>

</div>
</div>

### has\_colors() {#a8e526ce08487bfff0b9befaea2324cce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool raw_fd_ostream::has_colors ()</td>
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

<p>This function determines if this stream is displayed and supports colors.</p>


<p>The result is unaffected by calls to enable_color().</p>


<p>Declaration at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 868 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a6c753dc2ccb8b41c097dee19f3690e0d">llvm::sys::Process::FileDescriptorHasColors</a>.</p>

</div>
</div>

### has\_error() {#a0d5a564fb5459ab9ce6e56401786542b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::raw_fd_ostream::has_error ()</td>
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

<p>Return the value of the flag in this <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream">raw_fd_ostream</a> indicating whether an output error has been encountered.</p>


<p>This doesn't implicitly flush any pending output. Also, it doesn't guarantee to detect all errors unless the stream has been closed.</p>


<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga4879fe0f5852edd39ea4a1e14d413bb0">LLVMPrintModuleToFile</a>, <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#ae09841830258172ba68866f0376898eb">llvm::LockFileManager::LockFileManager</a>, <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#ae6c084cf21df6bb57da846088680146b">llvm::LTOCodeGenerator::writeMergedModules</a> and <a href="#a77063e0754fec7f06f3cdfa9e9bb5c1b">~raw_fd_ostream</a>.</p>

</div>
</div>

### is\_displayed() {#a0c2a4031566b90f46f0dc8329e670598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool raw_fd_ostream::is_displayed ()</td>
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

<p>This function determines if this stream is connected to a "tty" or "console" window.</p>


<p>That is, the output would be displayed to the user rather than being put on a pipe or stored in a file.</p>


<p>Declaration at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 864 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a2bd9c876be050d32ff622ef5b562bb4e">llvm::sys::Process::FileDescriptorIsDisplayed</a>.</p>

</div>
</div>

### isRegularFile() {#a98031dbf79580cd3975105f7397b9712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::raw_fd_ostream::isRegularFile ()</td>
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



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream/#ac9a76e6fdfee784d51393f12ce7c5256">llvm::raw_fd_stream::raw_fd_stream</a>.</p>

</div>
</div>

### lock() {#a5a33d325e887c5cfa94e8abac79145b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; sys::fs::FileLocker &gt; raw_fd_ostream::lock ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Locks the underlying file.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>RAII object that releases the lock upon leaving the scope, if the locking was successful. Otherwise returns corresponding error code.</p></dd>
</dl>


<p>The function blocks the current thread until the lock become available or error occurs.</p>


<p>Possible use of this function may be as follows:</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> L = stream.lock()) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// ... do action that require file to be locked.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">} </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-llvm/docs/api/namespaces/llvm/#a2aa0f5c36ac6291f5d5f2b4efd9ffe70">handleAllErrors</a>(std::move(<a href="/web-llvm/docs/api/namespaces/llvm/m68k/#ab3a288f2953d8eca3e363959fc2cf38ead20caec3b48a1eef164cb4ca81ba2587">L</a>.takeError()), [&amp;](ErrorInfoBase &amp;EIB) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// ... handle lock error.</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  });</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Declaration at line 595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 874 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a8cfdb79a3567fce1c216d03ee1c92663">llvm::sys::fs::lockFile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a8eb4d536e570cc08e82d91095b892ed2">writeJSON</a>.</p>

</div>
</div>

### seek() {#a9e2a27de71f137279ac47e6edd4abc47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t raw_fd_ostream::seek (uint64_t off)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flushes the stream and repositions the underlying file descriptor position to the offset specified from the beginning of the file.</p>

<p>Declaration at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 813 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae075c94db10b09d6d5876d32219eaf0d">llvm::errnoAsErrorCode</a>, <a href="#af96ea3efa5212f54e22e5d5d01cf029c">error_detected</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp/#a498738d65e5a3c57d210f97b7a475d54">pad</a>, <a href="/web-llvm/docs/api/classes/llvm/cgdataostream/#a1d951f57be86b30e864740019b41f0f2">llvm::CGDataOStream::patch</a> and <a href="/web-llvm/docs/api/classes/llvm/profostream/#a52299b07451a31e9fc5a62e305d5fe21">llvm::ProfOStream::patch</a>.</p>

</div>
</div>

### supportsSeeking() {#a651eedc8418fc6d2ee6bdaaff02cd72d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::raw_fd_ostream::supportsSeeking ()</td>
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



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### tie() {#a63dfdb79daa6f106196f4acc2748ce43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_fd_ostream::tie (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> * TieTo)</td>
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

<p>Tie this stream to the specified stream.</p>


<p>Replaces any existing tied-to stream. Specifying a nullptr unties the stream. This is intended for to tie <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">errs()</a> to <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">outs()</a>, so that <a href="/web-llvm/docs/api/namespaces/llvm/#a2d79a00fa7c56f57b87f2fe2a3f118c7">outs()</a> is flushed whenever something is written to <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">errs()</a>, preventing weird and hard-to-test output when stderr is redirected to stdout.</p>


<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### tryLockFor() {#add43014c83b068e09ccf25789ee0af48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; sys::fs::FileLocker &gt; raw_fd_ostream::tryLockFor (<a href="/web-llvm/docs/api/classes/llvm/duration">Duration</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Timeout)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tries to lock the underlying file within the specified period.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>RAII object that releases the lock upon leaving the scope, if the locking was successful. Otherwise returns corresponding error code.</p></dd>
</dl>


<p>It is used as <a href="#a5a33d325e887c5cfa94e8abac79145b3">lock</a>.</p>


<p>Declaration at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 882 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/classes/llvm/duration/#acd16cd299fd2560ad59a03f2e718a35a">llvm::Duration::getDuration</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a2b8ef26c55540747c5f83d0cd898fe92">llvm::sys::fs::tryLockFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### error\_detected() {#af96ea3efa5212f54e22e5d5d01cf029c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_fd_ostream::error_detected (std::error_code EC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the flag indicating that an output error has been encountered.</p>

<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="#a293545f9b5864a8e1b33e57becbc5b3a">close</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream/#af64d05ca7d5c140c9a967027408c93a8">llvm::raw_fd_stream::read</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream/#af22cc7ec55d3e7b68bf83856ed991f0e">llvm::raw_socket_stream::read</a>, <a href="#a9e2a27de71f137279ac47e6edd4abc47">seek</a> and <a href="#a77063e0754fec7f06f3cdfa9e9bb5c1b">~raw_fd_ostream</a>.</p>

</div>
</div>

### get\_fd() {#ad429e128376a6912c6074e6c59dab97e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::raw_fd_ostream::get_fd ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the file descriptor.</p>

<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream/#af64d05ca7d5c140c9a967027408c93a8">llvm::raw_fd_stream::read</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-socket-stream/#af22cc7ec55d3e7b68bf83856ed991f0e">llvm::raw_socket_stream::read</a>.</p>

</div>
</div>

### inc\_pos() {#a45c7da9b34cb308a76ace46770cf9a82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_fd_ostream::inc_pos (uint64_t Delta)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream/#af64d05ca7d5c140c9a967027408c93a8">llvm::raw_fd_stream::read</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a325ee764a71da98299fdb729a636ea8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_fd_ostream::anchor ()</td>
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



<p>Declaration at line 493 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 889 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

### current\_pos() {#ac851444a5791310104499d25780008bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::raw_fd_ostream::current_pos ()</td>
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

<p>Return the current position within the stream, not counting the bytes currently in the buffer.</p>

<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### preferred\_buffer\_size() {#a2b758dae40418c832fa1c80a677e0abc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t raw_fd_ostream::preferred_buffer_size ()</td>
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

<p>Determine an efficient buffer size.</p>

<p>Declaration at line 491 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 834 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

### pwrite\_impl() {#a643366c34481b229731d574e69da72ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_fd_ostream::pwrite_impl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size, uint64_t Offset)</td>
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



<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 826 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

### write\_impl() {#a025a0f815909cd5237226da9b60f35c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_fd_ostream::write_impl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size)</td>
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

<p>See raw_ostream::write_impl.</p>

<p>Declaration at line 482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 736 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EC {#a905a7b3427e8c6ea709342615c470d45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::raw_fd_ostream::EC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### FD {#a9ea8ba12eaa2b2941cdba9fc17bc16bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::raw_fd_ostream::FD</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### HasColors {#a16dbf52352f1bac9834d83f90f5f8d83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::raw_fd_ostream::HasColors</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### IsRegularFile {#ac5f3a19daee0fc03c9fbd4379fc70744}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::raw_fd_ostream::IsRegularFile = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### pos {#a0ac8e79b69f1b8cfe33ee2403b7849a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::raw_fd_ostream::pos = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### ShouldClose {#a792fdf2a036dc82a12f91543837c0aa5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::raw_fd_ostream::ShouldClose</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### SupportsSeeking {#ab189b025f38e99a7b41626118866b48f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::raw_fd_ostream::SupportsSeeking = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### TiedStream {#af5a17ce5f41d702e8ff929d513d4b869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream* llvm::raw_fd_ostream::TiedStream = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optional stream this stream is tied to.</p>


<p>If this stream is written to, the tied-to stream will be flushed first.</p>


<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
