---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/signals-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Signals.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/signals-h">llvm/Support/Signals.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/debugoptions-h">DebugOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">llvm/Support/ErrorOr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/fileutilities-h">llvm/Support/FileUtilities.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">llvm/Support/ManagedStatic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/path-h">llvm/Support/Path.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/program-h">llvm/Support/Program.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/stringsaver-h">llvm/Support/StringSaver.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;array&gt;
#include &lt;cmath&gt;
#include &lt;vector&gt;
#include "Unix/Signals.inc"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-signals-cpp-">anonymous{Signals.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-signals-cpp-/createdisablesymbolication">CreateDisableSymbolication</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-signals-cpp-/createcrashdiagnosticsdir">CreateCrashDiagnosticsDir</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/callbackandcookie">CallbackAndCookie</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::array&lt; <a href="/web-llvm/docs/api/structs/callbackandcookie">CallbackAndCookie</a>, <a href="#a8c60090b8acf9cbfff2736ce97e3e7e3">MaxSignalHandlerCallbacks</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a264b9d38cdac527e14628210ee764dba">CallBacksToRun</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af66fd5871ea182311d860975bd5de5e9">insertSignalHandler</a> (sys::SignalHandlerCallback FnPtr, void *Cookie)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a8bcb543c331c2d59d4005a62023344">findModulesAndOffsets</a> (void **StackTrace, int Depth, const char **Modules, intptr_t *Offsets, const char *MainExecutableName, StringSaver &amp;StrPool)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/formattednumber">FormattedNumber</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a108a0e76fa3727c0c510ac557c778234">format_ptr</a> (void *PC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Format a pointer value as hexadecimal. <a href="#a108a0e76fa3727c0c510ac557c778234">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a6881c00738b22a600dfee25a1c32dab3">LLVM_ATTRIBUTE_USED</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a> (StringRef Argv0, void **StackTrace, int Depth, llvm::raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper that launches llvm-symbolizer and symbolizes a backtrace. <a href="#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99bcf6310a14dca264a71b7863cf1e81">printMarkupContext</a> (raw_ostream &amp;OS, const char *MainExecutableName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a6881c00738b22a600dfee25a1c32dab3">LLVM_ATTRIBUTE_USED</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9c62fdad9f8cfb0551e47ad3116b699">printMarkupStackTrace</a> (StringRef Argv0, void **StackTrace, int Depth, raw_ostream &amp;OS)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3700661bd7b989467aa60e9cb7ac751e">DisableSymbolicationFlag</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca571eb5df1d4cdb5ebdce75f957cdf">CrashDiagnosticsDirectory</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1741ace2a7f31133d2c5f93fc077e5da">DisableSymbolizationEnv</a>[] = "LLVM_DISABLE_SYMBOLIZATION"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dcd02a07bc24565fe1faae5a77e6a48">LLVMSymbolizerPathEnv</a>[] = "LLVM_SYMBOLIZER_PATH"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd37850f227b8d23e6abf1ff21176a0c">EnableSymbolizerMarkupEnv</a>[] = "LLVM_ENABLE_SYMBOLIZER_MARKUP"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c60090b8acf9cbfff2736ce97e3e7e3">MaxSignalHandlerCallbacks</a> = 8</td>
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

### CallBacksToRun() {#a264b9d38cdac527e14628210ee764dba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt; CallbackAndCookie, MaxSignalHandlerCallbacks &gt; &amp; CallBacksToRun ()</td>
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



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>


<p>Referenced by <a href="#af66fd5871ea182311d860975bd5de5e9">insertSignalHandler</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aa9516bcffe612375e99ac8c722b82847">llvm::sys::RunSignalHandlers</a>.</p>

</div>
</div>

### findModulesAndOffsets() {#a2a8bcb543c331c2d59d4005a62023344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool findModulesAndOffsets (void ** StackTrace, int Depth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** Modules, intptr_t * Offsets, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * MainExecutableName, <a href="/web-llvm/docs/api/classes/llvm/stringsaver">StringSaver</a> &amp; StrPool)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>.</p>


<p>Referenced by <a href="#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>.</p>

</div>
</div>

### format\_ptr() {#a108a0e76fa3727c0c510ac557c778234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FormattedNumber format_ptr (void * PC)</td>
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

<p>Format a pointer value as hexadecimal.</p>


<p>Zero pad it out so its always the same width.</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>.</p>


<p>Referenced by <a href="#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>.</p>

</div>
</div>

### insertSignalHandler() {#af66fd5871ea182311d860975bd5de5e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void insertSignalHandler (<a href="/web-llvm/docs/api/namespaces/llvm/sys/#ae36d96d14c99fdcf62cf0a82008d71a3">sys::SignalHandlerCallback</a> FnPtr, void * Cookie)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>


<p>References <a href="#a264b9d38cdac527e14628210ee764dba">CallBacksToRun</a>, <a href="/web-llvm/docs/api/structs/callbackandcookie/#acc5d30a641e7fd26257088e420487685ace2c8aed9c2fa0cfbed56cbda4d8bf07">CallbackAndCookie::Empty</a>, <a href="/web-llvm/docs/api/structs/callbackandcookie/#acc5d30a641e7fd26257088e420487685a59d87a4758a9d35fbaf6b204341bb399">CallbackAndCookie::Initialized</a>, <a href="/web-llvm/docs/api/structs/callbackandcookie/#acc5d30a641e7fd26257088e420487685a32b169f72b293ef80d35435e9894f8e2">CallbackAndCookie::Initializing</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>.</p>

</div>
</div>

### printMarkupContext() {#a99bcf6310a14dca264a71b7863cf1e81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool printMarkupContext (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * MainExecutableName)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a6881c00738b22a600dfee25a1c32dab3">LLVM_ATTRIBUTE_USED</a>.</p>


<p>Referenced by <a href="#ae9c62fdad9f8cfb0551e47ad3116b699">printMarkupStackTrace</a>.</p>

</div>
</div>

### printMarkupStackTrace() {#ae9c62fdad9f8cfb0551e47ad3116b699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_USED bool printMarkupStackTrace (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Argv0, void ** StackTrace, int Depth, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#afd37850f227b8d23e6abf1ff21176a0c">EnableSymbolizerMarkupEnv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a645a607ffcccb12f16a5736db991e7d9">llvm::sys::fs::exists</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a057a733b2dfa2f0531ceb335cf3b1d03">llvm::sys::fs::getMainExecutable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a99bcf6310a14dca264a71b7863cf1e81">printMarkupContext</a>.</p>

</div>
</div>

### printSymbolizedStackTrace() {#a1c25905ebd1d19c4d5c4e2ca86cdb1f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_USED bool printSymbolizedStackTrace (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Argv0, void ** StackTrace, int Depth, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; OS)</td>
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

<p>Helper that launches llvm-symbolizer and symbolizes a backtrace.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocbasic-cpp/#ad5d00e1d77644d95847b9bf8da12b759">Allocator</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ade4b8410fbe0406fc61d1db65d1cfa12">llvm::SmallString&lt; InternalLen &gt;::c_str</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a83a294111af6d4412163b209725ca556">llvm::StringRef::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ab15b20ec21b28d9674608fd5aecc64de">llvm::sys::fs::createTemporaryFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#a3700661bd7b989467aa60e9cb7ac751e">DisableSymbolicationFlag</a>, <a href="#a1741ace2a7f31133d2c5f93fc077e5da">DisableSymbolizationEnv</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#abb13fbc7f52c659966b05092b19e6e19">llvm::sys::ExecuteAndWait</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a645a607ffcccb12f16a5736db991e7d9">llvm::sys::fs::exists</a>, <a href="#a2a8bcb543c331c2d59d4005a62023344">findModulesAndOffsets</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#ae87ab32d0995f94193aff5e380c8d251">llvm::sys::findProgramByName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>, <a href="#a108a0e76fa3727c0c510ac557c778234">format_ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a057a733b2dfa2f0531ceb335cf3b1d03">llvm::sys::fs::getMainExecutable</a>, <a href="#a8dcd02a07bc24565fe1faae5a77e6a48">LLVMSymbolizerPathEnv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a5326427c87607b2364a1fcdf13fa0eea">llvm::sys::path::parent_path</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c6d735dfe8fc13a113405c1dda2991e">llvm::right_justify</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a> and <a href="/web-llvm/docs/api/classes/llvm/smallstring/#af5dd7241878be5eed07736eb156bb10b">llvm::SmallString&lt; InternalLen &gt;::str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CrashDiagnosticsDirectory {#a6ca571eb5df1d4cdb5ebdce75f957cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ManagedStatic&lt;std::string&gt; CrashDiagnosticsDirectory</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-signals-cpp-/createcrashdiagnosticsdir/#ac474525c10f7b10fa69601864c50898f">anonymous{Signals.cpp}::CreateCrashDiagnosticsDir::call</a>.</p>

</div>
</div>

### DisableSymbolicationFlag {#a3700661bd7b989467aa60e9cb7ac751e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DisableSymbolicationFlag = false</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-signals-cpp-/createdisablesymbolication/#ac7acb8ce647dd517b18aefdadc004a86">anonymous{Signals.cpp}::CreateDisableSymbolication::call</a> and <a href="#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>.</p>

</div>
</div>

### DisableSymbolizationEnv {#a1741ace2a7f31133d2c5f93fc077e5da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char DisableSymbolizationEnv[] = "LLVM_DISABLE_SYMBOLIZATION"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>


<p>Referenced by <a href="#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>.</p>

</div>
</div>

### EnableSymbolizerMarkupEnv {#afd37850f227b8d23e6abf1ff21176a0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char EnableSymbolizerMarkupEnv[] = "LLVM_ENABLE_SYMBOLIZER_MARKUP"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>


<p>Referenced by <a href="#ae9c62fdad9f8cfb0551e47ad3116b699">printMarkupStackTrace</a>.</p>

</div>
</div>

### LLVMSymbolizerPathEnv {#a8dcd02a07bc24565fe1faae5a77e6a48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char LLVMSymbolizerPathEnv[] = "LLVM_SYMBOLIZER_PATH"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>


<p>Referenced by <a href="#a1c25905ebd1d19c4d5c4e2ca86cdb1f2">printSymbolizedStackTrace</a>.</p>

</div>
</div>

### MaxSignalHandlerCallbacks {#a8c60090b8acf9cbfff2736ce97e3e7e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t MaxSignalHandlerCallbacks = 8</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/support/signals-cpp">Signals.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
