include_directories("${MAINFOLDER}/src/quantsystem/orderbook")

ADD_EXECUTABLE(order_book 
BookConstructor.cpp  main.cpp  Message.cpp  OrderBook.cpp  Order.cpp  OrderPool.cpp  Reader.cpp  utility.cpp  Writer.cpp)

#TARGET_LINK_LIBRARIES(order_book)