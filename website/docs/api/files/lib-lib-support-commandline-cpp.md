---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/commandline-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `CommandLine.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/debugoptions-h">DebugOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/support-h">llvm-c/Support.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlfunctionalextras-h">llvm/ADT/STLFunctionalExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "llvm/Config/config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">llvm/Support/ConvertUTF.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">llvm/Support/ManagedStatic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/process-h">llvm/Support/Process.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">llvm/Support/StringSaver.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/virtualfilesystem-h">llvm/Support/VirtualFileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cstdlib&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/cl">cl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This namespace contains all of the command line option processing machinery. <a href="/web-llvm/docs/api/namespaces/llvm/cl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-commandline-cpp-">anonymous{CommandLine.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/printarg">PrintArg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser">CommandLineParser</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter">HelpPrinter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/categorizedhelpprinter">CategorizedHelpPrinter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinterwrapper">HelpPrinterWrapper</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/versionprinter">VersionPrinter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-commandline-cpp-/commandlinecommonoptions">CommandLineCommonOptions</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10755af4d39e62dbf3dfb1caa875a822">argPlusPrefixesSize</a> (StringRef ArgName, size_t Pad=DefaultPad)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48d1af604311ed1fe7a55be6137c2253">argPrefix</a> (StringRef ArgName, size_t Pad=DefaultPad)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afde3bd3a8ac6e4b4d8b0790969858956">isGrouping</a> (const Option *O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1111513f897e14b01f6f60b0832f56b2">isPrefixedOrGrouping</a> (const Option *O)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, T TrueVal, T FalseVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a272daafdf2acdf6c3fdb0c61d8f0b459">parseBool</a> (Option &amp;O, StringRef ArgName, StringRef Arg, T &amp;Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae015be66fae811e0fe4cc32ce868f373">LookupNearestOption</a> (StringRef Arg, const StringMap&lt; Option * &gt; &amp;OptionsMap, std::string &amp;NearestString)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LookupNearestOption - Lookup the closest match to the option specified by the specified option on the command line. <a href="#ae015be66fae811e0fe4cc32ce868f373">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030478956c379ec2bb71550cb0526fb6">CommaSeparateAndAddOccurrence</a> (Option *Handler, unsigned pos, StringRef ArgName, StringRef Value, bool MultiArg=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CommaSeparateAndAddOccurrence - A wrapper around Handler-&gt;addOccurrence() that does special handling of <a href="/web-llvm/docs/api/namespaces/llvm/cl/#ac96f30ba8b117dbd380b88ab8a03732baa2d228ea7bc126361de56c03e7edc3a8">cl::CommaSeparated</a> options. <a href="#a030478956c379ec2bb71550cb0526fb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80082128b2626dbac74c382b28062330">ProvideOption</a> (Option *Handler, StringRef ArgName, StringRef Value, int argc, const char *const *argv, int &amp;i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ProvideOption - For <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, this differentiates between an empty value ("") and a null value (StringRef()). <a href="#a80082128b2626dbac74c382b28062330">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a663360d68b89c4eca45ecd19921a8bbd">getOptionPred</a> (StringRef Name, size_t &amp;Length, bool(*Pred)(const Option *), const StringMap&lt; Option * &gt; &amp;OptionsMap)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21de2c5fb30965f2300f1e49f791c915">HandlePrefixedOrGroupedOption</a> (StringRef &amp;Arg, StringRef &amp;Value, bool &amp;ErrorParsing, const StringMap&lt; Option * &gt; &amp;OptionsMap)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>HandlePrefixedOrGroupedOption - The specified argument string (which started with at least one '-') does not fully match an available option. <a href="#a21de2c5fb30965f2300f1e49f791c915">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be046f5ecc4c5eedd4dfe7b2310a87a">RequiresValue</a> (const Option *O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5338ad16d90987a4431af6701844f8e">EatsUnboundedNumberOfValues</a> (const Option *O)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac9ca7e06279e47b024290a211dd4bdf">isWhitespace</a> (char C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2b79510c44855834f9122e4e87f8d67">isWhitespaceOrNull</a> (char C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a812742fde8e7e1667727887d56dad5e2">isQuote</a> (char C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abba3a1b37c8d40cefcab729ee016441d">parseBackslash</a> (StringRef Src, size_t I, SmallString&lt; 128 &gt; &amp;Token)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Backslashes are interpreted in a rather complicated way in the Windows-style command line, because backslashes are used both to separate path and to escape double quote. <a href="#abba3a1b37c8d40cefcab729ee016441d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc191c75433191f605360ccc5fb882bf">isWindowsSpecialChar</a> (char C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56da0a49f13c1ae66144bf854ef8435f">isWindowsSpecialCharInCommandName</a> (char C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa5adc2409ac3c78b33d4813ff31ae6e">tokenizeWindowsCommandLineImpl</a> (StringRef Src, StringSaver &amp;Saver, function_ref&lt; void(StringRef)&gt; AddToken, bool AlwaysCopy, function_ref&lt; void()&gt; MarkEOL, bool InitialCommandName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a376abaf43fce7db08a674a90db19f84c">hasUTF8ByteOrderMark</a> (ArrayRef&lt; char &gt; S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b32f7427a25293e5cb32d481a342ebc">ExpandBasePaths</a> (StringRef BasePath, StringSaver &amp;Saver, const char *&amp;Arg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f3f8a458b73f542dc0210d97a3aa420">initCommonOptions</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a4d445518ce697c672e1b78ab05ae9f">getValueStr</a> (const Option &amp;O, StringRef DefaultMsg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2341e5774b19822016fa89ecf49a5aa8">parseDouble</a> (Option &amp;O, StringRef Arg, double &amp;Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a721eae5470452f3d65a749573a299c9a">getOptionPrefixesSize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3a00a397d505999a690bef5cdee1c8">shouldPrintOption</a> (StringRef Name, StringRef Description, const Option &amp;O)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae58e0cb29a8354f5244b643cf2a32050">OptNameCompare</a> (const std::pair&lt; const char *, Option * &gt; *LHS, const std::pair&lt; const char *, Option * &gt; *RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101c1e06829662051b14a7da33b3e08c">SubNameCompare</a> (const std::pair&lt; const char *, SubCommand * &gt; *LHS, const std::pair&lt; const char *, SubCommand * &gt; *RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa436b61ad2191b0937d9d9240c37013">sortOpts</a> (StringMap&lt; Option * &gt; &amp;OptMap, SmallVectorImpl&lt; std::pair&lt; const char *, Option * &gt; &gt; &amp;Opts, bool ShowHidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceec35695771c1b589aec748d34e9e4b">sortSubCommands</a> (const SmallPtrSetImpl&lt; SubCommand * &gt; &amp;SubMap, SmallVectorImpl&lt; std::pair&lt; const char *, SubCommand * &gt; &gt; &amp;Subs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmccore/#ga81494b4c1a36f4eb0aae2c1225ede0e4">LLVMParseCommandLineOptions</a> (int argc, const char *const *argv, const char *Overview)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function parses the given arguments using the LLVM command line parser. <a href="/web-llvm/docs/api/groups/llvmccore/#ga81494b4c1a36f4eb0aae2c1225ede0e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a332d25290fedd8ca4331c72baabffb36">DefaultPad</a> = 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa833a3efe2cde9ebf0973641d21200c">ArgPrefix</a> = "-"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1dde994236a96d6d4a0a34eb0a3dcf1">ArgPrefixLong</a> = "--"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507f69f9820910a2015099e6f0bc84d6">ArgHelpPrefix</a> = " - "</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a>&lt; CommandLineParser &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a391287ed187d72f0c6b3ebe84178bda9">GlobalParser</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a29de8410a1056ad1b234905755dbf5da">LLVM_REQUIRE_CONSTANT_INITIALIZATION</a> <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2f76f2b92b75733ac63b96c4e56202c">TopLevelSubCommand</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a210deb1402e4e9a128d05dd20ffee841">AllSubCommands</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad75990fb590f918e6921688593a9e7fe">EqValue</a> = "=&lt;value&gt;"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a335a6ffb9d879df0b103d8eeccb6498c">EmptyOption</a> = "&lt;empty&gt;"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05bea50643fcc616e36d98c5ff1bf858">OptionPrefix</a> = "    ="</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf6bd40afd516376818b15686f3e0ea9">MaxOptWidth</a> = 8</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a>&lt; CommandLineCommonOptions &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac44c2bdda9ce0b3da929e15237389b">CommonOptions</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"commandline"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf26c122cc786773aa526fa308672128">PRINT_OPT_DIFF</a>(T)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9703549ddbaa2f01a6f11b695f922a1e">LLVM_IS_DEBUG_BUILD</a>&nbsp;&nbsp;&nbsp;0</td>
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

### argPlusPrefixesSize() {#a10755af4d39e62dbf3dfb1caa875a822}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t argPlusPrefixesSize (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArgName, size_t Pad=<a href="#a332d25290fedd8ca4331c72baabffb36">DefaultPad</a>)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#a507f69f9820910a2015099e6f0bc84d6">ArgHelpPrefix</a>, <a href="#afa833a3efe2cde9ebf0973641d21200c">ArgPrefix</a>, <a href="#ac1dde994236a96d6d4a0a34eb0a3dcf1">ArgPrefixLong</a>, <a href="#a332d25290fedd8ca4331c72baabffb36">DefaultPad</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/basic-parser-impl/#abcd302380d7f7f1143da20a56b23cdec">llvm::cl::basic_parser_impl::getOptionWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a005329aa15a8ea20232fa18fc2cba61d">llvm::cl::generic_parser_base::getOptionWidth</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a84230421edc594e09adc8a9a743823de">llvm::cl::generic_parser_base::printOptionInfo</a>.</p>

</div>
</div>

### argPrefix() {#a48d1af604311ed1fe7a55be6137c2253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt; 8 &gt; argPrefix (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArgName, size_t Pad=<a href="#a332d25290fedd8ca4331c72baabffb36">DefaultPad</a>)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#afa833a3efe2cde9ebf0973641d21200c">ArgPrefix</a>, <a href="#ac1dde994236a96d6d4a0a34eb0a3dcf1">ArgPrefixLong</a>, <a href="#a332d25290fedd8ca4331c72baabffb36">DefaultPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#afcbd4ecc474e2d218391d6d3027b086aa7861ef1db44eac8ea7a373cd7c53a7c5">llvm::cl::Prefix</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/printarg/#a16a8e1dc40509b1f72c2f557a37d18d5">anonymous{CommandLine.cpp}::PrintArg::operator&lt;&lt;</a>.</p>

</div>
</div>

### CommaSeparateAndAddOccurrence() {#a030478956c379ec2bb71550cb0526fb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CommaSeparateAndAddOccurrence (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * Handler, unsigned pos, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArgName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value, bool MultiArg=false)</td>
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

<p>CommaSeparateAndAddOccurrence - A wrapper around Handler-&gt;addOccurrence() that does special handling of <a href="/web-llvm/docs/api/namespaces/llvm/cl/#ac96f30ba8b117dbd380b88ab8a03732baa2d228ea7bc126361de56c03e7edc3a8">cl::CommaSeparated</a> options.</p>

<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a3fd88dc36919959053fc85208201680d">llvm::cl::Option::addOccurrence</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#ac96f30ba8b117dbd380b88ab8a03732baa2d228ea7bc126361de56c03e7edc3a8">llvm::cl::CommaSeparated</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#aaa1c8565b0bb78da114f0d7f628e9d79">llvm::cl::Option::getMiscFlags</a>, <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#ad0f54a163ac500b144590640c6f1eb6b">anonymous{Path.cpp}::StringRef::npos</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="#a80082128b2626dbac74c382b28062330">ProvideOption</a>.</p>

</div>
</div>

### EatsUnboundedNumberOfValues() {#ae5338ad16d90987a4431af6701844f8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool EatsUnboundedNumberOfValues (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * O)</td>
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



<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a492234b10e0c5918d72a3a15a6f0fa6eafa11e887576398ca8a5fd74979a5a4c6">llvm::cl::OneOrMore</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a492234b10e0c5918d72a3a15a6f0fa6ea61d3cb794533763159788c493ad266d9">llvm::cl::ZeroOrMore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>.</p>

</div>
</div>

### ExpandBasePaths() {#a3b32f7427a25293e5cb32d481a342ebc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExpandBasePaths (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> BasePath, <a href="/web-llvm/docs/api/classes/llvm/stringsaver">StringSaver</a> &amp; Saver, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *&amp; Arg)</td>
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



<p>Definition at line 1119 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ac35ec1dacb408d4c65d55249c0e02474">llvm::sys::path::is_absolute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#ad0f54a163ac500b144590640c6f1eb6b">anonymous{Path.cpp}::StringRef::npos</a>, <a href="/web-llvm/docs/api/classes/llvm/stringsaver/#ada08f15f76fa550da28d92b038b6644b">llvm::StringSaver::save</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>

</div>
</div>

### getOptionPred() {#a663360d68b89c4eca45ecd19921a8bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Option * getOptionPred (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, size_t &amp; Length, bool(*)(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> *) Pred, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * &gt; &amp; OptionsMap)</td>
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



<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a16e5eaf2df56249e87019be23ee07695">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a49e68e4c86fe0b96c633adea0c366d74">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::find</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>.</p>


<p>Referenced by <a href="#a21de2c5fb30965f2300f1e49f791c915">HandlePrefixedOrGroupedOption</a>.</p>

</div>
</div>

### getOptionPrefixesSize() {#a721eae5470452f3d65a749573a299c9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t getOptionPrefixesSize ()</td>
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



<p>Definition at line 2082 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#a507f69f9820910a2015099e6f0bc84d6">ArgHelpPrefix</a> and <a href="#a05bea50643fcc616e36d98c5ff1bf858">OptionPrefix</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a005329aa15a8ea20232fa18fc2cba61d">llvm::cl::generic_parser_base::getOptionWidth</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a84230421edc594e09adc8a9a743823de">llvm::cl::generic_parser_base::printOptionInfo</a>.</p>

</div>
</div>

### getValueStr() {#a6a4d445518ce697c672e1b78ab05ae9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getValueStr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> &amp; O, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DefaultMsg)</td>
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



<p>Definition at line 1874 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/basic-parser-impl/#abcd302380d7f7f1143da20a56b23cdec">llvm::cl::basic_parser_impl::getOptionWidth</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/basic-parser-impl/#a18eb7156b6dd9a066f2d8b33dc12eb2b">llvm::cl::basic_parser_impl::printOptionInfo</a>.</p>

</div>
</div>

### HandlePrefixedOrGroupedOption() {#a21de2c5fb30965f2300f1e49f791c915}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Option * HandlePrefixedOrGroupedOption (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Arg, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Value, bool &amp; ErrorParsing, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * &gt; &amp; OptionsMap)</td>
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

<p>HandlePrefixedOrGroupedOption - The specified argument string (which started with at least one '-') does not fully match an available option.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> to see if this is a prefix or grouped option. If so, split arg into output an Arg/Value pair and return the <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> to parse it with.</p>


<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cl/#afcbd4ecc474e2d218391d6d3027b086aa7ed84199293df6d657c52fa751e4729e">llvm::cl::AlwaysPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a9846bb2bc5672e7627011260772b8d09">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a8be5b89e05ade5c6e5a08c6351b9821a">llvm::cl::Option::error</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a49e68e4c86fe0b96c633adea0c366d74">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::find</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a56457123d8727edb2035dd014f284a21">llvm::cl::Option::getFormattingFlag</a>, <a href="#a663360d68b89c4eca45ecd19921a8bbd">getOptionPred</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a387d22a966adbdd73fa7568d27b7d492">llvm::cl::Option::getValueExpectedFlag</a>, <a href="#afde3bd3a8ac6e4b4d8b0790969858956">isGrouping</a>, <a href="#a1111513f897e14b01f6f60b0832f56b2">isPrefixedOrGrouping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#afcbd4ecc474e2d218391d6d3027b086aa7861ef1db44eac8ea7a373cd7c53a7c5">llvm::cl::Prefix</a>, <a href="#a80082128b2626dbac74c382b28062330">ProvideOption</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a55b680a07606a474047e2174261f14b1a4951a2ed2e2bb55015144fbac894fdcc">llvm::cl::ValueRequired</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>.</p>

</div>
</div>

### hasUTF8ByteOrderMark() {#a376abaf43fce7db08a674a90db19f84c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasUTF8ByteOrderMark (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; char &gt; S)</td>
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



<p>Definition at line 1114 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>

</div>
</div>

### initCommonOptions() {#a8f3f8a458b73f542dc0210d97a3aa420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initCommonOptions ()</td>
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



<p>Definition at line 2649 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="#a8ac44c2bdda9ce0b3da929e15237389b">CommonOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4c8865e5ec32b9608c5ac5edba951767">llvm::initDebugCounterOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35526021c09988c9ef8e25cc9e6bb74c">llvm::initDebugOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7d5f066559eb7410393929dac4b21fb">llvm::initGraphWriterOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa631c524fdedeed39b78ca7113ee525c">llvm::initRandomSeedOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a80b0d3e26da154563aab079c8b32ec32">llvm::initSignalsOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87a54c835d57e5f3da731e65fcdddeb6">llvm::initStatisticOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a020f377cc123ca6dfabe1ebc5cc55f">llvm::initTimerOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85604c506a712961324c0191a372e329">llvm::initTypeSizeOptions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0739379f5a2348f4a22afcfa79f7a41b">llvm::initWithColorOptions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a6d52a42303dabd7949d77a3da9d1ee6a">llvm::cl::getRegisteredOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a22aba70ff931d97f2ae7de13b16c54fa">llvm::cl::HideUnrelatedOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#aeb4508557302c61518095f4325c8b80b">llvm::cl::HideUnrelatedOptions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a7225497318f6c1bd57e8a80d4273031e">llvm::cl::ParseCommandLineOptions</a>.</p>

</div>
</div>

### isGrouping() {#afde3bd3a8ac6e4b4d8b0790969858956}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isGrouping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * O)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/cl/#ac96f30ba8b117dbd380b88ab8a03732bad23ddff77c9269f78524506f333ca1f0">llvm::cl::Grouping</a>.</p>


<p>Referenced by <a href="#a21de2c5fb30965f2300f1e49f791c915">HandlePrefixedOrGroupedOption</a> and <a href="#a1111513f897e14b01f6f60b0832f56b2">isPrefixedOrGrouping</a>.</p>

</div>
</div>

### isPrefixedOrGrouping() {#a1111513f897e14b01f6f60b0832f56b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isPrefixedOrGrouping (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * O)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cl/#afcbd4ecc474e2d218391d6d3027b086aa7ed84199293df6d657c52fa751e4729e">llvm::cl::AlwaysPrefix</a>, <a href="#afde3bd3a8ac6e4b4d8b0790969858956">isGrouping</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#afcbd4ecc474e2d218391d6d3027b086aa7861ef1db44eac8ea7a373cd7c53a7c5">llvm::cl::Prefix</a>.</p>


<p>Referenced by <a href="#a21de2c5fb30965f2300f1e49f791c915">HandlePrefixedOrGroupedOption</a>.</p>

</div>
</div>

### isQuote() {#a812742fde8e7e1667727887d56dad5e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isQuote (char C)</td>
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



<p>Definition at line 819 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cl/#aff28c3d477d3a7870ec643381f186ed4">llvm::cl::TokenizeGNUCommandLine</a>.</p>

</div>
</div>

### isWhitespace() {#aac9ca7e06279e47b024290a211dd4bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isWhitespace (char C)</td>
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



<p>Definition at line 811 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="#ad2b79510c44855834f9122e4e87f8d67">isWhitespaceOrNull</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a67d781b9bcae2cbdf19f35456132a85b">llvm::cl::tokenizeConfigFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#aff28c3d477d3a7870ec643381f186ed4">llvm::cl::TokenizeGNUCommandLine</a>.</p>

</div>
</div>

### isWhitespaceOrNull() {#ad2b79510c44855834f9122e4e87f8d67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isWhitespaceOrNull (char C)</td>
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



<p>Definition at line 815 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#aac9ca7e06279e47b024290a211dd4bdf">isWhitespace</a>.</p>


<p>Referenced by <a href="#afc191c75433191f605360ccc5fb882bf">isWindowsSpecialChar</a>, <a href="#a56da0a49f13c1ae66144bf854ef8435f">isWindowsSpecialCharInCommandName</a> and <a href="#aaa5adc2409ac3c78b33d4813ff31ae6e">tokenizeWindowsCommandLineImpl</a>.</p>

</div>
</div>

### isWindowsSpecialChar() {#afc191c75433191f605360ccc5fb882bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isWindowsSpecialChar (char C)</td>
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



<p>Definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ad2b79510c44855834f9122e4e87f8d67">isWhitespaceOrNull</a>.</p>


<p>Referenced by <a href="#aaa5adc2409ac3c78b33d4813ff31ae6e">tokenizeWindowsCommandLineImpl</a>.</p>

</div>
</div>

### isWindowsSpecialCharInCommandName() {#a56da0a49f13c1ae66144bf854ef8435f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isWindowsSpecialCharInCommandName (char C)</td>
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



<p>Definition at line 926 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ad2b79510c44855834f9122e4e87f8d67">isWhitespaceOrNull</a>.</p>


<p>Referenced by <a href="#aaa5adc2409ac3c78b33d4813ff31ae6e">tokenizeWindowsCommandLineImpl</a>.</p>

</div>
</div>

### LookupNearestOption() {#ae015be66fae811e0fe4cc32ce868f373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Option * LookupNearestOption (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * &gt; &amp; OptionsMap, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; NearestString)</td>
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

<p>LookupNearestOption - Lookup the closest match to the option specified by the specified option on the command line.</p>


<p>If there is a value specified (after an equal sign) return that as well. This assumes that leading dashes have already been stripped.</p>


<p>Definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a2d71dc9a645a91493dd60a723be28720">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a51c1f447b5d754191564ae340ee4253b">llvm::StringRef::edit_distance</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a16e5eaf2df56249e87019be23ee07695">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a68075925a54790e71ca790e1d4f21a40ab81f279502bb9ca74e6629cfb62844be">llvm::cl::ReallyHidden</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a55b680a07606a474047e2174261f14b1a167e8276fb67a7c61a368e2e1924689b">llvm::cl::ValueDisallowed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>.</p>

</div>
</div>

### OptNameCompare() {#ae58e0cb29a8354f5244b643cf2a32050}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int OptNameCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * &gt; * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * &gt; * RHS)</td>
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



<p>Definition at line 2255 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#afa436b61ad2191b0937d9d9240c37013">sortOpts</a>.</p>

</div>
</div>

### parseBackslash() {#abba3a1b37c8d40cefcab729ee016441d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t parseBackslash (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Src, size_t I, <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 128 &gt; &amp; Token)</td>
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

<p>Backslashes are interpreted in a rather complicated way in the Windows-style command line, because backslashes are used both to separate path and to escape double quote.</p>


<p>This method consumes runs of backslashes as well as the following double quote if it's escaped.</p>


<ul class="doxyList ">
<li>If an even number of backslashes is followed by a double quote, one backslash is output for every pair of backslashes, and the last double quote remains unconsumed. The double quote will later be interpreted as the start or end of a quoted string in the main loop outside of this function.</li>
<li>If an odd number of backslashes is followed by a double quote, one backslash is output for every pair of backslashes, and a double quote is output for the last pair of backslash-double quote. The double quote is consumed in this case.</li>
<li>Otherwise, backslashes are interpreted literally.</li>
</ul>

<p>Definition at line 899 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#aaa5adc2409ac3c78b33d4813ff31ae6e">tokenizeWindowsCommandLineImpl</a>.</p>

</div>
</div>

### parseBool() {#a272daafdf2acdf6c3fdb0c61d8f0b459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, T TrueVal, T FalseVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool parseBool (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> &amp; O, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArgName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arg, T &amp; Value)</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### parseDouble() {#a2341e5774b19822016fa89ecf49a5aa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool parseDouble (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> &amp; O, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Arg, double &amp; Value)</td>
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



<p>Definition at line 2043 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>

</div>
</div>

### ProvideOption() {#a80082128b2626dbac74c382b28062330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ProvideOption (<a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * Handler, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ArgName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value, int argc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * argv, int &amp; i)</td>
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

<p>ProvideOption - For <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, this differentiates between an empty value ("") and a null value (StringRef()).</p>


<p>The later is accepted for arguments that don't allow a value (-foo) the former is rejected (-foo=).</p>


<p>Definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cl/#afcbd4ecc474e2d218391d6d3027b086aa7ed84199293df6d657c52fa751e4729e">llvm::cl::AlwaysPrefix</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a030478956c379ec2bb71550cb0526fb6">CommaSeparateAndAddOccurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a8be5b89e05ade5c6e5a08c6351b9821a">llvm::cl::Option::error</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a56457123d8727edb2035dd014f284a21">llvm::cl::Option::getFormattingFlag</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#ad16f2d8b8f534124c0f8adc03d329c5e">llvm::cl::Option::getNumAdditionalVals</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a387d22a966adbdd73fa7568d27b7d492">llvm::cl::Option::getValueExpectedFlag</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a55b680a07606a474047e2174261f14b1a167e8276fb67a7c61a368e2e1924689b">llvm::cl::ValueDisallowed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a55b680a07606a474047e2174261f14b1a0294efef342c4177930633ea45ceb54f">llvm::cl::ValueOptional</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a55b680a07606a474047e2174261f14b1a4951a2ed2e2bb55015144fbac894fdcc">llvm::cl::ValueRequired</a>.</p>


<p>Referenced by <a href="#a21de2c5fb30965f2300f1e49f791c915">HandlePrefixedOrGroupedOption</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#aba3d2a652f73ed425dbbea55f4e7208c">llvm::cl::ProvidePositionalOption</a>.</p>

</div>
</div>

### RequiresValue() {#a0be046f5ecc4c5eedd4dfe7b2310a87a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RequiresValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * O)</td>
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



<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a492234b10e0c5918d72a3a15a6f0fa6eafa11e887576398ca8a5fd74979a5a4c6">llvm::cl::OneOrMore</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a492234b10e0c5918d72a3a15a6f0fa6eafb49e6d343a4ce63c7048a222586cc9e">llvm::cl::Required</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>.</p>

</div>
</div>

### shouldPrintOption() {#a1e3a00a397d505999a690bef5cdee1c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool shouldPrintOption (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Description, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> &amp; O)</td>
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



<p>Definition at line 2086 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a55b680a07606a474047e2174261f14b1a0294efef342c4177930633ea45ceb54f">llvm::cl::ValueOptional</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a005329aa15a8ea20232fa18fc2cba61d">llvm::cl::generic_parser_base::getOptionWidth</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a84230421edc594e09adc8a9a743823de">llvm::cl::generic_parser_base::printOptionInfo</a>.</p>

</div>
</div>

### sortOpts() {#afa436b61ad2191b0937d9d9240c37013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void sortOpts (<a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * &gt; &amp; OptMap, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> * &gt; &gt; &amp; Opts, bool ShowHidden)</td>
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



<p>Definition at line 2266 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#add1eb5637dd671428b6f138ed3db6428">llvm::array_pod_sort</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a2d71dc9a645a91493dd60a723be28720">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/stringmap/#a16e5eaf2df56249e87019be23ee07695">llvm::StringMap&lt; ValueTy, AllocatorTy &gt;::end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a68075925a54790e71ca790e1d4f21a40a263ac008d8d31f13ce460395fc4cf7e6">llvm::cl::Hidden</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="#ae58e0cb29a8354f5244b643cf2a32050">OptNameCompare</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a68075925a54790e71ca790e1d4f21a40ab81f279502bb9ca74e6629cfb62844be">llvm::cl::ReallyHidden</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a1007dc3842414831c7641e4b5824e4a0">anonymous{CommandLine.cpp}::HelpPrinter::printHelp</a> and <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a936ffbef3dd147515d76ff3ad15ba22c">anonymous{CommandLine.cpp}::CommandLineParser::printOptionValues</a>.</p>

</div>
</div>

### sortSubCommands() {#aceec35695771c1b589aec748d34e9e4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void sortSubCommands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl">SmallPtrSetImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> * &gt; &amp; SubMap, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> * &gt; &gt; &amp; Subs)</td>
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



<p>Definition at line 2294 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#add1eb5637dd671428b6f138ed3db6428">llvm::array_pod_sort</a> and <a href="#a101c1e06829662051b14a7da33b3e08c">SubNameCompare</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a1007dc3842414831c7641e4b5824e4a0">anonymous{CommandLine.cpp}::HelpPrinter::printHelp</a>.</p>

</div>
</div>

### SubNameCompare() {#a101c1e06829662051b14a7da33b3e08c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SubNameCompare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> * &gt; * LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand">SubCommand</a> * &gt; * RHS)</td>
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



<p>Definition at line 2260 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>


<p>Referenced by <a href="#aceec35695771c1b589aec748d34e9e4b">sortSubCommands</a>.</p>

</div>
</div>

### tokenizeWindowsCommandLineImpl() {#aaa5adc2409ac3c78b33d4813ff31ae6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void tokenizeWindowsCommandLineImpl (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Src, <a href="/web-llvm/docs/api/classes/llvm/stringsaver">StringSaver</a> &amp; Saver, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; AddToken, bool AlwaysCopy, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void()&gt; MarkEOL, bool InitialCommandName)</td>
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



<p>Definition at line 932 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c/#af319751162595d897c085e511c7e7d4a">INIT</a>, <a href="#ad2b79510c44855834f9122e4e87f8d67">isWhitespaceOrNull</a>, <a href="#afc191c75433191f605360ccc5fb882bf">isWindowsSpecialChar</a>, <a href="#a56da0a49f13c1ae66144bf854ef8435f">isWindowsSpecialCharInCommandName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#abba3a1b37c8d40cefcab729ee016441d">parseBackslash</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringsaver/#ada08f15f76fa550da28d92b038b6644b">llvm::StringSaver::save</a> and <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a3b42fd69f84c0ceef44857e925613ee4">llvm::cl::TokenizeWindowsCommandLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#af896b229210e1e59c2d9f66112fc48d3">llvm::cl::TokenizeWindowsCommandLineFull</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a8d80076c6887cc447e544881292a3ad0">llvm::cl::TokenizeWindowsCommandLineNoCopy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AllSubCommands {#a210deb1402e4e9a128d05dd20ffee841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ManagedStatic&lt;SubCommand&gt; AllSubCommands</td>
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



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a76b56989e390102900666b2aec0b3504">llvm::cl::SubCommand::getAll</a>.</p>

</div>
</div>

### ArgHelpPrefix {#a507f69f9820910a2015099e6f0bc84d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef ArgHelpPrefix = " - "</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="#a10755af4d39e62dbf3dfb1caa875a822">argPlusPrefixesSize</a>, <a href="#a721eae5470452f3d65a749573a299c9a">getOptionPrefixesSize</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#acae182b4c4d76e0489cde49f97f4be7f">llvm::cl::Option::printEnumValHelpStr</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/option/#adbafb62d9a5896bf0485dea594d111bb">llvm::cl::Option::printHelpStr</a>.</p>

</div>
</div>

### ArgPrefix {#afa833a3efe2cde9ebf0973641d21200c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef ArgPrefix = "-"</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="#a10755af4d39e62dbf3dfb1caa875a822">argPlusPrefixesSize</a> and <a href="#a48d1af604311ed1fe7a55be6137c2253">argPrefix</a>.</p>

</div>
</div>

### ArgPrefixLong {#ac1dde994236a96d6d4a0a34eb0a3dcf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef ArgPrefixLong = "--"</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="#a10755af4d39e62dbf3dfb1caa875a822">argPlusPrefixesSize</a> and <a href="#a48d1af604311ed1fe7a55be6137c2253">argPrefix</a>.</p>

</div>
</div>

### CommonOptions {#a8ac44c2bdda9ce0b3da929e15237389b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ManagedStatic&lt;CommandLineCommonOptions&gt; CommonOptions</td>
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



<p>Definition at line 2647 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/cl/#af482fe65d5cc4df7480d60fdf731c14e">llvm::cl::AddExtraVersionPrinter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a22aba70ff931d97f2ae7de13b16c54fa">llvm::cl::HideUnrelatedOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#aeb4508557302c61518095f4325c8b80b">llvm::cl::HideUnrelatedOptions</a>, <a href="#a8f3f8a458b73f542dc0210d97a3aa420">initCommonOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinterwrapper/#a5145cb8838015591ebe3eff9655d583c">anonymous{CommandLine.cpp}::HelpPrinterWrapper::operator=</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/versionprinter/#a291c3173496836b5695bce139668821a">anonymous{CommandLine.cpp}::VersionPrinter::operator=</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#af6c58129ea2fde5a453070dc10abf3fc">llvm::cl::PrintHelpMessage</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a936ffbef3dd147515d76ff3ad15ba22c">anonymous{CommandLine.cpp}::CommandLineParser::printOptionValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a2bbf208c1ca72320e906f62b82f73482">llvm::cl::PrintVersionMessage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a63ee793fde9a73bea7b33527e7e1260f">llvm::cl::SetVersionPrinter</a>.</p>

</div>
</div>

### DefaultPad {#a332d25290fedd8ca4331c72baabffb36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t DefaultPad = 2</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="#a10755af4d39e62dbf3dfb1caa875a822">argPlusPrefixesSize</a>, <a href="#a48d1af604311ed1fe7a55be6137c2253">argPrefix</a> and <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/printarg/#a47f6ef7ff78d94111de4d7b7d9adce51">anonymous{CommandLine.cpp}::PrintArg::PrintArg</a>.</p>

</div>
</div>

### EmptyOption {#a335a6ffb9d879df0b103d8eeccb6498c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef EmptyOption = "&lt;empty&gt;"</td>
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



<p>Definition at line 2080 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a005329aa15a8ea20232fa18fc2cba61d">llvm::cl::generic_parser_base::getOptionWidth</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a84230421edc594e09adc8a9a743823de">llvm::cl::generic_parser_base::printOptionInfo</a>.</p>

</div>
</div>

### EqValue {#ad75990fb590f918e6921688593a9e7fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef EqValue = "=&lt;value&gt;"</td>
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



<p>Definition at line 2079 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a005329aa15a8ea20232fa18fc2cba61d">llvm::cl::generic_parser_base::getOptionWidth</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a84230421edc594e09adc8a9a743823de">llvm::cl::generic_parser_base::printOptionInfo</a>.</p>

</div>
</div>

### GlobalParser {#a391287ed187d72f0c6b3ebe84178bda9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ManagedStatic&lt;CommandLineParser&gt; GlobalParser</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a87b607d9ac42d0506a670d834bdca991">llvm::cl::Option::addArgument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a851cee28a41c51f864c4593fa23df4b2">llvm::cl::AddLiteralOption</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a8be5b89e05ade5c6e5a08c6351b9821a">llvm::cl::Option::error</a>, <a href="/web-llvm/docs/api/structs/llvm/cl/extrahelp/#ae3207bcbcbb8e0c039027d44427240fa">llvm::cl::extrahelp::extrahelp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a6d52a42303dabd7949d77a3da9d1ee6a">llvm::cl::getRegisteredOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a7c9dfd181a13452706925939524d6829">llvm::cl::getRegisteredSubcommands</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#aec3f60533c02f25c929a5396e354eb4c">llvm::cl::SubCommand::operator bool</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinterwrapper/#a5145cb8838015591ebe3eff9655d583c">anonymous{CommandLine.cpp}::HelpPrinterWrapper::operator=</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/commandlineparser/#a8ff4dbfdf39c7f753e0258704d834879">anonymous{CommandLine.cpp}::CommandLineParser::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a7225497318f6c1bd57e8a80d4273031e">llvm::cl::ParseCommandLineOptions</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a1007dc3842414831c7641e4b5824e4a0">anonymous{CommandLine.cpp}::HelpPrinter::printHelp</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/categorizedhelpprinter/#ab00bf8967de6bcd0ed813dd9ec8b09a9">anonymous{CommandLine.cpp}::CategorizedHelpPrinter::printOptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a7a97c47068ba1a23594a92b551ff2da6">llvm::cl::PrintOptionValues</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#acbe714a766051424993c5909def2d3e8">llvm::cl::SubCommand::registerSubCommand</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#ad34afb802d1e49a9235a9019704785ae">llvm::cl::Option::removeArgument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a5db1a221190b0a9136749cbea271082c">llvm::cl::ResetAllOptionOccurrences</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a71b984ac26593df611601411b9af1cc2">llvm::cl::ResetCommandLineParser</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#a9174b74c91e38ef13386aaa81fa484f9">llvm::cl::Option::setArgStr</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a500bcef097029745e7391cadc1c7a87b">llvm::cl::SubCommand::unregisterSubCommand</a>.</p>

</div>
</div>

### MaxOptWidth {#adf6bd40afd516376818b15686f3e0ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const size_t MaxOptWidth = 8</td>
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



<p>Definition at line 2164 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a7c44bc839272e942aa1a7c622eb9affb">llvm::cl::generic_parser_base::printGenericOptionDiff</a>.</p>

</div>
</div>

### OptionPrefix {#a05bea50643fcc616e36d98c5ff1bf858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef OptionPrefix = "    ="</td>
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



<p>Definition at line 2081 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="#a721eae5470452f3d65a749573a299c9a">getOptionPrefixesSize</a> and <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a84230421edc594e09adc8a9a743823de">llvm::cl::generic_parser_base::printOptionInfo</a>.</p>

</div>
</div>

### TopLevelSubCommand {#ab2f76f2b92b75733ac63b96c4e56202c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_REQUIRE_CONSTANT_INITIALIZATION ManagedStatic&lt;SubCommand&gt; TopLevelSubCommand</td>
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



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cl/subcommand/#a3faf2de70f129bd4fc2eeff949d81806">llvm::cl::SubCommand::getTopLevel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"commandline"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>

</div>
</div>

### LLVM\_IS\_DEBUG\_BUILD {#a9703549ddbaa2f01a6f11b695f922a1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVM_IS_DEBUG_BUILD&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2520 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>

</div>
</div>

### PRINT\_OPT\_DIFF {#acf26c122cc786773aa526fa308672128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PRINT_OPT_DIFF(T)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  void <a href="/web-llvm/docs/api/classes/llvm/cl/parser">parser</a>&lt;T&gt;::printOptionDiff(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/cl/option">Option</a> &amp;O, T V, <a href="/web-llvm/docs/api/structs/llvm/cl/optionvalue">OptionValue</a>&lt;T&gt; <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>,      \
                                  size_t GlobalWidth) <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> {                  \
    printOptionName(O, GlobalWidth);                                           \
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> Str;                                                           \
    {                                                                          \
      <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a> SS(Str);                                              \
      SS &lt;&lt; V;                                                                 \
    }                                                                          \
    outs() &lt;&lt; "= " &lt;&lt; Str;                                                     \
    size_t NumSpaces =                                                         \
        <a href="#adf6bd40afd516376818b15686f3e0ea9">MaxOptWidth</a> &gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">Str.size</a>() ? <a href="#adf6bd40afd516376818b15686f3e0ea9">MaxOptWidth</a> - <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">Str.size</a>() : 0;               \
    outs().<a href="/web-llvm/docs/api/structs/llvm/indent">indent</a>(NumSpaces) &lt;&lt; " (default: ";                                 \
    if (D.hasValue())                                                          \
      outs() &lt;&lt; D.getValue();                                                  \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a>                                                                       \
      outs() &lt;&lt; "*no default*";                                                \
    outs() &lt;&lt; ")\n";                                                           \
  }
</div>
</dd>
</dl>

<p>Definition at line 2198 of file <a href="/web-llvm/docs/api/files/lib/lib/support/commandline-cpp">CommandLine.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
