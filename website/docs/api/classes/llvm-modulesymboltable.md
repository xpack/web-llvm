---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/modulesymboltable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ModuleSymbolTable` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ModuleSymbolTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">llvm/Object/ModuleSymbolTable.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39c72fdc2ed1ff4829689fb72d13f426">AsmSymbol</a> = std::pair&lt; std::string, uint32_t &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee10b9e113136c4ba54121bc66751c5">Symbol</a> = <a href="/web-llvm/docs/api/classes/llvm/pointerunion">PointerUnion</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *, <a href="#a39c72fdc2ed1ff4829689fb72d13f426">AsmSymbol</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="#a8ee10b9e113136c4ba54121bc66751c5">Symbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3d925fc38ac06d622cfb41f581c1e02">symbols</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1793bf2002e7eb8d7199b58aa5252808">addModule</a> (Module *M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a736649b9c166082173376116d527d172">printSymbolName</a> (raw_ostream &amp;OS, Symbol S) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c6d3dc79159798bdccacf3e0ee99468">getSymbolFlags</a> (Symbol S) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f4f0dbdf8fdfc50a8a3cd0b09942f5">FirstMod</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="#a39c72fdc2ed1ff4829689fb72d13f426">AsmSymbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c8b67ae2177139acfe3d44b19124ad6">AsmSymbols</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="#a8ee10b9e113136c4ba54121bc66751c5">Symbol</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cd9f44561daf3e0a64ed3de94989ee9">SymTab</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mangler">Mangler</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8c35894f4a14681b4fbc260becc78c">Mang</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeaa3f8d791f06d24dbe1ed910c27a9a">CollectAsmSymbols</a> (const Module &amp;M, function_ref&lt; void(StringRef, object::BasicSymbolRef::Flags)&gt; AsmSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse inline ASM and collect the symbols that are defined or referenced in the current module. <a href="#afeaa3f8d791f06d24dbe1ed910c27a9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a260eabd30cac206a16723c8cd6e0c5c4">CollectAsmSymvers</a> (const Module &amp;M, function_ref&lt; void(StringRef, StringRef)&gt; AsmSymver)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse inline ASM and collect the symvers directives that are defined in the current module. <a href="#a260eabd30cac206a16723c8cd6e0c5c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### AsmSymbol {#a39c72fdc2ed1ff4829689fb72d13f426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ModuleSymbolTable::AsmSymbol =  std::pair&lt;std::string, uint32_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>.</p>

</div>
</div>

### Symbol {#a8ee10b9e113136c4ba54121bc66751c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ModuleSymbolTable::Symbol =  PointerUnion&lt;GlobalValue *, AsmSymbol *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addModule() {#a1793bf2002e7eb8d7199b58aa5252808}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSymbolTable::addModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/object/modulesymboltable-cpp">ModuleSymbolTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#afeaa3f8d791f06d24dbe1ed910c27a9a">CollectAsmSymbols</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a9e5d9d56a410f0bd58fa931731c9e644">anonymous{IRSymtab.cpp}::Builder::addModule</a>.</p>

</div>
</div>

### getSymbolFlags() {#a9c6d3dc79159798bdccacf3e0ee99468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t ModuleSymbolTable::getSymbolFlags (<a href="#a8ee10b9e113136c4ba54121bc66751c5">Symbol</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/object/modulesymboltable-cpp">ModuleSymbolTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a788ede5201dc9b44e419e9fd2fbb38bf">llvm::GlobalValue::getAliaseeObject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a917d4e0252fa1d20b2086b2e99e78e57">llvm::object::BasicSymbolRef::SF_Common</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431adb0e2612e20ba28b3b1fe8697f0b095a">llvm::object::BasicSymbolRef::SF_Const</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a2d0d252cebc6c9ccac230cb8625d8d59">llvm::object::BasicSymbolRef::SF_Executable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac0848bf2e216fe6f4664820d93ab7265">llvm::object::BasicSymbolRef::SF_FormatSpecific</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34">llvm::object::BasicSymbolRef::SF_Global</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a204140e5ce85b4dc444bf37cb0d8e402">llvm::object::BasicSymbolRef::SF_Hidden</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a9660b615b36c70668b966e987719d9d6">llvm::object::BasicSymbolRef::SF_Indirect</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1cfe0c449b3dd82ae0eaeff1da6f766">llvm::object::BasicSymbolRef::SF_None</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a> and <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a15ad3b408efc55e12e201e1cd1dfbc45">anonymous{IRSymtab.cpp}::Builder::addSymbol</a>.</p>

</div>
</div>

### printSymbolName() {#a736649b9c166082173376116d527d172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSymbolTable::printSymbolName (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="#a8ee10b9e113136c4ba54121bc66751c5">Symbol</a> S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>, definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/object/modulesymboltable-cpp">ModuleSymbolTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a15ad3b408efc55e12e201e1cd1dfbc45">anonymous{IRSymtab.cpp}::Builder::addSymbol</a>.</p>

</div>
</div>

### symbols() {#ab3d925fc38ac06d622cfb41f581c1e02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Symbol &gt; llvm::ModuleSymbolTable::symbols ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a9e5d9d56a410f0bd58fa931731c9e644">anonymous{IRSymtab.cpp}::Builder::addModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AsmSymbols {#a3c8b67ae2177139acfe3d44b19124ad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;AsmSymbol&gt; llvm::ModuleSymbolTable::AsmSymbols</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>.</p>

</div>
</div>

### FirstMod {#aa8f4f0dbdf8fdfc50a8a3cd0b09942f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module* llvm::ModuleSymbolTable::FirstMod = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>.</p>

</div>
</div>

### Mang {#a0f8c35894f4a14681b4fbc260becc78c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Mangler llvm::ModuleSymbolTable::Mang</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>.</p>

</div>
</div>

### SymTab {#a6cd9f44561daf3e0a64ed3de94989ee9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Symbol&gt; llvm::ModuleSymbolTable::SymTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### CollectAsmSymbols() {#afeaa3f8d791f06d24dbe1ed910c27a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSymbolTable::CollectAsmSymbols (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431">object::BasicSymbolRef::Flags</a>)&gt; AsmSymbol)</td>
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

<p>Parse inline ASM and collect the symbols that are defined or referenced in the current module.</p>


<p>For each found symbol, call <span class="doxyComputerOutput"><a href="#a39c72fdc2ed1ff4829689fb72d13f426">AsmSymbol</a></span> with the name of the symbol found and the associated flags.</p>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/object/modulesymboltable-cpp">ModuleSymbolTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#a30345c5991aa113e45ca828442920d79ae7df0ff533351ab7bad9352151008333">llvm::RecordStreamer::Defined</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#a30345c5991aa113e45ca828442920d79a8f29852e43dc39446fcdaaadb63a360f">llvm::RecordStreamer::DefinedGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#a30345c5991aa113e45ca828442920d79a65304bb6c2bf1507b761c39b494b8b64">llvm::RecordStreamer::DefinedWeak</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#ae36c2a9293b9a50a2870d02f93d7d202">llvm::RecordStreamer::flushSymverDirectives</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#a30345c5991aa113e45ca828442920d79a74d0c5a35544d5d655b9e8c1428e332c">llvm::RecordStreamer::Global</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/modulesymboltable-cpp/#af63cc4141d5da9ef88eb0ec4b2b3c959">initializeRecordStreamer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#a30345c5991aa113e45ca828442920d79ac5f137d9e66ccfef984def002584e42b">llvm::RecordStreamer::NeverSeen</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a2d0d252cebc6c9ccac230cb8625d8d59">llvm::object::BasicSymbolRef::SF_Executable</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431a1cc593ee22b60969ba0a3cb1e5e21b34">llvm::object::BasicSymbolRef::SF_Global</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ad1131f10939b205635a0dc81ca3c45d7">llvm::object::BasicSymbolRef::SF_Undefined</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a9004a106627deafd45a7c95ee497d431ac199a3dc25299a191397723e89fd303e">llvm::object::BasicSymbolRef::SF_Weak</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#a30345c5991aa113e45ca828442920d79a7bade7b61e6d1bf22b1355cdb603d78a">llvm::RecordStreamer::UndefinedWeak</a>, <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#a30345c5991aa113e45ca828442920d79a6a6ff7ed42d4c487edcfaaac5b29632c">llvm::RecordStreamer::Used</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a>.</p>


<p>Referenced by <a href="#a1793bf2002e7eb8d7199b58aa5252808">addModule</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a49170e37072dd286a1fcf76f2efec373">llvm::buildModuleSummaryIndex</a>.</p>

</div>
</div>

### CollectAsmSymvers() {#a260eabd30cac206a16723c8cd6e0c5c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleSymbolTable::CollectAsmSymvers (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)&gt; AsmSymver)</td>
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

<p>Parse inline ASM and collect the symvers directives that are defined in the current module.</p>


<p>For each found symbol, call <span class="doxyComputerOutput">AsmSymver</span> with the name of the symbol and its alias.</p>


<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/object/modulesymboltable-cpp">ModuleSymbolTable.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/modulesymboltable-cpp/#af63cc4141d5da9ef88eb0ec4b2b3c959">initializeRecordStreamer</a> and <a href="/web-llvm/docs/api/classes/llvm/recordstreamer/#a3945e54a1e7a69399bd13a229e58cb5b">llvm::RecordStreamer::symverAliases</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-irmover-cpp-/irlinker/#a29e247c718172acd518f8bb0255ff851">anonymous{IRMover.cpp}::IRLinker::run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/modulesymboltable-h">ModuleSymbolTable.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/modulesymboltable-cpp">ModuleSymbolTable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
