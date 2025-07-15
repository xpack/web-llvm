---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarf-linker/parallel/compileunit/dieinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DIEInfo` Struct Reference

<p>Information gathered about source DIEs. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::dwarf_linker::parallel::CompileUnit::DIEInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinker/Parallel/DWARFLinkerCompileUnit.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c12cfb18584ff4ba43a40ff780488c8">DIEInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbc8310db2485b04f94845473fce2db3">DIEInfo</a> (const DIEInfo &amp;Other)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/compileunit/dieinfo">DIEInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab17d81e80f6ed99860e78c928a2baa54">operator=</a> (const DIEInfo &amp;Other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549">DieOutputPlacement</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa410d61287a4ff37d4d8c3bf5e3879a1">getPlacement</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29d892081e6d10f999dcf96f7a1b4729">setPlacement</a> (DieOutputPlacement Placement)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets Placement kind for the corresponding die. <a href="#a29d892081e6d10f999dcf96f7a1b4729">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6d1a1a7b9363619824d233cee425a74">unsetPlacement</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unsets Placement kind for the corresponding die. <a href="#aa6d1a1a7b9363619824d233cee425a74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafd1866158f770ae45b007771e01ab0c">setPlacementIfUnset</a> (DieOutputPlacement Placement)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets Placement kind for the corresponding die. <a href="#aafd1866158f770ae45b007771e01ab0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1174d0ac0a156a3107668426402df15">unsetFlagsWhichSetDuringLiveAnalysis</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> is a part of the linked output. <a href="#ac1174d0ac0a156a3107668426402df15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae021f90685d05a053bb091bd648d9896">eraseData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase all flags. <a href="#ae021f90685d05a053bb091bd648d9896">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bb4b5ce7e0731e88c8a45d8de5db37b">dump</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb9f942a186fdee7f8665c5d3363ee3">needToPlaceInTypeTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e5611206ac6f6a6c6fc7f570a368c4">needToKeepInPlainDwarf</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; uint16_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31a42cf476def7a056ff4226eb9e6872">Flags</a> = {0}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Data member keeping various flags. <a href="#a31a42cf476def7a056ff4226eb9e6872">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Information gathered about source DIEs.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DIEInfo() {#a3c12cfb18584ff4ba43a40ff780488c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::DIEInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Referenced by <a href="#adbc8310db2485b04f94845473fce2db3">DIEInfo</a> and <a href="#ab17d81e80f6ed99860e78c928a2baa54">operator=</a>.</p>

</div>
</div>

### DIEInfo() {#adbc8310db2485b04f94845473fce2db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::DIEInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/compileunit/dieinfo">DIEInfo</a> &amp; Other)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="#a3c12cfb18584ff4ba43a40ff780488c8">DIEInfo</a>, <a href="#a31a42cf476def7a056ff4226eb9e6872">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ab17d81e80f6ed99860e78c928a2baa54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIEInfo &amp; llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/compileunit/dieinfo">DIEInfo</a> &amp; Other)</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="#a3c12cfb18584ff4ba43a40ff780488c8">DIEInfo</a>, <a href="#a31a42cf476def7a056ff4226eb9e6872">Flags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a0bb4b5ce7e0731e88c8a45d8de5db37b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::CompileUnit::DIEInfo::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af3a2b03b115846b5339469ce1e603976a02bce93bff905887ad2233110bf9c49e">llvm::Keep</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

### eraseData() {#ae021f90685d05a053bb091bd648d9896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::eraseData ()</td>
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

<p>Erase all flags.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="#a31a42cf476def7a056ff4226eb9e6872">Flags</a>.</p>

</div>
</div>

### getPlacement() {#aa410d61287a4ff37d4d8c3bf5e3879a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DieOutputPlacement llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::getPlacement ()</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Placement kind for the corresponding die.</p></dd>
</dl>


<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="#a31a42cf476def7a056ff4226eb9e6872">Flags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/classic/compileunit/dieinfo/#a6bc3abd441871fd4bd6affec72c71249">llvm::dwarf_linker::classic::CompileUnit::DIEInfo::dump</a>, <a href="#a29e5611206ac6f6a6c6fc7f570a368c4">needToKeepInPlainDwarf</a> and <a href="#a4fb9f942a186fdee7f8665c5d3363ee3">needToPlaceInTypeTable</a>.</p>

</div>
</div>

### needToKeepInPlainDwarf() {#a29e5611206ac6f6a6c6fc7f570a368c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::needToKeepInPlainDwarf ()</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549a5d59de2bbf0cc536bfb1d56049d26d68">llvm::dwarf_linker::parallel::CompileUnit::Both</a>, <a href="#aa410d61287a4ff37d4d8c3bf5e3879a1">getPlacement</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549aecc6950928c245961306947efbae3db7">llvm::dwarf_linker::parallel::CompileUnit::PlainDwarf</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a066fd5533813e5df6d52cb59fc8afd4e">llvm::dwarf_linker::parallel::DependencyTracker::verifyKeepChain</a>.</p>

</div>
</div>

### needToPlaceInTypeTable() {#a4fb9f942a186fdee7f8665c5d3363ee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::needToPlaceInTypeTable ()</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549a5d59de2bbf0cc536bfb1d56049d26d68">llvm::dwarf_linker::parallel::CompileUnit::Both</a>, <a href="#aa410d61287a4ff37d4d8c3bf5e3879a1">getPlacement</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549ae4e2eb6616a94c80f428778e4b1bb3bf">llvm::dwarf_linker::parallel::CompileUnit::TypeTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a62035c942faa72252459166166847bff">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneDieRefAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#af28b850047c908b6602c0783a0c4688f">llvm::dwarf_linker::parallel::DependencyTracker::updateDependenciesCompleteness</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a066fd5533813e5df6d52cb59fc8afd4e">llvm::dwarf_linker::parallel::DependencyTracker::verifyKeepChain</a>.</p>

</div>
</div>

### setPlacement() {#a29d892081e6d10f999dcf96f7a1b4729}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::setPlacement (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549">DieOutputPlacement</a> Placement)</td>
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

<p>Sets Placement kind for the corresponding die.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="#a31a42cf476def7a056ff4226eb9e6872">Flags</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a10783a549bfb83fd142ae4e645a283ef">Placement</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#ac29d7dd5c7ba980d5a368339b4fc03af">llvm::dwarf_linker::parallel::DependencyTracker::resolveDependenciesAndMarkLiveness</a>.</p>

</div>
</div>

### setPlacementIfUnset() {#aafd1866158f770ae45b007771e01ab0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::setPlacementIfUnset (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549">DieOutputPlacement</a> Placement)</td>
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

<p>Sets Placement kind for the corresponding die.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="#a31a42cf476def7a056ff4226eb9e6872">Flags</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5270021419d157f502aba678e1ee8549ae9311639cca717631f1dc39e18b1f62d">llvm::dwarf_linker::parallel::CompileUnit::NotSet</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a10783a549bfb83fd142ae4e645a283ef">Placement</a>.</p>

</div>
</div>

### unsetFlagsWhichSetDuringLiveAnalysis() {#ac1174d0ac0a156a3107668426402df15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::unsetFlagsWhichSetDuringLiveAnalysis ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> is a part of the linked output.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> has children which are part of the linked output. <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> has children which are part of the type table. <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> is in module scope. <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> is in function scope. <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> is in anonymous namespace scope. <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> is available for ODR type deduplication. Track liveness for the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. Track liveness for the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>References <a href="#a31a42cf476def7a056ff4226eb9e6872">Flags</a> and <a href="#ac1174d0ac0a156a3107668426402df15">unsetFlagsWhichSetDuringLiveAnalysis</a>.</p>


<p>Referenced by <a href="#ac1174d0ac0a156a3107668426402df15">unsetFlagsWhichSetDuringLiveAnalysis</a>.</p>

</div>
</div>

### unsetPlacement() {#aa6d1a1a7b9363619824d233cee425a74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::unsetPlacement ()</td>
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

<p>Unsets Placement kind for the corresponding die.</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Reference <a href="#a31a42cf476def7a056ff4226eb9e6872">Flags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Flags {#a31a42cf476def7a056ff4226eb9e6872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;uint16_t&gt; llvm::dwarf_linker::parallel::CompileUnit::DIEInfo::Flags = {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Data member keeping various flags.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a>.</p>


<p>Referenced by <a href="#adbc8310db2485b04f94845473fce2db3">DIEInfo</a>, <a href="#ae021f90685d05a053bb091bd648d9896">eraseData</a>, <a href="#aa410d61287a4ff37d4d8c3bf5e3879a1">getPlacement</a>, <a href="#ab17d81e80f6ed99860e78c928a2baa54">operator=</a>, <a href="#a29d892081e6d10f999dcf96f7a1b4729">setPlacement</a>, <a href="#aafd1866158f770ae45b007771e01ab0c">setPlacementIfUnset</a>, <a href="#ac1174d0ac0a156a3107668426402df15">unsetFlagsWhichSetDuringLiveAnalysis</a> and <a href="#aa6d1a1a7b9363619824d233cee425a74">unsetPlacement</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/classic/dwarflinkercompileunit-cpp">DWARFLinkerCompileUnit.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkercompileunit-h">DWARFLinkerCompileUnit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
