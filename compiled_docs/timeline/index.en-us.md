{"meta":"<h2 id=\"guide\">Guide<a href=\"#guide\" class=\"anchor\">#</a></h2><p>Vertical display of time flow information.</p>\n<h3 id=\"when-to-use\">When to use<a href=\"#when-to-use\" class=\"anchor\">#</a></h3><ul>\n<li>When there is a series of information that needs to be ordered from top to bottom.</li>\n<li>There is a need to carry out a series of visual timeline time.</li>\n</ul>\n<h2 id=\"api\">API<a href=\"#api\" class=\"anchor\">#</a></h2>","api":"<h3 id=\"timeline\">Timeline<a href=\"#timeline\" class=\"anchor\">#</a></h3><table>\n<thead>\n<tr>\n<th>Parameters</th>\n<th>Description</th>\n<th>Type</th>\n<th>Default value</th>\n</tr>\n</thead>\n<tbody>\n<tr>\n<td>fold</td>\n<td>custom folding options, eg: <code>[{foldArea: [startIndex, endIndex], foldShow: boolean}]</code></td>\n<td>Array</td>\n<td>[]</td>\n</tr>\n</tbody>\n</table>\n<h3 id=\"timeline-item\">Timeline.Item<a href=\"#timeline-item\" class=\"anchor\">#</a></h3><table>\n<thead>\n<tr>\n<th>Parameters</th>\n<th>Description</th>\n<th>Type</th>\n<th>Default value</th>\n</tr>\n</thead>\n<tbody>\n<tr>\n<td>state</td>\n<td>node state <br><br><strong>optional</strong>:<br>&apos;done&apos;, &apos;process&apos;, &apos;error&apos;, &apos;success&apos;</td>\n<td>Enum</td>\n<td>&apos;done&apos;</td>\n</tr>\n<tr>\n<td>icon</td>\n<td>icon</td>\n<td>String</td>\n<td>-</td>\n</tr>\n<tr>\n<td>dot</td>\n<td>custom timeline node</td>\n<td>ReactNode</td>\n<td>-</td>\n</tr>\n<tr>\n<td>time</td>\n<td>formatted time</td>\n<td>ReactNode</td>\n<td>-</td>\n</tr>\n<tr>\n<td>title</td>\n<td>title</td>\n<td>ReactNode</td>\n<td>-</td>\n</tr>\n<tr>\n<td>timeLeft</td>\n<td>the time of timeline left</td>\n<td>ReactNode</td>\n<td>-</td>\n</tr>\n<tr>\n<td>content</td>\n<td>the content of timeline right</td>\n<td>ReactNode</td>\n<td>-</td>\n</tr>\n<tr>\n<td>animation</td>\n<td>animation</td>\n<td>Boolean</td>\n<td>true</td>\n</tr>\n</tbody>\n</table>\n"}