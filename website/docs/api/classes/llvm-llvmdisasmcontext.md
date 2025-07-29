---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/llvmdisasmcontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LLVMDisasmContext` Class



## Declaration

<div class="doxyDeclaration">
class llvm::LLVMDisasmContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">MC/MCDisassembler/Disassembler.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3d393ecff08342f307bd92a72841183">LLVMDisasmContext</a> (std::string TripleName, void *DisInfo, int TagType, LLVMOpInfoCallback GetOpInfo, LLVMSymbolLookupCallback SymbolLookUp, const Target *TheTarget, std::unique_ptr&lt; const MCAsmInfo &gt; &amp;&amp;MAI, std::unique_ptr&lt; const MCRegisterInfo &gt; &amp;&amp;MRI, std::unique_ptr&lt; const MCSubtargetInfo &gt; &amp;&amp;MSI, std::unique_ptr&lt; const MCInstrInfo &gt; &amp;&amp;MII, std::unique_ptr&lt; const llvm::MCContext &gt; &amp;&amp;Ctx, std::unique_ptr&lt; const MCDisassembler &gt; &amp;&amp;DisAsm, std::unique_ptr&lt; MCInstPrinter &gt; &amp;&amp;IP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6472ad3902ecbb48480e46eb60217b9">getTripleName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac122d75c34da790e5116677a9f42d9b6">getDisInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae29f174e4b89c59433ed98d8fc8025de">getTagType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61df5b94800da805be55cba86e71ef83">getGetOpInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3859e9d1bd00cdaf607db13a873320fe">getSymbolLookupCallback</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf9ddd5b499d9fe5c3a5e8374ec6a73">getTarget</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a025b4cae7b0009c9b81088eec80d4bdd">getDisAsm</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aaa235a27bfb38f0a782db0e5945176">getAsmInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1b025fe9218ff51f65b8d0be826e3db">getInstrInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6a4fae6275aca4dfeb6d0e2618482ba">getRegisterInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38cda99e294483fa025f4eb57f6544b9">getSubtargetInfo</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd7a5e2ee33e79a76e07153242061fc3">getIP</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36eaceae57946055f0f9439da556700c">setIP</a> (MCInstPrinter *NewIP)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf18895a5ca03704be21ce808e03c83">getOptions</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a242ff66f07dcc065b46e07959edf6e4d">addOptions</a> (uint64_t Options)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf19fba4e0fcd1425a837d3634c3c853">getCPU</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a043768d184e14c6c14e4db9389e6218a">setCPU</a> (const char *CPU)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 128 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca3253766aa266590e688a23f97ac612">CommentsToEmit</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream">raw_svector_ostream</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ae4b99e4c6cd8620f8603354572a33">CommentStream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88fa03dea71c8782cac1ca1af7c8c66">TripleName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b728491e08f589b11a9c3a47721b711">DisInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa12e5253daf3805ce6fe38a195c2281">TagType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f59f9332ba0d7876e870d0adb05a7cb">GetOpInfo</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7b4f72a8a33ca89b1173a06e783e7fd">SymbolLookUp</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd0cdc91dbe6ef8fe11323a982b0e4eb">TheTarget</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">llvm::MCAsmInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56707caa5c09ae8aa9b476da844838b2">MAI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">llvm::MCRegisterInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b0b972185529c7639653741b6ddc63c">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">llvm::MCSubtargetInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56767ece5cc3c9329b520fa302c32ba0">MSI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">llvm::MCInstrInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5f2049dbb681d5da0217492a9787d6e">MII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mccontext">llvm::MCContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a020b21a838d253a0b2f26bdcc85f6e98">Ctx</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">llvm::MCDisassembler</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b83690cccf691a481bcea4f23609d75">DisAsm</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">llvm::MCInstPrinter</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a747756eb6963c35db27def2b98a18a2e">IP</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada0b1e977f8b32ea7164d0f858aceeb4">Options</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb267f50210b822505f00c2452487c4a">CPU</a></td>
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


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LLVMDisasmContext() {#af3d393ecff08342f307bd92a72841183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LLVMDisasmContext::LLVMDisasmContext (std::string TripleName, void * DisInfo, int TagType, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gaa8eb7ea1e53fd6e7a11b6aa4749c6e60">LLVMOpInfoCallback</a> GetOpInfo, <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga05ffa603beb390898904a06b14ee5537">LLVMSymbolLookupCallback</a> SymbolLookUp, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> * TheTarget, std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasminfo">MCAsmInfo</a> &gt; &amp;&amp; MAI, std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo">MCRegisterInfo</a> &gt; &amp;&amp; MRI, std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &gt; &amp;&amp; MSI, std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &gt; &amp;&amp; MII, std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mccontext">llvm::MCContext</a> &gt; &amp;&amp; Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcdisassembler">MCDisassembler</a> &gt; &amp;&amp; DisAsm, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> &gt; &amp;&amp; IP)</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>References <a href="#aca3253766aa266590e688a23f97ac612">CommentsToEmit</a>, <a href="#a26ae4b99e4c6cd8620f8603354572a33">CommentStream</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addOptions() {#a242ff66f07dcc065b46e07959edf6e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LLVMDisasmContext::addOptions (uint64_t Options)</td>
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



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### getAsmInfo() {#a4aaa235a27bfb38f0a782db0e5945176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCAsmInfo * llvm::LLVMDisasmContext::getAsmInfo ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#a0e50dc982f01eab3eeb5eef624e25f03">emitComments</a> and <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### getCPU() {#acf19fba4e0fcd1425a837d3634c3c853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::LLVMDisasmContext::getCPU ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### getDisAsm() {#a025b4cae7b0009c9b81088eec80d4bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCDisassembler * llvm::LLVMDisasmContext::getDisAsm ()</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a>.</p>

</div>
</div>

### getDisInfo() {#ac122d75c34da790e5116677a9f42d9b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::LLVMDisasmContext::getDisInfo ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### getGetOpInfo() {#a61df5b94800da805be55cba86e71ef83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOpInfoCallback llvm::LLVMDisasmContext::getGetOpInfo ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### getInstrInfo() {#ad1b025fe9218ff51f65b8d0be826e3db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCInstrInfo * llvm::LLVMDisasmContext::getInstrInfo ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo/#a176ca2c9108a997dcfd8aadf4c0f0fa0">llvm::MCInstrInfo::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#ad7331753737602bb545def2c960c209d">emitLatency</a> and <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### getIP() {#acd7a5e2ee33e79a76e07153242061fc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCInstPrinter * llvm::LLVMDisasmContext::getIP ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a> and <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### getOptions() {#a8cf18895a5ca03704be21ce808e03c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::LLVMDisasmContext::getOptions ()</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a>.</p>

</div>
</div>

### getRegisterInfo() {#aa6a4fae6275aca4dfeb6d0e2618482ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterInfo * llvm::LLVMDisasmContext::getRegisterInfo ()</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcregisterinfo/#a20afbbc02b58a57256a9ac9736d08838">llvm::MCRegisterInfo::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### getSubtargetInfo() {#a38cda99e294483fa025f4eb57f6544b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo * llvm::LLVMDisasmContext::getSubtargetInfo ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#ad7331753737602bb545def2c960c209d">emitLatency</a> and <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a>.</p>

</div>
</div>

### getSymbolLookupCallback() {#a3859e9d1bd00cdaf607db13a873320fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMSymbolLookupCallback llvm::LLVMDisasmContext::getSymbolLookupCallback ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### getTagType() {#ae29f174e4b89c59433ed98d8fc8025de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::LLVMDisasmContext::getTagType ()</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### getTarget() {#aebf9ddd5b499d9fe5c3a5e8374ec6a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Target * llvm::LLVMDisasmContext::getTarget ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### getTripleName() {#af6472ad3902ecbb48480e46eb60217b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::LLVMDisasmContext::getTripleName ()</td>
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



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

### setCPU() {#a043768d184e14c6c14e4db9389e6218a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LLVMDisasmContext::setCPU (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CPU)</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga0ed319f9f853493c0b38e551ec2adfc5">LLVMCreateDisasmCPUFeatures</a>.</p>

</div>
</div>

### setIP() {#a36eaceae57946055f0f9439da556700c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::LLVMDisasmContext::setIP (<a href="/web-llvm/docs/api/classes/llvm/mcinstprinter">MCInstPrinter</a> * NewIP)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CommentsToEmit {#aca3253766aa266590e688a23f97ac612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;128&gt; llvm::LLVMDisasmContext::CommentsToEmit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#a0e50dc982f01eab3eeb5eef624e25f03">emitComments</a> and <a href="#af3d393ecff08342f307bd92a72841183">LLVMDisasmContext</a>.</p>

</div>
</div>

### CommentStream {#a26ae4b99e4c6cd8620f8603354572a33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_svector_ostream llvm::LLVMDisasmContext::CommentStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#ad7331753737602bb545def2c960c209d">emitLatency</a>, <a href="#af3d393ecff08342f307bd92a72841183">LLVMDisasmContext</a> and <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#gad1cbbd5aa7b51f04687926e8f9e4aebb">LLVMSetDisasmOptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CPU {#adb267f50210b822505f00c2452487c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LLVMDisasmContext::CPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### Ctx {#a020b21a838d253a0b2f26bdcc85f6e98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const llvm::MCContext&gt; llvm::LLVMDisasmContext::Ctx</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### DisAsm {#a8b83690cccf691a481bcea4f23609d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const llvm::MCDisassembler&gt; llvm::LLVMDisasmContext::DisAsm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### DisInfo {#a3b728491e08f589b11a9c3a47721b711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::LLVMDisasmContext::DisInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### GetOpInfo {#a3f59f9332ba0d7876e870d0adb05a7cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOpInfoCallback llvm::LLVMDisasmContext::GetOpInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### IP {#a747756eb6963c35db27def2b98a18a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;llvm::MCInstPrinter&gt; llvm::LLVMDisasmContext::IP</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### MAI {#a56707caa5c09ae8aa9b476da844838b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const llvm::MCAsmInfo&gt; llvm::LLVMDisasmContext::MAI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### MII {#ab5f2049dbb681d5da0217492a9787d6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const llvm::MCInstrInfo&gt; llvm::LLVMDisasmContext::MII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### MRI {#a4b0b972185529c7639653741b6ddc63c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const llvm::MCRegisterInfo&gt; llvm::LLVMDisasmContext::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### MSI {#a56767ece5cc3c9329b520fa302c32ba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const llvm::MCSubtargetInfo&gt; llvm::LLVMDisasmContext::MSI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### Options {#ada0b1e977f8b32ea7164d0f858aceeb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::LLVMDisasmContext::Options</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### SymbolLookUp {#ad7b4f72a8a33ca89b1173a06e783e7fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMSymbolLookupCallback llvm::LLVMDisasmContext::SymbolLookUp</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### TagType {#afa12e5253daf3805ce6fe38a195c2281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::LLVMDisasmContext::TagType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### TheTarget {#afd0cdc91dbe6ef8fe11323a982b0e4eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Target* llvm::LLVMDisasmContext::TheTarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

### TripleName {#ae88fa03dea71c8782cac1ca1af7c8c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::LLVMDisasmContext::TripleName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-h">Disassembler.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
