---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/msgpack/fixmin
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `FixMin` Namespace

<p>The minimum value or size encodable in "Fix" variants of formats. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::msgpack::FixMin { ... }
</div>

## Description {#details}

<p>The minimum value or size encodable in "Fix" variants of formats.</p>


<p>The only object for which a minimum makes sense is a negative FixNum.</p>


<p>Negative FixNum objects encode their signed integer value in one byte, but they must have the pattern "111" as their three most significant bits. This means all values are negative, and the smallest representable value is 0b11100000.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
