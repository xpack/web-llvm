---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sys/process
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Process` Class Reference

<p>A collection of legacy interfaces for querying information about the current executing process. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sys::Process { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">llvm/Support/Process.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af96f4ca9b4641dfa3b45ed1a07a7d525">Pid</a> = int32_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#af96f4ca9b4641dfa3b45ed1a07a7d525">Pid</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afee014293ce837f92658166fc36a2d15">getProcessId</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the process's identifier. <a href="#afee014293ce837f92658166fc36a2d15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b6f374dc4eb2a7f84cc346e5630e132">getPageSize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the process's page size. <a href="#a2b6f374dc4eb2a7f84cc346e5630e132">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a774becf3d10728695b270703bca011ec">getPageSizeEstimate</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the process's estimated page size. <a href="#a774becf3d10728695b270703bca011ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb2b72e3e500a8b559e5d8c265b40e6">GetMallocUsage</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return process memory usage. <a href="#aefb2b72e3e500a8b559e5d8c265b40e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac44dcee71ca072093786da6b7d04149c">GetTimeUsage</a> (TimePoint&lt;&gt; &amp;elapsed, std::chrono::nanoseconds &amp;user_time, std::chrono::nanoseconds &amp;sys_time)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This static function will set <span class="doxyComputerOutput">user_time</span> to the amount of CPU time spent in user (non-kernel) mode and <span class="doxyComputerOutput">sys_time</span> to the amount of CPU time spent in system (kernel) mode. <a href="#ac44dcee71ca072093786da6b7d04149c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a044be33f2a65605a957e19d5e8d549a5">PreventCoreFiles</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function makes the necessary calls to the operating system to prevent core files or any other kind of large memory dumps that can occur when a program fails. <a href="#a044be33f2a65605a957e19d5e8d549a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92a5bd75c81ada9ad86716daac4a4fdc">AreCoreFilesPrevented</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>true if PreventCoreFiles has been called, false otherwise. <a href="#a92a5bd75c81ada9ad86716daac4a4fdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8806fc38b760a88a96d5d7fb67de545f">GetEnv</a> (StringRef name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d23569135fe239b43594b6e8b99e67e">FindInEnvPath</a> (StringRef EnvName, StringRef FileName, ArrayRef&lt; std::string &gt; IgnoreList, char Separator=EnvPathSeparator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function searches for an existing file in the list of directories in a PATH like environment variable, and returns the first file found, according to the order of the entries in the PATH like environment variable. <a href="#a2d23569135fe239b43594b6e8b99e67e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab97a24142bebbcf14ce0d586645abb5e">FindInEnvPath</a> (StringRef EnvName, StringRef FileName, char Separator=EnvPathSeparator)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafb9f9b515200177db8c2bde7e02c4b3">FixupStandardFileDescriptors</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::error_code</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0777b5060c78b24c4765fffbac259f93">SafelyCloseFileDescriptor</a> (int FD)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2aac231a0752ab9d6c3d7bae48f7adc">StandardInIsUserInput</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if the standard input is connected directly to a user's input (keyboard probably), rather than coming from a file or pipe. <a href="#ad2aac231a0752ab9d6c3d7bae48f7adc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2af58ec26c804a6836864d970c78df1">StandardOutIsDisplayed</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if the standard output is connected to a "tty" or "console" window. <a href="#ab2af58ec26c804a6836864d970c78df1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30f5096a2364f58d967775a553c1143b">StandardErrIsDisplayed</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if the standard error is connected to a "tty" or "console" window. <a href="#a30f5096a2364f58d967775a553c1143b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bd9c876be050d32ff622ef5b562bb4e">FileDescriptorIsDisplayed</a> (int fd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if the given file descriptor is connected to a "tty" or "console" window. <a href="#a2bd9c876be050d32ff622ef5b562bb4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c753dc2ccb8b41c097dee19f3690e0d">FileDescriptorHasColors</a> (int fd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if the given file descriptor is displayd and supports colors. <a href="#a6c753dc2ccb8b41c097dee19f3690e0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab21a24de36e15ce39ddb32192ff723ef">StandardOutColumns</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines the number of columns in the window if standard output is connected to a "tty" or "console" window. <a href="#ab21a24de36e15ce39ddb32192ff723ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89927683c57b686c4694bbc0ee822653">StandardErrColumns</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines the number of columns in the window if standard error is connected to a "tty" or "console" window. <a href="#a89927683c57b686c4694bbc0ee822653">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2512fe676260dcee1c2ba5e917dad4aa">StandardOutHasColors</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines whether the terminal connected to standard output supports colors. <a href="#a2512fe676260dcee1c2ba5e917dad4aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae619d8f1ff7ce90bd18ee54d504b126">StandardErrHasColors</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines whether the terminal connected to standard error supports colors. <a href="#aae619d8f1ff7ce90bd18ee54d504b126">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f01fd2553456500f600d83db62c6932">UseANSIEscapeCodes</a> (bool enable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enables or disables whether ANSI escape sequences are used to output colors. <a href="#a6f01fd2553456500f600d83db62c6932">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae688bc9ea544596962674ee94437ec00">ColorNeedsFlush</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether changing colors requires the output to be flushed. <a href="#ae688bc9ea544596962674ee94437ec00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17881ed9155bdf983b849c4c69c365b0">OutputColor</a> (char c, bool bold, bool bg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function returns the colorcode escape sequences. <a href="#a17881ed9155bdf983b849c4c69c365b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f838fbf3e04fdf7763b38ae5c499bbe">OutputBold</a> (bool bg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as OutputColor, but only enables the bold attribute. <a href="#a5f838fbf3e04fdf7763b38ae5c499bbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad9fc0056cabdeff2e16f13ec879688f">OutputReverse</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function returns the escape sequence to reverse forground and background colors. <a href="#aad9fc0056cabdeff2e16f13ec879688f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add81bb27661c8bce42dee6b4b5828e83">ResetColor</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resets the terminals colors, or returns an escape sequence to do so. <a href="#add81bb27661c8bce42dee6b4b5828e83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92b058c34d04f6d0adf6eac3060343c6">GetRandomNumber</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the result of a process wide random number generator. <a href="#a92b058c34d04f6d0adf6eac3060343c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38ee110d150d9b436e4d01405bd7f1a9">Exit</a> (int RetCode, bool NoCleanup=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Equivalent to ::exit(), except when running inside a <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a>. <a href="#a38ee110d150d9b436e4d01405bd7f1a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6dbd188251c69c120952f5ce81b1d4b">ExitNoCleanup</a> (int RetCode)</td>
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

<p>A collection of legacy interfaces for querying information about the current executing process.</p>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Pid {#af96f4ca9b4641dfa3b45ed1a07a7d525}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sys::Process::Pid =  int32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### AreCoreFilesPrevented() {#a92a5bd75c81ada9ad86716daac4a4fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Process::AreCoreFilesPrevented ()</td>
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

<p>true if PreventCoreFiles has been called, false otherwise.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/support/process-cpp">Process.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/process-cpp/#a3e1976a70072c9f199a4b9ab049faf4b">coreFilesPrevented</a>.</p>

</div>
</div>

### ColorNeedsFlush() {#ae688bc9ea544596962674ee94437ec00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::Process::ColorNeedsFlush ()</td>
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

<p>Whether changing colors requires the output to be flushed.</p>


<p>This is needed on systems that don't support escape sequences for changing colors.</p>


<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

### Exit() {#a38ee110d150d9b436e4d01405bd7f1a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Process::Exit (int RetCode, bool NoCleanup=false)</td>
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

<p>Equivalent to ::exit(), except when running inside a <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext">CrashRecoveryContext</a>.</p>


<p>In that case, the control flow will resume after RunSafely(), like for a crash, rather than exiting the current process. <a href="/web-llvm/docs/api/classes/llvm/use">Use</a></p>


<ul class="doxyList ">
<li>NoCleanup for calling _exit() instead of exit().</li>
</ul>

<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/support/process-cpp">Process.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/crashrecoverycontext/#a105fa65624c954b0a44d73615cbbeba1">llvm::CrashRecoveryContext::GetCurrent</a>.</p>

</div>
</div>

### FileDescriptorHasColors() {#a6c753dc2ccb8b41c097dee19f3690e0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::Process::FileDescriptorHasColors (int fd)</td>
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

<p>This function determines if the given file descriptor is displayd and supports colors.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a8e526ce08487bfff0b9befaea2324cce">llvm::raw_fd_ostream::has_colors</a>.</p>

</div>
</div>

### FileDescriptorIsDisplayed() {#a2bd9c876be050d32ff622ef5b562bb4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::Process::FileDescriptorIsDisplayed (int fd)</td>
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

<p>This function determines if the given file descriptor is connected to a "tty" or "console" window.</p>


<p>That is, the output would be displayed to the user rather than being put on a pipe or stored in a file.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a0c2a4031566b90f46f0dc8329e670598">llvm::raw_fd_ostream::is_displayed</a>.</p>

</div>
</div>

### FindInEnvPath() {#a2d23569135fe239b43594b6e8b99e67e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::string &gt; Process::FindInEnvPath (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EnvName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; std::string &gt; IgnoreList, char Separator=<a href="/web-llvm/docs/api/namespaces/llvm/sys/#a77295e6c130654c888b57aa25f9f90c5">EnvPathSeparator</a>)</td>
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

<p>This function searches for an existing file in the list of directories in a PATH like environment variable, and returns the first file found, according to the order of the entries in the PATH like environment variable.</p>


<p>If an ignore list is specified, then any folder which is in the PATH like environment variable but is also in IgnoreList is not considered.</p>


<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/support/process-cpp">Process.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a142386357a8879fc0b5041dc2e275bf5">llvm::sys::fs::equivalent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a645a607ffcccb12f16a5736db991e7d9">llvm::sys::fs::exists</a>, <a href="#a8806fc38b760a88a96d5d7fb67de545f">GetEnv</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ac35ec1dacb408d4c65d55249c0e02474">llvm::sys::path::is_absolute</a>.</p>


<p>Referenced by <a href="#ab97a24142bebbcf14ce0d586645abb5e">FindInEnvPath</a>.</p>

</div>
</div>

### FindInEnvPath() {#ab97a24142bebbcf14ce0d586645abb5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::string &gt; Process::FindInEnvPath (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> EnvName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, char Separator=<a href="/web-llvm/docs/api/namespaces/llvm/sys/#a77295e6c130654c888b57aa25f9f90c5">EnvPathSeparator</a>)</td>
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



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>, definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/support/process-cpp">Process.cpp</a>.</p>


<p>Reference <a href="#a2d23569135fe239b43594b6e8b99e67e">FindInEnvPath</a>.</p>

</div>
</div>

### FixupStandardFileDescriptors() {#aafb9f9b515200177db8c2bde7e02c4b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::sys::Process::FixupStandardFileDescriptors ()</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

### GetEnv() {#a8806fc38b760a88a96d5d7fb67de545f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; std::string &gt; llvm::sys::Process::GetEnv (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> name)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a77295e6c130654c888b57aa25f9f90c5">llvm::sys::EnvPathSeparator</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a719be92a1a97a3e61b32768d7240a120">llvm::cl::expandResponseFiles</a>, <a href="#a2d23569135fe239b43594b6e8b99e67e">FindInEnvPath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a9952645a56e841314d2b880bd31375">llvm::findVCToolChainViaEnvironment</a>, <a href="/web-llvm/docs/api/files/lib/lib/tooldrivers/lib/tooldrivers/llvm-lib/libdriver-cpp/#a8c99c6a7b32e47161b669182402a5c66">getSearchPaths</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a7225497318f6c1bd57e8a80d4273031e">llvm::cl::ParseCommandLineOptions</a>.</p>

</div>
</div>

### GetMallocUsage() {#aefb2b72e3e500a8b559e5d8c265b40e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::sys::Process::GetMallocUsage ()</td>
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

<p>Return process memory usage.</p>


<p>This static function will return the total amount of memory allocated by the process. This only counts the memory allocated via the malloc, calloc and realloc functions and includes any "free" holes in the allocated space.</p>


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/timer-cpp/#a552e7f089f2210623ca8ee55d313ddfe">getMemUsage</a>.</p>

</div>
</div>

### getPageSize() {#a2b6f374dc4eb2a7f84cc346e5630e132}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; llvm::sys::Process::getPageSize ()</td>
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

<p>Get the process's page size.</p>


<p>This may fail if the underlying syscall returns an error. In most cases, page size information is used for optimization, and this error can be safely discarded by calling consumeError, and an estimated page size substituted instead.</p>


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/inprocessmemorymanager/#a4033076ae4631e6acd10a0d94e8307d1">llvm::jitlink::InProcessMemoryManager::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/inprocessmemorymapper/#ace0850e56331e89848ec64c74dada4bd">llvm::orc::InProcessMemoryMapper::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#ae15684412736f37c545f8f2ec65cce56">llvm::orc::SelfExecutorProcessControl::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/sharedmemorymapper/#a05efc99c84f85d88901dd71a716814dd">llvm::orc::SharedMemoryMapper::Create</a> and <a href="#a774becf3d10728695b270703bca011ec">getPageSizeEstimate</a>.</p>

</div>
</div>

### getPageSizeEstimate() {#a774becf3d10728695b270703bca011ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sys::Process::getPageSizeEstimate ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the process's estimated page size.</p>


<p>This function always succeeds, but if the underlying syscall to determine the page size fails then this will silently return an estimated page size. The estimated page size is guaranteed to be a power of 2.</p>


<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#a2b6f374dc4eb2a7f84cc346e5630e132">getPageSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/implicitnullchecks-cpp/#a90146d35673da9e3e4a7f41f3b8c9b7e">PageSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/elfdebugobject/#a54c6b5a386504b3dd5ef2eb0111102ad">llvm::orc::ELFDebugObject::finalizeWorkingMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/memorybuffer-cpp/#a7a23441815c1bba5006a34529e58aa86">getOpenFileImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/selfexecutorprocesscontrol/#a5005b8f3deda0a47253e985ed2ca3591">llvm::orc::SelfExecutorProcessControl::SelfExecutorProcessControl</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a1a113f05f76ab4f04dc0d9d63c9d9962">llvm::trimBlockToPageSize</a>.</p>

</div>
</div>

### getProcessId() {#afee014293ce837f92658166fc36a2d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Pid llvm::sys::Process::getProcessId ()</td>
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

<p>Get the process's identifier.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#af5ca20f498adaec1f940475984ad7050">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/codegencoverage/#af3df1d6092ed500be1f2e3ca76d3e844">llvm::CodeGenCoverage::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/lockfilemanager/#ae09841830258172ba68866f0376898eb">llvm::LockFileManager::LockFileManager</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/rt-bootstrap/executorsharedmemorymapperservice/#aded6fc2ddd0d73f2f6b24beff42b70ea">llvm::orc::rt_bootstrap::ExecutorSharedMemoryMapperService::reserve</a>.</p>

</div>
</div>

### GetRandomNumber() {#a92b058c34d04f6d0adf6eac3060343c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sys::Process::GetRandomNumber ()</td>
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

<p>Get the result of a process wide random number generator.</p>


<p>The generator will be automatically seeded in non-deterministic fashion.</p>


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#aa37537b95a42a73ea04d8dd2803378da">llvm::sys::fs::createUniquePath</a>.</p>

</div>
</div>

### GetTimeUsage() {#ac44dcee71ca072093786da6b7d04149c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::Process::GetTimeUsage (<a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">TimePoint</a>&lt;&gt; &amp; elapsed, std::chrono::nanoseconds &amp; user_time, std::chrono::nanoseconds &amp; sys_time)</td>
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

<p>This static function will set <span class="doxyComputerOutput">user_time</span> to the amount of CPU time spent in user (non-kernel) mode and <span class="doxyComputerOutput">sys_time</span> to the amount of CPU time spent in system (kernel) mode.</p>


<p>If the operating system does not support collection of these metrics, a zero duration will be for both values.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">elapsed</td>
<td class="doxyParamItemDescription"><p>Returns the system_clock::now() giving current time</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">user_time</td>
<td class="doxyParamItemDescription"><p>Returns the current amount of user time for the process</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">sys_time</td>
<td class="doxyParamItemDescription"><p>Returns the current amount of system time for the process</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/timerecord/#a867cbf168949d9b11c9dcb23ffb6989b">llvm::TimeRecord::getCurrentTime</a>.</p>

</div>
</div>

### OutputBold() {#a5f838fbf3e04fdf7763b38ae5c499bbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::sys::Process::OutputBold (bool bg)</td>
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

<p>Same as OutputColor, but only enables the bold attribute.</p>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a28fa4a2054d6d628fa4eea21c5262212">llvm::raw_ostream::changeColor</a>.</p>

</div>
</div>

### OutputColor() {#a17881ed9155bdf983b849c4c69c365b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::sys::Process::OutputColor (char c, bool bold, bool bg)</td>
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

<p>This function returns the colorcode escape sequences.</p>


<p>If <a href="#ae688bc9ea544596962674ee94437ec00">ColorNeedsFlush()</a> is true then this function will change the colors and return an empty escape sequence. In that case it is the responsibility of the client to flush the output stream prior to calling this function.</p>


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a28fa4a2054d6d628fa4eea21c5262212">llvm::raw_ostream::changeColor</a>.</p>

</div>
</div>

### OutputReverse() {#aad9fc0056cabdeff2e16f13ec879688f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::sys::Process::OutputReverse ()</td>
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

<p>This function returns the escape sequence to reverse forground and background colors.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6095e2a0ebe961a05e2b3a7b6acbe769">llvm::raw_ostream::reverseColor</a>.</p>

</div>
</div>

### PreventCoreFiles() {#a044be33f2a65605a957e19d5e8d549a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::Process::PreventCoreFiles ()</td>
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

<p>This function makes the necessary calls to the operating system to prevent core files or any other kind of large memory dumps that can occur when a program fails.</p>


<p>Prevent core file generation.</p>


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

### ResetColor() {#add81bb27661c8bce42dee6b4b5828e83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::sys::Process::ResetColor ()</td>
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

<p>Resets the terminals colors, or returns an escape sequence to do so.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a4219e33c3cd0cc8383f615fc40254d21">llvm::raw_ostream::resetColor</a>.</p>

</div>
</div>

### SafelyCloseFileDescriptor() {#a0777b5060c78b24c4765fffbac259f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::error_code llvm::sys::Process::SafelyCloseFileDescriptor (int FD)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filepermissionsapplier/#a958cd3b9790b98d062b8e5fb5ebc32e6">llvm::FilePermissionsApplier::apply</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a293545f9b5864a8e1b33e57becbc5b3a">llvm::raw_fd_ostream::close</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/filecollector-cpp/#a1f7c3aa9196e89483c3ad89f2718dec3">copyAccessAndModificationTime</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a77063e0754fec7f06f3cdfa9e9bb5c1b">llvm::raw_fd_ostream::~raw_fd_ostream</a>.</p>

</div>
</div>

### StandardErrColumns() {#a89927683c57b686c4694bbc0ee822653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sys::Process::StandardErrColumns ()</td>
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

<p>This function determines the number of columns in the window if standard error is connected to a "tty" or "console" window.</p>


<p>If standard error is not connected to a tty or console, or if the number of columns cannot be determined, this routine returns zero.</p>


<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

### StandardErrHasColors() {#aae619d8f1ff7ce90bd18ee54d504b126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::Process::StandardErrHasColors ()</td>
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

<p>This function determines whether the terminal connected to standard error supports colors.</p>


<p>If standard error is not connected to a terminal, this function returns false.</p>


<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

### StandardErrIsDisplayed() {#a30f5096a2364f58d967775a553c1143b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::Process::StandardErrIsDisplayed ()</td>
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

<p>This function determines if the standard error is connected to a "tty" or "console" window.</p>


<p>That is, the output would be displayed to the user rather than being put on a pipe or stored in a file.</p>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

### StandardInIsUserInput() {#ad2aac231a0752ab9d6c3d7bae48f7adc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::Process::StandardInIsUserInput ()</td>
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

<p>This function determines if the standard input is connected directly to a user's input (keyboard probably), rather than coming from a file or pipe.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

### StandardOutColumns() {#ab21a24de36e15ce39ddb32192ff723ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sys::Process::StandardOutColumns ()</td>
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

<p>This function determines the number of columns in the window if standard output is connected to a "tty" or "console" window.</p>


<p>If standard output is not connected to a tty or console, or if the number of columns cannot be determined, this routine returns zero.</p>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

### StandardOutHasColors() {#a2512fe676260dcee1c2ba5e917dad4aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::Process::StandardOutHasColors ()</td>
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

<p>This function determines whether the terminal connected to standard output supports colors.</p>


<p>If standard output is not connected to a terminal, this function returns false.</p>


<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

### StandardOutIsDisplayed() {#ab2af58ec26c804a6836864d970c78df1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::Process::StandardOutIsDisplayed ()</td>
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

<p>This function determines if the standard output is connected to a "tty" or "console" window.</p>


<p>That is, the output would be displayed to the user rather than being put on a pipe or stored in a file.</p>


<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

### UseANSIEscapeCodes() {#a6f01fd2553456500f600d83db62c6932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::Process::UseANSIEscapeCodes (bool enable)</td>
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

<p>Enables or disables whether ANSI escape sequences are used to output colors.</p>


<p>This only has an effect on Windows. Note: Setting this option is not thread-safe and should only be done during initialization.</p>


<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### ExitNoCleanup() {#ac6dbd188251c69c120952f5ce81b1d4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sys::Process::ExitNoCleanup (int RetCode)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">Process.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/process-cpp">Process.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
