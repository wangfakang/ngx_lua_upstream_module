
CC = cc
CFLAGS =  -pipe  -O -W -Wall -Wpointer-arith -Wno-unused-parameter -Werror -g -O0 -DNDK_SET_VAR -fPIC
CPP = cc -E
LINK = $(CC) -rdynamic  -fPIC  -shared  


CORE_LIBS = 
CORE_INCS = 
HTTP_INCS = 

CORE_LINK = 
NGX_LD_OPT = -Wl,-rpath,


ALL_INCS =  -I/usr/local/include/luajit-2.0 -I../lua-nginx-module/src/api -I../ngx_devel_kit/objs -Iobjs/addon/ndk -Iobjs -I../ngx_devel_kit/src -I/usr/local/nginxchash//include

CORE_DEPS =  /usr/local/nginxchash//include/nginx.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_config.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_core.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_log.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_palloc.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_array.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_list.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_hash.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_buf.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_queue.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_string.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_parse.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_inet.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_file.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_crc.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_crc32.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_murmurhash.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_md5.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_sha1.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_rbtree.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_trie.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_segment_tree.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_radix_tree.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_slab.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_times.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_shmtx.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_connection.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_cycle.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_conf_file.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_resolver.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_open_file_cache.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_crypt.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_proxy_protocol.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_event.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_event_timer.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_event_posted.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_event_busy_lock.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_event_connect.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_event_pipe.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_time.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_errno.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_alloc.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_files.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_channel.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_shmem.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_process.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_setaffinity.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_setproctitle.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_atomic.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_gcc_atomic_x86.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_thread.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_socket.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_os.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_user.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_pipe.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_sysinfo.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_process_cycle.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_linux_config.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_linux.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_syslog.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_proc.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_event_openssl.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_regex.h /usr/local/nginxchash//include/ /usr/local/nginxchash//include/ngx_auto_config.h

HTTP_DEPS =  /usr/local/nginxchash//include/ngx_http.h /usr/local/nginxchash//include/ngx_http_request.h /usr/local/nginxchash//include/ngx_http_config.h /usr/local/nginxchash//include/ngx_http_core_module.h /usr/local/nginxchash//include/ngx_http_cache.h /usr/local/nginxchash//include/ngx_http_variables.h /usr/local/nginxchash//include/ngx_http_script.h /usr/local/nginxchash//include/ngx_http_upstream.h /usr/local/nginxchash//include/ngx_http_upstream_round_robin.h /usr/local/nginxchash//include/ngx_http_busy_lock.h /usr/local/nginxchash//include/ngx_http_ssi_filter_module.h /usr/local/nginxchash//include/ngx_http_ssl_module.h /usr/local/nginxchash//include/ngx_http_reqstat.h

ADDON_DEPS = $(CORE_DEPS) /home/wangfakang/nginx/tengine/lua-upstream-nginx-module//src/ngx_http_lua_upstream_module.c


objs/ngx_http_lua_upstream_module.so:	objs/src/src/ngx_http_lua_upstream_module.o

	$(LINK) -o  objs/ngx_http_lua_upstream_module.so \
	objs/src/src/ngx_http_lua_upstream_module.o \
	-Wl,-rpath,
	


objs/src/src/ngx_http_lua_upstream_module.o:	$(ADDON_DEPS) \
	/home/wangfakang/nginx/tengine/lua-upstream-nginx-module//src/ngx_http_lua_upstream_module.c
	$(CC) -c -g $(CFLAGS) $(CORE_INCS) $(HTTP_INCS) \
		$(ALL_INCS) \
		-o objs/src/src/ngx_http_lua_upstream_module.o \
		/home/wangfakang/nginx/tengine/lua-upstream-nginx-module//src/ngx_http_lua_upstream_module.c

