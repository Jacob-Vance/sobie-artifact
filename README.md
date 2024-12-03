# Jacob's Sobie Artifact
index.ejs
```
<%- include('partials/sobie-start') %>
    <%- include('partials/sobie-nav') %>


    <%- include('sobieCards/sobie-alert') %>

<div class="row">
    <div class="col-md-12 mb-2">
        <%- include('sobieCards/sobie-jumbo') %>
    </div>
    <div class="col-md-6 mb-2">
        <%- include('sobieCards/sobie-venue') %>
    </div>
    <div class="col-md-6">
        <%- include('sobieCards/sobie-registration') %>
    </div>      
    <div class="col-md-12 mt-2">
        <%- include('sobieCards/sobie-jobie') %>
    </div>
</div>





<%- include('partials/sobie-footer') %>
<%- include('partials/sobie-end') %>
<%- include('partials/sobie-start') %>
<%- include('partials/sobie-nav') %>
```
```
 <%- include('sobieCards/sobie-alert') %>
            <div class="row">
                <div class="col-md-12">
                    <%- include('sobieCards/sobie-jumbo') %>
                </div>
                <div class="col-md-6 mt-2">

                </div>

            </div>
            <div class="row">
                <div class="col-md-6">
                    <div class="mt-2">
                        <%- include('sobieCards/sobie-venue') %>
                    </div>
                    <div class="mt-2">
                        <%- include('sobieCards/sobie-research') %>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="mt-2">
                        <%- include('sobieCards/sobie-registration') %>
                    </div>
                    <div class="mt-2">
                        <%- include('sobieCards/sobie-history') %>
                    </div>
                </div>



                <div class="col-md-12 mt-2">
                    <%- include('sobieCards/sobie-jobie') %>
                </div>
            </div>





            <%- include('partials/sobie-footer') %>
                <%- include('partials/sobie-end') %>
```

sobie-venue.ejs
```
<div class="card">
  <div class="card-body">
    <h2 class="card-title">Conference Hotel & Venue</h2>
    <div class="card-text">
    <ul>
      <li class="list-group-item border-0">
        <h4><a href="https://www.sandestin.com" target="_blank" class="fs-5">Sandestin Golf & Beach Resort</a>
        <i class="bi bi-box-arrow-up-right fs-6"></i></h4>
      </li>
      <li class="list-group-item border-0">Book your stay by <strong class="fs-5">March <del>1st</del> 10th<i class="bi bi-star"></i></strong> to get the
        SOBIE discount</li>
      <li class="list-group-item border-0">
          <strong class="fs-5">
             SOBIE Group Code:
          </strong> 
          <a
        href="https://www.sandestin.com/book-now?group=24Q3L3&checkin=04/09/2024&checkout=04/13/2024&rooms=1&adults=1#/room"
        target="_blank" class="btn-outline-primary">
            Book Online</a> or by Phone: <a href="tel:800-320-8115"
        target="_blank">800-320-8115</a>, (use code: 24V5SN)
  
      </li>
      <li class="list-group-item border-0">Discounted rates are available for the weekends <strong class="fs-5">before &
          after</strong> the SOBIE conference.</li>
      <li class="list-group-item border-0">Extend your stay and enjoy the Sandestin Area</li>
       </ul>
      <p class="text-center">
          <a href="#hotelTravelModal" class="btn btn-primary" role="button" data-bs-toggle="modal"
            data-bs-target="#hotelTravelModal">More Hotel & Travel...</a>
      </p>
    </div>
  
    
  </div>


</div>


<!--  hotelTravelModal -->
<div class="modal fade" id="hotelTravelModal" tabindex="-1" aria-labelledby="hotelTravelModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered modal-xl">
    <div class="modal-content">
      <div class="modal-header">
        <h2 class="modal-title">Hotel & Travel</h2>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body ">

        <!-- hotel card  -->

        <h2 class="card-title">Hotel Accommodations</h2>
        <!-- <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6> -->
        <p class="card-text">
          <b>SOBIE</b> offers a variety of accommodations for you and your family.<!--, starting at
        <b>$161</b-->. Please make your hotel reservations separate from the conference registration, by
          <!-- TODO: update -->
          <b>Sunday, March 10, 2024</b>.
        </p>
        <p class="card-text">
          Make your hotel registration using the 
          <strong>SOBIE Group Code:</strong> <a
            href="https://www.sandestin.com/book-now?group=24Q3L3&checkin=04/09/2024&checkout=04/13/2024&rooms=1&adults=1#/room"
            target="_blank" class="btn-outline-primary">Book Online</a> or by Phone: <a href="tel:800-320-8115"
            target="_blank">800-320-8115</a>, (use code: 24V5SN)

        </p>
        <p class="card-text">
          <b>Sandestin Group Reservations:</b>
          <br />
          <!-- todo: review this link...always update?  -->
          <a href="https://www.sandestin.com/book-now?group=24Q5QK&checkin=04/11/2023&checkout=04/15/2023&rooms=1&adults=1#/room"
            target="_blank">https://www.sandestin.com/</a>
          <br />
          Phone: <a href="tel:+18003208115">800-320-8115</a>
          <br />
          Fax: 850-267-8221
        </p>
        <p class="card-text">
          As always, Sandestin has a variety of room types available at the popular Bayside, Luau, and Beachside
          locations, with rates beginning at $158 at Bayside. Contact Sandestin for rental rates of specific room types
          at the various locations.
        </p>
        <!-- end hotel card  -->

        <!-- airports card  -->
        <h2 class="card-title">Area Airports</h2>
        <!-- <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6> -->
        <!-- todo: add in airport code, driving directions, g.map link -->
        <p class="card-text">
          Northwest Florida Beaches International Airport (Panama City; about 30 minutes east of Sandestin): <a
            href="https://www.iflybeaches.com/" target="flybeaches">https://www.iflybeaches.com/</a>
        </p>
        <p class="card-text">
          Destin-Fort Walton Beach Airport: <a href=" https://www.flyvps.com/"
            target="flyvps">https://www.flyvps.com/</a>
        </p>
        <p class="card-text">
          Pensacola International Airport: <a href="https://flypensacola.com/"
            target="flypensacola">https://flypensacola.com/</a>
        </p>
        <!-- end airports card -->

      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>
<!-- end hotelTravelModal -->
```
```
<div class="card">
  <div class="card-body">
    <h2 class="card-title">Conference Hotel & Venue</h2>
    <div class="card-text">
    <ul>
      <li class="list-group-item border-0">
        <h4><a href="https://www.sandestin.com" target="_blank" class="fs-5">Sandestin Golf & Beach Resort</a>
        <i class="bi bi-box-arrow-up-right fs-6"></i></h4>
      </li>
      <li class="list-group-item border-0">Book your stay by <strong class="fs-5">March <del>1st</del> 10th<i class="bi bi-star"></i></strong> to get the
        SOBIE discount</li>
      <li class="list-group-item border-0">
          <strong class="fs-5">
             SOBIE Group Code:
          </strong> 
          <a
        href="https://www.sandestin.com/book-now?group=24Q3L3&checkin=04/09/2024&checkout=04/13/2024&rooms=1&adults=1#/room"
        target="_blank" class="btn-outline-primary">
            Book Online</a> or by Phone: <a href="tel:800-320-8115"
        target="_blank">800-320-8115</a>, (use code: 24V5SN)
  
      </li>
      <li class="list-group-item border-0">Discounted rates are available for the weekends <strong class="fs-5">before &
          after</strong> the SOBIE conference.</li>
      <li class="list-group-item border-0">Extend your stay and enjoy the Sandestin Area</li>
       </ul>
      <p class="text-center">
          <a href="#hotelTravelModal" class="btn btn-primary" role="button" data-bs-toggle="modal"
            data-bs-target="#hotelTravelModal">More Hotel & Travel...</a>
            <a href="#sandestinModal" class="btn btn-primary" role="button" data-bs-toggle="modal"
          data-bs-target="#sandestinModal">More Sandestin...</a>
      </p>
    </div>
  
    
  </div>


</div>

<div class="modal fade" id="sandestinModal" tabindex="-1" aria-labelledby="sandestinModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered modal-xl">
    <div class="modal-content">
      <div class="modal-header">
        <h2 class="modal-title">Sandestin</h2>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body ">

        <p>
        <img src="../images/sandestin3.jpg" width="225" alt=""
          style="float:left;margin:10px 20px 20px 0;border:1px solid #000;box-shadow: 4px 4px 5px #444;"
          data-pagespeed-url-hash="3843628397" onload="pagespeed.CriticalImages.checkImageForCriticality(this);" />
        </br>
      </br>
        <a href="http://www.sandestin.com/" target="sandestin">Sandestin</a> has become a destination conference site
          for SOBIE, starting with the 2008 conference. SOBIE 2020 will also be held at Sandestin. We encourage you to
          bring your family to enjoy the beach, as well as all the resort offers you to experience in recreation,
          dining, shopping, and entertainment!
          </br>
        </br>
          Sandestin offers the conference rate to SOBIE participants for the weekends before and after the conference.
          We encourage you to extend your stay to enjoy the beautiful beaches and surrounding area!</p>
        </br>
      </br>
          <p>
            <img src="../images/sandestin1.jpg" height="225" alt=""
              style="float:left;margin:10px 35px 20px 0;border:1px solid #000;box-shadow: 4px 4px 5px #444;"
              data-pagespeed-url-hash="3254628555" onload="pagespeed.CriticalImages.checkImageForCriticality(this);" />
          
            <img src="../images/sandestin2.jpg" height="225" alt=""
              style="float:left;margin:10px 35px 20px 0;border:1px solid #000;box-shadow: 4px 4px 5px #444;"
              data-pagespeed-url-hash="3549128476" onload="pagespeed.CriticalImages.checkImageForCriticality(this);" />
          
            <img src="../images/sandestin4.jpg" height="225" alt=""
              style="float:left;margin:10px 0px 20px 0;border:1px solid #000;box-shadow: 4px 4px 5px #444;"
              data-pagespeed-url-hash="4138128318" onload="pagespeed.CriticalImages.checkImageForCriticality(this);" />
          </p>
        </div>
          </div>
  </div>
</div>

<!--  hotelTravelModal -->
<div class="modal fade" id="hotelTravelModal" tabindex="-1" aria-labelledby="hotelTravelModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered modal-xl">
    <div class="modal-content">
      <div class="modal-header">
        <h2 class="modal-title">Hotel & Travel</h2>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body ">

        <!-- hotel card  -->

        <h2 class="card-title">Hotel Accommodations</h2>
        <!-- <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6> -->
        <p class="card-text">
          <b>SOBIE</b> offers a variety of accommodations for you and your family.<!--, starting at
        <b>$161</b-->. Please make your hotel reservations separate from the conference registration, by
          <!-- TODO: update -->
          <b>Sunday, March 10, 2024</b>.
        </p>
        <p class="card-text">
          Make your hotel registration using the 
          <strong>SOBIE Group Code:</strong> <a
            href="https://www.sandestin.com/book-now?group=24Q3L3&checkin=04/09/2024&checkout=04/13/2024&rooms=1&adults=1#/room"
            target="_blank" class="btn-outline-primary">Book Online</a> or by Phone: <a href="tel:800-320-8115"
            target="_blank">800-320-8115</a>, (use code: 24V5SN)

        </p>
        <p class="card-text">
          <b>Sandestin Group Reservations:</b>
          <br />
          <!-- todo: review this link...always update?  -->
          <a href="https://www.sandestin.com/book-now?group=24Q5QK&checkin=04/11/2023&checkout=04/15/2023&rooms=1&adults=1#/room"
            target="_blank">https://www.sandestin.com/</a>
          <br />
          Phone: <a href="tel:+18003208115">800-320-8115</a>
          <br />
          Fax: 850-267-8221
        </p>
        <p class="card-text">
          As always, Sandestin has a variety of room types available at the popular Bayside, Luau, and Beachside
          locations, with rates beginning at $158 at Bayside. Contact Sandestin for rental rates of specific room types
          at the various locations.
        </p>
        <!-- end hotel card  -->

        <!-- airports card  -->
        <h2 class="card-title">Area Airports</h2>
        <!-- <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6> -->
        <!-- todo: add in airport code, driving directions, g.map link -->
        <p class="card-text">
          Northwest Florida Beaches International Airport (Panama City; about 30 minutes east of Sandestin): <a
            href="https://www.iflybeaches.com/" target="flybeaches">https://www.iflybeaches.com/</a>
        </p>
        <p class="card-text">
          Destin-Fort Walton Beach Airport: <a href=" https://www.flyvps.com/"
            target="flyvps">https://www.flyvps.com/</a>
        </p>
        <p class="card-text">
          Pensacola International Airport: <a href="https://flypensacola.com/"
            target="flypensacola">https://flypensacola.com/</a>
        </p>
        <!-- end airports card -->

      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>
<!-- end hotelTravelModal -->
```

sobie-history.ejs
```
<div class="card">
    <div class="card-body">
        <h2 class="card-title">History</h2>
        <div class="card-text">
            <ul>
                <li class="list-group-item border-0"><b>SOBIE</b> was founded in 1999 by Doug Barrett and the late Jim
                    Couch, both from the University of North</li>
                <li class="list-group-item border-0">Alabama, with about 30 participants from 5 schools.</li>
                <li class="list-group-item border-0"><b>SOBIE</b> is now the premier academic conference for small and
                    regional universities, attracting</li>
                <li class="list-group-item border-0">participants from almost every state, several countries,
                    businesses, and government agencies.</li>
            </ul>
        </div>
    </div>
</div>
```
