---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmcerror
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Error Handling Reference



## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOpaqueError * <a href="#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Opaque reference to an error instance. <a href="#gad81d81a316ef38888533a24b786a6605">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * <a href="#gabf3930c1476f60f432d79776858039f6">LLVMErrorTypeId</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Error type identifier. <a href="#gabf3930c1476f60f432d79776858039f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">void(* <a href="#gaaba79ae56a17485c5d3fbd004ff60e47">LLVMFatalErrorHandler</a>)(const char *Reason)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gabf3930c1476f60f432d79776858039f6">LLVMErrorTypeId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2847de0d8da92d7f217dad48c14fee23">LLVMGetErrorTypeId</a> (LLVMErrorRef Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type id for the given error instance, which must be a failure value (i.e. <a href="#ga2847de0d8da92d7f217dad48c14fee23">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gafa975b13e476c457d93779475f960540">LLVMConsumeError</a> (LLVMErrorRef Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of the given error without handling it. <a href="#gafa975b13e476c457d93779475f960540">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga946eaac2a6fc0b492ffc6e59545c4378">LLVMCantFail</a> (LLVMErrorRef Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Report a fatal error if Err is a failure value. <a href="#ga946eaac2a6fc0b492ffc6e59545c4378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga089f52c976405b1df7daa6718bbed82a">LLVMGetErrorMessage</a> (LLVMErrorRef Err)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the given string's error message. <a href="#ga089f52c976405b1df7daa6718bbed82a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga68cbd8d8b7b1a6819f3a7fab9c1e777c">LLVMDisposeErrorMessage</a> (char *ErrMsg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of the given error message. <a href="#ga68cbd8d8b7b1a6819f3a7fab9c1e777c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gabf3930c1476f60f432d79776858039f6">LLVMErrorTypeId</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4a05289ff7e0e3ad3ae432894a40c2f3">LLVMGetStringErrorTypeId</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the type id for llvm StringError. <a href="#ga4a05289ff7e0e3ad3ae432894a40c2f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf49e4718877356aa8d4e88ed8b652668">LLVMCreateStringError</a> (const char *ErrMsg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a StringError. <a href="#gaf49e4718877356aa8d4e88ed8b652668">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf6159e6764fb23072ec25514b90b0ebd">LLVMInstallFatalErrorHandler</a> (LLVMFatalErrorHandler Handler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Install a fatal error handler. <a href="#gaf6159e6764fb23072ec25514b90b0ebd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7ea3d621a4b178b39e068f2c017ae617">LLVMResetFatalErrorHandler</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the fatal error handler. <a href="#ga7ea3d621a4b178b39e068f2c017ae617">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacd4315fc836550166df8bff5bf55dc32">LLVMEnablePrettyStackTrace</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable LLVM's built-in stack trace code. <a href="#gacd4315fc836550166df8bff5bf55dc32">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7073a9a5281337ab9bc306eeb567dd48">LLVMErrorSuccess</a>&nbsp;&nbsp;&nbsp;0</td>
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

## Typedefs

### LLVMErrorRef {#gad81d81a316ef38888533a24b786a6605}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOpaqueError* LLVMErrorRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Opaque reference to an error instance.</p>


<p>Null serves as the 'success' value.</p>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">Error.h</a>.</p>

</div>
</div>

### LLVMErrorTypeId {#gabf3930c1476f60f432d79776858039f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef const void* LLVMErrorTypeId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Error type identifier.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">Error.h</a>.</p>

</div>
</div>

### LLVMFatalErrorHandler {#gaaba79ae56a17485c5d3fbd004ff60e47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef void(* LLVMFatalErrorHandler) (const char *Reason)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/errorhandling-h">ErrorHandling.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### LLVMCantFail() {#ga946eaac2a6fc0b492ffc6e59545c4378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMCantFail (<a href="#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a> Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Report a fatal error if Err is a failure value.</p>


<p>This function can be used to wrap calls to fallible functions ONLY when it is known that the Error will always be a success value.</p>


<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">Error.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/support/error-cpp">Error.cpp</a>.</p>

</div>
</div>

### LLVMConsumeError() {#gafa975b13e476c457d93779475f960540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMConsumeError (<a href="#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a> Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dispose of the given error without handling it.</p>


<p>This operation consumes the error, and the given <a href="#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a> value is not usable once this call returns. Note: This method <em>only</em> needs to be called if the error is not being passed to some other consuming operation, e.g. LLVMGetErrorMessage.</p>


<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">Error.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/support/error-cpp">Error.cpp</a>.</p>

</div>
</div>

### LLVMCreateStringError() {#gaf49e4718877356aa8d4e88ed8b652668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorRef LLVMCreateStringError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ErrMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a StringError.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">Error.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/support/error-cpp">Error.cpp</a>.</p>

</div>
</div>

### LLVMDisposeErrorMessage() {#ga68cbd8d8b7b1a6819f3a7fab9c1e777c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDisposeErrorMessage (char * ErrMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dispose of the given error message.</p>

<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">Error.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/support/error-cpp">Error.cpp</a>.</p>

</div>
</div>

### LLVMEnablePrettyStackTrace() {#gacd4315fc836550166df8bff5bf55dc32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMEnablePrettyStackTrace (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Enable LLVM's built-in stack trace code.</p>


<p>This intercepts the OS's crash signals and prints which component of LLVM you were in at the time if the crash.</p>


<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/errorhandling-h">ErrorHandling.h</a>, definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/support/prettystacktrace-cpp">PrettyStackTrace.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#acfde701cd4218fcd2f236f2e4d893fef">llvm::EnablePrettyStackTrace</a>.</p>

</div>
</div>

### LLVMGetErrorMessage() {#ga089f52c976405b1df7daa6718bbed82a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * LLVMGetErrorMessage (<a href="#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a> Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the given string's error message.</p>


<p>This operation consumes the error, and the given <a href="#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a> value is not usable once this call returns. The caller is responsible for disposing of the string by calling LLVMDisposeErrorMessage.</p>


<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">Error.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/support/error-cpp">Error.cpp</a>.</p>

</div>
</div>

### LLVMGetErrorTypeId() {#ga2847de0d8da92d7f217dad48c14fee23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorTypeId LLVMGetErrorTypeId (<a href="#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a> Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the type id for the given error instance, which must be a failure value (i.e.</p>


<p>non-null).</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">Error.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/support/error-cpp">Error.cpp</a>.</p>

</div>
</div>

### LLVMGetStringErrorTypeId() {#ga4a05289ff7e0e3ad3ae432894a40c2f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorTypeId LLVMGetStringErrorTypeId (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the type id for llvm StringError.</p>

<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">Error.h</a>, definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/testing/lib/testing/support/error-cpp">Error.cpp</a>.</p>

</div>
</div>

### LLVMInstallFatalErrorHandler() {#gaf6159e6764fb23072ec25514b90b0ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMInstallFatalErrorHandler (<a href="#gaaba79ae56a17485c5d3fbd004ff60e47">LLVMFatalErrorHandler</a> Handler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Install a fatal error handler.</p>


<p>By default, if LLVM detects a fatal error, it will call exit(1). This may not be appropriate in many contexts. For example, doing exit(1) will bypass many crash reporting/tracing system tools. This function allows you to install a callback that will be invoked prior to the call to exit(1).</p>


<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/errorhandling-h">ErrorHandling.h</a>, definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp">ErrorHandling.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp/#a8bf77e8726f283ee9fa0a48c07a871ee">bindingsErrorHandler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2aeb96bbf49b1dd8f8a6cf1ceb4e86a7">llvm::install_fatal_error_handler</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa308b4893c1ee3415893491cd9c061d1">LLVM_EXTENSION</a>.</p>

</div>
</div>

### LLVMResetFatalErrorHandler() {#ga7ea3d621a4b178b39e068f2c017ae617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMResetFatalErrorHandler (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset the fatal error handler.</p>


<p>This resets LLVM's fatal error handling behavior to the default.</p>


<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/errorhandling-h">ErrorHandling.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp">ErrorHandling.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abdb4f14b8a339d669818c3c274d1add3">llvm::remove_fatal_error_handler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### LLVMErrorSuccess {#ga7073a9a5281337ab9bc306eeb567dd48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LLVMErrorSuccess&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">Error.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga7286ab56f015dc3d1364ee35c18248a0">LLVMOrcCreateDynamicLibrarySearchGeneratorForPath</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga989066e131860f8fe758251c061860a7">LLVMOrcCreateDynamicLibrarySearchGeneratorForProcess</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gae5289a7cc63f872a7ba713bdaef88cd9">LLVMOrcCreateLLJIT</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga18d11d3d068c59207d39cd72a6224f01">LLVMOrcCreateLocalLazyCallThroughManager</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp/#a734850637f9fd595b4fb8aac2f1fe061">LLVMOrcCreateStaticLibrarySearchGeneratorForPath</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga364a3b00fb6982a14e2532cec903e8ae">LLVMOrcDisposeLLJIT</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga9293a65df367929436b36c2fff46e563">LLVMOrcDumpObjects_CallOperator</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaec6788883ef8ca0728d8f31c16a8a90e">LLVMOrcExecutionSessionCreateJITDylib</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga4af207d5a28d38c765a7f33d658df2a5">LLVMOrcExecutionSessionLookup</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa349e25fd72cbf480e926aeab681b4e2">LLVMOrcJITDylibDefine</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga5718550d7bc69420aef9830b23a1bec7">LLVMOrcJITTargetMachineBuilderDetectHost</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaf8efaaa71b4b22ed96c3c05b93e98273">LLVMOrcLLJITLookup</a> and <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga8ed0de76e9767b06afa96fd9df5796b6">LLVMOrcMaterializationResponsibilityDelegate</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
