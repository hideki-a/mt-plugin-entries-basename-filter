# mt-plugin-entries-basename-filter

MTEntiresで、記事のベースネームを使用して出力する記事をフィルタ可能にします。

## 例

~~~
<mt:Ignore>basenameがsampleではじまる</mt:Ignore>
<mt:Entries lastn="5" basename_filter="sample%">
~~~

~~~
<mt:Ignore>basenameにsampleを含む</mt:Ignore>
<mt:Entries lastn="5" basename_filter="%sample%">
~~~
