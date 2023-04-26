main_0.c: In function â€˜print_stringâ€™:
main_0.c:11:1: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜{â€™ token
   11 | {
      | ^
main_0.c:24: error: expected â€˜{â€™ at end of input
   24 | }
      | 
In file included from main_0.c:3:
main.h:9:24: error: unused parameter â€˜sâ€™ [-Werror=unused-parameter]
    9 | int print_string(char *s)
      |                  ~~~~~~^
main_0.c:24: error: control reaches end of non-void function [-Werror=return-type]
   24 | }
      | 
cc1: all warnings being treated as errors
In file included from /usr/include/stdio.h:33,
                 from _printf.c:3:
/usr/lib/gcc/x86_64-linux-gnu/9/include/stddef.h: In function â€˜print_stringâ€™:
/usr/lib/gcc/x86_64-linux-gnu/9/include/stddef.h:209:23: error: storage class specified for parameter â€˜size_tâ€™
  209 | typedef __SIZE_TYPE__ size_t;
      |                       ^~~~~~
In file included from /usr/include/stdio.h:38,
                 from _printf.c:3:
/usr/include/x86_64-linux-gnu/bits/types.h:31:23: error: storage class specified for parameter â€˜__u_charâ€™
   31 | typedef unsigned char __u_char;
      |                       ^~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:32:28: error: storage class specified for parameter â€˜__u_shortâ€™
   32 | typedef unsigned short int __u_short;
      |                            ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:33:22: error: storage class specified for parameter â€˜__u_intâ€™
   33 | typedef unsigned int __u_int;
      |                      ^~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:34:27: error: storage class specified for parameter â€˜__u_longâ€™
   34 | typedef unsigned long int __u_long;
      |                           ^~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:37:21: error: storage class specified for parameter â€˜__int8_tâ€™
   37 | typedef signed char __int8_t;
      |                     ^~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:38:23: error: storage class specified for parameter â€˜__uint8_tâ€™
   38 | typedef unsigned char __uint8_t;
      |                       ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:39:26: error: storage class specified for parameter â€˜__int16_tâ€™
   39 | typedef signed short int __int16_t;
      |                          ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:40:28: error: storage class specified for parameter â€˜__uint16_tâ€™
   40 | typedef unsigned short int __uint16_t;
      |                            ^~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:41:20: error: storage class specified for parameter â€˜__int32_tâ€™
   41 | typedef signed int __int32_t;
      |                    ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:42:22: error: storage class specified for parameter â€˜__uint32_tâ€™
   42 | typedef unsigned int __uint32_t;
      |                      ^~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:44:25: error: storage class specified for parameter â€˜__int64_tâ€™
   44 | typedef signed long int __int64_t;
      |                         ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:45:27: error: storage class specified for parameter â€˜__uint64_tâ€™
   45 | typedef unsigned long int __uint64_t;
      |                           ^~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:52:18: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜__int_least8_tâ€™
   52 | typedef __int8_t __int_least8_t;
      |                  ^~~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:53:19: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜__uint_least8_tâ€™
   53 | typedef __uint8_t __uint_least8_t;
      |                   ^~~~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:54:19: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜__int_least16_tâ€™
   54 | typedef __int16_t __int_least16_t;
      |                   ^~~~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:55:20: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜__uint_least16_tâ€™
   55 | typedef __uint16_t __uint_least16_t;
      |                    ^~~~~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:56:19: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜__int_least32_tâ€™
   56 | typedef __int32_t __int_least32_t;
      |                   ^~~~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:57:20: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜__uint_least32_tâ€™
   57 | typedef __uint32_t __uint_least32_t;
      |                    ^~~~~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:58:19: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜__int_least64_tâ€™
   58 | typedef __int64_t __int_least64_t;
      |                   ^~~~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:59:20: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜__uint_least64_tâ€™
   59 | typedef __uint64_t __uint_least64_t;
      |                    ^~~~~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:63:18: error: storage class specified for parameter â€˜__quad_tâ€™
   63 | typedef long int __quad_t;
      |                  ^~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:64:27: error: storage class specified for parameter â€˜__u_quad_tâ€™
   64 | typedef unsigned long int __u_quad_t;
      |                           ^~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:72:18: error: storage class specified for parameter â€˜__intmax_tâ€™
   72 | typedef long int __intmax_t;
      |                  ^~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:73:27: error: storage class specified for parameter â€˜__uintmax_tâ€™
   73 | typedef unsigned long int __uintmax_t;
      |                           ^~~~~~~~~~~
In file included from /usr/include/stdio.h:38,
                 from _printf.c:3:
/usr/include/x86_64-linux-gnu/bits/types.h:145:25: error: storage class specified for parameter â€˜__dev_tâ€™
  145 | __STD_TYPE __DEV_T_TYPE __dev_t; /* Type of device numbers.  */
      |                         ^~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:146:25: error: storage class specified for parameter â€˜__uid_tâ€™
  146 | __STD_TYPE __UID_T_TYPE __uid_t; /* Type of user identifications.  */
      |                         ^~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:147:25: error: storage class specified for parameter â€˜__gid_tâ€™
  147 | __STD_TYPE __GID_T_TYPE __gid_t; /* Type of group identifications.  */
      |                         ^~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:148:25: error: storage class specified for parameter â€˜__ino_tâ€™
  148 | __STD_TYPE __INO_T_TYPE __ino_t; /* Type of file serial numbers.  */
      |                         ^~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:149:27: error: storage class specified for parameter â€˜__ino64_tâ€™
  149 | __STD_TYPE __INO64_T_TYPE __ino64_t; /* Type of file serial numbers (LFS).*/
      |                           ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:150:26: error: storage class specified for parameter â€˜__mode_tâ€™
  150 | __STD_TYPE __MODE_T_TYPE __mode_t; /* Type of file attribute bitmasks.  */
      |                          ^~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:151:27: error: storage class specified for parameter â€˜__nlink_tâ€™
  151 | __STD_TYPE __NLINK_T_TYPE __nlink_t; /* Type of file link counts.  */
      |                           ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:152:25: error: storage class specified for parameter â€˜__off_tâ€™
  152 | __STD_TYPE __OFF_T_TYPE __off_t; /* Type of file sizes and offsets.  */
      |                         ^~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:153:27: error: storage class specified for parameter â€˜__off64_tâ€™
  153 | __STD_TYPE __OFF64_T_TYPE __off64_t; /* Type of file sizes and offsets (LFS).  */
      |                           ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:154:25: error: storage class specified for parameter â€˜__pid_tâ€™
  154 | __STD_TYPE __PID_T_TYPE __pid_t; /* Type of process identifications.  */
      |                         ^~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:155:26: error: storage class specified for parameter â€˜__fsid_tâ€™
  155 | __STD_TYPE __FSID_T_TYPE __fsid_t; /* Type of file system IDs.  */
      |                          ^~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:156:27: error: storage class specified for parameter â€˜__clock_tâ€™
  156 | __STD_TYPE __CLOCK_T_TYPE __clock_t; /* Type of CPU usage counts.  */
      |                           ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:157:26: error: storage class specified for parameter â€˜__rlim_tâ€™
  157 | __STD_TYPE __RLIM_T_TYPE __rlim_t; /* Type for resource measurement.  */
      |                          ^~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:158:28: error: storage class specified for parameter â€˜__rlim64_tâ€™
  158 | __STD_TYPE __RLIM64_T_TYPE __rlim64_t; /* Type for resource measurement (LFS).  */
      |                            ^~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:159:24: error: storage class specified for parameter â€˜__id_tâ€™
  159 | __STD_TYPE __ID_T_TYPE __id_t;  /* General type for IDs.  */
      |                        ^~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:160:26: error: storage class specified for parameter â€˜__time_tâ€™
  160 | __STD_TYPE __TIME_T_TYPE __time_t; /* Seconds since the Epoch.  */
      |                          ^~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:161:30: error: storage class specified for parameter â€˜__useconds_tâ€™
  161 | __STD_TYPE __USECONDS_T_TYPE __useconds_t; /* Count of microseconds.  */
      |                              ^~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:162:31: error: storage class specified for parameter â€˜__suseconds_tâ€™
  162 | __STD_TYPE __SUSECONDS_T_TYPE __suseconds_t; /* Signed count of microseconds.  */
      |                               ^~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:164:27: error: storage class specified for parameter â€˜__daddr_tâ€™
  164 | __STD_TYPE __DADDR_T_TYPE __daddr_t; /* The type of a disk address.  */
      |                           ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:165:25: error: storage class specified for parameter â€˜__key_tâ€™
  165 | __STD_TYPE __KEY_T_TYPE __key_t; /* Type of an IPC key.  */
      |                         ^~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:168:29: error: storage class specified for parameter â€˜__clockid_tâ€™
  168 | __STD_TYPE __CLOCKID_T_TYPE __clockid_t;
      |                             ^~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:171:27: error: storage class specified for parameter â€˜__timer_tâ€™
  171 | __STD_TYPE __TIMER_T_TYPE __timer_t;
      |                           ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:174:29: error: storage class specified for parameter â€˜__blksize_tâ€™
  174 | __STD_TYPE __BLKSIZE_T_TYPE __blksize_t;
      |                             ^~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:179:28: error: storage class specified for parameter â€˜__blkcnt_tâ€™
  179 | __STD_TYPE __BLKCNT_T_TYPE __blkcnt_t;
      |                            ^~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:180:30: error: storage class specified for parameter â€˜__blkcnt64_tâ€™
  180 | __STD_TYPE __BLKCNT64_T_TYPE __blkcnt64_t;
      |                              ^~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:183:30: error: storage class specified for parameter â€˜__fsblkcnt_tâ€™
  183 | __STD_TYPE __FSBLKCNT_T_TYPE __fsblkcnt_t;
      |                              ^~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:184:32: error: storage class specified for parameter â€˜__fsblkcnt64_tâ€™
  184 | __STD_TYPE __FSBLKCNT64_T_TYPE __fsblkcnt64_t;
      |                                ^~~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:187:30: error: storage class specified for parameter â€˜__fsfilcnt_tâ€™
  187 | __STD_TYPE __FSFILCNT_T_TYPE __fsfilcnt_t;
      |                              ^~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:188:32: error: storage class specified for parameter â€˜__fsfilcnt64_tâ€™
  188 | __STD_TYPE __FSFILCNT64_T_TYPE __fsfilcnt64_t;
      |                                ^~~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:191:28: error: storage class specified for parameter â€˜__fsword_tâ€™
  191 | __STD_TYPE __FSWORD_T_TYPE __fsword_t;
      |                            ^~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:193:27: error: storage class specified for parameter â€˜__ssize_tâ€™
  193 | __STD_TYPE __SSIZE_T_TYPE __ssize_t; /* Type of a byte count, or error.  */
      |                           ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:196:33: error: storage class specified for parameter â€˜__syscall_slong_tâ€™
  196 | __STD_TYPE __SYSCALL_SLONG_TYPE __syscall_slong_t;
      |                                 ^~~~~~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:198:33: error: storage class specified for parameter â€˜__syscall_ulong_tâ€™
  198 | __STD_TYPE __SYSCALL_ULONG_TYPE __syscall_ulong_t;
      |                                 ^~~~~~~~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:202:19: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜__loff_tâ€™
  202 | typedef __off64_t __loff_t; /* Type of file sizes and offsets (LFS).  */
      |                   ^~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:203:15: error: storage class specified for parameter â€˜__caddr_tâ€™
  203 | typedef char *__caddr_t;
      |               ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:206:25: error: storage class specified for parameter â€˜__intptr_tâ€™
  206 | __STD_TYPE __SWORD_TYPE __intptr_t;
      |                         ^~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:209:23: error: storage class specified for parameter â€˜__socklen_tâ€™
  209 | __STD_TYPE __U32_TYPE __socklen_t;
      |                       ^~~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types.h:214:13: error: storage class specified for parameter â€˜__sig_atomic_tâ€™
  214 | typedef int __sig_atomic_t;
      |             ^~~~~~~~~~~~~~
In file included from /usr/include/x86_64-linux-gnu/bits/types/__fpos_t.h:5,
                 from /usr/include/stdio.h:39,
                 from _printf.c:3:
/usr/include/x86_64-linux-gnu/bits/types/__mbstate_t.h:21:3: error: storage class specified for parameter â€˜__mbstate_tâ€™
   21 | } __mbstate_t;
      |   ^~~~~~~~~~~
In file included from /usr/include/stdio.h:39,
                 from _printf.c:3:
/usr/include/x86_64-linux-gnu/bits/types/__fpos_t.h:12:3: error: expected specifier-qualifier-list before â€˜__off_tâ€™
   12 |   __off_t __pos;
      |   ^~~~~~~
/usr/include/x86_64-linux-gnu/bits/types/__fpos_t.h:14:3: error: storage class specified for parameter â€˜__fpos_tâ€™
   14 | } __fpos_t;
      |   ^~~~~~~~
In file included from /usr/include/stdio.h:40,
                 from _printf.c:3:
/usr/include/x86_64-linux-gnu/bits/types/__fpos64_t.h:12:3: error: expected specifier-qualifier-list before â€˜__off64_tâ€™
   12 |   __off64_t __pos;
      |   ^~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types/__fpos64_t.h:14:3: error: storage class specified for parameter â€˜__fpos64_tâ€™
   14 | } __fpos64_t;
      |   ^~~~~~~~~~
In file included from /usr/include/stdio.h:41,
                 from _printf.c:3:
/usr/include/x86_64-linux-gnu/bits/types/__FILE.h:5:25: error: storage class specified for parameter â€˜__FILEâ€™
    5 | typedef struct _IO_FILE __FILE;
      |                         ^~~~~~
In file included from /usr/include/stdio.h:42,
                 from _printf.c:3:
/usr/include/x86_64-linux-gnu/bits/types/FILE.h:7:25: error: storage class specified for parameter â€˜FILEâ€™
    7 | typedef struct _IO_FILE FILE;
      |                         ^~~~
In file included from /usr/include/stdio.h:43,
                 from _printf.c:3:
/usr/include/x86_64-linux-gnu/bits/types/struct_FILE.h:43:14: error: storage class specified for parameter â€˜_IO_lock_tâ€™
   43 | typedef void _IO_lock_t;
      |              ^~~~~~~~~~
/usr/include/x86_64-linux-gnu/bits/types/struct_FILE.h:74:3: error: expected specifier-qualifier-list before â€˜__off_tâ€™
   74 |   __off_t _old_offset; /* This used to be _offset but it's too small.  */
      |   ^~~~~~~
In file included from _printf.c:3:
/usr/include/stdio.h:63:17: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜off_tâ€™
   63 | typedef __off_t off_t;
      |                 ^~~~~
/usr/include/stdio.h:77:19: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜ssize_tâ€™
   77 | typedef __ssize_t ssize_t;
      |                   ^~~~~~~
/usr/include/stdio.h:84:18: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜fpos_tâ€™
   84 | typedef __fpos_t fpos_t;
      |                  ^~~~~~
In file included from _printf.c:3:
/usr/include/stdio.h:137:13: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜*â€™ token
  137 | extern FILE *stdin;  /* Standard input stream.  */
      |             ^
/usr/include/stdio.h:138:13: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜*â€™ token
  138 | extern FILE *stdout;  /* Standard output stream.  */
      |             ^
/usr/include/stdio.h:139:13: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜*â€™ token
  139 | extern FILE *stderr;  /* Standard error output stream.  */
      |             ^
/usr/include/stdio.h:146:12: error: storage class specified for parameter â€˜removeâ€™
  146 | extern int remove (const char *__filename) __THROW;
      |            ^~~~~~
/usr/include/stdio.h:148:12: error: storage class specified for parameter â€˜renameâ€™
  148 | extern int rename (const char *__old, const char *__new) __THROW;
      |            ^~~~~~
/usr/include/stdio.h:152:12: error: storage class specified for parameter â€˜renameatâ€™
  152 | extern int renameat (int __oldfd, const char *__old, int __newfd,
      |            ^~~~~~~~
/usr/include/stdio.h:173:13: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜*â€™ token
  173 | extern FILE *tmpfile (void) __wur;
      |             ^
/usr/include/stdio.h:187:14: error: storage class specified for parameter â€˜tmpnamâ€™
  187 | extern char *tmpnam (char *__s) __THROW __wur;
      |              ^~~~~~
/usr/include/stdio.h:192:14: error: storage class specified for parameter â€˜tmpnam_râ€™
  192 | extern char *tmpnam_r (char *__s) __THROW __wur;
      |              ^~~~~~~~
/usr/include/stdio.h:204:14: error: storage class specified for parameter â€˜tempnamâ€™
  204 | extern char *tempnam (const char *__dir, const char *__pfx)
      |              ^~~~~~~
/usr/include/stdio.h:213:20: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  213 | extern int fclose (FILE *__stream);
      |                    ^~~~
/usr/include/stdio.h:218:20: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  218 | extern int fflush (FILE *__stream);
      |                    ^~~~
/usr/include/stdio.h:227:29: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  227 | extern int fflush_unlocked (FILE *__stream);
      |                             ^~~~
/usr/include/stdio.h:246:13: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜*â€™ token
  246 | extern FILE *fopen (const char *__restrict __filename,
      |             ^
/usr/include/stdio.h:252:13: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜*â€™ token
  252 | extern FILE *freopen (const char *__restrict __filename,
      |             ^
/usr/include/stdio.h:279:13: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜*â€™ token
  279 | extern FILE *fdopen (int __fd, const char *__modes) __THROW __wur;
      |             ^
/usr/include/stdio.h:292:13: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜*â€™ token
  292 | extern FILE *fmemopen (void *__s, size_t __len, const char *__modes)
      |             ^
/usr/include/stdio.h:298:13: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜*â€™ token
  298 | extern FILE *open_memstream (char **__bufloc, size_t *__sizeloc) __THROW __wur;
      |             ^
/usr/include/stdio.h:304:21: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  304 | extern void setbuf (FILE *__restrict __stream, char *__restrict __buf) __THROW;
      |                     ^~~~
/usr/include/stdio.h:308:21: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  308 | extern int setvbuf (FILE *__restrict __stream, char *__restrict __buf,
      |                     ^~~~
/usr/include/stdio.h:309:20: error: expected declaration specifiers or â€˜...â€™ before â€˜size_tâ€™
  309 |       int __modes, size_t __n) __THROW;
      |                    ^~~~~~
/usr/include/stdio.h:314:24: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  314 | extern void setbuffer (FILE *__restrict __stream, char *__restrict __buf,
      |                        ^~~~
/usr/include/stdio.h:315:10: error: expected declaration specifiers or â€˜...â€™ before â€˜size_tâ€™
  315 |          size_t __size) __THROW;
      |          ^~~~~~
/usr/include/stdio.h:318:25: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  318 | extern void setlinebuf (FILE *__stream) __THROW;
      |                         ^~~~
/usr/include/stdio.h:326:21: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  326 | extern int fprintf (FILE *__restrict __stream,
      |                     ^~~~
/usr/include/stdio.h:332:12: error: storage class specified for parameter â€˜printfâ€™
  332 | extern int printf (const char *__restrict __format, ...);
      |            ^~~~~~
/usr/include/stdio.h:334:12: error: storage class specified for parameter â€˜sprintfâ€™
  334 | extern int sprintf (char *__restrict __s,
      |            ^~~~~~~
/usr/include/stdio.h:341:22: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  341 | extern int vfprintf (FILE *__restrict __s, const char *__restrict __format,
      |                      ^~~~
/usr/include/stdio.h:347:12: error: storage class specified for parameter â€˜vprintfâ€™
  347 | extern int vprintf (const char *__restrict __format, __gnuc_va_list __arg);
      |            ^~~~~~~
/usr/include/stdio.h:349:12: error: storage class specified for parameter â€˜vsprintfâ€™
  349 | extern int vsprintf (char *__restrict __s, const char *__restrict __format,
      |            ^~~~~~~~
/usr/include/stdio.h:354:44: error: expected declaration specifiers or â€˜...â€™ before â€˜size_tâ€™
  354 | extern int snprintf (char *__restrict __s, size_t __maxlen,
      |                                            ^~~~~~
/usr/include/stdio.h:358:45: error: expected declaration specifiers or â€˜...â€™ before â€˜size_tâ€™
  358 | extern int vsnprintf (char *__restrict __s, size_t __maxlen,
      |                                             ^~~~~~
/usr/include/stdio.h:379:12: error: storage class specified for parameter â€˜vdprintfâ€™
  379 | extern int vdprintf (int __fd, const char *__restrict __fmt,
      |            ^~~~~~~~
/usr/include/stdio.h:382:12: error: storage class specified for parameter â€˜dprintfâ€™
  382 | extern int dprintf (int __fd, const char *__restrict __fmt, ...)
      |            ^~~~~~~
/usr/include/stdio.h:391:20: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  391 | extern int fscanf (FILE *__restrict __stream,
      |                    ^~~~
/usr/include/stdio.h:397:12: error: storage class specified for parameter â€˜scanfâ€™
  397 | extern int scanf (const char *__restrict __format, ...) __wur;
      |            ^~~~~
/usr/include/stdio.h:399:12: error: storage class specified for parameter â€˜sscanfâ€™
  399 | extern int sscanf (const char *__restrict __s,
      |            ^~~~~~
In file included from /usr/include/features.h:461,
                 from /usr/include/x86_64-linux-gnu/bits/libc-header-start.h:33,
                 from /usr/include/stdio.h:27,
                 from _printf.c:3:
/usr/include/stdio.h:407:12: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  407 | extern int __REDIRECT (fscanf, (FILE *__restrict __stream,
      |            ^~~~~~~~~~
/usr/include/stdio.h:410:12: error: storage class specified for parameter â€˜scanfâ€™
  410 | extern int __REDIRECT (scanf, (const char *__restrict __format, ...),
      |            ^~~~~~~~~~
/usr/include/stdio.h:410:12: error: redefinition of parameter â€˜scanfâ€™
In file included from _printf.c:3:
/usr/include/stdio.h:397:12: note: previous definition of â€˜scanfâ€™ was here
  397 | extern int scanf (const char *__restrict __format, ...) __wur;
      |            ^~~~~
In file included from /usr/include/features.h:461,
                 from /usr/include/x86_64-linux-gnu/bits/libc-header-start.h:33,
                 from /usr/include/stdio.h:27,
                 from _printf.c:3:
/usr/include/stdio.h:412:12: error: storage class specified for parameter â€˜sscanfâ€™
  412 | extern int __REDIRECT_NTH (sscanf, (const char *__restrict __s,
      |            ^~~~~~~~~~~~~~
/usr/include/stdio.h:412:12: error: redefinition of parameter â€˜sscanfâ€™
In file included from _printf.c:3:
/usr/include/stdio.h:399:12: note: previous definition of â€˜sscanfâ€™ was here
  399 | extern int sscanf (const char *__restrict __s,
      |            ^~~~~~
/usr/include/stdio.h:432:21: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  432 | extern int vfscanf (FILE *__restrict __s, const char *__restrict __format,
      |                     ^~~~
/usr/include/stdio.h:440:12: error: storage class specified for parameter â€˜vscanfâ€™
  440 | extern int vscanf (const char *__restrict __format, __gnuc_va_list __arg)
      |            ^~~~~~
/usr/include/stdio.h:444:12: error: storage class specified for parameter â€˜vsscanfâ€™
  444 | extern int vsscanf (const char *__restrict __s,
      |            ^~~~~~~
In file included from /usr/include/features.h:461,
                 from /usr/include/x86_64-linux-gnu/bits/libc-header-start.h:33,
                 from /usr/include/stdio.h:27,
                 from _printf.c:3:
/usr/include/stdio.h:451:12: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  451 | extern int __REDIRECT (vfscanf,
      |            ^~~~~~~~~~
/usr/include/stdio.h:456:12: error: storage class specified for parameter â€˜vscanfâ€™
  456 | extern int __REDIRECT (vscanf, (const char *__restrict __format,
      |            ^~~~~~~~~~
/usr/include/stdio.h:456:12: error: redefinition of parameter â€˜vscanfâ€™
In file included from _printf.c:3:
/usr/include/stdio.h:440:12: note: previous definition of â€˜vscanfâ€™ was here
  440 | extern int vscanf (const char *__restrict __format, __gnuc_va_list __arg)
      |            ^~~~~~
In file included from /usr/include/features.h:461,
                 from /usr/include/x86_64-linux-gnu/bits/libc-header-start.h:33,
                 from /usr/include/stdio.h:27,
                 from _printf.c:3:
/usr/include/stdio.h:459:12: error: storage class specified for parameter â€˜vsscanfâ€™
  459 | extern int __REDIRECT_NTH (vsscanf,
      |            ^~~~~~~~~~~~~~
/usr/include/stdio.h:459:12: error: redefinition of parameter â€˜vsscanfâ€™
In file included from _printf.c:3:
/usr/include/stdio.h:444:12: note: previous definition of â€˜vsscanfâ€™ was here
  444 | extern int vsscanf (const char *__restrict __s,
      |            ^~~~~~~
/usr/include/stdio.h:485:19: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  485 | extern int fgetc (FILE *__stream);
      |                   ^~~~
/usr/include/stdio.h:486:18: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  486 | extern int getc (FILE *__stream);
      |                  ^~~~
/usr/include/stdio.h:492:12: error: storage class specified for parameter â€˜getcharâ€™
  492 | extern int getchar (void);
      |            ^~~~~~~
/usr/include/stdio.h:499:27: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  499 | extern int getc_unlocked (FILE *__stream);
      |                           ^~~~
/usr/include/stdio.h:500:12: error: storage class specified for parameter â€˜getchar_unlockedâ€™
  500 | extern int getchar_unlocked (void);
      |            ^~~~~~~~~~~~~~~~
/usr/include/stdio.h:510:28: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  510 | extern int fgetc_unlocked (FILE *__stream);
      |                            ^~~~
/usr/include/stdio.h:521:28: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  521 | extern int fputc (int __c, FILE *__stream);
      |                            ^~~~
/usr/include/stdio.h:522:27: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  522 | extern int putc (int __c, FILE *__stream);
      |                           ^~~~
/usr/include/stdio.h:528:12: error: storage class specified for parameter â€˜putcharâ€™
  528 | extern int putchar (int __c);
      |            ^~~~~~~
/usr/include/stdio.h:537:37: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  537 | extern int fputc_unlocked (int __c, FILE *__stream);
      |                                     ^~~~
/usr/include/stdio.h:545:36: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  545 | extern int putc_unlocked (int __c, FILE *__stream);
      |                                    ^~~~
/usr/include/stdio.h:546:12: error: storage class specified for parameter â€˜putchar_unlockedâ€™
  546 | extern int putchar_unlocked (int __c);
      |            ^~~~~~~~~~~~~~~~
/usr/include/stdio.h:553:18: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  553 | extern int getw (FILE *__stream);
      |                  ^~~~
/usr/include/stdio.h:556:27: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  556 | extern int putw (int __w, FILE *__stream);
      |                           ^~~~
/usr/include/stdio.h:564:52: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  564 | extern char *fgets (char *__restrict __s, int __n, FILE *__restrict __stream)
      |                                                    ^~~~
/usr/include/stdio.h:577:14: error: storage class specified for parameter â€˜getsâ€™
  577 | extern char *gets (char *__s) __wur __attribute_deprecated__;
      |              ^~~~
/usr/include/stdio.h:603:18: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜__getdelimâ€™
  603 | extern __ssize_t __getdelim (char **__restrict __lineptr,
      |                  ^~~~~~~~~~
/usr/include/stdio.h:606:18: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜getdelimâ€™
  606 | extern __ssize_t getdelim (char **__restrict __lineptr,
      |                  ^~~~~~~~
/usr/include/stdio.h:616:18: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜getlineâ€™
  616 | extern __ssize_t getline (char **__restrict __lineptr,
      |                  ^~~~~~~
/usr/include/stdio.h:626:47: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  626 | extern int fputs (const char *__restrict __s, FILE *__restrict __stream);
      |                                               ^~~~
/usr/include/stdio.h:632:12: error: storage class specified for parameter â€˜putsâ€™
  632 | extern int puts (const char *__s);
      |            ^~~~
/usr/include/stdio.h:639:29: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  639 | extern int ungetc (int __c, FILE *__stream);
      |                             ^~~~
/usr/include/stdio.h:646:15: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜freadâ€™
  646 | extern size_t fread (void *__restrict __ptr, size_t __size,
      |               ^~~~~
/usr/include/stdio.h:652:15: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜fwriteâ€™
  652 | extern size_t fwrite (const void *__restrict __ptr, size_t __size,
      |               ^~~~~~
/usr/include/stdio.h:673:15: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜fread_unlockedâ€™
  673 | extern size_t fread_unlocked (void *__restrict __ptr, size_t __size,
      |               ^~~~~~~~~~~~~~
/usr/include/stdio.h:675:15: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜fwrite_unlockedâ€™
  675 | extern size_t fwrite_unlocked (const void *__restrict __ptr, size_t __size,
      |               ^~~~~~~~~~~~~~~
/usr/include/stdio.h:684:19: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  684 | extern int fseek (FILE *__stream, long int __off, int __whence);
      |                   ^~~~
/usr/include/stdio.h:689:24: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  689 | extern long int ftell (FILE *__stream) __wur;
      |                        ^~~~
/usr/include/stdio.h:694:21: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  694 | extern void rewind (FILE *__stream);
      |                     ^~~~
/usr/include/stdio.h:707:20: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  707 | extern int fseeko (FILE *__stream, __off_t __off, int __whence);
      |                    ^~~~
/usr/include/stdio.h:707:36: error: expected declaration specifiers or â€˜...â€™ before â€˜__off_tâ€™
  707 | extern int fseeko (FILE *__stream, __off_t __off, int __whence);
      |                                    ^~~~~~~
/usr/include/stdio.h:712:16: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜ftelloâ€™
  712 | extern __off_t ftello (FILE *__stream) __wur;
      |                ^~~~~~
/usr/include/stdio.h:731:21: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  731 | extern int fgetpos (FILE *__restrict __stream, fpos_t *__restrict __pos);
      |                     ^~~~
/usr/include/stdio.h:731:48: error: unknown type name â€˜fpos_tâ€™
  731 | extern int fgetpos (FILE *__restrict __stream, fpos_t *__restrict __pos);
      |                                                ^~~~~~
/usr/include/stdio.h:134:1: note: â€˜fpos_tâ€™ is defined in header â€˜<stdio.h>â€™; did you forget to â€˜#include <stdio.h>â€™?
  133 | #include <bits/stdio_lim.h>
  +++ |+#include <stdio.h>
  134 | 
/usr/include/stdio.h:736:21: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  736 | extern int fsetpos (FILE *__stream, const fpos_t *__pos);
      |                     ^~~~
/usr/include/stdio.h:736:43: error: unknown type name â€˜fpos_tâ€™
  736 | extern int fsetpos (FILE *__stream, const fpos_t *__pos);
      |                                           ^~~~~~
/usr/include/stdio.h:757:23: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  757 | extern void clearerr (FILE *__stream) __THROW;
      |                       ^~~~
/usr/include/stdio.h:759:18: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  759 | extern int feof (FILE *__stream) __THROW __wur;
      |                  ^~~~
/usr/include/stdio.h:761:20: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  761 | extern int ferror (FILE *__stream) __THROW __wur;
      |                    ^~~~
/usr/include/stdio.h:765:32: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  765 | extern void clearerr_unlocked (FILE *__stream) __THROW;
      |                                ^~~~
/usr/include/stdio.h:766:27: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  766 | extern int feof_unlocked (FILE *__stream) __THROW __wur;
      |                           ^~~~
/usr/include/stdio.h:767:29: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  767 | extern int ferror_unlocked (FILE *__stream) __THROW __wur;
      |                             ^~~~
/usr/include/stdio.h:775:13: error: storage class specified for parameter â€˜perrorâ€™
  775 | extern void perror (const char *__s);
      |             ^~~~~~
In file included from /usr/include/stdio.h:781,
                 from _printf.c:3:
/usr/include/x86_64-linux-gnu/bits/sys_errlist.h:26:12: error: storage class specified for parameter â€˜sys_nerrâ€™
   26 | extern int sys_nerr;
      |            ^~~~~~~~
/usr/include/x86_64-linux-gnu/bits/sys_errlist.h:27:26: error: storage class specified for parameter â€˜sys_errlistâ€™
   27 | extern const char *const sys_errlist[];
      |                          ^~~~~~~~~~~
In file included from _printf.c:3:
/usr/include/stdio.h:786:20: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  786 | extern int fileno (FILE *__stream) __THROW __wur;
      |                    ^~~~
/usr/include/stdio.h:791:29: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  791 | extern int fileno_unlocked (FILE *__stream) __THROW __wur;
      |                             ^~~~
/usr/include/stdio.h:800:13: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜*â€™ token
  800 | extern FILE *popen (const char *__command, const char *__modes) __wur;
      |             ^
/usr/include/stdio.h:806:20: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  806 | extern int pclose (FILE *__stream);
      |                    ^~~~
/usr/include/stdio.h:812:14: error: storage class specified for parameter â€˜ctermidâ€™
  812 | extern char *ctermid (char *__s) __THROW;
      |              ^~~~~~~
/usr/include/stdio.h:840:24: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  840 | extern void flockfile (FILE *__stream) __THROW;
      |                        ^~~~
/usr/include/stdio.h:844:26: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  844 | extern int ftrylockfile (FILE *__stream) __THROW __wur;
      |                          ^~~~
/usr/include/stdio.h:847:26: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  847 | extern void funlockfile (FILE *__stream) __THROW;
      |                          ^~~~
/usr/include/stdio.h:858:21: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  858 | extern int __uflow (FILE *);
      |                     ^~~~
/usr/include/stdio.h:859:24: error: expected declaration specifiers or â€˜...â€™ before â€˜FILEâ€™
  859 | extern int __overflow (FILE *, int);
      |                        ^~~~
_printf.c:12:1: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜{â€™ token
   12 | {
      | ^
_printf.c:24:1: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜{â€™ token
   24 | {
      | ^
_printf.c:51:1: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜{â€™ token
   51 | {
      | ^
_printf.c:63:1: error: expected â€˜=â€™, â€˜,â€™, â€˜;â€™, â€˜asmâ€™ or â€˜__attribute__â€™ before â€˜{â€™ token
   63 | {
      | ^
In file included from _printf.c:1:
main.h:9:5: error: old-style parameter declarations in prototyped function definition
    9 | int print_string(char *s)
      |     ^~~~~~~~~~~~
_printf.c:103: error: expected â€˜{â€™ at end of input
  103 | 
      | 
In file included from _printf.c:1:
main.h:9:24: error: unused parameter â€˜sâ€™ [-Werror=unused-parameter]
    9 | int print_string(char *s)
      |                  ~~~~~~^
_printf.c:103: error: control reaches end of non-void function [-Werror=return-type]
  103 | 
      | 
cc1: all warnings being treated as errors
