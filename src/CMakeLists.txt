
include_directories(
  basic
)



add_subdirectory(NNCNNMaxReluUniGramLabeler)
add_subdirectory(NNCNNMaxReluUniBiGramLabeler)
add_subdirectory(NNCNNMaxReluUniBiTriGramLabeler)

add_subdirectory(NNCNNTriReluUniGramLabeler)
add_subdirectory(NNCNNTriReluUniBiGramLabeler)
add_subdirectory(NNCNNTriReluUniBiTriGramLabeler)

add_subdirectory(NNCNNTriTanhUniGramLabeler)
add_subdirectory(NNCNNTriTanhUniBiGramLabeler)
add_subdirectory(NNCNNTriTanhUniBiTriGramLabeler)