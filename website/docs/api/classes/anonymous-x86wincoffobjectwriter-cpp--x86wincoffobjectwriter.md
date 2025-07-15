---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86wincoffobjectwriter-cpp-/x86wincoffobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86WinCOFFObjectWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{X86WinCOFFObjectWriter.cpp}::X86WinCOFFObjectWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcwincoffobjecttargetwriter">MCWinCOFFObjectTargetWriter</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c1e5ad0045b6db17a3ec6dd4526aa10">X86WinCOFFObjectWriter</a> (bool Is64Bit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0003f12de600b11fab37ffb75678c0b8">~X86WinCOFFObjectWriter</a> () override=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0243074481f98b09727ac1f90c1bd7b1">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsCrossSection, const MCAsmBackend &amp;MAB) const override</td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincoffobjectwriter-cpp">X86WinCOFFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86WinCOFFObjectWriter() {#a0c1e5ad0045b6db17a3ec6dd4526aa10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86WinCOFFObjectWriter::X86WinCOFFObjectWriter (bool Is64Bit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincoffobjectwriter-cpp">X86WinCOFFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcwincoffobjecttargetwriter/#a1a0a17e6c398aabca7cb280e753ca9de">llvm::MCWinCOFFObjectTargetWriter::MCWinCOFFObjectTargetWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~X86WinCOFFObjectWriter() {#a0003f12de600b11fab37ffb75678c0b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86WinCOFFObjectWriter.cpp}::X86WinCOFFObjectWriter::~X86WinCOFFObjectWriter ()</td>
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



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincoffobjectwriter-cpp">X86WinCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a> and <a href="#a0243074481f98b09727ac1f90c1bd7b1">getRelocType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRelocType() {#a0243074481f98b09727ac1f90c1bd7b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86WinCOFFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsCrossSection, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcasmbackend">MCAsmBackend</a> &amp; MAB)</td>
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



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincoffobjectwriter-cpp">X86WinCOFFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d3d3a355228d2f64fa312abbd7abfbf">llvm::FixupKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a0f7a8485c2c761bc5e870fe2b6466372">llvm::FK_PCRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a128346d352fde2e704c07867f4d82eef">llvm::FK_SecRel_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a8b2acba82b6d0830ab47d67eb8f1ccf0">llvm::FK_SecRel_4</a>, <a href="/web-llvm/docs/api/classes/llvm/mcwincoffobjecttargetwriter/#ab177b1e7fe9db24b4218cdc77a81a4b9">llvm::MCWinCOFFObjectTargetWriter::getMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8a57211898d4494ccede1f9e90b92ebad4">llvm::COFF::IMAGE_FILE_MACHINE_AMD64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a38731f9b23370e15ad002c2a712d89a8ab9b603eafcb824ebeb03f246cff0b4d4">llvm::COFF::IMAGE_FILE_MACHINE_I386</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a7d8b48e10ac507c952d8d53a1ed68125a74ff32507ab7d0274cb957664ffef605">llvm::COFF::IMAGE_REL_AMD64_ADDR32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a7d8b48e10ac507c952d8d53a1ed68125a69bb08ed3be752cf59e3f3c920551467">llvm::COFF::IMAGE_REL_AMD64_ADDR32NB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a7d8b48e10ac507c952d8d53a1ed68125a3519acbba55d10d0496e430296daa1fa">llvm::COFF::IMAGE_REL_AMD64_ADDR64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a7d8b48e10ac507c952d8d53a1ed68125a1376dddaf4ade08fe5429571a06c6249">llvm::COFF::IMAGE_REL_AMD64_REL32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a7d8b48e10ac507c952d8d53a1ed68125ae30c886f401334cad8d2449d448fd60d">llvm::COFF::IMAGE_REL_AMD64_SECREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#a7d8b48e10ac507c952d8d53a1ed68125a8f9e666d5d3e545df5cb40aa5a8fd08d">llvm::COFF::IMAGE_REL_AMD64_SECTION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#adb84e9917e2d3804c02e45f01918cc2da9fa52f0b329c0ef93995df4e6a481674">llvm::COFF::IMAGE_REL_I386_DIR32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#adb84e9917e2d3804c02e45f01918cc2daeba9eeaecc6cf04e02e2f0b65d0304ce">llvm::COFF::IMAGE_REL_I386_DIR32NB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#adb84e9917e2d3804c02e45f01918cc2da32627d83f2285f6f55acdf638a21284d">llvm::COFF::IMAGE_REL_I386_REL32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#adb84e9917e2d3804c02e45f01918cc2da92e53639f295d8c325c5d8611e9ccb46">llvm::COFF::IMAGE_REL_I386_SECREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coff/#adb84e9917e2d3804c02e45f01918cc2da1e566304d1862ff86ae112d102a63a43">llvm::COFF::IMAGE_REL_I386_SECTION</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca3b2a5a68543379e2c0ecada70a114244">llvm::X86::reloc_branch_4byte_pcrel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcaea3ac30c46fc4086e0fac8473ece1f8b">llvm::X86::reloc_riprel_4byte</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcacd0ed684ad2d4c067ca938d45567540c">llvm::X86::reloc_riprel_4byte_movq_load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca303862a22911ad0a16f5f88c89d7c105">llvm::X86::reloc_riprel_4byte_movq_load_rex2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca711b77689359fcf4cb49f96b5571d5c0">llvm::X86::reloc_riprel_4byte_relax</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca7b4bcca3a40ad945a73f1c1d199c6362">llvm::X86::reloc_riprel_4byte_relax_evex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca962ed593088a527512dad825d971922e">llvm::X86::reloc_riprel_4byte_relax_rex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fcaea71f97aa32a2a3fabf01372d4079a5c">llvm::X86::reloc_riprel_4byte_relax_rex2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca8b029ea6e687fd2d4caf13cbbe2cde08">llvm::X86::reloc_signed_4byte</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#af437e70f011e7e19b5614a0b8f9531fca372de3ecc0967f0c818089f93138a0de">llvm::X86::reloc_signed_4byte_relax</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a61907d1fede3c9e9713b6b3a29d35b01">llvm::MCSymbolRefExpr::VK_COFF_IMGREL32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a01bc6396c4d841a7ea268c3cbf62d3b3">llvm::MCSymbolRefExpr::VK_None</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a0cca43f5b196466926fb823727bd8902">llvm::MCSymbolRefExpr::VK_SECREL</a>.</p>


<p>Referenced by <a href="#a0003f12de600b11fab37ffb75678c0b8">~X86WinCOFFObjectWriter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86wincoffobjectwriter-cpp">X86WinCOFFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
