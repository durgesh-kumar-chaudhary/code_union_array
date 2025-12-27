def union_array(nums1,nums2):
    return sorted(set(nums1).union(set(nums2)))
nums1=[1,2,3,4,5]
nums2=[1,2,7]
print(union_array(nums1,nums2))


