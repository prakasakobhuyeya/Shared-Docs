# prakasakobhuyeya vision
*The REST API is one of the primary access methods, allowing read-only apps to be created.

_Note: Authorization & Session information is NOT included by this spec, 
and can simply be appended at the end of the URL as need by servers._
*

## Basic Pattern
{site}/{tool}/{sources}/{controls}/{inputEncoding}/{outputs}/{outputEncoding}/{inputString}

{site}/shloka-parser/svarna,mw/parse-2d-table-with-definitions/devanagari,phrase/JSON,devanagari/दोषधातुमला-मूलं-सदा-देहस्य--
{site}/dictionary/svarna,mw,amara/lookup/slp1,word/JSON,iast/pAda

## Tools
{site}/{tool}/{sources}/{controls}/{inputEncoding}/{outputs}/{outputEncoding}/{inputString}
Where tool is one of: 
1. dictionary
2. shloka-parser
3. shloka-retriever
4. shloka-commentary-retriever
5. shloka-search
6. phrase-search (slow!)
7. pada-generator
