---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mipselfobjectwriter-cpp-/mipselfobjectwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MipsELFObjectWriter` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{MipsELFObjectWriter.cpp}::MipsELFObjectWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter">MCELFObjectTargetWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40fe9503bf2ae9d73f83b6fd39e86bf3">MipsELFObjectWriter</a> (uint8_t OSABI, bool HasRelocationAddend, bool Is64)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d7113ad912833e0fadec1ec516e6854">~MipsELFObjectWriter</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ce0a61a47b9839aeb123796d9558fe5">getRelocType</a> (MCContext &amp;Ctx, const MCValue &amp;Target, const MCFixup &amp;Fixup, bool IsPCRel) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab03619c0adfc7e8318628a08e39a4354">needsRelocateWithSymbol</a> (const MCValue &amp;Val, const MCSymbol &amp;Sym, unsigned Type) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb8605e7260a242de5a25e2b3add57d">sortRelocs</a> (const MCAssembler &amp;Asm, std::vector&lt; ELFRelocationEntry &gt; &amp;Relocs) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sort relocation table entries by offset except where another order is required by the MIPS ABI. <a href="#a5fb8605e7260a242de5a25e2b3add57d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipselfobjectwriter-cpp">MipsELFObjectWriter.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MipsELFObjectWriter() {#a40fe9503bf2ae9d73f83b6fd39e86bf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsELFObjectWriter::MipsELFObjectWriter (uint8_t OSABI, bool HasRelocationAddend, bool Is64)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipselfobjectwriter-cpp">MipsELFObjectWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#ae6c6e76c9d8e0c912542fe4f8375e8ce">llvm::MCELFObjectTargetWriter::MCELFObjectTargetWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~MipsELFObjectWriter() {#a9d7113ad912833e0fadec1ec516e6854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MipsELFObjectWriter.cpp}::MipsELFObjectWriter::~MipsELFObjectWriter ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipselfobjectwriter-cpp">MipsELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="#a8ce0a61a47b9839aeb123796d9558fe5">getRelocType</a>, <a href="#ab03619c0adfc7e8318628a08e39a4354">needsRelocateWithSymbol</a> and <a href="#a5fb8605e7260a242de5a25e2b3add57d">sortRelocs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getRelocType() {#a8ce0a61a47b9839aeb123796d9558fe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned MipsELFObjectWriter::getRelocType (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Target, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcfixup">MCFixup</a> &amp; Fixup, bool IsPCRel)</td>
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



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipselfobjectwriter-cpp">MipsELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a1864d2003d3e30137067084e7f2e7898">llvm::FirstLiteralRelocationKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppctlsdynamiccall-cpp/#a4a235aedca5bbfc39934045b6cbf9c70">Fixup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ab5cc10bb4bb0b7c27777cc6d6336ed59">llvm::Mips::fixup_MICROMIPS_26_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a515f8848142f500447c79f9529d20ce2">llvm::Mips::fixup_MICROMIPS_CALL16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a51060e5d732b3b086038dc48f6ec3064">llvm::Mips::fixup_MICROMIPS_GOT16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a91fa94291c3d1c568f5e2a3bc10ce94f">llvm::Mips::fixup_MICROMIPS_GOT_DISP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a5d681ebbbf7ccd4ecdf20992c6dcfce9">llvm::Mips::fixup_MICROMIPS_GOT_OFST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a12dd04a6f3222eb075bb7bbb7a877686">llvm::Mips::fixup_MICROMIPS_GOT_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5addc624c0c979e72440d037f862ddc8e3">llvm::Mips::fixup_MICROMIPS_GOTTPREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5afcce79f2cce72a302edfee45aa7d4695">llvm::Mips::fixup_MICROMIPS_GPOFF_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a402c60b5bbab1160e7f4af8e4aa9c5a2">llvm::Mips::fixup_MICROMIPS_GPOFF_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a0c89de79bbc8e24d7c8729d3809c2d1d">llvm::Mips::fixup_MICROMIPS_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a2d430e04261f84befeb853879cc7c2d2">llvm::Mips::fixup_MICROMIPS_HIGHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a8a927ca45e8ad03129965f62997df971">llvm::Mips::fixup_MICROMIPS_HIGHEST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a649fdfac2fb6a04791d3a857fb7128c8">llvm::Mips::fixup_MICROMIPS_JALR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a899fa34e895181020ba099bae8a63cb2">llvm::Mips::fixup_MICROMIPS_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a8297df7f9768b5bb575ab89d20b30ff3">llvm::Mips::fixup_MICROMIPS_PC10_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a27da3393b1100b6a207b58257889bb54">llvm::Mips::fixup_MICROMIPS_PC16_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ace202b97f731ed38cb43988dc0699e40">llvm::Mips::fixup_MICROMIPS_PC18_S3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a4bd2e7fe8b6417bbdc61a96bf85a7224">llvm::Mips::fixup_MICROMIPS_PC19_S2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a39ec2eeed1cf046f572cb552fdb6ee2c">llvm::Mips::fixup_MICROMIPS_PC21_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ad6983cbf07a871ee8722596488c5f9cb">llvm::Mips::fixup_MICROMIPS_PC26_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a111b39a21b625c58137cd19b6c21308e">llvm::Mips::fixup_MICROMIPS_PC7_S1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5af3e67f73426baade7a01c5fc850dcc4a">llvm::Mips::fixup_MICROMIPS_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a6dcd134b90027fe09258de1b1acbe96f">llvm::Mips::fixup_MICROMIPS_TLS_DTPREL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ae8210f9b20325f1f373ba65d6c450834">llvm::Mips::fixup_MICROMIPS_TLS_DTPREL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a8490753dcd2baed10ed9499d0af3c910">llvm::Mips::fixup_MICROMIPS_TLS_GD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a53b0c2d53b83db98a608596e490aaceb">llvm::Mips::fixup_MICROMIPS_TLS_LDM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a331d4409d1e73993aec8660ec95c9927">llvm::Mips::fixup_MICROMIPS_TLS_TPREL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a005bba69839f43aea295fd4b9b04b468">llvm::Mips::fixup_MICROMIPS_TLS_TPREL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a493c08ff4c7daaa4e981326660778a1e">llvm::Mips::fixup_Mips_16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a462a8407acaf99e32df2276bf05112c9">llvm::Mips::fixup_Mips_26</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a59c8cc52b33f258a483bd3784980dc62">llvm::Mips::fixup_Mips_32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5abf0d35311026f6e95d49eab0a5aa189d">llvm::Mips::fixup_Mips_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5afa608906d37f0bf1c6367992f7a5068e">llvm::Mips::fixup_Mips_Branch_PCRel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a60c41d65c5b85e60845d0b5d9a5e2cad">llvm::Mips::fixup_Mips_CALL16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5aa1da7ac91e24d477f5f1456ea78867ef">llvm::Mips::fixup_Mips_CALL_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ab88a975afcf636548981251ccbe94308">llvm::Mips::fixup_Mips_CALL_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a0d08270c90f999bfc66bbac0d6bde120">llvm::Mips::fixup_Mips_DTPREL_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a9db2f1c56b099bee5e6e9b38ce74d44d">llvm::Mips::fixup_Mips_DTPREL_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5adb3fcfd2186ba8a2d087e1dd6aa81835">llvm::Mips::fixup_Mips_GOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a78e19d4edaf2ec86f2b8c0bad7e880db">llvm::Mips::fixup_Mips_GOT_DISP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a50816e1bb1c03b9f9e78fc51cda22812">llvm::Mips::fixup_Mips_GOT_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ae862242d904102cd8ae48b5e4617e5a0">llvm::Mips::fixup_Mips_GOT_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5aa9c59af1b95c717f8dbb3d368c137033">llvm::Mips::fixup_Mips_GOT_OFST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a6c25bcd83d096682c436213d1c449908">llvm::Mips::fixup_Mips_GOT_PAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a06928a5f5009c5df8048e4fbdac5f741">llvm::Mips::fixup_Mips_GOTTPREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a0944f7b895b814ebef8189a68a7cc18e">llvm::Mips::fixup_Mips_GPOFF_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a400c3fdeb8e0640fba7ceb6974eeb27d">llvm::Mips::fixup_Mips_GPOFF_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a40dd4035924bb1240b2f7ce4852e9393">llvm::Mips::fixup_Mips_GPREL16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a7f5070b2e64fb6be8f7cbb1f9d3720ec">llvm::Mips::fixup_Mips_HI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a12a25267be170c5dee7f9d696f7761d1">llvm::Mips::fixup_Mips_HIGHER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a5e99fde95ca7f0aa830dd98ef0db0b63">llvm::Mips::fixup_Mips_HIGHEST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5af4abf81a504e1e70891390ee5739bedb">llvm::Mips::fixup_Mips_JALR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a055845d89e962573651965ea13667b9b">llvm::Mips::fixup_Mips_LO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5afac721a28dd1bd12f2fb53010f24f45e">llvm::Mips::fixup_Mips_PC16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a597d2e0218cfdf8e2f9b39af616b7fe5">llvm::Mips::fixup_MIPS_PC18_S3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a8efbc2773d136010014a7b65a31a5605">llvm::Mips::fixup_MIPS_PC19_S2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a537b4ce4509c3dee196ef3f1a98ea3c0">llvm::Mips::fixup_MIPS_PC21_S2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5ab3bb518acbac617634c54e31403ad4b4">llvm::Mips::fixup_MIPS_PC26_S2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a5d7eb45487db4b915c25c2e12fb0c949">llvm::Mips::fixup_MIPS_PCHI16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5af534b6a07f3786fe4335086ec57851f0">llvm::Mips::fixup_MIPS_PCLO16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5adb7dca17c0aa3f4d51bf3fc512383c03">llvm::Mips::fixup_Mips_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a0c08af5309247c17e74b8a371bacc619">llvm::Mips::fixup_Mips_TLSGD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a336dcdb17a6f36a1a33945ef20d8cf2f">llvm::Mips::fixup_Mips_TLSLDM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a7ab045ce0b118beba9895b611eb42ff2">llvm::Mips::fixup_Mips_TPREL_HI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mips/#a38ecef98b92ae1203d8bdf85c5ecabb5a523f4b256997b5dcc3e870e4d89e5eef">llvm::Mips::fixup_Mips_TPREL_LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a4aee2a3e203379bbb0c9639d4ef31b6e">llvm::FK_Data_1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58afe607fbae154a24e4b463cf9fd5916f7">llvm::FK_Data_2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d58ab615cde98af13deb16dbc09f42d">llvm::FK_Data_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a3a9388f6478ca218e5d1996e4063c8fe">llvm::FK_Data_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5d9ad9ac8119a17f5b0d392039449416">llvm::FK_DTPRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a5f04203be5ebb87da1ce3b98527bbf7f">llvm::FK_DTPRel_8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ab39a952893aef8c5d618b3d6f7d6bc84">llvm::FK_GPRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58a845a63cbed041d42d8c3452991d629c4">llvm::FK_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58aa495238fa611ab89c4323df0081a0eb1">llvm::FK_TPRel_4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84cef097f15848752272d38769011f58ac91b4c1d01ae3cf9d55abd97a6654cb7">llvm::FK_TPRel_8</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#af1596fcc642359d1fbb138da1910b616">llvm::MCELFObjectTargetWriter::is64Bit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#a4a5f0265da0f4592af582f8a50dc14a4">llvm::MCELFObjectTargetWriter::setRTypes</a>.</p>


<p>Referenced by <a href="#a9d7113ad912833e0fadec1ec516e6854">~MipsELFObjectWriter</a>.</p>

</div>
</div>

### needsRelocateWithSymbol() {#ab03619c0adfc7e8318628a08e39a4354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsELFObjectWriter::needsRelocateWithSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcvalue">MCValue</a> &amp; Val, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> &amp; Sym, unsigned Type)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipselfobjectwriter-cpp">MipsELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#ab03619c0adfc7e8318628a08e39a4354">needsRelocateWithSymbol</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#a29b00051aee706fc5bbc604742a66f55a920f3ac6d4e61d6e58a5377436c31587">llvm::ELF::STO_MIPS_MICROMIPS</a>.</p>


<p>Referenced by <a href="#ab03619c0adfc7e8318628a08e39a4354">needsRelocateWithSymbol</a> and <a href="#a9d7113ad912833e0fadec1ec516e6854">~MipsELFObjectWriter</a>.</p>

</div>
</div>

### sortRelocs() {#a5fb8605e7260a242de5a25e2b3add57d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsELFObjectWriter::sortRelocs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcassembler">MCAssembler</a> &amp; Asm, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/elfrelocationentry">ELFRelocationEntry</a> &gt; &amp; Relocs)</td>
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

<p>Sort relocation table entries by offset except where another order is required by the MIPS ABI.</p>


<p>MIPS has a few relocations that have an AHL component in the expression used to evaluate them. This AHL component is an addend with the same number of bits as a symbol value but not all of our ABI's are able to supply a sufficiently sized addend in a single relocation.</p>


<p>The O32 ABI for example, uses REL relocations which store the addend in the section data. All the relocations with AHL components affect 16-bit fields so the addend for a single relocation is limited to 16-bit. This ABI resolves the limitation by linking relocations (e.g. R_MIPS_HI16 and R_MIPS_LO16) and distributing the addend between the linked relocations. The ABI mandates that such relocations must be next to each other in a particular order (e.g. R_MIPS_HI16 must be immediately followed by a matching R_MIPS_LO16) but the rule is less strict in practice.</p>


<p>The de facto standard is lenient in the following ways:</p>


<ul class="doxyList ">
<li>'Immediately following' does not refer to the next relocation entry but the next matching relocation.</li>
<li>There may be multiple high parts relocations for one low part relocation.</li>
<li>There may be multiple low part relocations for one high part relocation.</li>
<li>The AHL addend in each part does not have to be exactly equal as long as the difference does not affect the carry bit from bit 15 into 16. This is to allow, for example, the use of lo(foo) and lo(foo+4) when loading both halves of a long long.</li>
</ul>

<p>See <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipselfobjectwriter-cpp/#af29f17b9965a9f3bdcbbfafbf90b7f0c">getMatchingLoType()</a> for a description of which high part relocations match which low part relocations. One particular thing to note is that R_MIPS_GOT16 and similar only have AHL addends if they refer to local symbols.</p>


<p>It should also be noted that this function is not affected by whether the symbol was kept or rewritten into a section-relative equivalent. We always match using the expressions from the source.</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipselfobjectwriter-cpp">MipsELFObjectWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipselfobjectwriter-cpp/#af29f17b9965a9f3bdcbbfafbf90b7f0c">getMatchingLoType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcelfobjecttargetwriter/#a18895a2343e1b4a90083d13c8ddc90cd">llvm::MCELFObjectTargetWriter::hasRelocationAddend</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipselfobjectwriter-cpp/#a0b9745f3db31eb4f80f4acdaff1bbe76">isMatchingReloc</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>.</p>


<p>Referenced by <a href="#a9d7113ad912833e0fadec1ec516e6854">~MipsELFObjectWriter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipselfobjectwriter-cpp">MipsELFObjectWriter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
