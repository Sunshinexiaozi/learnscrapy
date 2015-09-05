官方对这个的解释，是你要request的地址和allow_domain里面的冲突，从而被过滤掉。可以停用过滤功能。
yield Request(url, callback=self.parse_item, dont_filter=True)
