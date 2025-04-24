To see the issue: 
1. enable compiling JVM targets using IntelliJ compiler in Experimental settings
2. Then go to settings -> project structure (ctrl + alt + shift + S) 
3. Now press apply, you should see

Content root '~/bazel-plugin-resource-repro/sql/some_sql_file.sql' is defined for modules 'src.main.java.com.somecorp.module1.module1_lib' and 'src.main.java.com.somecorp.module2.module2_lib'.
Two modules in a project cannot share the same content root.