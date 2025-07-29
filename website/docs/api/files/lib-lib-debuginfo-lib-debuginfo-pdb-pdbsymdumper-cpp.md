---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymdumper-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `PDBSymDumper.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/pdbsymdumper-h">llvm/DebugInfo/PDB/PDBSymDumper.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
</div>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedfe929c2d67379c9be657e3a18e18af">PDB_SYMDUMP_UNREACHABLE</a>(Type)&nbsp;&nbsp;&nbsp;...</td>
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

## Macro Definitions

### PDB\_SYMDUMP\_UNREACHABLE {#aedfe929c2d67379c9be657e3a18e18af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PDB_SYMDUMP_UNREACHABLE(Type)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (RequireImpl)                                                             \
    <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>("Attempt to dump " #Type " with no dump implementation");
</div>
</dd>
</dl>

<p>Definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/pdbsymdumper-cpp">PDBSymDumper.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a0a9c807b3e63885f9d510ba25ecfc6ce">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#ad4e04b750d9f74f849f0a81a116bdef5">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a3c5438b714381880d10a1218d9d335d4">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a1b9437cce238d481880b045f5d184203">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#aca6cba3982ac3d92706bd37f1bd57fe4">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a0481e32c67b4db2fe190607c787ff95c">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a31f5cab509047d2d1c7cc7a040d8aa9d">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a988097df683c32dbf94bcddf7ed3ec73">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#ad04fcdbb9c38e19fc1a30df9f29f9bf0">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#ad245ad3ac70b3e8e79a5c94cc4670f3c">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a4e57f9a4715faeca110c53206e64b07c">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a7bbf2bf407698fabe4543a32be963eeb">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#ab87a1a162a47b25cda466c58a0483150">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#aa448c8d14ee76bd39bfedab2bb6974bd">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a1dd29673647e4b8396ea78504d86beca">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a7a59f299bc2185e6fd457a5ef1a888a9">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a2e9b68c0b89a5766faa93807200d6240">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a51ff03d120cacef3a9d56597bb405a0b">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#ad524c88b554725d2824b19ba7521e488">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a90f8bf2d442e1ae5f5cd41848b38df41">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a5e6523908ae1d85a9f22aed590b49fb5">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a80a44a03bdb52eeaa133d179269a0a07">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#aea837fcb759e01e974164083235a686d">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#abde28cf1e454e6a2e10d1356b814b929">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#abcd22131e36cbd8d4b5ac2faca4a43cc">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a1d9007ab119a617d19e7da3c7b7cc0b4">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a80545a194857afbe1cc3b5a89f8172ab">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a945d8890250db203fb895d1f197edef4">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a987be404eb41f2337467ca13024e8346">llvm::pdb::PDBSymDumper::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a42f094c09c3f1683b6958e9c82f70dc6">llvm::pdb::PDBSymDumper::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymdumper/#a48c21702cb690ff82d4bd7d5371fd062">llvm::pdb::PDBSymDumper::dump</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
