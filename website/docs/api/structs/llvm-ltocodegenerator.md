---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/ltocodegenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LTOCodeGenerator` Struct Reference

<p>C++ class which implements the opaque <a href="/web-llvm/docs/api/groups/llvmclto/#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::LTOCodeGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">llvm/LTO/legacy/LTOCodeGenerator.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8858e53845218c6fa6d63d84f0d02f78">LTOCodeGenerator</a> (LLVMContext &amp;Context)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca8ea9b26ccba3b9941df6442337e6ce">~LTOCodeGenerator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa825905bb00e926e44bc04afbea56603">addModule</a> (struct LTOModule *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge given module. <a href="#aa825905bb00e926e44bc04afbea56603">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a225a89bc98401f30bfb332461d9cebae">setModule</a> (std::unique_ptr&lt; LTOModule &gt; M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the destination module. <a href="#a225a89bc98401f30bfb332461d9cebae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b55049858b0cebc4cc15b9bcaff3598">setAsmUndefinedRefs</a> (struct LTOModule *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75732f59c3f31c22131b521c927da20f">setTargetOptions</a> (const TargetOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc416d3bc1e7f6d368903dfdcdfba358">setDebugInfo</a> (lto_debug_model)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a897cf21ea578203afe02daf8b8309188">setCodePICModel</a> (std::optional&lt; Reloc::Model &gt; Model)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7540fde79e9d4fb63a56781f7260e3ea">setFileType</a> (CodeGenFileType FT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the file type to be emitted (assembly or object code). <a href="#a7540fde79e9d4fb63a56781f7260e3ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa1d4d83f2702dca75ce883b59bad1b">setCpu</a> (StringRef MCpu)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a435726751887478120c87646f4525814">setAttrs</a> (std::vector&lt; std::string &gt; MAttrs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d11ddd6ea999809e6670e52a6219cb">setOptLevel</a> (unsigned OptLevel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38938d28a7fb26e67c31e1c3bd3bbb11">setShouldInternalize</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0163531a045e6005ca513bb4c315b0b">setShouldEmbedUselists</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf54718a25d8f2d5e985ea12b15c6bee">setSaveIRBeforeOptPath</a> (std::string Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af08f01d6b672143c1225085a731868be">setShouldRestoreGlobalsLinkage</a> (bool Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Restore linkage of globals. <a href="#af08f01d6b672143c1225085a731868be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32cfe4929393f5d065a15fdd18a17a43">addMustPreserveSymbol</a> (StringRef Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a265f64928bda17c0d48f963779e7b3">setCodeGenDebugOptions</a> (ArrayRef&lt; StringRef &gt; Opts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> options to the driver and optimization passes. <a href="#a7a265f64928bda17c0d48f963779e7b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53905a26d815c643e7d298da17f93079">parseCodeGenDebugOptions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the options set in setCodeGenDebugOptions. <a href="#a53905a26d815c643e7d298da17f93079">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6c084cf21df6bb57da846088680146b">writeMergedModules</a> (StringRef Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the merged module to the file specified by the given path. <a href="#ae6c084cf21df6bb57da846088680146b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d611481aad540d852ba2c91587bd54">compile_to_file</a> (const char **Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compile the merged module into a <em>single</em> output file; the path to output file is returned to the caller via argument "name". <a href="#a27d611481aad540d852ba2c91587bd54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0094212f9cb4bcbe1b3c39b2785e55">compile</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>As with <a href="#a27d611481aad540d852ba2c91587bd54">compile_to_file()</a>, this function compiles the merged module into single output file. <a href="#a0b0094212f9cb4bcbe1b3c39b2785e55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0662a37baac76f3ec5c6ca268ae277ac">optimize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimizes the merged module. <a href="#a0662a37baac76f3ec5c6ca268ae277ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a933d031a629f7261df21829fbea78f94">compileOptimized</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compiles the merged optimized module into a single output file. <a href="#a933d031a629f7261df21829fbea78f94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcf354bfe0e74d87f632076d2cedd08d">compileOptimized</a> (AddStreamFn AddStream, unsigned ParallelismLevel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compile the merged optimized module <span class="doxyComputerOutput">ParallelismLevel</span> output files each representing a linkable partition of the module. <a href="#afcf354bfe0e74d87f632076d2cedd08d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe9393c3af8e0cc6aba8e3045603d2e3">setFreestanding</a> (bool Enabled)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable the Freestanding mode: indicate that the optimizer should not assume builtins are present on the target. <a href="#afe9393c3af8e0cc6aba8e3045603d2e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfdcf6f523c35684057b92a7ce677d34">setDisableVerify</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd1a3698b32729075e4d192b0f423d0">setDebugPassManager</a> (bool Enabled)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73ebc6975f447eb8194812f637d6caf4">setDiagnosticHandler</a> (lto_diagnostic_handler_t, void *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed5e3fb796971352b5bda5ae880f24f">getContext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad64e193bcb991de025f9e0096fb20d7b">resetMergedModule</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bbdd648bb050563755e846cdf43932">DiagnosticHandler</a> (const DiagnosticInfo &amp;DI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06461c1e63e1e5d9cca5abb73cb5481c">verifyMergedModuleOnce</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Verify the merged module on first call. <a href="#a06461c1e63e1e5d9cca5abb73cb5481c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac94bf4c6c8e57984c8a522d3cd8567">compileOptimizedToFile</a> (const char **Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec304f3a1b3cf9dde39f1996ba335f21">restoreLinkageForExternals</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Restore original linkage for symbols that may have been internalized. <a href="#aec304f3a1b3cf9dde39f1996ba335f21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41279c43827c65a7a85916fa29519475">applyScopeRestrictions</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acee6ecb649f9f5349b6ad3947a23946b">preserveDiscardableGVs</a> (Module &amp;TheModule, llvm::function_ref&lt; bool(const GlobalValue &amp;)&gt; mustPreserveGV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac799838e139f21e5bdb836107edd0540">determineTarget</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52301bf564759ac74c09807da982d9d2">createTargetMachine</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84bfa51d7c2717dccf3d0c8f5e54b901">useAIXSystemAssembler</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5d8475bd690a822ee0d0b72770af0d">runAIXSystemAssembler</a> (SmallString&lt; 128 &gt; &amp;AssemblyFile)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa02c7f2d291452e35065d0f7fd43a16c">emitError</a> (const std::string &amp;ErrMsg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32a79302880c17b570effd8f62e638e4">emitWarning</a> (const std::string &amp;ErrMsg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711fd84a85816af2a62329c920cfde97">finishOptimizationRemarks</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a406e9ad5a2ef0d5f545abb11bba438e5">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a191b69106cc0c6818f9c72e996353f1b">MergedModule</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/linker">Linker</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02a39cb16e439a3554c26409f8eb00f">TheLinker</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adec82d4cb2897c1194fa890b642a8289">TargetMach</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7bb04d6b79d37b088101adb708f43e8">EmitDwarfDebugInfo</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2f0a9412f6ff9989fc142a53e11dfd">ScopeRestrictionsDone</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b2eefca5528695cd87f003adc7c470">HasVerifiedInput</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47649ea6f677b0e79952369eaf6c9689">MustPreserveSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9effeab65f4da5df81f13fbdcbade77">AsmUndefinedRefs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d228f1fce8fdea7e1a628e310fb55f9">ExternalSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515088d09629113ad2d3ed27d2d7acb9">CodegenOptions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af548343e08d1de0ee12943f3e360ebcb">FeatureStr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ff86f253f667be38428bdcf0f8cdf9d">NativeObjectPath</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9b28cb9a270260f117c30e6ca036b6">MArch</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3a1da000932de3cef155247cfa4015e">TripleStr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmclto/#gacc8bcb5e44e35ed3a8b8e9f077218c21">lto_diagnostic_handler_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4ca6f3cfd3b42d5b5a3ba36c1955f76">DiagHandler</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa15e0b963a30bbf2ba69c11d0ac17a26">DiagContext</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2025a08a702675e8d830f1428f4460c4">ShouldInternalize</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a8762ebd5bf9405ac3edf4c40d8cb36a9">EnableLTOInternalization</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46162c00b587c9777e5ea9c422a99610">ShouldEmbedUselists</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09d869780d76070a5d396965b84b5fe9">ShouldRestoreGlobalsLinkage</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tooloutputfile">ToolOutputFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce2028edd0a3f65ce0f56c348fe62a1">DiagnosticOutputFile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/tooloutputfile">ToolOutputFile</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac49ea6b7f05b3a76a99628f36bc87867">StatsFile</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dfa8b8171636a996b23b25b78fe15a3">SaveIRBeforeOptPath</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lto/config">lto::Config</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aef3419c03e774c1fabe8e457fb0a0a">Config</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf2d24b4735f4a67429957fa8b652dd">getVersionString</a> ()</td>
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

<p>C++ class which implements the opaque <a href="/web-llvm/docs/api/groups/llvmclto/#ga6e1ba6da4277057a20e147d9412a03d7">lto_code_gen_t</a> type.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LTOCodeGenerator() {#a8858e53845218c6fa6d63d84f0d02f78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LTOCodeGenerator::LTOCodeGenerator (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2345a4b944cb14fc13cab54753b494ca">llvm::LTOCSIRProfile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a18e129cc13b9fb9f4ac54d2b21e2c37f">llvm::LTODiscardValueNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7469ca236475e973384e0969a1fb87c">llvm::LTORunCSIRInstr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adedfc2b0c018d94c23687647fd2b9317">llvm::LTOStatsFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LTOCodeGenerator() {#aca8ea9b26ccba3b9941df6442337e6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LTOCodeGenerator::~LTOCodeGenerator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addModule() {#aa825905bb00e926e44bc04afbea56603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LTOCodeGenerator::addModule (struct <a href="/web-llvm/docs/api/structs/llvm/ltomodule">LTOModule</a> * Mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge given module.</p>


<p>Return true on success.</p>


<p>Resets <em>HasVerifiedInput</em>.</p>


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a> and <a href="#a6b55049858b0cebc4cc15b9bcaff3598">setAsmUndefinedRefs</a>.</p>

</div>
</div>

### addMustPreserveSymbol() {#a32cfe4929393f5d065a15fdd18a17a43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::addMustPreserveSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Sym)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### compile() {#a0b0094212f9cb4bcbe1b3c39b2785e55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; LTOCodeGenerator::compile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>As with <a href="#a27d611481aad540d852ba2c91587bd54">compile_to_file()</a>, this function compiles the merged module into single output file.</p>


<p>Instead of returning the output file path to the caller (linker), it brings the output to a buffer, and returns the buffer to the caller. This function should delete the intermediate file once its content is brought to memory. Return NULL if the compilation was not successful.</p>


<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>References <a href="#a933d031a629f7261df21829fbea78f94">compileOptimized</a> and <a href="#a0662a37baac76f3ec5c6ca268ae277ac">optimize</a>.</p>

</div>
</div>

### compile\_to\_file() {#a27d611481aad540d852ba2c91587bd54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LTOCodeGenerator::compile_to_file (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compile the merged module into a <em>single</em> output file; the path to output file is returned to the caller via argument "name".</p>


<p>Return true on success.</p>



:::info
<p>It is up to the linker to remove the intermediate output file. Do not try to remove the object file in <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator">LTOCodeGenerator</a>'s destructor as we don't who (<a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator">LTOCodeGenerator</a> or the output file) will last longer.</p>
:::


<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 369 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>Reference <a href="#a0662a37baac76f3ec5c6ca268ae277ac">optimize</a>.</p>

</div>
</div>

### compileOptimized() {#a933d031a629f7261df21829fbea78f94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; MemoryBuffer &gt; LTOCodeGenerator::compileOptimized ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compiles the merged optimized module into a single output file.</p>


<p>It brings the output to a buffer, and returns the buffer to the caller. Return NULL if the compilation was not successful.</p>


<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a921e0b01f22f9a37012450f9b5f0ccb7">llvm::sys::fs::remove</a>.</p>


<p>Referenced by <a href="#a0b0094212f9cb4bcbe1b3c39b2785e55">compile</a>.</p>

</div>
</div>

### compileOptimized() {#afcf354bfe0e74d87f632076d2cedd08d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LTOCodeGenerator::compileOptimized (<a href="/web-llvm/docs/api/namespaces/llvm/#aeb8b31be7b2c7dd67496051d7f952e94">AddStreamFn</a> AddStream, unsigned ParallelismLevel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compile the merged optimized module <span class="doxyComputerOutput">ParallelismLevel</span> output files each representing a linkable partition of the module.</p>


<p>If out contains more than one element, code generation is done in parallel with <span class="doxyComputerOutput">ParallelismLevel</span> threads. Output files will be written to the streams created using the <span class="doxyComputerOutput">AddStream</span> callback. Returns true on success.</p>


<p>Calls <em>verifyMergedModuleOnce()</em>.</p>


<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a846137dc22b3b399b62f606698f3ed59">llvm::AreStatisticsEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5094c6f6a737f5a94596cdab0b2b449">llvm::PrintStatistics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec1a19ebf309a206257e212c33f045a1">llvm::PrintStatisticsJSON</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4fcfca5f1acab67334c771877cd83a21">llvm::reportAndResetTimings</a>.</p>

</div>
</div>

### DiagnosticHandler() {#ae8bbdd648bb050563755e846cdf43932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::DiagnosticHandler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo">DiagnosticInfo</a> &amp; DI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5caa73815097c71f15fe54ab447a7ff00ba">llvm::DS_Error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca320faa3dfbce0b3e99c5c255d45da362">llvm::DS_Note</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1b15350d527e821b198f76a0cd080fc3">llvm::DS_Remark</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfcab32516704f11d146c757f402ad5ca1cde8c8828756cdaf2a93260e247ae31">llvm::DS_Warning</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#a442499cb808b8d5b55eec9087eaf3f3f">llvm::DiagnosticInfo::getSeverity</a>, <a href="/web-llvm/docs/api/groups/llvmclto/#gga7d1dffbb71e58b376fc879b8098957b3a56df7007d9125bb715a76233ba550933">LTO_DS_ERROR</a>, <a href="/web-llvm/docs/api/groups/llvmclto/#gga7d1dffbb71e58b376fc879b8098957b3a3f49e62e22757ac378175adf24290baa">LTO_DS_NOTE</a>, <a href="/web-llvm/docs/api/groups/llvmclto/#gga7d1dffbb71e58b376fc879b8098957b3a2f2659d7b052eff3b70bc3c6d70e67c5">LTO_DS_REMARK</a>, <a href="/web-llvm/docs/api/groups/llvmclto/#gga7d1dffbb71e58b376fc879b8098957b3a30389796c848e8df04427fb26ca4d477">LTO_DS_WARNING</a> and <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfo/#afe1ba88d90b63845116236a764a670a3">llvm::DiagnosticInfo::print</a>.</p>

</div>
</div>

### getContext() {#a5ed5e3fb796971352b5bda5ae880f24f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; llvm::LTOCodeGenerator::getContext ()</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### optimize() {#a0662a37baac76f3ec5c6ca268ae277ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LTOCodeGenerator::optimize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimizes the merged module.</p>


<p>Optimize merged modules using various IPO passes.</p>


<p>Returns true on success.</p>


<p>Calls <em>verifyMergedModuleOnce()</em>.</p>


<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a18e129cc13b9fb9f4ac54d2b21e2c37f">llvm::LTODiscardValueNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adedfc2b0c018d94c23687647fd2b9317">llvm::LTOStatsFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8dbf0a7ff527022e0bc9313961d098d9">llvm::RemarksFilename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a00aed2787bd3f818d745a1ef171bf3">llvm::RemarksFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2f0e273d7dfee8425f06bc1959a6e36">llvm::RemarksHotnessThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29a674af5908403fd9aa59aa8194241f">llvm::RemarksPasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b19e8926f03fc73e087818aa81bcb37">llvm::RemarksWithHotness</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#adf0da31fd6ca90efb2819d0f6061bd74">llvm::lto::setupLLVMOptimizationRemarks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lto/#a7df2e6bd8a987ca6e4e4ced678ecbfcf">llvm::lto::setupStatsFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a714c6f3608e37d0dba17cdc086dc16d2">llvm::updatePublicTypeTestCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af8b10064b29ab4bb0c85f28342ce72dd">llvm::updateVCallVisibilityInModule</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>.</p>


<p>Referenced by <a href="#a0b0094212f9cb4bcbe1b3c39b2785e55">compile</a> and <a href="#a27d611481aad540d852ba2c91587bd54">compile_to_file</a>.</p>

</div>
</div>

### parseCodeGenDebugOptions() {#a53905a26d815c643e7d298da17f93079}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::parseCodeGenDebugOptions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the options set in setCodeGenDebugOptions.</p>


<p>Like <em><a href="#a7a265f64928bda17c0d48f963779e7b3">setCodeGenDebugOptions()</a></em>, this must be called before LTOCodeGenerator::compilexxx() and <a href="#ae6c084cf21df6bb57da846088680146b">LTOCodeGenerator::writeMergedModules()</a>.</p>


<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 677 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9483b4c6174d8b7ef3725c85222b9484">llvm::parseCommandLineOptions</a>.</p>

</div>
</div>

### resetMergedModule() {#ad64e193bcb991de025f9e0096fb20d7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::resetMergedModule ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### setAsmUndefinedRefs() {#a6b55049858b0cebc4cc15b9bcaff3598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::setAsmUndefinedRefs (struct <a href="/web-llvm/docs/api/structs/llvm/ltomodule">LTOModule</a> * Mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>.</p>


<p>Referenced by <a href="#aa825905bb00e926e44bc04afbea56603">addModule</a> and <a href="#a225a89bc98401f30bfb332461d9cebae">setModule</a>.</p>

</div>
</div>

### setAttrs() {#a435726751887478120c87646f4525814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::setAttrs (std::vector&lt; std::string &gt; MAttrs)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### setCodeGenDebugOptions() {#a7a265f64928bda17c0d48f963779e7b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::setCodeGenDebugOptions (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Opts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> options to the driver and optimization passes.</p>


<p>These options are not necessarily for debugging purpose (the function name is misleading). This function should be called before LTOCodeGenerator::compilexxx(), and <a href="#ae6c084cf21df6bb57da846088680146b">LTOCodeGenerator::writeMergedModules()</a>.</p>


<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

### setCodePICModel() {#a897cf21ea578203afe02daf8b8309188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::setCodePICModel (std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; Model)</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### setCpu() {#a2aa1d4d83f2702dca75ce883b59bad1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::setCpu (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> MCpu)</td>
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



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### setDebugInfo() {#abc416d3bc1e7f6d368903dfdcdfba358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::setDebugInfo (<a href="/web-llvm/docs/api/groups/llvmclto/#ga45b08530a7582678cb4c03bc70a33bae">lto_debug_model</a> Debug)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/debug-cpp/#a3fd0c3ac7c0e9187aa5c690ef9c70ebe">Debug</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/groups/llvmclto/#gga45b08530a7582678cb4c03bc70a33baea4bd5cb0d20be9e3459e946632969ae3e">LTO_DEBUG_MODEL_DWARF</a> and <a href="/web-llvm/docs/api/groups/llvmclto/#gga45b08530a7582678cb4c03bc70a33baea9c4180379ab2964e5545899510832af6">LTO_DEBUG_MODEL_NONE</a>.</p>

</div>
</div>

### setDebugPassManager() {#a9fd1a3698b32729075e4d192b0f423d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::setDebugPassManager (bool Enabled)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp/#a558f5c44426d0eb7abb82a65e8892d9a">Enabled</a>.</p>

</div>
</div>

### setDiagnosticHandler() {#a73ebc6975f447eb8194812f637d6caf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::setDiagnosticHandler (<a href="/web-llvm/docs/api/groups/llvmclto/#gacc8bcb5e44e35ed3a8b8e9f077218c21">lto_diagnostic_handler_t</a> DiagHandler, void * Ctxt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 735 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### setDisableVerify() {#abfdcf6f523c35684057b92a7ce677d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::setDisableVerify (bool Value)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### setFileType() {#a7540fde79e9d4fb63a56781f7260e3ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::setFileType (<a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260">CodeGenFileType</a> FT)</td>
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

<p>Set the file type to be emitted (assembly or object code).</p>


<p>The default is <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260a95aca07e95d9459c1bb31f4e7f9fda10">CodeGenFileType::ObjectFile</a>.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### setFreestanding() {#afe9393c3af8e0cc6aba8e3045603d2e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::setFreestanding (bool Enabled)</td>
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

<p>Enable the Freestanding mode: indicate that the optimizer should not assume builtins are present on the target.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp/#a558f5c44426d0eb7abb82a65e8892d9a">Enabled</a>.</p>

</div>
</div>

### setModule() {#a225a89bc98401f30bfb332461d9cebae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::setModule (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/ltomodule">LTOModule</a> &gt; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the destination module.</p>


<p>Resets <em>HasVerifiedInput</em>.</p>


<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 163 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a> and <a href="#a6b55049858b0cebc4cc15b9bcaff3598">setAsmUndefinedRefs</a>.</p>

</div>
</div>

### setOptLevel() {#a57d11ddd6ea999809e6670e52a6219cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::setOptLevel (unsigned OptLevel)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codegenopt/#a6f32c8cbe9e69d7926b20fcf456281b7">llvm::CodeGenOpt::getLevel</a>.</p>

</div>
</div>

### setSaveIRBeforeOptPath() {#abf54718a25d8f2d5e985ea12b15c6bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::setSaveIRBeforeOptPath (std::string Value)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### setShouldEmbedUselists() {#ac0163531a045e6005ca513bb4c315b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::setShouldEmbedUselists (bool Value)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### setShouldInternalize() {#a38938d28a7fb26e67c31e1c3bd3bbb11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::setShouldInternalize (bool Value)</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### setShouldRestoreGlobalsLinkage() {#af08f01d6b672143c1225085a731868be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LTOCodeGenerator::setShouldRestoreGlobalsLinkage (bool Value)</td>
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

<p>Restore linkage of globals.</p>


<p>When set, the linkage of globals will be restored prior to code generation. That is, a global symbol that had external linkage prior to LTO will be emitted with external linkage again; and a local will remain local. Note that this option only affects the end result - globals may still be internalized in the process of LTO and may be modified and/or deleted where legal.</p>


<p>The default behavior will internalize globals (unless on the preserve list) and, if parallel code generation is enabled, will externalize all locals.</p>


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### setTargetOptions() {#a75732f59c3f31c22131b521c927da20f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::setTargetOptions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp; Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>

</div>
</div>

### writeMergedModules() {#ae6c084cf21df6bb57da846088680146b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LTOCodeGenerator::writeMergedModules (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Write the merged module to the file specified by the given path.</p>


<p>Return true on success.</p>


<p>Calls <em>verifyMergedModuleOnce()</em>.</p>


<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a7b4fefe70f73556669fd513ed9d0fae4">llvm::raw_fd_ostream::clear_error</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a293545f9b5864a8e1b33e57becbc5b3a">llvm::raw_fd_ostream::close</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a215c95ed69aa5b5756dd9c0f1b1de410">llvm::raw_fd_ostream::error</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a0d5a564fb5459ab9ce6e56401786542b">llvm::raw_fd_ostream::has_error</a>, <a href="/web-llvm/docs/api/classes/llvm/tooloutputfile/#a736bcda698a82e4ae3a92310d706868d">llvm::ToolOutputFile::keep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/classes/llvm/tooloutputfile/#afd739434d6e7e26f93a9e87c23e4e7a3">llvm::ToolOutputFile::os</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyScopeRestrictions() {#a41279c43827c65a7a85916fa29519475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::applyScopeRestrictions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### compileOptimizedToFile() {#aeac94bf4c6c8e57984c8a522d3cd8567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LTOCodeGenerator::compileOptimizedToFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char ** Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### createTargetMachine() {#a52301bf564759ac74c09807da982d9d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; TargetMachine &gt; LTOCodeGenerator::createTargetMachine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 421 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### determineTarget() {#ac799838e139f21e5bdb836107edd0540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LTOCodeGenerator::determineTarget ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### emitError() {#aa02c7f2d291452e35065d0f7fd43a16c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::emitError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; ErrMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 757 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### emitWarning() {#a32a79302880c17b570effd8f62e638e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::emitWarning (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; ErrMsg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### finishOptimizationRemarks() {#a711fd84a85816af2a62329c920cfde97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::finishOptimizationRemarks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### preserveDiscardableGVs() {#acee6ecb649f9f5349b6ad3947a23946b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::preserveDiscardableGVs (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; TheModule, <a href="/web-llvm/docs/api/classes/llvm/function-ref">llvm::function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp;)&gt; mustPreserveGV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### restoreLinkageForExternals() {#aec304f3a1b3cf9dde39f1996ba335f21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::restoreLinkageForExternals ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Restore original linkage for symbols that may have been internalized.</p>

<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 516 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### runAIXSystemAssembler() {#a0f5d8475bd690a822ee0d0b72770af0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LTOCodeGenerator::runAIXSystemAssembler (<a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 128 &gt; &amp; AssemblyFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### useAIXSystemAssembler() {#a84bfa51d7c2717dccf3d0c8f5e54b901}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LTOCodeGenerator::useAIXSystemAssembler ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

### verifyMergedModuleOnce() {#a06461c1e63e1e5d9cca5abb73cb5481c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LTOCodeGenerator::verifyMergedModuleOnce ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Verify the merged module on first call.</p>


<p>Sets <em>HasVerifiedInput</em> on first call and doesn't run again on the same input.</p>


<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AsmUndefinedRefs {#aa9effeab65f4da5df81f13fbdcbade77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet llvm::LTOCodeGenerator::AsmUndefinedRefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### CodegenOptions {#a515088d09629113ad2d3ed27d2d7acb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::LTOCodeGenerator::CodegenOptions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### Config {#a3aef3419c03e774c1fabe8e457fb0a0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto::Config llvm::LTOCodeGenerator::Config</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### Context {#a406e9ad5a2ef0d5f545abb11bba438e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; llvm::LTOCodeGenerator::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### DiagContext {#aa15e0b963a30bbf2ba69c11d0ac17a26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::LTOCodeGenerator::DiagContext = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### DiagHandler {#ab4ca6f3cfd3b42d5b5a3ba36c1955f76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">lto_diagnostic_handler_t llvm::LTOCodeGenerator::DiagHandler = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### DiagnosticOutputFile {#a7ce2028edd0a3f65ce0f56c348fe62a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ToolOutputFile&gt; llvm::LTOCodeGenerator::DiagnosticOutputFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### EmitDwarfDebugInfo {#ad7bb04d6b79d37b088101adb708f43e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LTOCodeGenerator::EmitDwarfDebugInfo = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### ExternalSymbols {#a3d228f1fce8fdea7e1a628e310fb55f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;GlobalValue::LinkageTypes&gt; llvm::LTOCodeGenerator::ExternalSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### FeatureStr {#af548343e08d1de0ee12943f3e360ebcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LTOCodeGenerator::FeatureStr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### HasVerifiedInput {#a13b2eefca5528695cd87f003adc7c470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LTOCodeGenerator::HasVerifiedInput = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### MArch {#abb9b28cb9a270260f117c30e6ca036b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Target* llvm::LTOCodeGenerator::MArch = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### MergedModule {#a191b69106cc0c6818f9c72e996353f1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Module&gt; llvm::LTOCodeGenerator::MergedModule</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### MustPreserveSymbols {#a47649ea6f677b0e79952369eaf6c9689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet llvm::LTOCodeGenerator::MustPreserveSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### NativeObjectPath {#a8ff86f253f667be38428bdcf0f8cdf9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LTOCodeGenerator::NativeObjectPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### SaveIRBeforeOptPath {#a1dfa8b8171636a996b23b25b78fe15a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LTOCodeGenerator::SaveIRBeforeOptPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### ScopeRestrictionsDone {#a5e2f0a9412f6ff9989fc142a53e11dfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LTOCodeGenerator::ScopeRestrictionsDone = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### ShouldEmbedUselists {#a46162c00b587c9777e5ea9c422a99610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LTOCodeGenerator::ShouldEmbedUselists = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### ShouldInternalize {#a2025a08a702675e8d830f1428f4460c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LTOCodeGenerator::ShouldInternalize = <a href="/web-llvm/docs/api/namespaces/llvm/#a8762ebd5bf9405ac3edf4c40d8cb36a9">EnableLTOInternalization</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### ShouldRestoreGlobalsLinkage {#a09d869780d76070a5d396965b84b5fe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LTOCodeGenerator::ShouldRestoreGlobalsLinkage = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### StatsFile {#ac49ea6b7f05b3a76a99628f36bc87867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ToolOutputFile&gt; llvm::LTOCodeGenerator::StatsFile = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### TargetMach {#adec82d4cb2897c1194fa890b642a8289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;TargetMachine&gt; llvm::LTOCodeGenerator::TargetMach</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### TheLinker {#ab02a39cb16e439a3554c26409f8eb00f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Linker&gt; llvm::LTOCodeGenerator::TheLinker</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

### TripleStr {#ae3a1da000932de3cef155247cfa4015e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LTOCodeGenerator::TripleStr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getVersionString() {#aedf2d24b4735f4a67429957fa8b652dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LTOCodeGenerator::getVersionString ()</td>
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



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/include/llvm/lto/legacy/ltocodegenerator-h">LTOCodeGenerator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/ltocodegenerator-cpp">LTOCodeGenerator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
