idf_component_register(SRCS "../../../../engine/src/nd_cact.c"
                            "../../../../engine/src/nd_grammar.c"
                            "../../../../engine/src/nd_model.c"
                            "../../../../engine/src/nd_quant.c"
                            "../../../../engine/src/nd_sample.c"
                            "../../../../engine/src/nd_tokenizer.c"
                       INCLUDE_DIRS "../../../../engine/include")
# target_compile_definitions(${COMPONENT_LIB} PUBLIC ND_PROFILE=1)
