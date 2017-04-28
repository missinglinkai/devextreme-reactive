# LocalPaging Plugin Reference

A plugin that performs local data paging. It also changes the current page if the provided one cannot be applied due to a smaller amount of available pages.

## User Reference

### Dependencies

- [PagingState](paging-state.md)

### Properties

none

## Plugin Developer Reference

### Imports

Name | Plugin | Type | Description
-----|--------|------|------------
rows | Getter | Array&lt;[Row](datagrid.md#row)&gt; | Rows to be paged
pageSize | Getter | number | Provides the page size
currentPage | Getter | number | Provides the current page
setCurrentPage | Action | ({ page: number }) => void | Changes the current page

### Exports

Name | Plugin | Type | Description
-----|--------|------|------------
rows | Getter | () => Array&lt;[Row](datagrid.md#row)&gt; | Rows with the applied paging
totalPages | Getter | () => number | The total pages count