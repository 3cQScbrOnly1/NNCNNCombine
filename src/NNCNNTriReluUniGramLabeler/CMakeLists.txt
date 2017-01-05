
include_directories(
  model
)

add_executable(NNCNNTriReluUniGramLabeler NNCNNTriReluUniGramLabeler.cpp)
target_link_libraries(NNCNNTriReluUniGramLabeler ${LIBS})
