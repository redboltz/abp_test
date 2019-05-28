list (APPEND exec_programs
    server.cpp
)

foreach (source_file ${exec_programs})
    get_filename_component (source_file_we ${source_file} NAME_WE)
    add_executable (
        ${source_file_we}
        ${source_file}
    )
endforeach ()
