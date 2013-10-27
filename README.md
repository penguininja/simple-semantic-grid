simple-semantic-grid
====================

Simple Semantic SASS Grid System

Basic Usage:

1. Add this file to your theme.
2. Import into your stylesheet using the @import SASS directive.  
        @import "grid";
3. Override default variables such as number of columns and max-width in your layout stylesheet as necessary.  
        $max-width: 960px;
4. Add container(s) to your layout by calling the container mixin.  
        #page {  
          @include container;  
        }
4. Add columns to your stylesheets by calling the appropriate mixin column.  
        article {  
          @include column(9);  
        }  
        aside {  
          @include column(3);  
        }  