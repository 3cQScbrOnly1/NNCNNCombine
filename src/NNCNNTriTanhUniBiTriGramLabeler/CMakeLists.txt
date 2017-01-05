
include_directories(
  model
)

add_executable(NNCNNTriTanhUniBiTriGramLabeler NNCNNTriTanhUniBiTriGramLabeler.cpp)
target_link_libraries(NNCNNTriTanhUniBiTriGramLabeler ${LIBS})
