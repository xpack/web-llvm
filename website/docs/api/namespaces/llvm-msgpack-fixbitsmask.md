---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/msgpack/fixbitsmask
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `FixBitsMask` Namespace

<p>Mask of bits used to identify "Fix" variants in MessagePack. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::msgpack::FixBitsMask { ... }
</div>

## Description {#details}

<p>Mask of bits used to identify "Fix" variants in MessagePack.</p>


<p>For example, FixStr objects encode their size in the five least significant bits of their first byte, which is identified by the bit pattern "101" in the three most significant bits. So FixBitsMask::String contains 0b11100000.</p>


<p>The corresponding bit pattern to mask for is found in <a href="/web-llvm/docs/api/namespaces/llvm/msgpack/fixbits">FixBits</a>.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
