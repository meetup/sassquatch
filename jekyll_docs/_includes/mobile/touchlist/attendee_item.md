<div class="doc-content">
	
	<h2>Attendee Item TouchList</h2>
	<p> Initially designed for the Attendee/RSVP list on event details, 
		we can use this pattern whenever we need to display member data in a list.
	</p>

</div>

	{% include mobile/touchlist/attendee_item_example.md %}
		<li class="touchList-item--attendee">
			<div class="ff-box">
		         <div class="ff-box-flex">
		             <a href="${member_url}" class="figureset j-btn touchList-item--attendee-figureset">
		                 <div class="figureset-figure avatar-m pin-top">
		                   <img src="assets/img/uhura.jpg" />
		                 </div>
		                 <div class="figureset-description">
		                     <h4 class="touchList-item--attendee-label">
		                        Lieutenant Uhura
		                     </h4>
		                 </div>
		             </a>
		         </div>
		         <div class="ff-box-fix touchList-item--attendee-secondary-actions">
		           <a class="button small niceToSeeYou primary" data-memberId="${attendee.member.id}" href="#">
		               <span>Good to see you</span>
		           </a>
		         </div>
		     </div>
		</li>
		<li class="touchList-item--attendee">
			<div class="ff-box">
				<div class="ff-box-flex">
					<a href="${member_url}" class="figureset j-btn touchList-item--attendee-figureset">
						<div class="figureset-figure avatar-m pin-top">
							<img src="assets/img/kirk2.jpg" />
						</div>
						<div class="figureset-description">
							<h4 class="touchList-item--attendee-label">
								Evil Kirk
							</h4>
						</div>
					</a>
				</div>
				<div class="ff-box-fix touchList-item--attendee-secondary-actions">
					<a class="button small niceToSeeYou primary" data-memberId="${attendee.member.id}" href="#">
						<span>Good to see you</span>
					</a>
				</div>
			</div>
		</li>
	</ul>
</div>

<div class="doc-content j-code">
	{% highlight jsp %}{% include mobile/touchlist/attendee_item_example_jsp.md %}{% endhighlight %}
	{% highlight html %}{% include mobile/touchlist/attendee_item_example.md %}
	</ul>
</div> 
{% endhighlight %}

</div>