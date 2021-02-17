# Font technical notes

[![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nd/4.0/)
 
This page offers an index of technical font documentation. This is mainly a way
to preserve legacy technical documentation for certain Adobe technologies. It is
meant to be used as a historical reference. There is no technical support
provided and no guarantee of future availability.

Please refer to the [licensing terms](LICENSE.md) for information about copying and redistribution.
 

_Note: For technical notes about Adobe® Acrobat® and Adobe PDF font topics, such as ToUnicode tables and Widths-only fonts, see [Advanced Acrobat/PDF technical documentation.](http://www.adobe.com/go/acrobatsdk_distiller)_

Documentation is available in the following areas:

## Specifications
 - [Adobe Font Metrics File Format Specification #5004](pdfs/5004.AFM_Spec.pdf)  (PDF, 238k) Version 4.1 10/9/97
 - [Adobe Type 1 Font Format](pdfs/T1_SPEC.pdf)  (PDF, 459k) Version 1.1 02/93
 - [Type 1 Font Format Supplement](pdfs/5015.Type1_Supp.pdf) #5015   (PDF, 225k) (supersedes #5047 and #5086) 5/15/94
 - [Glyph Bitmap Distribution Format](pdfs/5005.BDF_Spec.pdf) (BDF) Specification #5005  (PDF, 84k) Version 2.2 3/31/92
 - [Adobe Binary Screen Font Files Specification](pdfs/5006.ABF_Spec.pdf) #5006  (PDF, 41k) Version 2.0 3/31/92
 - [The Type 42 Font Format Specification](pdfs/5012.Type42_Spec.pdf) #5012  (PDF, 159k) 7/31/98
 - [Adobe Standard Cyrillic Font Specification](pdfs/5013.Cyrillic_Font_Spec.pdf) #5013  (PDF, 336k) 2/18/98
 - [Sonata® Font Design Specification](pdfs/5045.Sonata.pdf) #5045  (PDF, 40k) 3/31/92
 - [The Compact Font Format Specification](pdfs/5176.CFF.pdf) #5176  (PDF, 510k) 12/04/03
 - [The Type 2 Charstring Format](pdfs/5177.Type2.pdf) #5177  (PDF, 194k) 3/16/00
 - [CID-Keyed sfnt Font File Format for the Macintosh, version 2.0](pdfs/5180.sfnt.pdf) #5180  (PDF, 166k) 2/12/97
 - [PostScript Name Generation for Fonts Using OpenType Font Variations](pdfs/5902.AdobePSNameGeneration.pdf) #5902 (pdf, 158k) 9/14/2016
## General font issues
 - [Macintosh FOND Resources](pdfs/0091.Mac_Fond.pdf) #0091  (PDF, 106k) 3/31/92
 - [Supporting Downloadable PostScript® Language Fonts](pdfs/5040.Download_Fonts.pdf) #5040  (PDF, 87k) 3/31/92
 - [The StemSnap Hint Operator for Type 1 Font Programs](pdfs/5049.StemSnap.pdf) #5049  (PDF, 32k) 3/31/92
 - [Supporting Fonts in the PostScript Language Environment](pdfs/5075.Fonts_In_PS.pdf) #5075  (PDF, 125k) 3/31/92
 - [Font Naming Issues](pdfs/5088.FontNames.pdf) #5088   (PDF, 182k)
 - Glyph Naming #5098 12/17/98 Superseded - see [Adobe Glyph List Specification](https://github.com/adobe-type-tools/agl-specification)
 - [Adobe Font Name Reference Table](pdfs/5090.FontNameList.pdf) #5090  (PDF, 469k) 1/29/98
 - [Designing Multiple Master Typefaces](pdfs/5091.Design_MM_Fonts.pdf) #5091  (PDF, 3.3M) 9/7/95
 - [Bar Code Font Vendor List](pdfs/5096.BarCode_Vendors.pdf) #5096  (PDF, 27k) 9/25/98
 - [PostScript 3 Core Font Set Overview](pdfs/TN5609.PS3_Fonts.pdf) #5609  (PDF, 30k) 10/9/97
 - [Font Embedding Guidelines](pdfs/AcrobatDC_FontPolicies.pdf)  (PDF, 262k)

## CJK/CID-keyed fonts
 - [CMap Resources open source project on GitHub](https://github.com/adobe-type-tools/cmap-resources/)
 - [Adobe CJKV Character Collections and CMaps for CID-Keyed Fonts](pdfs/5094.CJK_CID.pdf) #5094 (deprecated and superseded by the [CMap Resources open source project on GitHub](https://github.com/adobe-type-tools/cmap-resources/))
 - [The Adobe-Japan1-6 Character Collection on GitHub](https://github.com/adobe-type-tools/Adobe-Japan1/)
 - [The Adobe-Japan2-0 Character Collection on GitHub](https://github.com/adobe-type-tools/Adobe-Japan1/) (deprecated and superseded by Adobe-Japan1-6)
 - [The Adobe-KR-9 Character Collection on GitHub](https://github.com/adobe-type-tools/Adobe-KR/)
 - [The Adobe-Korea1-2 Character Collection on GitHub](https://github.com/adobe-type-tools/Adobe-KR/) (deprecated and superseded by Adobe-KR-9)
 - [The Adobe-GB1-5 Character Collection on GitHub](https://github.com/adobe-type-tools/Adobe-GB1/)
 - [The Adobe-CNS1-7 Character Collection on GitHub](https://github.com/adobe-type-tools/Adobe-CNS1/)
 - [Adobe CMap and CID Font Files Specification](pdfs/5014.CIDFont_Spec.pdf) #5014  (PDF, 530k) 10/08/96 Version 1.0
 - [CID-Keyed Font Technology Overview](pdfs/5092.CID_Overview.pdf) #5092  (PDF, 2MB) 9/12/94
 - [Developing CMap Resources for CID-Keyed Fonts](pdfs/5099.CMapResources.pdf) #5099  (PDF, 275k) 3/15/12
 - [CID-Keyed Font Installation for PostScript File Systems](pdfs/5174.CID_PS.pdf) #5174  (PDF, 37k) 8/96
 - [CID-Keyed Font Installation for ATM Software](pdfs/5175.CID_ATM.pdf) #5175  (PDF, 61k) 3/18/98
 - [Building JIS2004-Savvy OpenType Fonts](misc/otf_jis2004.tar) (TAR, 3MB) 10/31/07
 - [OpenType-CID/CFF CJK Fonts: 'name' Table Tutorial](pdfs/5149.OTFname_Tutorial.pdf) #5149  (PDF, 156k) 08/05/2010
 - [AFDKO Version 2.0 Tutorial: mergeFonts, rotateFont & autohint](pdfs/5900.RFMFAH_Tutorial.pdf) #5900  (PDF, 760k) 02/21/2007
 - [Special-Purpose OpenType Japanese Font Tutorial: Kazuraki](pdfs/5901.Kazuraki_Tutorial.pdf) #5901  (PDF, 2.9M) 05/10/2010

<!-- ## PDF core font information
### Font Metrics for PDF Core 14 Fonts
 - Mac (SIT/HQX: 175k)
 - Win (ZIP: 125k)
 - Unix (TAR: 640k) -->
 
### CMaps for PDF CJK Fonts
These resources are now managed at the [GitHub project site Mapping Resources for PDF](https://github.com/adobe-type-tools/mapping-resources-pdf)
