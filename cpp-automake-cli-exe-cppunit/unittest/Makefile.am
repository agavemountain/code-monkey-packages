# Rules for the test code (use `make check` to execute)
TESTS = hellotest
check_PROGRAMS = $(TESTS)

AM_CPPFLAGS = -I$(top_builddir)/include -I$(top_srcdir)/include

hellotest_SOURCES = cppunit-test-main.cpp
hellotest_CXXFLAGS = $(CPPUNIT_CFLAGS)
hellotest_LDFLAGS = $(CPPUNIT_LIBS) -ldl

