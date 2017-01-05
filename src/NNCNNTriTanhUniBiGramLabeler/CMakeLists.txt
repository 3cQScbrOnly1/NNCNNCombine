
include_directories(
  model
)

add_executable(NNCNNTriTanhUniBiGramLabeler NNCNNTriTanhUniBiGramLabeler.cpp)
target_link_libraries(NNCNNTriTanhUniBiGramLabeler ${LIBS})
