# sobie-artifact
index.ejs
```
<%- include('partials/sobie-start') %>
    <%- include('partials/sobie-nav') %>


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
```
