
include_directories(
  model
)

add_executable(NNCNNTriReluUniBiTriGramLabeler NNCNNTriReluUniBiTriGramLabeler.cpp)
target_link_libraries(NNCNNTriReluUniBiTriGramLabeler ${LIBS})
