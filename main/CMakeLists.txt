set(COMPONENT_SRCS "\
  main.c\
  ../components/microvium/dist-c/microvium.c\
")

set(COMPONENT_ADD_INCLUDEDIRS "\
  .\
  ../include\
  ../components/microvium/dist-c/\
  ../components/microvium/native-vm-bindings\
")


register_component()
