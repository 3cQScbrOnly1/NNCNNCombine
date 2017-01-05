
include_directories(
  model
)

add_executable(NNCNNTriTanhUniGramLabeler NNCNNTriTanhUniGramLabeler.cpp)
target_link_libraries(NNCNNTriTanhUniGramLabeler ${LIBS})
