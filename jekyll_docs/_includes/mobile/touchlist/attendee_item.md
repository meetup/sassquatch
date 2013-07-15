<h2 class="section-subtitle">Attendee Item TouchList  <span class='candidate'></span></h2>
<p> Initially designed for the Attendee/RSVP list on event details, 
	we can use this pattern whenever we need to display member data in a list.
</p>

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
	<!-- leaving extra els out of the example, these tags close it off -->
	</ul>
</div>

<div class="j-code">
	{% highlight jsp %}{% include mobile/touchlist/attendee_item_example_jsp.md %}{% endhighlight %}
	{% highlight html %}{% include mobile/touchlist/attendee_item_example.md %}
	</ul>
</div> 
{% endhighlight %}

</div>