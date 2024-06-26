# extract_split_ids

## Signature
    extract_split_ids(
	    destinations split_result[]
    )
    RETURNS TABLE(
        id integer
    )

## Arguments
| Name        | Type           | Description                                                                                                                |
| ----------- | -------------- | -------------------------------------------------------------------------------------------------------------------------- |
| destination | split_result[] | An array of [split_result](/docs/type/split_result.md) objects representing the distribution of the children of the source |

## Returns
A table of all the children from the split_result array.

## Explanation
Extracts the ids of all children in the given `destinations` array. Used primarily as a means to check the validity of a proposed split operation

## Example