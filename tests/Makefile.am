TESTS = test_policy.sh

check_PROGRAMS = test_policy test_sysfs

test_policy_SOURCES = test_policy.c 
test_policy_LDADD = ../src/libpmount-util.a
test_policy_CPPFLAGS = -I$(srcdir)/../src

# This is not a real test
test_sysfs_SOURCES = test_sysfs.c 
test_sysfs_LDADD = ../src/libpmount-util.a
test_sysfs_CPPFLAGS = -I$(srcdir)/../src
