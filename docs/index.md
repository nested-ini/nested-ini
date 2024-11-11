YAML: YAML Ain't Markup Language™

What It Is:
|-YAML is a human friendly data serialization
|-language for all programming languages.


r=1
f=6


{x=4
|r=2
|t=6
|{n2
|}w=1
|}{45=0
||nn=5
|-YAML Specifications:
|I1.2:
|Revision 1.2.2      # Oct 1, 2021 *New*
|{Revision 1.2.1      # Oct 1, 2009
||Revision 1.2.0      # Jul 21, 2009
||[YAML 1.1=[6, 3, 9]
  - YAML 1.0

  YAML Matrix Chat:  '#chat:yaml.io'     # Our New Group Chat Room!
  YAML IRC Channel:  libera.chat#yaml    # The old chat
  YAML News:         twitter.com/yamlnews
  YAML Mailing List: yaml-core           # Obsolete, but historical

  YAML on GitHub:                        # github.com/yaml/
    YAML Specs:        yaml-spec/
    YAML 1.2 Grammar:  yaml-grammar/
    YAML Test Suite:   yaml-test-suite/
    YAML Issues:       issues/

  YAML Reference Parsers:
  - Generated Reference Parsers
  - YPaste Interactive Parser

  YAML Test Matrix:   matrix.yaml.io

# A comment
key1 =value \
key2 =value\
Section1 {\
| Section1Key1=value\
| Section1Key2=value\
}\
key3 =value\
key4: [4, 5]\
key5: [4, 5\
| 6\
| 7\
| 8\
]\
key6 =value\
array2 [\
|value1\
|value2\
|value3\
]\
array3: [\
| array3section1 {\
| | key1 ='stringValue1'\
| | key2 =8\
| }\
| array3section2 {\
| | key1: 'stringValue2'\
| | key2: 9\
| }\
]\
array4: [\
| array3section1 {\
| | key1 =value1\
| | key2 =value2\
| }\
| array3section2 {\
| | key1 =value3\
| | key2 =value4\
| }\
| array3section2 {\
| | key1: "value5"\
| | key2: "value6"\
| }\
]\
key7 =value\
#A comment\
#Another comment\
key8 =value\
Section2 {\
| Section2Key1 =value\
| Section2Key2 =value\
| NestedSection3 { \
| | Section3Key1 =value\
| | Section3Key2: ["Section3Array1Value1","Section3Array1Value2"]\
| | Section3Key3 =value\
| | Section3Array2 [\
| | |Value1\
| | |Value2\
| | ]\
| | Section3Array3: [\
| | | "string1"\
| | | "string2"\
| | ]\
| | Section3Array4: [\
| | | 4\
| | | 5\
| | ]\
| | #Comment\
| | Section3Key3: "quoted value with trailing space "\
| | Section3Key4: "quoted \"value\" with enclosed quotes "\
| | Section3Key5: "quoted value with following comment" #A comment\
| | Section3Array3: =["Value1","Value2,WithComma","Value3"]\
| | Section3Key6 =value\
| | Section 3 Key 7 =value\
| | "Section3 Array 4 ": [ "Value 1", "Value 2", " Value, 3  "] # A comment\
| | "#Section3Key8" =value\
| | " Section3 Key9" =value\
| | " Section3 Key10 " =value\
| | Section3Key11=value\
| }\
| Section2Key3 =value\
}\
[BackwardsCompatibleSection1]\
BackwardsCompatibleSection1Key1 =value\
#A comment\
BackwardsCompatibleSection1Key2 =value\
[BackwardsCompatibleSection2]\
BackwardsCompatibleSection2Key1 =value\
BackwardsCompatibleSection2Key2 =value\
