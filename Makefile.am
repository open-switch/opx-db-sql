ACLOCAL_AMFLAGS=-I m4
SUBDIRS = inc

#The db sql library
lib_LTLIBRARIES = libopx_db_sql.la

libopx_db_sql_la_SOURCES = src/db_sql_ops.c

libopx_db_sql_la_LDFLAGS = -lrt -version-info 1:1:0
libopx_db_sql_la_CPPFLAGS = -I$(top_srcdir)/inc/opx -I$(top_srcdir)/opx  -I$(includedir)/opx 
libopx_db_sql_la_LIBADD = -lsqlite3  -lpthread -lopx_common -lopx_logging

