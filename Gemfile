source "https://rubygems.org"

gem "metanorma-cli"

# Testbed: pull unreleased fixes from main until the next release lands.
# metanorma-ietf main (3.7.6): RfcConvert#document_preprocess now passes
#   `conv:` to Metanorma::Requirements, fixing `init_i18n for nil` against
#   mn-requirements 0.5.11 (released 3.7.5 crashes before .rfc.xml).
# metanorma-standoc main: mathml_sanitise strips pretty-print whitespace,
#   fixing the fatal "Invalid MathML" abort on compound script expressions.
gem "metanorma-ietf", git: "https://github.com/metanorma/metanorma-ietf",
                      branch: "main"
gem "metanorma-standoc", git: "https://github.com/metanorma/metanorma-standoc",
                         branch: "main"
