
include_directories(
  model
)

add_executable(NNCNNTriReluUniBiGramLabeler NNCNNTriReluUniBiGramLabeler.cpp)
target_link_libraries(NNCNNTriReluUniBiGramLabeler ${LIBS})
